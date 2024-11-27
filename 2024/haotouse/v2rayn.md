---
icon: windows
description: V2rayN
---

# V2rayN教程

**界面预览**

<figure><img src="../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

## **下载**

本站提供官方Github下载地址、Google Play商店与本站镜像三种下载途径，不定时更新客户端版本。本站镜像已经过多个杀毒软件及安防平台扫描，安全无毒，请放心下载。

<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td>Github官方下载</td><td> <a href="https://github.com/2dust/v2rayNG/releases/download/1.9.16/v2rayNG_1.9.16_universal.apk">1.9.16版本</a></td><td></td></tr><tr><td>GooglePlay安装</td><td><a href="https://play.google.com/store/apps/details?id=com.v2ray.ang">GooglePlay商店下载</a></td><td></td></tr><tr><td>本站镜像</td><td></td><td></td></tr></tbody></table>

## **安装教程**

a. 软件目录

下载完成后，找到合适的目录，推荐安装在非系统盘，解压压缩包，解压后的目录如下图所示。

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

找到软件主程序 `v2rayN.exe` 双击鼠标左键即可开始使用，程序启动后会最小化到任务右小角的托盘，鼠标双击蓝色的 `V` 字小图标，即可打开软件的主界面。

b. 托盘图标状态说明

不同状态下软件的图标颜色是不一样的，参考下表图标颜色说明。

<table><thead><tr><th width="90">图标</th><th width="171">软件状态</th><th>说明</th></tr></thead><tbody><tr><td><img src="../.gitbook/assets/image (5) (1).png" alt="" data-size="original"></td><td>清除系统代理</td><td>每次启动/重启服务的时候，强制把windows系统(ie)的代理清除掉。</td></tr><tr><td><img src="../.gitbook/assets/image (6) (1).png" alt="" data-size="original"></td><td>自动配置系统代理</td><td>每次启动/重启服务的时候，强制设定windows系统(ie)的代理。</td></tr><tr><td><img src="../.gitbook/assets/image (7) (1).png" alt="" data-size="original"></td><td>不改变系统代理</td><td>每次启动/重启服务的时候，什么都不做。作用就是保留其他软件设定的代理。</td></tr></tbody></table>

## **使用教程**

1.首先找到文件夹中的「v2rayN.exe」文件，双击运行

<figure><img src="../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure>

**注意**：此软件打开后如果找不到主画面，可以在电脑右下角任务栏中点击 “V” 图标以显示主页面

<figure><img src="../.gitbook/assets/image (9) (1).png" alt=""><figcaption></figcaption></figure>

2.从本站【仪表盘→一键订阅】中【复制订阅地址】

3.设置「V2rayN-Core」订阅

3.1.点击主界面的「订阅分组」-「订阅分组设置」-「左上角添加」

<figure><img src="../.gitbook/assets/image (24).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

3.2.点击主界面的「随意设置分组名」-「可选地址填入主页复制的订阅地址」-「点击确认」

<figure><img src="../.gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>

3.3.回到v2rayN主页界面「点击订阅分组」-「选择更新全部订阅不通过代理」

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption></figcaption></figure>

## **连接教程**

在添加完节点信息后，开启系统代理并选择路由模式，即可开始使用代理服务器上网了，如下面**系统代理**及**路由模式**章节所述。

#### 选择节点

在软件主界面选择任意节点，单击鼠标右键，在弹出的窗口中扎到设为活动服务器即可选择节点，如下图所示，然后开启系统代理即可，也可以选择任意节点，双击鼠标左键选择节点。

<figure><img src="../.gitbook/assets/image (25).png" alt=""><figcaption></figcaption></figure>

#### 系统代理

按照上面的配置教程配置完服务器（节点）后，需要设置系统代理才能让浏览器支持科学上网功能，在任务栏右下角系统托盘找到软件的图标，在图标上**单击鼠标右键**，点击**自动配置系统代理**，此时软件的图标会标称**红色**，至此就可以开始使用了，打开 [Google](https://www.google.com/) 试试能不能访问吧。

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption></figcaption></figure>

#### 路由模式

路由的功能是将入站数据按需求由不同的出站连接发出，以达到按需代理的目的。这一功能的常见用法是分流国内外流量，可以通过内部机制判断不同地区的流量，然后将它们发送到不同的出站代理，有以下三种路由模式可以选择。

* 绕过大陆(Whitelist)模式：即原先版本里的白名单，只是白名单内的网站通过节点服务器代理上网
* 黑名单(Blacklist)模式：除了黑名单内的网站，其余网站都通过节点服务器代理上网
* 全局(Global)模式：所有网站通过节点服务器代理上网

根据不同的需求选择合适的路由模式，一般选择白名单模式。

<figure><img src="../.gitbook/assets/image (27).png" alt=""><figcaption></figcaption></figure>

#### 开机自动启动

在点击软件主界面的`设置`，点击`设置`然后点击`参数设置`进入参数设置页面，如下图所示：

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

进入参数设置后，选择`v2rayN设置`标签页，勾选上开机自动启动复选框，然后点击确认，如下图所示。

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

### 更新教程

可在线自动更新软件、Xray-Core、sing-box Core、Geo files，通过点击软件主界面的`检查更新`进行在线更新，如下图所示。

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>
