# skillsclone

test git branch
git checkout -b branchName
git branch 

Administrator@SY-PC-0019 /E/skillclone/skillsclone (dev)
$ git branch
* dev
  master

Administrator@SY-PC-0019 /E/skillclone/skillsclone (dev)
$ git merge dev
Already up-to-date.

Administrator@SY-PC-0019 /E/skillclone/skillsclone (dev)
$ git checkout master
Switched to branch 'master'
Your branch is up-to-date with 'origin/master'.

Administrator@SY-PC-0019 /E/skillclone/skillsclone (master)
$ git merge dev
Updating 8123cb9..cdbbfb5
Fast-forward
 README.md | 6 +++++-
 1 file changed, 5 insertions(+), 1 deletion(-)

Administrator@SY-PC-0019 /E/skillclone/skillsclone (master)

Git鼓励大量使用分支：

查看分支：git branch

创建分支：git branch <name>

切换分支：git checkout <name>

创建+切换分支：git checkout -b <name>

合并某分支到当前分支：git merge <name>

删除分支：git branch -d <name>
$