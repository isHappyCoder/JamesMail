##JamesMail部署步骤
JamesMail下载完成后解压，打开config目录,config下存放james的配置文件：

- 修改*james-database.properties*加入数据源配置
![james-database.properties](https://github.com/GepengCn/tonglian-openfire/blob/master/images/filezilla.png?raw=true)

- 配置协议端口IMAP默认端口是143，如果想修改在imapserver.xml中将143改为其他端口
- 配置协议端口SMTP默认端口是25，如果想修改在smtpserver.xml中将25改为其他端口
- 配置协议端口POP3默认端口是110，如果想修改在pop3server.xml中将110改为其他端口
