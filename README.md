## mac 使用

```shell
# 安装
brew install fortune

# 添加字典
git clone https://github.com/N1h1l157/fortunes.git
strfile fortunes/Mund4n3
mv fortunes/Mund4n3 fortunes/Mund4n3.dat /opt/homebrew/Cellar/fortune/9708/share/games/fortunes

# 使用字典
fortune -e Mund4n3
alias fortune='fortune -e Mund4n3'
```

## linux使用

```shell
# 安装
sudo yum -y install fortune-mod
sudo apt-get -y install fortune-mod

# 添加字典
git clone https://github.com/N1h1l157/fortunes.git
strfile fortunes/Mund4n3
mv fortunes/Mund4n3 fortunes/Mund4n3.dat /usr/share/games/fortune/

# 使用字典
fortune -e Mund4n3
alias fortune='fortune -e Mund4n3'
```

![](../images/example.png)