## Git 基本操作

- 克隆到本地仓库的命令：  

  ```
  git clone https://xxxxx.git
  ```

- 删除文件夹

  ```
  git rm -rf foldername
  ```

- 添加文件

  ```
  git add filename
  ```

- 提交更改,添加注释

  ```
  #commit 并添加注释
  git commit -m "note"
  #提交到远程分支
  git push origin brachname
  ```

- 本地更新代码

  ```
  git pull
  ```

### Git 创建分支

- 创建分支

  ```
  git checkout -b new_branch_name
  #相当于

  #创建分支
  git branch new_branch_name
  #切换分支
  git checkout new_branch_name
  ```

- ![git_2](images\git_3.png)

- ![git_2](images\git_4.png)

### Git pull request

- fork别人的项目  创建自己的分支a（master）  提交修改 
- PR之后提交到分支a的所有修改都会同步到本次PR中
- 更广泛简单的描述是  请求别人合并你的修改

### commit vs push

- commit 操作的是本地仓库
- push 操作的是远程仓库
- 简而言之…… 就是有修改一定要先commit，再push

参考链接

- [Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)
- [参考文档](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)  所有基本操作基本都涉及到了