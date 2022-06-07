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

3. 