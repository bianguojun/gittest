Git学习内容整理：
创建版本库：
1.初始化一个Git仓库，使用git init命令。
2.添加文件到Git仓库，分两步：
  先在路径下创建文件，或者通过命令创建 mkdir 文件名；（新建文件夹），
  touch 文件名带后缀；（创建文件）；
  第一步：使用命令git add <文件名>，注意，可反复多次使用，添加多个文件；
  第二步：使用命令git commit -m "提交描述信息"；完成提交；