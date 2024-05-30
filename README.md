# LiveHelper

一个安全、简单、易用的多平台直播流转推工具。

不同直播厂商的推流地址只需要保存在本地，没有隐私泄漏的问题。界面简单，操作容易。


## 如何使用

此工具需要和其他推流工具配合使用，比如使用OBS开播，需要先把直播流推到LiveHelper，LiveHelper再把直播流分发到不同的直播平台。

*注意：此工具需要同推流工具部署到同一台机器上*

### 1、启动服务

填入端口号，点击【启动】。

![image](https://github.com/LiveMediaTools/LiveHelper/assets/90186099/a6b616d9-a246-4e96-a1ee-58584e03d24c)

### 2、创建流

在流配置界面，点击【+】，输入流名称（这个随意填写）和流地址，流地址点击 【GENERATE URL】自动生成。
![image](https://github.com/LiveMediaTools/LiveHelper/assets/90186099/813fd424-8136-47ea-befc-710dd7214d2d)

### 3、添加不同平台转发配置

点击流转发平台下的 【+】，输入特定平台的推流地址（从直播平台获取）和名称（随意），点击【OK】。


![image](https://github.com/LiveMediaTools/LiveHelper/assets/90186099/a23b4185-0443-44ed-8758-675d6b5f1605)

点击各个平台的开始按钮。

![image](https://github.com/LiveMediaTools/LiveHelper/assets/90186099/67cbd500-d15c-46c3-b929-016808c3c07b)


### 4、OBS推流

把流配置TAB页对应的 Server 和 Stream Key 填入到OBS对应的推流信息中，开始推流即可。直播流就可以转发到不同的平台上。

![image](https://github.com/LiveMediaTools/LiveHelper/assets/90186099/c9e78cf3-fab4-41cf-ae29-e2764bf08595)

![image](https://github.com/LiveMediaTools/LiveHelper/assets/90186099/c3bcccac-3b14-4633-b2ea-734920f8ab2e)
