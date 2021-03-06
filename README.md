# rik-vim
My self-built vim and vimrc

test git environments

git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

vim +PluginInstall +qall


apt install build-essential ctags cmake vim-nox python3-dev

apt install mono-complete golang nodejs default-jdk npm

apt install g++-8

update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-7 700 --slave /usr/bin/g++ g++ /usr/bin/g++-7

update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-8 800 --slave /usr/bin/g++ g++ /usr/bin/g++-8

cd ~/.vim/bundle/YouCompleteMe

python3 install.py --all

