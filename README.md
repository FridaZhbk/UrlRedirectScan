# UrlRedirectScan

<img src="https://img.shields.io/badge/Author-Zhbk-brightgreen"/> <img src="https://img.shields.io/github/stars/FridaZhbk/UrlRedirectScan.svg"/>

该插件可自动获取Burp中的流量信息，将

## 插件介绍
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
1、该插件可自动获取Logger中的所有流量信息，插件捕获流量信息后会去自动进行Fuzzing，将Fuzzing后成功的请求包显现出来，显现中会带有部分信息。从而实现被动扫描。如果被动扫描成功即可在下列图中显示
  
<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210027086-438b8f35-31b4-4e16-9905-38605f7d7987.png">

2、如果利用内置payload未检测成功，会在此处打印检测了xxxx，没检测到。可根据需求在Logger中找到对应的请求包，发到Repeater中进行绕过操作等

<img width="416" alt="image" src="https://user-images.githubusercontent.com/64958753/210027170-0ce55e9e-400a-4652-b9b3-03302e580d53.png">


