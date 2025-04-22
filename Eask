;; -*- mode: eask; lexical-binding: t -*-

(package "vs-light-theme"
         "2.0"
         "Visual Studio IDE light theme")

(website-url "https://github.com/emacs-vs/vs-light-theme")
(keywords "faces")

(package-file "vs-light-theme.el")

(script "test" "echo \"Error: no test specified\" && exit 1")

(source 'gnu)
(source 'melpa)

(depends-on "emacs" "24.1")

(development
 (depends-on "ert-runner"))

(setq network-security-level 'low)  ; see https://github.com/jcs090218/setup-emacs-windows/issues/156#issuecomment-932956432

(add-hook 'eask-before-compile-hook
           (lambda (&rest _)
             (setq byte-compile-error-on-warn t)))
