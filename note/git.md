# Git

> 系统：Win10 64位

## 全局配置

- git config --global user.name "`<用户名>`"
- git config --global user.email "`<邮箱>`"

## 克隆仓库

- git clone `<仓库>`
- git clone `<仓库>` `<文件夹>`

## 提交

- git add .
- git commit -m "<备注>"
- git push

## 查看信息

- git config --list
- git config user.name
- git config user.email

## 配置文件

经过配置以后，会生成一个`~/.gitconfig`文件：

```
[user]
    name = 用户名
    email = 邮箱
[http "https://github.com"]
    proxy = socks5://地址:端口
[https "https://github.com"]
    proxy = socks5://地址:端口
```

## 设置代理

- 设置全局代理
  - git config --global http.proxy "`http://地址:端口`"
  - git config --global http.proxy '`socks5://地址:端口`'
  - git config --global https.proxy "`https://地址:端口`"
  - git config --global https.proxy '`socks5://地址:端口`'
- 设置局部代理
  - git config --local http.proxy "`地址:端口`"
- 查询全局代理
  - git config --global http.proxy
- 查询局部代理
  - git config --local http.proxy
- 取消代理：
  - git config --global --unset http.proxy
  - git config --local --unset http.proxy

## 多用户密钥
