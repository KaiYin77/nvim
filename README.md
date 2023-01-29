## My Nvim template
### Prerequisite: 
- install [neovim](https://github.com/neovim/neovim/wiki/Installing-Neovim) >= 0.8.
```bash
> sudo apt remove neovim -y
> sudo add-apt-repository ppa:neovim-ppa/stable
> sudo apt-get update
> sudo apt-get install neovim
```
or
```bash
cd ~/bin
curl -LO https://github.com/neovim/neovim/releases/latest/download/nvim.appimage
chmod u+x nvim.appimage
```
- setting nvim path
```bash
# For bash
# CUSTOM_NVIM_PATH=~/bin/nvim.appimage
# For fish
# set CUSTOM_NVIM_PATH ~/bin/nvim.appimage

# Set the above with the correct path, then run the rest of the commands:
set -u
sudo update-alternatives --install /usr/bin/ex ex "${CUSTOM_NVIM_PATH}" 110
sudo update-alternatives --install /usr/bin/vi vi "${CUSTOM_NVIM_PATH}" 110
sudo update-alternatives --install /usr/bin/view view "${CUSTOM_NVIM_PATH}" 110
sudo update-alternatives --install /usr/bin/vim vim "${CUSTOM_NVIM_PATH}" 110
sudo update-alternatives --install /usr/bin/vimdiff vimdiff "${CUSTOM_NVIM_PATH}" 110
```

- install [ripgrep](https://github.com/BurntSushi/ripgrep).
- install [packer.nvim](https://github.com/wbthomason/packer.nvim).
- install [nerd-font](https://www.nerdfonts.com/font-downloads).
- or install [MesloLGS nerd-font](https://github.com/ryanoasis/nerd-fonts/blob/master/patched-fonts/Meslo/M/Regular/complete/Meslo%20LG%20M%20Regular%20Nerd%20Font%20Complete.ttf).

[For the rest of settings, please follow ThePrimeagen video](https://www.youtube.com/watch?v=w7i4amO_zaE)
