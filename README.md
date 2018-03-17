# golang-on-ubuntu
# download and install
wget "https://dl.google.com/go/go1.10.linux-amd64.tar.gz" --no-check-certificate

sudo tar -C /usr/local  -xzf go1.10.linux-amd64.tar.gz

# set environment
export PATH=$PATH:/usr/local/go/bin

create folder  home/go/src/[projectname]
