# Counsel Dumb Jump

This package improves the ivy integration for
[dumb-jump](https://github.com/jacktasia/dumb-jump)

## Installation
``` emacs-lisp
(use-package counsel-dumb-jump
    :init
    (setq dumb-jump-ivy-jump-to-selected-function #'counsel-dumb-jump-ivy-jump-to-selected))
```
