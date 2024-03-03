# 本地文件加入到github已有仓库
## 生成密钥和连接
### 生成密钥
``` 
ssh-keygen -t rsa -C 'email@xxx.com' 
```
### 加入到github
略
### 测试连通
```
ssh -T ssh@github.com
```

## 本地文件操作
### 本地分支关联
```
git remote add origin '远程地址url'
```
### 中途有问题的时候清除本地分支关联
```
git remote rm origin
```
### 拉取
```
git pull origin main (main为分支名)
```