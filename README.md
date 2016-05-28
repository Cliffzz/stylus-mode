# stylus-mode

`stylus-mode` offers Emacs support for [Stylus](http://stylus-lang.com/). It is based on [pug-mode](https://github.com/hlissner/pug-mode) and [jade-mode](https://github.com/brianc/jade-mode).

## Installation

`stylus-mode` isn't available on MELPA yet.

In the meantime, download `pug-mode.el` and insert the following into your emacs.d:

```elisp
(require 'pug-mode)
```

For Spacemacs:

```elisp
dotspacemacs-additional-packages '(
  (stylus-mode :location (recipe :fetcher github :repo "vladh/stylus-mode"))
)
```

## Why not use jade-mode?

For pretty much the same reason that `pug-mode` was created to be used over `jade-mode`,
mainly `jade-mode`'s malfunctioning indentation and confusing source.
