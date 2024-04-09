# 模组加载器中心

{% hint style="warning" %}
**此工具处于 BETA 持续开发阶段。**

如遇到任何错误，请通过 [用户群](https://jq.qq.com/?\_wv=1027\&k=A9YzWvbS) 或 [灵工艺社区](https://nullcraft.org/t/feedback) 进行反馈。
{% endhint %}

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

## 关于《模组加载器中心》

### 下载《模组加载器中心》

{% embed url="https://nullcraft.org/d/87" %}

### 更新日志

{% content-ref url="update.md" %}
[update.md](update.md)
{% endcontent-ref %}
