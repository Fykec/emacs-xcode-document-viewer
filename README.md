Scan Apple docset in Emacs
======

## Install Steps

#### Clone

```bash
$ git clone https://github.com/Fykec/emacs-xcode-document-viewer.git
```

#### Install

```bash
$ cp emacs-xcode-document-viewer ~/.emacs.d
```

```lisp
(add-to-list 'load-path  "~/.emacs.d/emacs-xcode-document-viewer")
(require 'xcode-document-viewer)
(setq xcdoc:document-path "~/Library/Developer/Shared/Documentation/DocSets/com.apple.adc.documentation.AppleiOS6.0.iOSLibrary.docset")
(setq xcdoc:open-w3m-other-buffer t)
```

#### Notice

* This sript depend on [w3m](http://emacs-w3m.namazu.org/)
* Also now depend on [Emacs Helm plugin](https://github.com/emacs-helm/helm/wiki).
