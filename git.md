#svn / git

	介绍:企业主流的两个版本控制/协同开发			工具

git使用的更多

svn:集中式，很多人共享一台服务器
	svn当一个出现问题时整个都会出现问题

	svn checkout	检出
	
	svn update		更新
	
	scn commit		提交
	
git:分布式,git更安全，人手一台服务器

	git 使用
	
		命令行中选择到当前目录
		
		然后 git clone git地址								克隆远程仓库
		
		然后 cd 到当前目录
		
		然后	 git add  文件名称  (添加所有 git add .)
		
		然后 git commit -m '说明'							将本地的文件提交到暂存区
		
		然后 git push 上传									如果是第一次push(上传),需要登陆
		