* [Lute HTTP 使用指南](https://ld246.com/article/1569240189601)
* [Lute 一款对中文语境优化的 Markdown 引擎，支持 Go 和 JavaScript](https://github.com/88250/lute)

### 环境变量
GOROOT=go安装位置 #gosetup

GOPATH=go工作位置 #gosetup

GOPROXY=https://goproxy.io #代理下载依赖

### 编译参数
windows下编译输出后台运行的go程序:

go build -ldflags -H=windowsgui -o ${输出绝对路径}\target\lute_http.exe . #gosetup

### 说明
这个程序编译启动后, 再启动solo.jar会自动连接到本程序. solo博客就能使用toc等功能;
target下有编译好的, 双击运行, 也可以使用源码自行编译.