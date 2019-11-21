# Windows-WSL-Ubuntu-SSH-Keys
Generate SSH keys in Ubuntu on WSL and share with Windows 10


## Make SSH key in Ubuntu on WSL.


```cd /home/WSLusername/```

```mkdir .ssh```

```cd .ssh```

```ssh-keygen -t rsa -b 4096 -C "youremail@provider.com"```


## Copy to WIN10


```cd /mnt/c/Users/WindowsUserName/```

```mkdir .ssh```

```cd .ssh```

```cp ~/.ssh/id_rsa* .```

Set id_rsa* to read only with right click in Windows File Explorer.

## Your public key

```cat ~/.ssh/id_rsa.pub```

