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
	 `git add ./`     			把当前目录下改变的所有文件都放到门口
- 2. 'git commit -m '提交描述'   放到.git仓储中

#### 一次性把修改的文件提交到.git仓储中
- `git commit --all -m '提交描述'`