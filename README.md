# Termux-Banner 👼🏻
<img width="1254" height="1254" alt="29324" src="https://github.com/user-attachments/assets/2e19c894-69de-4a5f-bfa0-4a89f2638729" />

## **FOLLOW GITHUB**
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=GitHub&logoColor=white)](https://GitHub.com/onxx-x145)
[![Instagram 🫅🏻](https://img.shields.io/badge/Instagram-FOOOE?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com/_insrnx_)
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

Then restart Termux, or run:

    exec bash

The installer intentionally uses shell-safe configuration files instead of putting Bash
heredoc syntax inside Fish, which avoids the `Expected a variable name after this $`
and redirection parsing errors encountered with Fish.
