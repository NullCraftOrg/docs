---
description: 2n2n
---

# 网上邻居

{% hint style="success" %}
现在已发布 3.0 版本，可加入 [用户群](https://jq.qq.com/?_wv=1027\&k=A9YzWvbS) 下载体验。
{% endhint %}

{% code title="n2n.sln" %}
```csharp
Software software = new Software();
software.Name = "网上邻居";
software.ProjectID = "2n2n";
software.Release = "https://nullcraft.org/d/39";
software.ReleaseDate = DateTime.Parse("2021,10,14").ToString();
software.Language = new string[] { "简体中文" };
software.Program = "C#";
software.Framework = ".NET8";

NullCraftSoftwareList.add(software);

Console.WriteLine(NullCraftSoftwareList.Items.Conut());

>>> 13
```
{% endcode %}

## 关于《网上邻居》

### 下载《网上邻居》

{% embed url="https://nullcraft.org/d/39" %}

### 了解《网上邻居》

{% content-ref url="introduction.md" %}
[introduction.md](introduction.md)
{% endcontent-ref %}

### 快速上手

{% content-ref url="tutorial.md" %}
[tutorial.md](tutorial.md)
{% endcontent-ref %}

### 查看更新日志

{% content-ref url="update.md" %}
[update.md](update.md)
{% endcontent-ref %}

### 软件图片

<figure><img src="../../.gitbook/assets/n2n_1.png" alt=""><figcaption><p>网上邻居 - 组网设置</p></figcaption></figure>
