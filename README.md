# UrlRedirectScan

<img src="https://img.shields.io/badge/Author-Zhbk-brightgreen"/> <img src="https://img.shields.io/github/stars/FridaZhbk/UrlRedirectScan.svg"/>

## 插件介绍

	该插件从最简单的Url重定向开始，目标是打造一款自动化漏洞挖掘的工具，该插件目前可实现自动化获取burp流量，并通过内置Payload方法进行Fuzzing，会将成功跳转的请求相关信息展示在页面中，用户可根据需求进一步操作及判断，目前涵盖到的Payload为作者通过Github、Freebuf、安全客、奇安信攻防社区等方面收集到的Payload结合后统计的，基本上已经涵盖了全部可能性。所以在测试过程中，可尽情的点击测试功能，该款插件会帮助你自动去识别流量，当你测试完毕的时候，只需点击插件UI界面查看是否有结果即可，是一款捡洞必备的工具，在今年，该工具已经帮助诸多白帽子获取各大SRC平台的中秋礼盒及春节礼盒。
	该插件不会仅仅局限于Url重定向，Url重定向只是这个插件的开始。

## 安装方法
1、在Burp中的Extender中点击Add添加

<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210026944-41cef7ce-8db1-41c6-a56b-46f2d4ba2357.png">
2、点击Select file

<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210026967-46b3499d-fe3b-4342-8990-2fb12df9e2e0.png">

3、选中插件

<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210026992-f8067137-3071-44ed-9e43-a302ca48a2e5.png">

4、选中后点击Next即可安装

<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210027016-5b460743-cc2a-4688-be7e-125d50747af4.png">

5、在output中出现以下输出即代表安装成功

<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210027039-b503f30e-e2c9-402f-b486-9b13ffdf0211.png">

## 使用方法
1、该插件可自动获取Logger中的所有流量信息，也就是经过Burp的所有httpl巨量，插件捕获流量信息后会去自动进行请求包Fuzzing，将Fuzzing后成功的请求包发送到插件的UI界面中展现，包括请求方法，Host、Url、Paramas信息
  
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210027086-438b8f35-31b4-4e16-9905-38605f7d7987.png">

2、如果利用内置payload未检测成功，会在此处打印检测了xxxx，没检测到。可根据输出的关键信息在burp流量中进行搜索，并根据自己的需求进行二次构造。

<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210027170-0ce55e9e-400a-4652-b9b3-03302e580d53.png">


## 使用反馈
  <img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210129886-89053bdb-8de5-4639-9aff-6aca8a30637a.png">
  <img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210129888-6389092d-66bc-48d6-a2ba-55b65dcbe8f2.png">
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210129896-33d89df1-ab4a-4451-90db-527d697d7159.png">
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210129899-14f2014c-88bc-4838-832f-a98f67a9c34e.png">


