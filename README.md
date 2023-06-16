# vimfiles
Cross platform vim configuration
## Installation
Change to home directory

    git clone https://github.com/shanemcandrewai/vimfiles.git
## Additional Linux installation bash commands
### Create Linux Vim intialization directory if required
    mkdir -p ~/.vim
### Create symbolic link in Linux Vim intialization directory to rc files
    ln -s ~/vimfiles/vimrc ~/.vim/vimrc
    ln -s ~/vimfiles/gvimrc ~/.vim/gvimrc
## Windows
### Using vim installed with git for windows
Copy the folder [.vim](./MSYS2/.vim) to $HOME
### Enable execution from command line
#### During installation select option
    [x] Create .bat files for command line use
#### Verify
    C:\>cd %windir%
    C:\WINDOWS>dir /b *.bat
## Launch gvim with python virtual environment
### Windows
    ..\venv\Scripts\activate & gvim
