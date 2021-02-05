## 配置python路径
- 确保安装Python
- 查看`_machine_specifc.vim`文件，修改对应python路径

## 需要安装的一些组件

- 安装`aptitude`
```
sudo install aptitude
```

- 安装`pynvim`

```
pip install pynvim
pip3 install pynvim
```

- 安装`nodejs`和`npm`, 然后安装`neovim`

```
sudo aptitude install nodejs npm
sudo npm install -g neovim
```

- 安装`fzf`

```
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
- ~/.fzf/install
```

- 安装ag或者rg

```
# 安装ag
sudo  aptitude-get install silversearcher-ag
# 安装rg
curl -LO https://github.com/BurntSushi/ripgrep/releases/download/12.1.1/ripgrep_12.1.1_amd64.deb
sudo dpkg -i ripgrep_12.1.1_amd64.deb
```

- 安装`figlet`

```
sudo aptitude install figlet
```

- 安装`lazygit`
```
sudo add-apt-repository ppa:lazygit-team/release
sudo aptitude update
sudo aptitude install lazygit
```
