# :window:	Deskbypass


```
                        _____            _    _                               
                       |  __ \          | |  | |                              
                       | |  | | ___  ___| | _| |__  _   _ _ __   __ _ ___ ___ 
                       | |  | |/ _ \/ __| |/ / '_ \| | | | '_ \ / _` / __/ __|
                       | |__| |  __/\__ \   <| |_) | |_| | |_) | (_| \__ \__ \
                       |_____/ \___||___/_|\_\_.__/ \__, | .__/ \__,_|___/___/
                                                     __/ | |                  
                                                    |___/|_|                  
```

<br/><br/>
  <p align="center">
    <img alt="GitHub Contributors" src="https://img.shields.io/badge/%E4%BD%9C%E8%80%85-%E5%BC%B1%E9%B8%A1-red" />
    <img alt="GitHub Contributors" src="https://img.shields.io/badge/%E5%8D%9A%E5%AE%A2-https://wiki.ruojisec.com/-blue" />
    <img alt="GitHub Contributors" src="https://img.shields.io/badge/%E5%AE%89%E5%85%A8%E5%9B%A2%E9%98%9F-One--fox-pink" />
    <img src="https://badgen.net/github/stars/RuoJi6/Deskbypass/?icon=github&color=black">
    <img src="https://badgen.net/github/issues/RuoJi6/Deskbypass">
    <a href="https://flowus.cn/share/134f2136-1c04-46fb-b1c1-693975dc42ee">
    <img src="https://img.shields.io/badge/%E6%96%87%E5%BA%93-wiki-yellow">
    </a>
</p>

拿到webshell权限之后，当我们想上C2远控的时候，发现有杀软，这个时候就很麻烦，那这个项目就是通过一些远程桌面软件绕过杀软件

<br/>

## 🚀上手指南

📢 请务必花一点时间阅读此文档，有助于你快速熟悉Deskbypass
<br/><br/>

| :lock:模块                                      | 火绒               | 360                | 卡巴斯基           | windows dfender    | 推荐指数                             | 备注                                                         |
| ----------------------------------------------- | ------------------ | ------------------ | ------------------ | ------------------ | ------------------------------------ | ------------------------------------------------------------ |
| RustDesk 1.1.9                                  | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star::star::star: |                                                              |
| 向日葵安装版本[旧版本]                          | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :star::star:                         |                                                              |
| 向日葵安装版本[SunloginClient_15.1.0.58718_x64] | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :star::star::star:                   | 因为需要读取内存，会被360发现                                |
| 向日葵SOS版本SunloginClientSOS_1.2.1.58835      | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star::star::star: |                                                              |
| ToDesk个人版本便携ToDesk_Lite_4.7.1.5           | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             |                                                              |
| ToDesk个人版本已经安装[临时密码] ToDesk_4.7.1.5 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             |                                                              |
| ToDesk个人版本已经安装[永久密码] ToDesk_4.7.1.5 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             |                                                              |
| ToDesk个人版本安装版静默安装                    | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             |                                                              |
| AnyDesk                                         | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             |                                                              |
| GotoHTTP                                        | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             |                                                              |
| TeamViewer                                      | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             | 11.0.259193 [yes]<br/> 12.0.259192 [yes]<br/>13.2.36224 [yes]<br/>14.7.48671 [yes]<br/>15.45.4 [NO] |
| 阿里云安全中心平台                              | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star::star:       |                                                              |
| 阿里云ECS云助手                                 | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star::star:       |                                                              |
| 360企业安全云                                   | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star::star:       |                                                              |
| 腾讯云自动化助手                                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star::star:       |                                                              |
| RayLink便携版本 RayLinkLite_v6.1.6.8            | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             | 因为需要读取内存，会被360发现                                |
| RayLink安装版本 RayLink_v6.2.6.9                | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             | 因为需要读取内存，会被360发现                                |
| 爱思安装版本i4Remote_v1.0.32_Setup_x64_700001   | :heavy_check_mark: | :x:                | :heavy_check_mark: | :heavy_check_mark: | :star::star::star::star:             | 因为需要读取内存，会被360发现                                |



<br/>

## :zap:提交问题
有问题建议请提交issues<br/>
<a href="https://github.com/RuoJi6/HackerPermKeeper/issues"><img src="https://badgen.net/github/issues/RuoJi6/HackerPermKeeper"></a>
<br/>
加我微信进开发者微信群聊 
<br/><img src="https://img.shields.io/badge/WeChat-vivo50KFCKFC-green">
<br/>
<br/>

## :world_map:版本更新
```
1.0 
 RustDesk
 向日葵安装版本
 向日葵SOS版本
 ToDesk个人版本便携
 ToDesk个人版本已经安装[临时密码]
 ToDesk个人版本已经安装[永久密码]
 ToDesk个人版本安装版静默安装
 AnyDesk
 GotoHTTP
------------------------------------------------------
1.1
 1、修改图片错误
 2、修改标题错误
 3、添加TeamViewer 11 12 13 14 15版本抓取密码测试
------------------------------------------------------
2.0
  1、阿里云安全中心平台，阿里云ECS云助手，360企业安全云，腾讯云自动化助手
------------------------------------------------------
3.0
  1、添加爱思，RayLink，向日葵最新版本读取密码
```

<br/>

## :beginner:开发日志
<a href="https://flowus.cn/share/134f2136-1c04-46fb-b1c1-693975dc42ee">点击跳转wiki</a>

<br/>

## :clap:致谢
Chixy👑<br/>
森然<br/>
李坦然<br/>
闲客<br/>
黑白之道<br/>
3had0w<br/>
Zhiyu<br/>
Q16G<br/>
zksmile<br/>
潇湘信安<br/>
冰蚕实验室<br/>
NGC660安全实验室<br/>
感谢这些师傅以及公众号提供的思路，让我受益良多[以上排名不分先后]

<br/>


## :star2:Stargazers over time [![Stargazers over time](https://starchart.cc/RuoJi6/Deskbypass.svg)](https://starchart.cc/RuoJi6/Deskbypass)

<a href="https://github.com/RuoJi6">
  <img height=150 align="center" src="https://github-readme-stats.vercel.app/api?username=RuoJi6"/>
</a>
<a href="https://github.com/RuoJi6/Deskbypass/">
  <img height=150 align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=RuoJi6&layout=compact&langs_count=8&card_width=320" />
</a>
