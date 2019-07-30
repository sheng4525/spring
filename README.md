# spring
# 1使用https推送
# 步骤
# 1.创建一个目录
mkdir Test
# 2.将当前目录变为git管理仓库
git init
# 3.将文件添加到版本库，这里将目录下的所有文件都添加进去了
git add .
# 4.告诉git将文件提交到仓库
git commit -m "first-commit"
# 5.将当前仓库与远程仓库关联
git remote add origin 远程仓库的https地址 # eg: git remote add origin https://github.com/sheng4525/spring.git
# 6.将仓库内master分支的所有内容推送到远程仓库,这里会使用到Github的账号密码
git push -u origin master


#如果已经提交过代码了，先进行本地与github代码同步
get pull --all

#强行上传
git push -u origin +master 
