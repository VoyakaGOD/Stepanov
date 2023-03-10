# Useless guide to using ssh:

## Fisrt of all you should call ssh-keygen to create new ssh-key-pair
## Then start ssh-agent(if it's stopped)
## Call ssh-add \[keyname\]
## Add ssh-key.bup to server
## And at last call "git clone git@github.com:username/repository.git" to copy remote repository on your machine