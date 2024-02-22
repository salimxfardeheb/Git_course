# Generating key ssh 
## Commands & decriptions 

> ssh-keygen -t rsa -b 4096 -C "salimxfardeheb@github.com"

- `ssh-keygen` : command for generating ssh keys.
- `-t rsa` RSA is the type of generated key.
- `-b 4096` size of key in byte.
- `-C "salimxfardeheb@github"` A comment to specify the purpose for which we use this key.

> ssh -T git@github.com

- `ssh` command for oppening ssh session.
- `-T` Option for verifying connection.
- `git@github` server github that we are testing connection.