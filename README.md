# zsh Completion for clingo

Warning this is a little out-dated but would be easy to update.

# Installation

   # create custom completion folder
    mkdir ~/.zsh_comp

    # copy `_potassco` file there
    cp _potassco ~/.zsh_comp/

    # add to .zshrc
    fpath=(~/.zsh_comp $fpath)
    autoload -U compinit
    compinit
