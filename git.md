git ssh windows

Open  C:\Program Files\Git\etc\ssh\ssh_config (if that’s where you installed Git)

Add lines

Host github.com
IdentityFile ~/.ssh/<your ssh key>
