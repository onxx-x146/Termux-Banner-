# I am Hari  🫅🏻 
# Termux-Banner 👼🏻
<img width="716" height="604" alt="28228" src="https://github.com/user-attachments/assets/25cbd377-fa4a-4ef0-b5f2-b094a11dfff1" />

Single-run Termux setup package based on the supplied @

Installs/configures:
- Bash name banner and `name ` prompt
- Fish configuration with safe Fish syntax
- Starship config from the supplied file
- Termux colors from the supplied file
- Ubuntu Mono Nerd Font from the supplied file
- Backup of existing Bash/Fish/Starship/Termux configs

## Install

From Termux, enter the extracted folder and run:

    git clone https://gitHub.com/onxx-x146/Termux-Banner-.git
    cd Termux-Banner-
    chmod +x install.sh
    ./install.sh
    set -U fish_greeting

Then restart Termux, or run:

    exec bash

The installer intentionally uses shell-safe configuration files instead of putting Bash
heredoc syntax inside Fish, which avoids the `Expected a variable name after this $`
and redirection parsing errors encountered with Fish.
