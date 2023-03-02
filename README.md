# arch-commands


![alt image](https://github.com/gkpiccoli/arch-commands/blob/main/Screenshot_2023-02-12_16-31-13.png?raw=true)

- Comandos úteis do gerenciador de arquivos do Linux Arch - pacman

 -   sudo pacman -Syu (fully system updgrade)
 -   sudo pacman -Sua (upgrade AUR packages)
 -   sudo pacman -Ss [packageName] (procura o diretorio do pacote desejado no repositorio do Arch)
 -   sudo pacman -Qdt (packages u dont need more)
 -   sudo pacman -R 'packageName'(remove package)
 -   sudo pacman -Qs procura o pacote na query do pc

 -   yay       (Faz todo o trabalho kkkk) 
 -   yay -Sua (lista os pacotes AUR p serem atualizados)
 -   yay -Yc (lista pacotes obsoletos e apaga-os)
 -   yay -P --stats (estatísticas sobre os pacotes do sistema - mais relevantes)
 -   yay -U package.tar.zst (instala o pacote)
 -   yay -S pamac-all (gerenciador de pacotes GUI)
 -   man yay (manual do yay)
 

 -   yay -Rns [package_name] Remove an installed package and both its dependencies and configuration files


 -   makepkg -si  no diretorio - instala o pacote

  -  less PKGBUILD
