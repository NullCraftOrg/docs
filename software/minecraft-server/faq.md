---
description: 在新手尝试开一个我的世界服务器时可能遇到的一些问题。
---

# 常见问题

{% hint style="info" %}
如果你的问题这里没有,可以到用户群发送报错截图反馈 (插件/模组报错别反馈,与我们无关!)
{% endhint %}

## Java 相关问题

### Java如何选择以及相关问题

目前随着 Minecraft 的更新，一些服务端要求在 1.17 版本以上开始需要使用 Java11，一些服务端会在 1.16.5 上就开始提示更换对应的 Java 版本。

经过测试，发现如果以 JDK11 作为默认 java 环境变量使用会出现套娃启动(其它版本也有类似情况)，导致开服器无法获取正常 java.exe 对应的 pid，从而无法正确判断服务端状态等。

目前解决方案是如果出现类似问题可以在 `开服器-本体设置` 中手动选择 java.exe 来指定路径，即可解决此问题(大概率)。

## 服务端相关问题

### 为什么我的服务端不能装插件?

**答:** 你用的服务端不支持，需要换服务端，推荐使用 Paper、Spigot、Purpur、Craftbukkit 等。

### 为什么我的服务端不能装模组?

**答:** 你用的服务端不支持 ForgeAPI，需要更换支持模组的服务端，如 Arclight、CatServer、Mohist、官方端打Forge(仅模组)。

{% hint style="info" %}
服务端下载可以前往 `开服器 > 资源广场` 按需选择下载。
{% endhint %}

### 错误: 找不到或无法加载主类 net.minecraft.client.Main 原因: java.lang.ClassNotFoundException: net.minecraft.client.Main

不要将客户端jar当作服务端jar来使用，服务端jar可以到轻开服器自带的资源广场下载或者到MCBBS下载

### _\*\*_ FAILED TO BIND TO PORT!

出现这个然后服务端自动关闭，说明端口与当前软件上的服务端端口冲突了，一般情况下默认端口**`25565`**是不会被使用，尝试关闭所**`java.exe`**的进程，如果依旧出现，重启电脑即可解决

### We appear to be missing one or more essential library files.

此错误代表使用支持模组的服务端但是没有将模组需要的 **`library`** 文件夹(支持库)与服务端一并放入使用导致。

### Error: This Java instance does not support a 64-bit JVM. Please install the desired version.

百度翻译:错误：此Java实例不支持64位JVM。请安装所需版本。\
谷歌翻译:错误：此Java实例不支持64位JVM。 请安装所需的版本。

解决方案:把你电脑所有的**32位Java**都卸载然后重新打开软件就能解决了

## 游戏客户端常见问题

### 登入失败:无效会话

加入服务器时出现此问题表明你使用了盗版模式启动了游戏然后服务端开启了正版验证。进入开服器的**`配置文件`**将正版验证关闭 **或** 使用正版登录进入后服务器即可

### 服务器已过期

顾名思义，绝大部分版本都必须服务端与客服端版本一致，例如**`1.12.2`**的服务端**`1.12`**是进不去的

目前可原生跨版本的有

* 1.8.X
* 1.16.4 - 1.16.5
