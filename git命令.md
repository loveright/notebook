### git命令

1. git push -u origin -f 强制推送
2. git status 查看提交状态
3. git commit -m "修改的信息" 提交到本地仓库
4. git push 提交到远程仓库

### git关联远程仓库

1. 从远程克隆一份到本地可以通过

   ```
   git clone git@github.com:nanfei9330/xx.git
   ```

2. 本地库关联远程库，在本地仓库目录运行命令：

   ```
    git remote add origin git@github.com:nanfei9330/learngit.git
   ```

