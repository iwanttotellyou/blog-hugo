# blog-hugo

## 使用方法
**mac下构建项目**
安装 brew
```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
安装 golang
```bash
brew install go
export GOPATH=$HOME/
```
安装 hugo
```bash
go get -v github.com/spf13/hugo
```

进入blog-hugo
```bash
hugo server
```
