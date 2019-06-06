# Apache james
<div align="left">

[![](https://img.shields.io/badge/%E4%B8%8B%E8%BD%BD-Apache%20james-yellowgreen.svg)](http://james.apache.org/download.cgi)
[![](https://img.shields.io/badge/%E7%89%88%E6%9C%AC-Apache%20James%20Server%203.0_beta4-green.svg)]()

</div>

## 介绍
   James小巧，可扩展而又不失强大，其支持pop，smtp以及相关SSL/TLS加密协议。可以用做开发测试，也可以对其扩展封装后作为企业级邮件服务。james-servser是一个配置好的jamesServserdemo可以下载用来参考。
不过有一点需要说明的是，现在国内的很多云服务器是默认关闭 25 端口的，也就是默认不能使用未加密的 smtp 发送邮件，据说是为了减少垃圾邮件的产生。
那如果服务器是国内云服务器，需要实现和外网（如QQ,163邮件服务）之间收发邮件的话，只有三个办法：
- 1.申请开通25端口。不过申请基本不会通过…
- 2.使用加密的smtp协议传输。其端口则可以使用 465 等，避免使用25端口。
- 3.使用aws服务器。网上也听说会封25端口，不过我当时（2017年12月份末）测试时，还是可以使用的。

 

## 入门

### 部署

- 下载jdk并配置环境变量

- 下载[JamesMail][DOWNLOAD_JAMESMAIl]并解压

- [部署][DEPLOY]

- [官方文档][DETAIL]





[DEPLOY]:https://github.com/GepengCn/tlim/blob/master/src/CAP_DEPLOY.md
[DOWNLOAD_JAMESMAIl]:https://http://james.apache.org/download.cgi
[DETAIL]:http://james.apache.org/server/index.html