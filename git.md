# git分布式版本控制系统

## 安装 
```
https://git-for-windows.github.io/
```

## 配置
```bash
git config --global user.name "wuxingzhong"
git config --global user.email "330332812@qq.com"
# 不自动修改换行符
git config --global core.autocrlf false

```

## 创建版本库
```bash
mkdir learngit
cd learngit
git init
# 添加文件到仓库
git add readme.md
# 提交到仓库
git commit -m "写入文件 git.md"
```

## 时光穿梭
```bash
# 查看未提交的修改
git statu 
# 当前添加到仓库的和已添加到仓库的修改比较 
git diff git.md 
```