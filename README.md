# code-paredit

[Paredit](http://mumble.net/~campbell/emacs/paredit.el) for [Visual Studio Code](https://code.visualstudio.com) (a thin wrapper around [paredit.js](http://robert.kra.hn/projects/paredit-js))

**Paredit**: provides structural editing and navigation for LISPs

Aiming for feature parity with Atom's [lisp-paredit](https://github.com/jonspalding/lisp-paredit)

## Commands

### Navigation

Default keybinding | Action
------------------ | ------
ctrl+right         | Forward Sexp
ctrl+left          | Backward Sexp
ctrl+down          | Forward Down Sexp
ctrl+up            | Backward Up Sexp
ctrl+w             | Expand Selection
ctrl+shift+w       | Expand Selection
---                | Close List
---                | Select Defn

### Editing

Default keybinding | Action
------------------ | ------
ctrl+alt-.         | Slurp Forward
ctrl+alt-<         | Slurp Backward
ctrl+alt-,         | Barf Forward
ctrl+alt->         | Barf Backward
ctrl+alt-s         | Splice
ctrl+alt-/         | Split Sexp
cmd-delete         | Kill Sexp Forward
cmd-backspace      | Kill Sexp Backward
ctrl+alt-down      | Splice & Kill Forward
ctrl+alt-up        | Splice & Kill Backward
ctrl+alt-(         | Wrap Around ()
ctrl+alt-[         | Wrap Around []
ctrl+alt-{         | Wrap Around {}
ctrl+alt-i         | Indent
---                | Transpose

## Why are there two Paredit extensions?

The old Paredit extension, made by [clptn](https://github.com/clptn/code-paredit) was abandonded and I couldn't reach him. This extension takes off extactly where clptn left, which was a beautiful clean extension, almost feature complete, and with just a few bugs. I intend to fix whatever bugs I and others find and have started to add the features I and others miss. I also intend to keep maintaining this extenson and if I find myself not able to do so I will try find another maintaner.

## Who am I?

I am a father of five children who loves to code. Relevant to this project might be:

* I released and maintain [Calva](https://marketplace.visualstudio.com/items?itemName=cospaia.clojure4vscode), another Visual Studio Code extension aimed at making it super easy to get Clojure and Clojurescript coding done. It sports interactive REPLs, inline evaluation and other stuff people from the Emacs Cider world are used to.
* I wrote a small piece about setting up [SPA routing with Reagent, Bidi and Accountant](https://pez.github.io/2016/03/01/Reagent-clientside-routing-with-Bidi-and-Accountant.html)

## Happy Coding

PRs welcome, file an issue or chat me (@pez) up in the [`#editors` channel](https://clojurians.slack.com/messages/editors/) of the Clojurians Slack. Tweeting [@pappapez](https://twitter.com/pappapez) works too.

❤️