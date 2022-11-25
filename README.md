## How to use it?

- Clone the  repository
- Copy the content of `.vimrc` to your .vimrc config file in the `$HOME/.vimrc`
- Install Plug-Vim with the below command

  ```
  curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
      https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
  ```
- Move `autoload` `plugged` `colors` directoty to `$HOME/.vim`
- Open vim
- Run `PlugInstall`
- Navigate to `$HOME/.vim/plugged/coc.nvim` and run `npm install` or `yarn install`
