#### 初始化git仓储
- 命令: `git init`

#### 添加用户和邮箱(必须填)
- 1. `git config --global user.name '用户名'`
- 2. `git config --global user.email '邮箱(必须是符合邮箱格式)'`

#### 查看配置是否添加成功
- 命令: `git config --list`

#### 查看状态
- 命令: `git status`

#### 把代码放到.git仓库中
- 1. `git add ./修改的文件名`   放到门口
     `git add ./`     		把当前目录下改变的所有文件都放到门口
- 2. 'git commit -m '提交描述'   放到.git仓储中

#### 一次性把修改的文件提交到.git仓储中
- `git commit --all -m '提交描述'`

#### 查看修改日志
- 1. `git log`   查看详细的修改日志
- 2. `git log --oneline`  查看简洁版的日志

#### 忽略某些文件(.ider)
- 新建一个 .gitignore 文件
    + `touch .gitignore`
    + 在该文件中添加配置  以 `/`开头 后面跟不需要提交的文件名 `.idea`

#### 版本返回 
- 1. `git reset --hard Head~0` 回退到上次提交的位置
- 2. `git reset --hard 版本号` 回到某个指定的版本号

#### 查看所有分支的所有操作记录
- 命令: `git reflog`
  **防止某些时候关掉了命令框而忘记版本信息**

#### git 创建分支,切换分支,查看分支,合并分支
- 1.创建分支 `git branch 分支名字`
- 2.删除一个分支 `git branch -d(或者D) 分支名字`
   + 要切换到别的分支才可以删除这个分支
- 3.切换分支 `git checkout 分支名字`
- 4.合并分支 `git merge 要合并的分支的名字`
  **一般都是合并到master,master默认为主支**
