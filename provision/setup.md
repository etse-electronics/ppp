1)	Install Multipass: https://canonical.com/multipass/install
2)	Create ‘n vm.  In terminal/cmd/powershell exec die volgende,   multipass launch --name foo --cloud-init docker-config.yml
3)	Install Docker Desktop: https://www.docker.com/products/docker-desktop/
4)	Install vscode: https://code.visualstudio.com/Download
5)  Install mqttx: https://mqttx.app/downloads


docker compose up

ssh -R 80:localhost:80 tunnel.etse-tech.com
ssh -R 1883:localhost:1883 tunnel.etse-tech.com