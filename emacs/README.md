### Setup

* Rename the file to `lsl-mode.el`.
* Put these lines into your [Emacs](http://www.gnu.org/software/emacs/) init file `.emacs`:

```lisp
(add-to-list 'load-path "~/.emacs.d/") ;; create the dir if it doesn't exist
(autoload 'lsl-mode "lsl-mode" "Load lsl-mode for editing Linden Scripting Language." t)
(add-to-list 'auto-mode-alist '("\\.lsl\\'" . lsl-mode))
```

* Restart [Emacs](http://www.gnu.org/software/emacs/).

### Snippets

* Download YASnippet from [github.com/capitaomorte/yasnippet](https://github.com/capitaomorte/yasnippet).
