## Crea llaves SSH y agregar a GITHUB
`ssh-keygen -t rsa -b 4096 -C "tuCorreo@com"` comando para crear la llave:
>Generating public/private rsa key pair.
>Enter file in which to save the key (/home/ruber/.ssh/id_rsa): 
>Created directory '/home/ruber/.ssh'. 
>Enter passphrase (empty for no passphrase): 
>Enter same passphrase again: 
>Your identification has been saved in /home/ruber/.ssh/id_rsa.
>Your public key has been saved in /home/ruber/.ssh/id_rsa.pub.
>The key fingerprint is:
>SHA256:FyNAx+r+5Aeu7q1eCyVfvsL6W3t7eWQWxbVXC5Znlf0 This is a key
# Encender el "servidor" de llaves SSH de tu computadora:
`eval $(ssh-agent -s)`    
>   Agent pid 8533

# Añadir tu llave SSH a este "servidor":
`ssh-add ruta-donde-guardaste-tu-llave-privada`
ej:`ssh-add ~/.ssh/id_rsa` 
    Enter passphrase for /home/ruber/.ssh/id_rsa: 
    Identity added: /home/ruber/.ssh/id_rsa (/home/ruber/.ssh/id_rsa



## Configuración de la terminal
1- instalar https://hyper.is/
2-Installing ZSH  https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH
    `zsh --version`
    `apt install zsh`
3-Installing Oh My ZSH https://ohmyz.sh/
    `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
    `nano .zshrc`:  y editamos el ZSH_THEME="robbyrussell" segun el tema:  https://github.com/robbyrussell/oh-my-zsh/wiki/Themes
    `source .zshrc`: reinicio de terminal

## Intalacion de plugins autocopletado 
#Oh My Zsh 
vamos al link de documentacion: -https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh
1.Clonamos el repository zsh-users/zsh-autosuggestions  (by default ~/.oh-my-zsh/custom/plugins)
`git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
2.Add el plugin en Oh My Zsh (`nano .zshrc`): buscar y agregamos "`zsh-autosuggestions`" en `plugins` con un espacion con algotro plugin que tenga
ejemplo:`plugins=(git zsh-autosuggestions)`
Start a new terminal session.

## Instalación y configuración de VSCode
 Visual Studio Code. Vamos a añadir diferentes plugins para VSCode:
`Git Blame:` va a mostrar el autor de la línea de código en la que estemos trabajando.
`ESLint:` es una herramienta de análisis de código estático para identificar patrones             problemáticos encontrados en el código JavaScript, o sea, nuestro linter. Debemos instalar y  configurar eslint para que siga el estilo de código que le indiquemos.
    `sudo npm install -g eslint` instalacion de eslint globalmente en nuetro sistema
    https://linuxize.com/post/how-to-install-node-js-on-ubuntu-18.04/ instalar nodejs
    `sudo npm init` antes de eso tenemos que tener un package.json
    `npx eslint --init` para inicializar la configuracion de eslint
        ❯ To check syntax, find problems, and enforce code styl
            ❯ JavaScript modules (import/export) 
                ❯ React
                    ❯◉ Browser
                        ❯ Use a popular style guide
                            ❯ Airbnb (https://github.com/airbnb/javascript)
                                ❯ JSON

`Color Highlight:` resalta el color que estemos escribiendo.
`SASS:` es un preprocesador de CSS.
##Herramientas de desarrollo del NAVEGADOR
-react : https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi
-redux: https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd
-JSON Viewer https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh
-postman: https://www.getpostman.com/ 
----> https://www.getpostman.com/downloads/

http://jsonplaceholder.typicode.com/todos  #JSON WEB

## INSTALACION DE GIT
- Instalar Git en Linux: $ `sudo apt-get update` $ `sudo apt-get install git`
- Instalar Git en Windows: https://gitforwindows.org/
https://github.com/INFINITY-RUBER/CURSO_GITHUB.github.io/blob/master/NOTA_COMANDOS.md

## Cómo crear un buen README.md y sintaxis de markdown
-https://pandao.github.io/editor.md/en.html

##reto clase primera js
## Intalacion de plugins autocopletado Oh My Zsh
 aquí: https://github.com/zsh-users/zsh-autosuggestions.
 vamos al link de documentacion: -https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md#oh-my-zsh
-1  Clonamos el repository zsh-users/zsh-autosuggestions (by default ~/.oh-my-zsh/custom/plugins) lo guarda:
`git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`
-2 Add el plugin en Oh My Zsh con el comando(nano .zshrc): buscar y agregamos  en plugins con un espacio si hay otro plugin que tenga y colocamos “zsh-autosuggestions”
ejemplo:
`plugins=(git zsh-autosuggestions)`
-3 Reiniciamos la terminal con: exit



``
``
``
``
``
``
