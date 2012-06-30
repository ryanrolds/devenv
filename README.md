
== jade-mode
https://github.com/brianc/jade-mode/

    (add-to-list 'load-path "~/devenv/jade-mode")
    (require 'sws-mode)
    (require 'jade-mode)
    (add-to-list 'auto-mode-alist '("\\.styl$" . sws-mode))
    (add-to-list 'auto-mode-alist '("\\.jade$" . jade-mode))

== less-mode

https://github.com/purcell/less-css-mode/

    (add-to-list 'load-path "~/devenv/less-mode")
    (require 'less-css-mode)
    (add-to-list 'auto-mode-alist '("\\.less$" . less-css-mode))

== indentation

=== js-mode

    (setq js-indent-level 2)