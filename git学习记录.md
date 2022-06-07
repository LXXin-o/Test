# git学习记录

1. 添加并提交文件
   - git add *文件名*
   - git commit -m *“添加备注”*
   - git push
   
2. 查看仓库的当前状态
   - git status
   
3. 查看历史记录
   - git log
   - git log --pretty=oneline
   
4. 退回到上一个版本

   - git reset --hard *HEAD^*

     HEAD^表示上一个版本

   - git reset --hard *1904a*

     1904a表示指定的版本号

5. 工作区和暂存区

   - 工作区：电脑里能看到的目录

     ![](C:\Users\ty\AppData\Roaming\Typora\typora-user-images\image-20220607103318944.png)

   - .git是git的版本库，里面最重要的就是成为stage（或叫index）的暂存区

     把文件往Git版本库里添加的时候，是分两步执行的：

     第一步是用`git add`把文件添加进去，实际上就是把文件修改添加到暂存区；

     第二步是用`git commit`提交更改，实际上就是把暂存区的所有内容提交到当前分支。

3. 