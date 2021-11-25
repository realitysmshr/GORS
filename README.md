# GORS
abrir editor no ficheiro /root/.ssh/config e escrever:
Host github.com
HostName github.com
User git
IdentityFile /root/gorsgit

scp gorsgit root@172.16.1.53:~/.ssh
