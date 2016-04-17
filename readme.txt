cd 进入需要进行管理的文件根目录

mkdir //创建文件夹

dir //查看当前路径下的所有文件目录

git init //创建版本库

git add //增加至版本库

git commit -m "修改注释" // 提交

git status //查看仓库状态

git log //查看所有版本（从最远的到最近的，最上边的是最近的），有版本号（16进制）

git log --pretty=oneline  //将版本日志简化成每个版本一行，可以看到版本号

git reset --hard head^  //回退到上一个版本

git reset --hard 6fd532 //回退后  返回之前的版本(后面的是之前版本的commit id) 

git reflog //会退后，想返回之前未回退的版本，根据此命令查看之前的版本号

