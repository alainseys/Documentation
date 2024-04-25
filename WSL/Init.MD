# Initalize WSL 
To get a working dev envriroment follow these instructions to get started.

    sudo apt-get update -y && sudo apt-get upgrade -y 
    sudo apt-get install wget -y 
    sudo apt-get install python3 -y
    sudo apt-get install openssh-server -y
    sudo systemctl start ssh
    sudo systemctl status ssh
    eval "(ssh-agent -s)"
    
if you already have generated any ssh keys you can add them by running the following command

    ssh-add ~/.ssh/NAME_PRIVATE_KEY

If not you can generate a new one

    ssh-keygen
Now the only thing to do is adding your ssh key in Github and you are good to go.
