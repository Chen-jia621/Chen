如何使用git 上传代码？
1.定位到要上传的文件夹位置，打开终端
  ssh -T git@github.com查看是连接github




2.git add . 上传全部文件
3.git commit -m "###"填写上传原因
4.git fetch origin 获取远程更新
5.git merge origin/master
6.git push origin master
