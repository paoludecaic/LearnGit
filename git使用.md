一、基础命令行
    
    1、查看配置     git config --global --list

        文件路径    "C:\Users\Username\.gitconfig"

        级别
            config  全局变量

                system  系统级变量
                global  用户级变量

    2、配置git

    配置用户名       git user.name='GithubUsername'
    配置用户邮箱     git user.email=1234567890@xxx.com

    3、基础命令行

    初始化仓库  git init

    添加文件到暂存区
        git add filename.filetype       
            *.filetype

    添加文件到仓库
        git commit -m "提交内容说明"

    查看提交日志
        git log     次数较少
        git log --pretty=oneline    次数较多

    
    查看仓库当前的状态    git status

    添加远程仓库    git remote add origin URL
    查看当前已有仓库    git remote -v
    推送到远程仓库  git push -u origin master
        默认master分支

    创建新的分支    git branch NowBranchName

    切换分支    git checkout BranchName

    删除分支    git branch -d BranchName

    合并分支    
        git checkout BranchName1
        git merge BranchName2

    克隆仓库    git clone URL




    链接：
        github ： https://github.com/
        清华大学镜像开源 ：https://mirrors.tuna.tsinghua.edu.cn/


        https://blog.csdn.net/qq_48759664/article/details/120462855