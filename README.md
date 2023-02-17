# nvim-config
Config para nvim - Easy mode

### Instalar Vim-plug
iwr -useb https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim |`
    ni "$(@($env:XDG_DATA_HOME, $env:LOCALAPPDATA)[$null -eq $env:XDG_DATA_HOME])/nvim-data/site/autoload/plug.vim" -Force
	
### Instalar essas ferramentas para o telescope
choco install ripgrep
choco install fd

### Instalar plugins dentro do nvim
:PlugInstall
