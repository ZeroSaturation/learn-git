#### 命令
```
--local         // 本地仓库 .git/config
--global        // 全局生效 ~/.gitconfig
```
#### 查看所有配置及所在文件
```
git config --list --show-origin
```

#### 基础命令操作

```
git init                            // 初始化
git add *.md                        // 添加文件到git仓库
git commit -m "message"             // 提交文件，-m 提交信息
git status                          // 查看仓库状态
git remote                          // 查看远程仓库
git remote add <shortname> <url>    // 添加一个新的远程git仓库
git remote remove <shortname>       // 删除一个远程仓库
git remote rename
```

