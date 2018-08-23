# hello gitbook
> 这是用gitbook创建的第一个笔记
 作为8月24号的分享
## 如何使用gitbook来做笔记

1. 首先安装gitbook-cli

```
npm install gitbook-cli -g
```

2. 然后创建自己专属的笔记文件夹

3. 进入文件夹运行`gitbook init`
就会生成两个文件
- Readme.md 显示书的封面
- Summary.md是书的目录

4. 启动服务器，查看和编辑书

```
gitbook serve
```
就可以在本地的4000端口访问
然后修改Sunmary.md就可以添加书的目录

```
# Sunmary

* [Introduction](README.md)
* 第一章
  - [第一节：hello.md](./git/1-hello.md)
```

创建了git文件夹就可以在其中写笔记了

5. 托管gitbook（首选肯定是github）

创建过github

