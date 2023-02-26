# packages
OpenfishOS package repository

Adding a repository key

    wget -qO - https://raw.githubusercontent.com/OpenfishOS/packages/main/openfishos.gpg.key | sudo apt-key add -

Adding a repository to APT

    echo "deb https://github.com/OpenfishOS/packages/raw/main/ openfishos main" | sudo tee /etc/apt/sources.list.d/openfishos.list
