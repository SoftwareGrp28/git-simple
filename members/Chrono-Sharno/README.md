## 第一次 Git 实验总结

1. `git add` 的作用是：把工作区的改动加入暂存区，标记这些改动准备参与下一次 commit 提交
2. `git commit` 的作用是：将暂存区里已经 add 的改动，生成本地的提交记录，保存到本地 Git 仓库
3. 本次实验中 `git restore notes.md` 的作用是：丢弃工作区对 notes.md 的修改，把文件恢复成暂存区的版本，撤销本地未 add 的改动
4. `commit` 与 `push` 的区别是：commit：只在本地电脑生成版本提交，改动保存在本机 Git 数据库，远程 GitHub 看不到。push：把本地已经存在的 commit 提交记录，上传推送到 GitHub 远程仓库，让远程服务器同步你的版本，其他人可以看到。