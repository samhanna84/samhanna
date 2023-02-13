# Welcome
## Everything is already configured to contain the data within it's own folder. That way it is easy to configure the service or for making backups. Please review the docker compose file to see if changes are needed. 


### Please be sure install docker first.

curl -sSL https://get.docker.com | sh

sudo usermod -aG docker {USER}

sudo systemctl start docker

sudo systemctl enable docker

### Navigate to the folder for the service you want to install.
<table><tr><td>cd foldername/</td></tr></table>

###  Then type command below to install it.
<table><tr><td>sudo docker-compose up -d</td></tr></table>
