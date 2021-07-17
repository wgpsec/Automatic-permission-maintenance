<h1 align="center">APM 自动维权插件 🏒</h1>

[![GitHub stars](https://img.shields.io/github/stars/wgpsec/Automatic-permission-maintenance)](https://github.com/wgpsec/tig) [![GitHub issues](https://img.shields.io/github/issues/wgpsec/Automatic-permission-maintenance)](https://github.com/wgpsec/tig/issues)  [![](https://img.shields.io/badge/author-H0e4a0r1t-blueviolet)](https://github.com/teamssix) [![](https://img.shields.io/badge/WgpSec-%E7%8B%BC%E7%BB%84%E5%AE%89%E5%85%A8%E5%9B%A2%E9%98%9F-blue)](https://github.com/wgpsec)

# 👾 介绍

Automatic-permission-maintenance，CobaltStrike 上线自动权限维持插件

## 计划任务（Schtasks）

### 主要修改下几个地方

#### Bitsadmin
1. 修改挂在你CS服务器上的可执行文件地址
2. 修改远程下载后要保存的地址及文件名
3. 修改计划任务名称及时间间隔，默认为1分钟执行一次
4. 如果使用Server酱功能请填写自己的key
#### 本地上传
1. 同一目录下新建`script`目录，将免杀exe放入该目录下
2. 修改插件中的exe文件名
3. 修改计划任务名称及时间间隔，默认为1分钟执行一次
4. 如果使用Server酱功能请填写自己的key

## Socks4

### 主要修改下几个地方

1. 如果使用Server酱功能请填写自己的key

![image](https://user-images.githubusercontent.com/48357278/124566143-5bf11c00-de75-11eb-902f-129ad4fc17e8.png)

## Spawn

### 主要修改下几个地方

1. 修改判断主机存活的心跳时长，默认为60S
2. 修改规定存活主机数量，默认为2
3. 修改系统位数，默认为64位
4. 将XXXX修改为监听器名称，后面的系统位数要保持一致
5. 如果使用Server酱功能请填写自己的key

## 🤖 更新日志

[2021.06.30]
<ul type="circle"> 
  <li>修改Server酱URL</li>
  <li>增加本地上传模块，可与bitsadmin进行替换</li>
</ul>

[2021.07.14]
<ul type="circle">
  <li> 增加Socks4插件</li>
  <li> 增加Spawn插件</li>
</ul>

## 🥷 其他

请自备免杀工具，免杀可以使用 [狼组Plat平台](https://plat.wgpsec.org)

[![Stargazers over time](https://starchart.cc/wgpsec/Automatic-permission-maintenance.svg)](https://starchart.cc/wgpsec/tig)

关注公众号回复 “加群” 即可加入官方交流群

![](https://teamssix.oss-cn-hangzhou.aliyuncs.com/wechat.png)

## ⚠️ 免责声明

此工具仅作为网络安全攻防研究交流，请使用者遵照网络安全法合理使用！
如果使用者使用该工具出现非法攻击等违法行为，与本作者无关！
