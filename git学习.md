# 版本控制

备份  保存历史记录 互相协作 共享

git下载

设置用户名和密码

![image-20220531171057877](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531171057877.png)

初始化

![image-20220531171123813](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531171123813.png)





![image-20220531171200089](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531171200089.png)

查看状态

git status

![image-20220531171243565](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531171243565.png)

红色表示我们还没有把这些文件上传到本地仓库

git add 添加到本地仓库

![image-20220531171403463](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531171403463.png)



git status 

![image-20220531171439866](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531171439866.png)

绿色代表已提交到工作区



git commit -m 'Register'提交到本地仓库

![image-20220531171803993](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531171803993.png)



远程仓库



设置ssl连接

![image-20220531172740000](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531172740000.png)



创建公钥

![image-20220531173231464](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531173231464.png)



在github上创建仓库

![image-20220531173440810](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531173440810.png)



本地关联远程仓库

![image-20220531173933731](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531173933731.png)

起别名叫origin

![image-20220531174108931](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531174108931.png)

指定主分支 现在github里的主分支就是main默认的

推送到远程仓库 出错

![image-20220531174305914](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531174305914.png)

将远程仓库pull到本地仓库

![image-20220531174650711](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531174650711.png)

[(180条消息) 解决办法：error: failed to push some refs to ‘https://github.com/xxxx.git‘_CreatiZ的博客-CSDN博客](https://blog.csdn.net/zhs260133172/article/details/113882475?ops_request_misc=%7B%22request%5Fid%22%3A%22165399028616780366579659%22%2C%22scm%22%3A%2220140713.130102334.pc%5Fall.%22%7D&request_id=165399028616780366579659&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-3-113882475-null-null.142^v11^pc_search_result_control_group,157^v12^new_style2&utm_term=error%3A+failed+to+push+some+refs+to+https%3A%2F%2Fgithub.com%2FFoolFBL%2FNewCoder.git&spm=1018.2226.3001.4187)

[https://blog.csdn.net/zhs260133172/article/details/113882475?ops_request_misc=%7B%22request_id%22%3A%22165399028616780366579659%22%2C%22scm%22%3A%2220140713.130102334.pc_all.%22%7D&request_id=165399028616780366579659&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-3-113882475-null-null.142%5Ev11%5Epc_search_result_control_group,157%5Ev12%5Enew_style2&utm_term=error%3A+failed+to+push+some+refs+to+https%3A%2F%2Fgithub.com%2FFoolFBL%2FNewCoder.git&spm=1018.2226.3001.4187](https://blog.csdn.net/zhs260133172/article/details/113882475?ops_request_misc={"request_id"%3A"165399028616780366579659"%2C"scm"%3A"20140713.130102334.pc_all."}&request_id=165399028616780366579659&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-3-113882475-null-null.142^v11^pc_search_result_control_group,157^v12^new_style2&utm_term=error%3A+failed+to+push+some+refs+to+https%3A%2F%2Fgithub.com%2FFoolFBL%2FNewCoder.git&spm=1018.2226.3001.4187)

强行提交成功



![image-20220531210652801](C:\Users\SUPER FBL\AppData\Roaming\Typora\typora-user-images\image-20220531210652801.png)