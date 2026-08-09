# Termux-Banner 👼🏻

Single-run Termux setup package based on the supplied `onas.zip`.

Installs/configures:
- Bash name banner and `name ` prompt
- Fish configuration with safe Fish syntax
- Starship config from the supplied file
- Termux colors from the supplied file
- Ubuntu Mono Nerd Font from the supplied file
- Backup of existing Bash/Fish/Starship/Termux configs

## Install

From Termux, enter the extracted folder and run:

    git clone https://gitHub.com/onxx-x146/Termux-Banner.git

Then restart Termux, or run:

    exec bash

The installer intentionally uses shell-safe configuration files instead of putting Bash
heredoc syntax inside Fish, which avoids the `Expected a variable name after this $`
and redirection parsing errors encountered with Fish.
