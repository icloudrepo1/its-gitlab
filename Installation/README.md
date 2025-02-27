# GitLab Install & Set up on Ubuntu
===========================================

### 1. Create an ubuntu instance & Connect

AMI = Ubuntu , Instance types = T2.micro , Keypair = jenkinskey.pem , SG = All traffic (Anywhere)


### 2. Installation of Gitlab

```
sudo apt update && sudo apt upgrade -y
sudo apt install -y curl openssh-server ca-certificates
```
