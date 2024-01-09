---
description: Minecraft Server
---

# 我的世界开服器

{% hint style="info" %}
**此项目是《灵工艺》目前为《我的世界》开发的最新版开服工具。**

此工具的前身项目为：[灵工艺我的世界开服器Pro](../../outdated/minecraft-server-pro.md)，由于年代久远，编码可读性差，性能优化问题等废弃。

目前已替换为当前版本。
{% endhint %}

```csharp
Software software = new Software();
software.Name = "我的世界开服器";
software.ProjectID = "Minecraft Server";
software.Release = "https://nullcraft.org/d/4";
software.ReleaseDate = DateTime.Parse("2015,12,10").ToString();
software.Language = new string[] { "简体中文" };
software.Program = "C#";
software.Framework = ".NET4.8";

//NullCraftSoftwareList.add(software);
NullCraftSoftwareList[0] = software;

Console.WriteLine(NullCraftSoftwareList.Items.Conut());

>>> 1
```

## 关于《我的世界开服器》

### 下载《我的世界开服器》

#### 前往灵工艺官方下载：

{% embed url="https://nullcraft.org/d/4" %}

#### 前往 MCBBS 论坛贴下载：

{% embed url="https://www.mcbbs.net/thread-529520-1-1.html" %}

### 如果你想知道最近更新了什么

{% content-ref url="update.md" %}
[update.md](update.md)
{% endcontent-ref %}

### 开服上的常见问题

{% content-ref url="faq.md" %}
[faq.md](faq.md)
{% endcontent-ref %}

### 软件图片

<figure><img src="../../.gitbook/assets/minecraft-server-lite_1.png" alt=""><figcaption><p>我的世界开服器 - 主页</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/minecraft-server-lite_2.png" alt=""><figcaption><p>我的世界开服器 - 控制面板</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/minecraft-server-lite_3.png" alt=""><figcaption><p>我的世界开服器 - 配置文件</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/minecraft-server-lite_4_1.png" alt=""><figcaption><p>我的世界开服器 - 文件管理 (插件)</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/minecraft-server-lite_5.png" alt=""><figcaption><p>我的世界开服器 - 计划任务</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/minecraft-server-lite_6.png" alt=""><figcaption><p>我的世界开服器 - 工具箱</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/minecraft-server-lite_7.png" alt=""><figcaption><p>我的世界开服器 - 本体设置</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/minecraft-server-lite_8.png" alt=""><figcaption><p>我的世界开服器 - 资源广场</p></figcaption></figure>

## 版权声明

本工具版权归属开发者：快辰，由灵工艺发布，其他人不得使用本软件用于商业用途或声称这是你开发的软件。
