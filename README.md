
## 一、概念

- 版本控制：是一种在开发过程中用于管理我们对文件、目录或工程等内容的**修改历史**，方便查看更改历史记录，备份以恢复以前版本的软件工程技术。
- 版本控制分类  
	1. 本地版本控制：记录文件每次的更新，可以对每个版本做一个快照，或是记录补丁文件，适合个人用，如RCS。<br>![image.png|500](https://raw.githubusercontent.com/tayentay/myimg/main/Obsidian/202304151550874.png)
	2. 集中式版本控制：所有的版本数据都保存在服务器上，协同开发者从服务器上同步更新或上传自己的修改，如SVN。![image.png|500](https://raw.githubusercontent.com/tayentay/myimg/main/Obsidian/202304151551540.png)
	3. 分布式版本控制：所有版本信息仓库全部同步到本地的每个用户，这样就可以在本地查看所有版本历史，可以离线在本地提交,只需在连网时push到相应的服务器或其他用户那里。由于每个用户那里保存的都是所有的版本数据，只要有一个用户的设备没有问题就可以恢复所有的数据，但这增加了本地存储空间的占用。每个人拥有全部代码（安全隐患），如Git。![image.png|500](https://raw.githubusercontent.com/tayentay/myimg/main/Obsidian/202304151610884.png)
- Git和SVN主要区别
	![image.png|800](https://raw.githubusercontent.com/tayentay/myimg/main/Obsidian/202304151614102.png)






