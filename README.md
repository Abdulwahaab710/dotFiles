# dotFiles
![vim screenshot](https://github.com/Abdulwahaab710/dotFiles/raw/master/vimScreenShot.png)
### To install my vimrc configuration:

1. Install [vim plug](https://github.com/junegunn/vim-plug)
```sh
    curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
        https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```        
2. clone the repo
```sh
    git clone https://github.com/Abdulwahaab710/dotFiles.git
```    
3. Linking the files
```sh
    ln -s ./dotFiles/.vimrc ~/.vimrc
    
    ln -s ./dotFiles/.vimrc_c++ ~/.vimrc_c++
    
    ln -s ./dotFiles/.vimrc_python ~/.vimrc_python
    
    ln -s ./dotFiles/.vimrc_java ~/.vimrc_java
```
