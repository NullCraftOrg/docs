---
description: Hash
---

# 哈希

{% hint style="success" %}
一个用于验证文件哈希(Hash)的小工具
{% endhint %}

{% code title="Hash.sln" %}
```csharp
Software software = new Software();
software.Name = "哈希";
software.ProjectID = "Hash";
software.Release = "https://nullcraft.org/d/12";
software.ReleaseDate = DateTime.Parse("2020,12,25").ToString();
software.Language = new string[] { "简体中文" };
software.Program = "C#";
software.Framework = ".NET3.0";

NullCraftSoftwareList.add(software);

Console.WriteLine(NullCraftSoftwareList.Items.Conut());

>>> 7
```
{% endcode %}

## 关于《哈希》

### 下载《哈希》

{% embed url="https://nullcraft.org/d/12" %}

### 哈希的使用教程

{% content-ref url="tutorial.md" %}
[tutorial.md](tutorial.md)
{% endcontent-ref %}

### 查看更新日志

{% content-ref url="update.md" %}
[update.md](update.md)
{% endcontent-ref %}

### 软件图片

<figure><img src="../../.gitbook/assets/hash_1.png" alt=""><figcaption><p>哈希 - 主界面 (查看文件状态)</p></figcaption></figure>
