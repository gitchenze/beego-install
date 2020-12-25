# beego-install

[beego框架安装出坑指南](http://note.youdao.com/noteshare?id=076970f625feac6737c5655f119f2288&sub=7A6FE4E2137844B6A6A7C181A877838F)

安装时间
2020年12月24日 10:05:13

### github地址

[beego](https://github.com/beego/beego)
[bee](https://github.com/beego/bee)


### 中国代理 介绍
https://github.com/goproxy/goproxy.cn/blob/master/README.zh-CN.md

翻墙都过不去的坑 请大家设置代理
直接在命令行执行

    go env -w GOPROXY=https://goproxy.cn
    go env -w GO111MODULE=on

安装BeeGo 框架建议安装 bee 工具

##### 执行

    go get  github.com/beego/bee/v2

##### 更新

    go get -u github.com/beego/bee/v2


### windows 安装
 
进入目录执行

    go build main.go

main.exe 改名 bee.exe

把生成的bee.exe 放入C:\Go\bin

命令行 bee 测试效果

## 创建项目

    bee new blog 

### mac 安装
安装后 找到bee可执行文件
我mac上安装并没有构建过程 直接就找到了bee 不知道为啥

bee 文件 

    cp bee /usr/local/bin


## 运行框架

进入 blog 目录 

    bee run
