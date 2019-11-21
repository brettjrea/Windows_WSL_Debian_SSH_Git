# Windows-WSL-Ubuntu-SSH-Keys
Generate SSH keys in Ubuntu on WSL and share with Windows 10


## Make ssh key in wsl


```cd /home/user/```

```mkdir .ssh```

```cd .ssh```

```ssh-keygen -t rsa -b 4096 -C "youremail@provider.com"```


## Copy to win10


```cd /mnt/c/Users/brett/```

```mkdir .ssh```

```cd .ssh```

```cp ~/.ssh/id_rsa* .```

## Your public key

```cat ~/.ssh/id_rsa.pub```

