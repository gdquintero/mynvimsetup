Importante instalar una fuente con todos los íconos que usará snacks, por ejemplo Meslo.

Instalar la última version de neovim, se logra con: sudo snap install nvim --classic. Pero antes hay que eliminar cualquier version ya instalada:

sudo apt remove neovim
sudo apt purge neovim
sudo apt autoremove

La función snacks.picker.grep() (en Explorer de snacks) necesita rg y fd para la busqueda de carpetas o archivos, se instala con sudo apt install ripgrep fd-find (Linux) o brew install ripgrep fd (MacOS).

Yo recomiendo usar zsh en vez de bash. Los siguientes link son de bastante utilidad:

https://ohmyz.sh/ (oh my zsh)
https://github.com/romkatv/powerlevel10k (powerlevel10k)
https://gist.github.com/n1snt/454b879b8f0b7995740ae04c5fb5b7df (algunos plugins)
