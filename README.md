# Vagrant Basebox Insecure key pair

Required for configuring base boxes.
For more details refer source comments @[Readme](https://github.com/mitchellh/vagrant/blob/master/keys/README.md)

## Setup
Add `vagrant.pub` to vagrant user's `authorize_keys`.
Update file permissions and ownerships 

```
chmod 700 .ssh
chmod 600 .ssh/authorized_keys
chown -R vagrant:vagrant .ssh
```
