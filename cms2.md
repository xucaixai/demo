1. 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？  
创建仓库、导入仓库、代码片段、组织
2. 如何能将仓库中的html文件直接解析成页面？  
在网页版中打开
3. 如何删除仓库  
在设置里面
4. Bash是什么操作系统的命令  
Linux
5. Pwd是什么命令  
打印当前目录
6. Cd是什么命令
改变当前目录
7. Echo是什么命令  
输出  
8. 配置git用户名的命令  
git config --global user.name ""
9. 配置邮箱的命令  
git config --global user.name ""
10. 命令行换行方式  
/
11. 命令行终结方式  

Ctrl C   (使用时的问题命令行换行\、命令行终结ctrl+c、命令行翻页和退出：j向下一行，k向上一行，G最底端，gg最上端，空格翻一屏，\搜索，n下一个匹配，u下一个匹配,q退出。、vim模式操作vim（模式编辑）：l向右，H向左，dd删除一行，i进入编辑模式，esc键回到普通模式，：键进入命令模式，q！放弃保存退出，wp保存退出、Linux Bash快捷键（ctrl+l清屏）)

12. 使用命令行比GUI方式有何优势  
命令行优势：一次可建多个文件夹，复杂操作可以批处理  
exit退出vim .gitconfig：wpcat .gitconfigworkspace工作区--add-->Index/Stage暂存区--     commit-->Repository仓库区（本地仓库）--checkout-->
     
新建代码仓库：git init在当前目录新建代码库   
下载一个项目和它的整个代码历史添加删除文件：git clone[url（https://github.com/[userName]/reposName）]  
 git add [file1] [file2]添加指定文件到暂存区   
 git rm [file1] [file2]删除工作区文件，并将此次删除放入暂存区   
 git mv [file-origin] [file-renamed]改名文件，并将改名放入暂存区代码提交  
 git commit -m [message]提交暂存区到仓库  
 git commit -a -m [message]直接从工作区提交到仓库，前提该文件已经有仓库中的历史版本   
 
13. 提交到本地仓库时为什么有暂存区  
workspace 里面有很多文件，commite可以提高提交的可密度 
14. 新建代码仓库的命令  
git init在当前目录新建代码库
15. git clone [url] 这个命令的作用是  
下载一个项目和它的整个代码历史添加删除文件：
16. 添加指定文件到暂存区的命令  
git add [file1] [file2]添加指定文件到暂存区  

17. 删除工作区文件，并且将这次删除放入暂存区的命令
git rm [file1] [file2]删除工作区文件，并将此次删除放入暂存区   
      
18. 改名文件，并且将这个改名文件放入暂存区的命令  
git mv [file-origin] [file-renamed]改名文件，并将改名放入暂存区代码提交  

19. 提交暂存区到仓库的命令  
git commit -m [message]提交暂存区到仓库  

20. 直接从工作区提交到仓库的命令  

git commit -a -m [message]直接从工作区提交到仓库，前提该文件已经有仓库中的历史版本  

21. 显示变更信息的命令  

git status  

22. 查看历史信息的命令   

git log  

23. Commit的意义是  ：  

提交  

24. Pull的意义是：  

从github 远程仓库将文件转移到本地  

25. Push的意义是：   

将本地的文件传送到远程仓库
