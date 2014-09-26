# About

This script will install Perforce Server 2014.1 on a 64-bit linux host. It has only been tested on Ubuntu so far. If you are looking for an Ubuntu host, I recommend the $20/month tier at [DigitalOcean](https://www.digitalocean.com/?refcode=070b959bc226).

# Usage

In shell, run the following commands in your terminal. You don't need to download this repo, that is what the first line in the following code does.

```shell
wget https://raw.githubusercontent.com/Allar/linux-perforce-installer/master/install-perforce
chmod +x install-perforce
sudo ./install-perforce
```

You will be asked to create a password and user details for a new user named `perforce`.

Afterwards, the server will restart and you should then be able to connect to your Perforce server.
