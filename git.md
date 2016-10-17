# git分布式版本控制系统

## 安装 
```
https://git-for-windows.github.io/
```

## 配置
```bash
git config --global user.name "wuxingzhong"
git config --global user.email "330332812@qq.com"
```

## 创建版本库
```bash
mkdir learngit
cd learngit
git init
# 添加文件到仓库
git add readme.md
# 提交到仓库
git commit -m "写入文件 readme.md"

```
## 时光穿梭
```bash
# 查看未提交的修改
git statu 
# 当前未提交的和之前的版本比较 
git diff git.md 
```
