
# openbsd-zsh-completions
Zsh completion completion fro OpenBSD


####Manual installation

* Clone the repository:

        git clone git://github.com/sizeofvoid/openbsd-zsh-completions.git

* Include the directory in your `$fpath`, for example by adding in `~/.zshrc`:

        fpath=(path/to/openbsd-zsh-completions/completions $fpath)

* You may have to force rebuild `zcompdump`:

        rm -f ~/.zcompdump; compinit


