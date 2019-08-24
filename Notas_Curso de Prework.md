## Crea llaves SSH
`ssh-keygen -t rsa -b 4096 -C "This is a key"` comando para crear la llave:
>Generating public/private rsa key pair.
>Enter file in which to save the key (/home/ruber/.ssh/id_rsa): 
>Created directory '/home/ruber/.ssh'.
>Enter passphrase (empty for no passphrase): 
>Enter same passphrase again: 
>Your identification has been saved in /home/ruber/.ssh/id_rsa.
>Your public key has been saved in /home/ruber/.ssh/id_rsa.pub.
>The key fingerprint is:
>SHA256:FyNAx+r+5Aeu7q1eCyVfvsL6W3t7eWQWxbVXC5Znlf0 This is a key
## Configuración de la terminal
1- instalar https://hyper.is/
2-Installing ZSH  https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH
    `zsh --version`
    `apt install zsh`
3-Installing Oh My ZSH https://ohmyz.sh/
    `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
    `nano .zshrc`  y editamos el ZSH_THEME="robbyrussell" segun el tema:  https://github.com/robbyrussell/oh-my-zsh/wiki/Themes
    `~ source .zshrc`
``
``
``
``
