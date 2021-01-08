curl -s --compressed "https://ti10ko.github.io/breeze/ubuntu/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/breeze.list "https://ti10ko.github.io/breeze/breeze.list"
sudo apt update
