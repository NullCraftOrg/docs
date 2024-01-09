---
description: LanTest
---

# 局域网探测

{% hint style="warning" %}
**此工具处于 BETA 持续开发阶段。**

如遇到任何错误，请通过 [用户群](https://jq.qq.com/?\_wv=1027\&k=A9YzWvbS) 或 [灵工艺社区](https://nullcraft.org/t/feedback) 进行反馈。
{% endhint %}

{% code title="LanTest.sln" %}
```csharp
Software software = new Software();
software.Name = "局域网探测";
software.ProjectID = "LanTest";
software.Release = "https://nullcraft.org/d/79";
software.ReleaseDate = DateTime.Parse("2023,12,13").ToString();
software.Language = new string[] { "简体中文" };
software.Program = "C#";
software.Framework = ".NET7";

NullCraftSoftwareList.add(software);

Trace.WriteLine(NullCraftSoftwareList.Items.Conut());

>>> 18
```
{% endcode %}

## 关于《局域网探测》

### 简单介绍

一款用于可视化显示局域网 IP 使用状态的软件。

### 下载《局域网探测》

{% embed url="https://nullcraft.org/d/79" %}

### 使用教学

{% content-ref url="tutorial.md" %}
[tutorial.md](tutorial.md)
{% endcontent-ref %}

### 更新日志

{% content-ref url="update.md" %}
[update.md](update.md)
{% endcontent-ref %}

### 软件图片

<figure><img src="../../.gitbook/assets/lantest_1.png" alt=""><figcaption><p>局域网探测 - 主界面 (简略模式)</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/lantest_3.png" alt=""><figcaption><p>局域网探测 - 主界面 (详细模式)</p></figcaption></figure>
