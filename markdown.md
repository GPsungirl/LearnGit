<!-- 1创建目录 -->
### mkdir filename (创建一个空文件夹)
### cd  filename   (进入到当前文件夹)
### pwd  (显示当前目录)
### ls -ah (查看当前.git这种隐藏起来的文件)

*** 注意：版本控制系统能追踪的是文本文件的改动，音视频，图片这种
二进制数据，虽然能追踪，也只是知道从100K改成了200K，具体改了啥不知道。***
<!-- 2GIT初始化 -->
### git init 

<!-- 3把文件交给GIT管理 -->
### git add readme.txt (把文件添加到仓库)
### git commit -m 'wrote a readme.txt' (把文件提交到仓库)

&&:insertions 插入 eg：1 file changed, 2 insertions(+)提示一个文件改变了，插入了2行
