本仓库用于win应用程序存放，如果你需要添加请提交请求。以下是提交新文件的步骤。

# 添加新文件不同步仓库文件

```bash
# 1. 克隆仓库元数据，不 checkout 任何文件
git clone --no-checkout git@github.com:hestiacn/win.git
cd win

# 2. 切换到目标分支（默认 master，如果是 main 改成 main）
git switch master

# 3. 此时工作区是空的，把你打算推送的新文件复制进来

# 4. 提交并推送
git add .
git commit -m "提交文件说明"
git push origin master
```
## 回退方法

```bash
# 回到指定的某个提交。
git reset --hard 3cffef3
# 强制推送
git push origin master --force
```
推荐使用以下站点进行本仓库的文件下载。谢谢！

1. [GitHub 加速下载](https://iixingchen.github.io) (Ctrl+点击或右键在新窗口打开)

2. [GitHub 加速](https://gh-proxy.org) (Ctrl+点击或右键在新窗口打开)