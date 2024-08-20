# git与github学习笔记

---
## 何为git与github
### git
- Git是一个分布式版本控制系统，用于跟踪文件的更改，特别是代码文件  
- 它允许多个开发者协同工作，管理项目的历史记录  
### github
- GitHub是一个基于Git的代码托管平台，提供了版本控制和协作功能  
- 开发者可以在GitHub上共享代码、提交问题、进行代码审查等  

---
## git解决冲突
- 当合并分支时，如果有冲突，Git会提示需要手动解决。
- 解决冲突后，使用git add和git commit提交更改。
---
## git分支管理
- 创建分支：git branch [branch-name]
- 切换分支：git checkout [branch-name]
- 删除分支：git branch -d [branch-name]

---
## gitHub工作流程
1. Fork一个项目。
2. 在自己的Fork上clone到本地。
3. 在本地进行更改，使用git add和git commit。
4. 将更改push到自己的Fork上。
5. 在GitHub上创建Pull Request，请求合并更改。
---

## gitHub基本操作
- 创建仓库：在GitHub上创建一个新的仓库。
- Fork：复制一个仓库到自己的账户下。
- Pull Request：向原仓库提交更改请求。
- Issues：用于跟踪问题和任务。