## Install Updates and Packages
```shell
apt update && apt upgrade -y
apt install curl git -y
```
## Install and Run Docker
```shell
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh
systemctl enable docker
reboot
docker run -dit --restart unless-stopped <image_name>
```