## Ubuntu
- **Udpate**
- sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list';
- wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -;
- sudo apt update;
- sudo apt -y dist-upgrade;
- sudo apt -y autoremove;
- **Tools**
- sudo apt install -y build-essential gcc make gdb autoconf automake pkg-config openjdk-17-jdk openjdk-17-jre;
- sudo apt install -y golang rust-all python3-dev python3-pip git-all lua5.4 luarocks lua-check vim-gtk3 jq;
- sudo apt install -y tree curl zip fzf ripgrep fd-find exa peco htop samba smbclient tmux cifs-utils wbritish;
- sudo apt install -y postgresql postgresql-contrib libpq-dev postgresql-plperl-15 postgresql-plpython3-15;
- sudo locale-gen zh_CN.UTF-8 en_US.UTF-8 zh_CN.GBK zh_CN;
- **Homebrew**
- /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
- brew install nvim node lazygit ctags pyright stylua flake8 starship google-java-format
- pip install pynvim autopep8 requests psycopg2 xlsxwriter openpyxl;
