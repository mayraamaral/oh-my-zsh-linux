# Oh my Zsh no Linux
Tentei seguir o [post do blog da Rocketseat](https://blog.rocketseat.com.br/terminal-com-oh-my-zsh-spaceship-dracula-e-mais/) porém enfrentei alguns problemas e resolvi compartilhar todo o passo a passo que segui para conseguir usar o Zsh com o framework Oh My Zsh no 
Linux Ubuntu 18.04.  
## Guia
- [1. Instalando o Zsh](#1-instale-o-zsh)
- [2 Instalando o Oh My Zsh](#2-instale-o-oh-my-zsh)
- [Desinstalando o Zsh](#desinstalando-o-zsh)
- [Desinstalando o Oh My Zsh](#desinstalando-o-oh-my-zsh)
## 1 Instale o Zsh
Esse é o primeiro passo e o mais simples.
Digite  
  
```sudo apt install zsh```
  
na linha de comando do terminal e a instalação irá começar.
  
[Guia de instalação do Zsh - Inglês](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)  
  
ALguns links de respostas em fóruns que podem ser úteis:  
  
[Remove Zsh from Ubuntu](https://askubuntu.com/questions/958120/remove-zsh-from-ubuntu-16-04)  
  
## 2 Instale o Oh My Zsh
  
Para instalar o Oh My Zsh, digite:  
  
``` $ sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"```  
    
### Desinstalando o Zsh
  
Caso tenha tido problema com alguma instalação anterior e deseje desinstalar o Zsh para reinstalá-lo corretamente (ou por qualquer outro motivo), siga os passos:  
  
**Desinstale o Zsh do computador:**  
  
```sudo apt-get --purge remove zsh```  
  
**Agora mude o terminal para bash, o padrão:**  
  
```chsh -s /bin/bash```  
  
### Desinstalando o Oh My Zsh

Caso deseje desisntalar, siga os passos:  
  
**Primeiro tente executar este código:**  
  
```https://askubuntu.com/questions/958120/remove-zsh-from-ubuntu-16-04```  
  
Caso não consiga, tente este outro:  
  
```rm -rf ~/.oh-my-zsh```  
  
Caso ainda não consiga, coloque o **sudo** na frente do código anterior e irá conseguir, desta forma:  
  
```sudo rm -rf ~/.oh-my-zsh```  
  
Alguns links de respostas em fóruns que podem ser úteis:  
  
[Troubes uninstalling oh-my-zsh](https://stackoverflow.com/questions/9813983/troubles-uninstalling-oh-my-zsh) - Esse foi o único que funcionou para mim.  
[Uninstall Oh My Zsh](https://askubuntu.com/questions/963874/uninstall-oh-my-zsh)
