---
description: GitBook Syntax
---

# GitBook 语法

{% hint style="warning" %}
这个主要是给在使用 Github 编辑上想调用 GitBook 语法而准备的示例页面

注：此语法并不适用于其它地方使用，仅限此文档使用。
{% endhint %}

## Hint (提示)

### 语法

{% code lineNumbers="true" fullWidth="false" %}
```
{% raw %}
{% hint style="info" %}
这里写内容，同时也支持 MarkDown 语法和引入图片、超链接等。
{% endhint %}
{% endraw %}
```
{% endcode %}

参数 `style=""` 可选 `info`、`warning`、`danger`、`success`

### 效果

Info 风格

{% hint style="info" %}
Info - 信息 蓝色 "i" 圆图标
{% endhint %}

```
{% raw %}
{% hint style="info" %} Info - 信息 蓝色 "i" 圆图标 {% endhint %}
{% endraw %}
```

Warning 风格

{% hint style="warning" %}
Warning - 警告 橙色 "!" 圆图标
{% endhint %}

```
{% raw %}
{% hint style="warning" %} Warning - 警告 橙色 "!" 圆图标 {% endhint %}
{% endraw %}
```

Danger 风格

{% hint style="danger" %}
Danger - 危险 红色 "!" 三角图标
{% endhint %}

```
{% raw %}
{% hint style="danger" %} Danger - 危险 红色 "!" 三角图标 {% endhint %}
{% endraw %}
```

Success 风格

{% hint style="success" %}
Success - 成功 绿色 "√" 圆图标
{% endhint %}

```
{% raw %}
{% hint style="success" %} Success - 成功 绿色 "√" 圆图标 {% endhint %}
{% endraw %}
```

## Embed (嵌入)

### 超链接卡片

#### 语法

```
{% raw %}
{% embed url="https://nullcraft.org/" %}
{% endraw %}
```

#### 效果

{% embed url="https://nullcraft.org/" %}

### 超链接文档卡片

#### 语法

```
{% raw %}
{% content-ref url="路径" %}
[文档文件名字](文档文件路径)
{% endcontent-ref %}

{% content-ref url="../../" %}
[..](../../)
{% endcontent-ref %}

{% content-ref url="../../donate/" %}
[donate](../../donate/)
{% endcontent-ref %}
{% endraw %}
```

参数 `url="../../"` url内填写文档的路径，以调用文档为基准，向上(../)或向下(/)写路径。

参数内容：使用MarkDown 超链接语法，\[文件名]\(文件路径)

#### 效果

{% content-ref url="../../readthis/" %}
[readthis](../../readthis/)
{% endcontent-ref %}

```
{% raw %}
{% content-ref url="../../" %}
[..](../../)
{% endcontent-ref %}
{% endraw %}
```

{% content-ref url="../../donate/" %}
[donate](../../donate/)
{% endcontent-ref %}

```
{% raw %}
{% content-ref url="../../donate/" %}
[donate](../../donate/)
{% endcontent-ref %}
{% endraw %}
{% endraw %}
```
