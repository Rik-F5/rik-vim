# rik-vim
My self-built vim and vimrc

test git environments

git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim

vim +PluginInstall +qall

add-apt-repository ppa:jonathonf/vim

add-apt-repository ppa:longsleep/golang-backports

sed -i 's/^deb/ded \[trusted=yes\] /g' /etc/apt/sources.list.d/*


apt update

apt upgrade

apt install -y build-essential ctags cmake vim-nox python3-dev mono-complete golang nodejs default-jdk npm g++-8



update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-7 700 --slave /usr/bin/g++ g++ /usr/bin/g++-7

update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-8 800 --slave /usr/bin/g++ g++ /usr/bin/g++-8

cd ~/.vim/bundle/YouCompleteMe

python3 install.py --all

