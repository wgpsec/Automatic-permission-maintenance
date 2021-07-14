# Automatic-permission-maintenance
CobaltStrike 上线自动权限维持插件

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

## Socket4

### 主要修改下几个地方

如果使用Server酱功能请填写自己的key

![image](https://user-images.githubusercontent.com/48357278/124566143-5bf11c00-de75-11eb-902f-129ad4fc17e8.png)

## Spawn

1. 修改判断主机存活的心跳时长，默认为60S
2. 修改规定存活主机数量，默认为2
3. 修改系统位数，默认为64位
4. 将XXXX修改为监听器名称，后面的系统位数要保持一致
5. 如果使用Server酱功能请填写自己的key

### 请自备免杀或使用狼组开源免杀工具
