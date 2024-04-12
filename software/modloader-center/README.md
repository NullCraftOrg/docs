---
description: ModLoader Center
---

# 模组加载器中心

{% hint style="warning" %}
**此工具处于 BETA 持续开发阶段。**

如遇到任何错误，请通过 [用户群](https://jq.qq.com/?\_wv=1027\&k=A9YzWvbS) 或 [灵工艺社区](https://nullcraft.org/t/feedback) 进行反馈。
{% endhint %}

{% code title="ModLoader_Center.sln" %}
```csharp
Software software = new Software();
software.Name = "模组加载器中心";
software.ProjectID = "ModLoader Center";
software.Release = "https://nullcraft.org/d/87";
software.ReleaseDate = DateTime.Parse("2024,04,09").ToString();
software.Language = new string[] { "简体中文" };
software.Program = "C#";
software.Framework = ".NET8";

NullCraftSoftwareList.add(software);

Trace.WriteLine(NullCraftSoftwareList.Items.Conut());

>>> 20
```
{% endcode %}

## 关于《模组加载器中心》

### 下载《模组加载器中心》

{% embed url="https://nullcraft.org/d/87" %}

### 介绍与使用

{% content-ref url="introduction.md" %}
[introduction.md](introduction.md)
{% endcontent-ref %}

### 更新日志

{% content-ref url="update.md" %}
[update.md](update.md)
{% endcontent-ref %}

### 软件图片

<figure><img src="../../.gitbook/assets/modloader_center_home.png" alt=""><figcaption><p>主界面</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/modloader_center_minecraft_forge.png" alt=""><figcaption><p>Minecraft Forge</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/modloader_center_minecraft_fabric.png" alt=""><figcaption><p>Minecraft Fabric</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/modloader_center_minecraft_quilt.png" alt=""><figcaption><p>Minecraft Quilt</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/modloader_center_minecraft_optifine.png" alt=""><figcaption><p>Minecraft Optifine</p></figcaption></figure>

<figure><img src="../../.gitbook/assets/modloader_center_rust_oxide.png" alt=""><figcaption><p>Rust Oxide</p></figcaption></figure>
