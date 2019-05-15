# github协作流程
* fork 目标工程到自己的github仓库
* git clone 
* git remote add upstream https://github.com/zhongxigong/stronger.git
* `git remote -v` 可以查看远程仓库,路金中包含origin的是自己的git仓库,包含upstream的是远程仓库
* 开发期间记得经常 `git remote update upstream` 以保持和远程仓库的同步。
* 在阶段性任务完成之后,`git push`到自己的远程仓库,然后可以在github的web界面发起一个merge request。