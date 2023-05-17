# Install zsh and make default shell
1. sudo apt install zsh
2. wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh
3. cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
4. chsh -s $(which zsh)

# Ubunly ZSH Theme 
The **new Kali Linux** console adapted to Ubuntu (and maybe any distro)!

![image](https://user-images.githubusercontent.com/43515908/208122228-41608f02-2ada-43a5-83cc-2e585082131d.png)

## <ins>Preview

![WindowsTerminal_c7APNwrBpI](https://user-images.githubusercontent.com/43515908/208122421-291a310b-99f1-4cb7-970d-6d7195bf31e2.png)

## <ins>Install
#### <ins>Prerequisites
* A Powerline/Nerd Font (for unicode characters) (Kali uses [Firacode](https://github.com/tonsky/FiraCode))

#### <ins>Steps

1. Clone the repository
2. Execute `INSTALL.sh`
3. Open your `.zshrc`
4. Change `ZSH_THEME` to `ubunly`
5. Add to the plugins `zsh-autosuggestions and zsh-syntax-highlighting`
6. Type `source ~/.zshrc` for reload

![28Y5wC6NkJ](https://user-images.githubusercontent.com/43515908/208123645-6494780e-3f6d-46cb-b54e-34b88bc2b093.gif)

