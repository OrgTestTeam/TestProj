# 开始

1. 使用brucel50对应的github账号创建组织OrgTestTeam。
2. brucel50邀请ruilovechu加入1中的组织。
3. ruilovechu通过点击2中brucel50发送的邮件确认加入组织。
4. brucel50在组织中创建新项目TestProj.
5. brucel50和ruilovechu分别将4中的项目clone到本地。

# 查看本地分支

1. ruilovechu进入项目文件夹内，使用git branch 查看本地分支。
2. brucel50同1

# 查看远程分支

1. ruilovechu进入项目文件夹内，使用git branch -r 查看远程分支。
2. brucel50同1

# 对比本地分支与远程分支

1. git diff master origin/master

# 切换或创建并切换本地分支

1. ruilovechu使用git checkout -b dev
2. brucel50使用git checkout -b odev

# 此文件是在brucel50的用户的文件夹下创建的，尝试提交本文件。

1. 保存本文件，使用add和commit。

# push 出错

1. 需要在github上由创建者在组织中创建team。并邀请每一个人，并给予相应权限

# 重新进行上面的操作

1. 将origin/master的最新版本恢复到没有该文件的状态，再保存此文件，然后add和commit。由另一用户（ruilovechu）获取