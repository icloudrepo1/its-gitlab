# GitLab Install & Set up on Ubuntu
===========================================

Follow this `https://about.gitlab.com/install/#amazonlinux-2023`

### 1. Create an ubuntu instance & Connect

AMI = Ubuntu , Instance types = T2.micro , Keypair = jenkinskey.pem , SG = All traffic (Anywhere)


### 2. Installation of Gitlab

```
sudo apt update && sudo apt upgrade -y
sudo apt install -y curl openssh-server ca-certificates
```

### 3. Add gitlab repo

```
curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ee/script.rpm.sh | sudo bash
```
