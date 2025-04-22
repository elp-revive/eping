;; -*- mode: eask; lexical-binding: t -*-

(package "eping"
         "0.1.1"
         "Ping websites to check internet connectivity")

(website-url "https://github.com/elp-revive/eping")
(keywords "comm" "processes" "terminals" "unix")

(package-file "eping.el")

(script "test" "echo \"Error: no test specified\" && exit 1")

(source "melpa")

(depends-on "emacs" "25.1")

(development
 (depends-on "package-lint")
 (depends-on "elisp-lint"))

(setq network-security-level 'low)  ; see https://github.com/jcs090218/setup-emacs-windows/issues/156#issuecomment-932956432
