**整体步骤：**

1.从云端同步文件

`git pull`  	



2.检查当前文件的状态（云端哪些文件在本地有changes，本地哪些文件在云端为untrack）

`git status`  	



3.将发生变化的目录纳入控制

`git add + 目录` 或 `git add .`	（纳入全部）

​	

4.再次检查状态，看看untrack和changes是否已经track

`git status`	



5.对此次上传添加commit

`git commit -m "本次的评论"`	



6.上传到云端

`git push origin master`	

