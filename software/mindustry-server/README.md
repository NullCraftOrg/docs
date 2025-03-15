---
description: Mindustry Server
---

# 像素工厂开服器

{% code title="Mindustry Server.sln" %}
```csharp
Software software = new Software();
software.Name = "像素工厂开服器";
software.ProjectID = "Mindustry Server";
software.Release = "https://nullcraft.org/d/107";
software.ReleaseDate = DateTime.Parse("2025,03,10").ToString();
software.Language = new string[] { "简体中文" };
software.Program = "C#";
software.Framework = ".NET8";

NullCraftSoftwareList.add(software);

Trace.WriteLine(NullCraftSoftwareList.Items.Conut());

>>> 25
```
{% endcode %}

## 关于《像素工厂开服器》 <a href="#guan-yu-mo-zu-jia-zai-qi-zhong-xin" id="guan-yu-mo-zu-jia-zai-qi-zhong-xin"></a>

### 下载《像素工厂开服器》 <a href="#xia-zai-mo-zu-jia-zai-qi-zhong-xin" id="xia-zai-mo-zu-jia-zai-qi-zhong-xin"></a>

{% embed url="https://nullcraft.org/d/107" %}

### 使用教学

{% content-ref url="../../tutorial/mindustry-server.md" %}
[mindustry-server.md](../../tutorial/mindustry-server.md)
{% endcontent-ref %}

### 软件介绍 <a href="#jie-shao-yu-shi-yong" id="jie-shao-yu-shi-yong"></a>

一款灵工艺风格的游戏：像素工厂(Mindustry)开服工具。

### 更新日志 <a href="#geng-xin-ri-zhi" id="geng-xin-ri-zhi"></a>

{% content-ref url="../the-forest-server/update.md" %}
[update.md](../the-forest-server/update.md)
{% endcontent-ref %}



### 软件图片 <a href="#ruan-jian-tu-pian" id="ruan-jian-tu-pian"></a>

<figure><img src="../../.gitbook/assets/mindustry-server_main.png" alt=""><figcaption><p>[灵工艺] 像素工厂(Mindustry)开服器 | 主页面</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/mindustry-server_server-properties.png" alt=""><figcaption><p>[灵工艺] 像素工厂(Mindustry)开服器 | 服务器配置页面</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/mindustry-server_trigger.png" alt=""><figcaption><p>[灵工艺] 像素工厂(Mindustry)开服器 | 触发事件</p></figcaption></figure>
