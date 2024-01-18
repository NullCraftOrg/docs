---
description: Pause Windows Update
---

# 视窗系统更新暂停工具

{% hint style="success" %}
此工具已开源发布。
{% endhint %}

{% embed url="https://github.com/FastChen/Pause-Windows-Update" %}

{% code title="Pause Windows Update.sln" %}
```csharp
Software software = new Software();
software.Name = "Windows更新暂停工具";
software.ProjectID = "Pause Windows Update";
software.Release = "https://nullcraft.org/d/80";
software.ReleaseDate = DateTime.Parse("2024,01,18").ToString();
software.Language = new string[] { "简体中文" };
software.Program = "C#";
software.Framework = ".NET8";

NullCraftSoftwareList.add(software);

Trace.WriteLine(NullCraftSoftwareList.Items.Conut());

>>> 19
```
{% endcode %}

## 关于《视窗系统更新暂停工具》

### 简单介绍

一个可以快捷自定义 Windows 暂停更新天数的工具，实现基本永久的禁用更新。

同时不影响 Microsoft Store (微软商店) 与 Xbox 游戏服务的使用，以及随时可以再次获得更新。

### 下载《视窗系统更新暂停工具》

{% embed url="https://github.com/FastChen/Pause-Windows-Update/releases" %}

### 使用教学

{% content-ref url="tutorial.md" %}
[tutorial.md](tutorial.md)
{% endcontent-ref %}

## 此软件开源协议声明

本工具已开放源代码，并托管至 Github ，使用 [GNU General Public License v3.0](https://github.com/FastChen/Pause-Windows-Update?tab=GPL-3.0-1-ov-file#readme) 许可，对于源码的使用，请遵守协议许可的范围内使用。
