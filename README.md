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
一、扫描显现
这块内容，会在插件检测到存在跳转漏洞时会将对应请求类型、请求头、请求Url、触发参数显现出来，显现出来后，也可将其发制Repeater模块进一步操作，具体不再演示，此处存在不可避免的误报情况。某些网站会检测出跳转到它们的多级域名下的情况，此处为误报。
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/223010025-1cc50d29-ef75-4433-af03-2b429aded4c2.png">
二、扫描设置
2.1 白名单设置
	此处可设置白名单
	
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/223010048-126dac33-aaff-43bc-9eba-d609446166f7.png">
	
	白名单可有四个按钮进行设置，第一个“Add”为在输入框输入后依次添加，第二个“Clear”为清除白名单中所有内容，第三个“Remove”依次从下到上移除信息，第四个“LoadFile“为加载外部txt文件(仅支持txt文件)
	例如，不测试test.com的域名，那么直接添加test.com
	
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/223010224-0cae19c8-df93-49b2-a7a9-51f1b53ac1f7.png">

当然也可以加载外部文件，点击LoadFile后选择txt文件即可添加到白名单中

<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/223010260-e52bf14a-adaf-4b33-b040-993a8ccd005a.png">

旁边的参数Params与Payloads都是类似的操作。
插件保留了原先设定的内置参数及payload，可以在此处进行选择

<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/223010290-2cb4e77d-6dc1-461c-b9df-a475d6c83165.png">

Self代表使用插件内置参数及Payload
Set代表使用用户自己设置的参数及Payload	



## 使用反馈
用户A
	通过该插件，梅开二度，并结合其他漏洞，结合形成组合拳攻击，在某平台上提交两个高危漏洞，并获取该平台的春节礼盒
	
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210129886-89053bdb-8de5-4639-9aff-6aca8a30637a.png">

用户B：
	通过该插件，在某平台上获取新人新春礼盒，该平台的新春礼盒真的好看，收到反馈后，作者表示羡慕死了
	
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210129888-6389092d-66bc-48d6-a2ba-55b65dcbe8f2.png">

作者：
	通过该插件捡了个重定向漏洞，不多不少，刚好凑齐最后一宫格新春礼盒
	
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210129896-33d89df1-ab4a-4451-90db-527d697d7159.png">


