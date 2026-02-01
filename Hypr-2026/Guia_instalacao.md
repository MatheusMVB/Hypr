### Comandos
## Instalação do Arch + Hyprland
==!!! Instalar Antes do hyprland -> Kitty !!!==

1. Conectar a internet 
* iwctl station 'interface\_de\_rede' connect 'Nome\_Rede'

2. Montar Partição
* lsbkl -l -> Ver particoes e discos
* Montar particoes
* Definir pontos de montagem

3. Montar o \ (raiz)
* pacstrap \mnt\ linux linux-headers base base-devel nano kitty

4. Configuraçoes pre instalacao
* Configurar pacman
* pacman -S refind kitty hyprland ...

5. bootar

## Configuração Hyprland
### Instalação Yay

#### Programas instalados via yay
* yay -S vscodium-bin
* yay -S librewolf-bin
* yay -Ss JetBrains Nerd Fonts Mono -> Pesquisar pois pode mudar de repositório

### Programas Hyprland
* sudo pacman -S waybar rofi refind hyprpicker nautilus nautilus-pyhton nvim nano micro 
* Instalar o wlogout
* Mover os arquivos de configuracao baixados do github.

* sudo pacman -S git curl wget
### Instalação de Progranas para media -> Foto, audio e video
* 
### Instalação de Programas para integração do sistema
* sudo pacman -S polkit gvfs gvfs-mtp gvfs-smb udisks2 polkit-gnome gnome-keyring xdg-desktop-portal xdg-desktop-portal-gtk xdg-desktop-portal-hyprland xdg-user-dirs nwg-look qt5ct qt6ct kvantum kvantum-qt5 qt5-wayland qt6-wayland file-roller
