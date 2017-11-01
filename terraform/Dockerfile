FROM ubuntu

RUN apt update && apt install -y wget unzip build-essential zip rsync git-core
RUN cd /usr/bin && wget -N https://releases.hashicorp.com/terraform/0.10.7/terraform_0.10.7_linux_amd64.zip
RUN cd /usr/bin && unzip -o terraform_0.10.7_linux_amd64.zip
