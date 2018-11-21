# TrainTicket
在12306.com购买火车票

## 使用方法:
1.在config.ini中设置12306用户名、密码，乘车人信息 
```
## 登陆账号和密码
[login]
### username：12306登录用户名，必选参数
username=
### password：12306登录密码，必选参数
password=

## users：乘客姓名，必选参数，中文姓名，支持多个乘客，用英文逗号隔开，例如：张三,李四
### 乘客姓名需要提前加入到登录的12306账号的联系人中，为了程序自动选择乘客姓名
[userInfo]
users =
```
2.[点击下载chromedriver](http://npm.taobao.org/mirrors/chromedriver/)  
3.在config.ini中配置chromedriver信息
```
## 路径信息
[pathInfo]
### driver_name: 浏览器名称，必选参数
driver_name = chrome
### executable_path: 浏览器驱动路径，必选参数
executable_path =

```
4.运行TicketInf.py
