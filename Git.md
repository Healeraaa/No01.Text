### Git全局配置

#### 设置用户名和email地址

![c846f297-55ad-4def-b34b-caf9eaa469d7](file:///C:/Users/UserX/Pictures/Typedown/c846f297-55ad-4def-b34b-caf9eaa469d7.png)

### 获取Git仓库

#### 本地初始化

![e993de21-5234-4d4a-bfc4-6cf1c5ca2b40](file:///C:/Users/UserX/Pictures/Typedown/e993de21-5234-4d4a-bfc4-6cf1c5ca2b40.png)

#### 克隆远程仓库

![0e708f41-4f36-4228-9af6-20415766d285](file:///C:/Users/UserX/Pictures/Typedown/0e708f41-4f36-4228-9af6-20415766d285.png)

### 基本概念

#### 工作区->暂存区：git add

#### 暂存区->版本库：git commit

![d1d4cc86-2b22-4baa-a17b-0b27f8e5382e](file:///C:/Users/UserX/Pictures/Typedown/d1d4cc86-2b22-4baa-a17b-0b27f8e5382e.png)

#### 工作区文件状态---git status查看

![e6feaba8-bdf5-4b31-8a02-ab1a99ac0488](file:///C:/Users/UserX/Pictures/Typedown/e6feaba8-bdf5-4b31-8a02-ab1a99ac0488.png)

### 本地仓库操作

![cafcbef0-b791-4de4-aab9-6ffdaf5efd66](file:///C:/Users/UserX/Pictures/Typedown/cafcbef0-b791-4de4-aab9-6ffdaf5efd66.png)

#### git status

用于查看文件状态

![3d5924fe-6114-4d5f-bcd9-1bf933d5f4eb](file:///C:/Users/UserX/Pictures/Typedown/3d5924fe-6114-4d5f-bcd9-1bf933d5f4eb.png)

#### git add

将文件的修改加入暂存区

![4a1fb1bc-c76f-432f-b026-ef1a091ad42b](file:///C:/Users/UserX/Pictures/Typedown/4a1fb1bc-c76f-432f-b026-ef1a091ad42b.png)

#### git reset

将暂存区的文件取消暂存或者是切换到指定版本

![53b84f3a-edae-43c4-bad9-a360fe1e2eef](file:///C:/Users/UserX/Pictures/Typedown/53b84f3a-edae-43c4-bad9-a360fe1e2eef.png)

#### git commit

git commit -m '*******'     将暂存区的文件修改提交到版本库-m '*******''是对于本次提交的注释

![0a15ddf2-66d7-4b42-906f-21eb758de231](file:///C:/Users/UserX/Pictures/Typedown/0a15ddf2-66d7-4b42-906f-21eb758de231.png)

#### git log

查看日治

必须在工作区目录下使用

![f1ab28f1-1e10-44bd-9b14-c95d6096a907](file:///C:/Users/UserX/Pictures/Typedown/f1ab28f1-1e10-44bd-9b14-c95d6096a907.png)

#### 回退版本

git reset --hard 版本号

![58e930b2-9821-4465-97ee-e2fdf3eb35da](file:///C:/Users/UserX/Pictures/Typedown/58e930b2-9821-4465-97ee-e2fdf3eb35da.png)



### 远程仓库操作

![149891d4-15af-44a4-84b9-df01744ecd41](file:///C:/Users/UserX/Pictures/Typedown/149891d4-15af-44a4-84b9-df01744ecd41.png)

#### git remote

远程仓库操作-查看

加上-v ，可以查看详细信息

![6a1559b2-2e0b-4f25-b1b1-0d7068475661](file:///C:/Users/UserX/Pictures/Typedown/6a1559b2-2e0b-4f25-b1b1-0d7068475661.png)

#### git remote add

远程仓库操作-添加

下方的<shortname>为远程仓库别名 <url>为远程仓库地址

![fc78e5ce-a1ec-4d58-bbbf-e4f3fa0417ad](file:///C:/Users/UserX/Pictures/Typedown/fc78e5ce-a1ec-4d58-bbbf-e4f3fa0417ad.png)

#### git clone

![219f54db-7538-4eb8-897b-8ffdbe2b930d](file:///C:/Users/UserX/Pictures/Typedown/219f54db-7538-4eb8-897b-8ffdbe2b930d.png)

#### git push

![55a321c5-3d5d-4b26-98ff-960e1ed787d3](file:///C:/Users/UserX/Pictures/Typedown/55a321c5-3d5d-4b26-98ff-960e1ed787d3.png)













### 可能会遇到的问题

#### END(end)问题

 q可以退出

#### Git 查看所有分支

git branch -a

#### 删除本地分支

git branch -d BranchName             （BranchName是你本地分支要删除的）

#### git分支切换

 git checkout BranchName              （BranchName切换分支的名字）













### 修改Git网络设置

![251d4f37-572f-4989-929c-acd87ec69d68](file:///C:/Users/UserX/Pictures/Typedown/251d4f37-572f-4989-929c-acd87ec69d68.png)

![43e9cb34-ff0c-47bf-b10e-0e54b3c5e4c3](file:///C:/Users/UserX/Pictures/Typedown/43e9cb34-ff0c-47bf-b10e-0e54b3c5e4c3.png)
