# Python-12306
12306自动抢票

## 程序功能：
基于Python的12306自动订票程序，如果暂时无票，会一直在后台进行刷新，直到成功购票为止。购票成功后发送邮件到配置邮箱，提醒你进行付款

## 前期准备条件：
一、安装谷歌浏览器（安装最新版即可）  
二、下载可执行程序，保存到本地  
![保存到本地](https://github.com/coder-MartinYoung/Python-12306/blob/master/1.png)  
三、保存“可执行程序”文件夹到本地之后，修改config.ini文件，主要修改如下信息：  
1.[login]段中：username（12306用户名）、password（密码）    
2.[cookieInfo]段中：starts（起始地点）、ends（终点）、dtime（出发日期，注意格式）  
3.[userInfo]段中：users（乘客名字）  
4.[trainInfo]段中：train_types（车次类型）、start_time（出发时间段）  
5.[mail]段中：mail_user[用户名]，mail_pwd（密码，如果是QQ邮箱需要填写授权码，具体授权码获取方式见链接：https://service.mail.qq.com/cgi-bin/help?subtype=1&&id=28&&no=1001256）  

## 程序执行
在上述环境、个人信息都设置好之后，进行如下操作：  
一、运行带有风骚的亚索图标的‘12306.exe’（可能反应会比较慢）  
二、运行之后程序会自动打开谷歌浏览器，根据上面的配置信息，自动填充你的12306的账号和密码，唯一需要做的就是输入12306恐怖的验证码  
![保存到本地](https://github.com/coder-MartinYoung/Python-12306/blob/master/2.png)    
三、第二步中，验证码输入成功后，网页会跳转到12306页面，此时需要做的是：@@@在12306.exe输入‘Y’，然后点击回车确定  
![保存到本地](https://github.com/coder-MartinYoung/Python-12306/blob/master/3.png)  
四、后台会一直刷新买票，当买票成功后悔发送邮件到指定邮箱，提醒你及时付款  
![保存到本地](https://github.com/coder-MartinYoung/Python-12306/blob/master/4.png)  
