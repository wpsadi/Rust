# To install Rust on your local computer. use this command
`curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`


To configure your current shell, you need to source
the corresponding env file under $HOME/.cargo.

This is usually done by running one of the following (note the leading DOT):
`. "$HOME/.cargo/env"    `        # For sh/bash/zsh/ash/dash/pdksh
`source "$HOME/.cargo/env.fish"`  # For fish



# to check if rust is installed on your machine 
`cargo --version`
