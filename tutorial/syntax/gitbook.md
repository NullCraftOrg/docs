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
```
{% endcode %}

\`\`\` \{% hint style="info" %\} 这里写内容，同时也支持 MarkDown 语法和引入图片、超链接等。 \{% endhint %\}

```

</div>

参数 `style=""` 可选 `info`、`warning`、`danger`、`success`

### 效果

Info 风格

<div data-gb-custom-block data-tag="hint" data-style='info'>

Info - 信息 蓝色 "i" 圆图标

</div>

```

\{% hint style="info" %\} Info - 信息 蓝色 "i" 圆图标 \{% endhint %\}

```

Warning 风格

<div data-gb-custom-block data-tag="hint" data-style='warning'>

Warning - 警告 橙色 "!" 圆图标

</div>

```

\{% hint style="warning" %\} Warning - 警告 橙色 "!" 圆图标 \{% endhint %\}

```

Danger 风格

<div data-gb-custom-block data-tag="hint" data-style='danger'>

Danger - 危险 红色 "!" 三角图标

</div>

```

\{% hint style="danger" %\} Danger - 危险 红色 "!" 三角图标 \{% endhint %\}

```

Success 风格

<div data-gb-custom-block data-tag="hint" data-style='success'>

Success - 成功 绿色 "√" 圆图标

</div>

```

\{% hint style="success" %\} Success - 成功 绿色 "√" 圆图标 \{% endhint %\}

```

## Embed (嵌入)

### 超链接卡片

#### 语法

```

\{% embed url="https://nullcraft.org/" %\}

```

#### 效果

<div data-gb-custom-block data-tag="embed" data-url='https://nullcraft.org/'></div>

### 超链接文档卡片

#### 语法

```

\{% content-ref url="路径" %\} [文档文件名字](%E6%96%87%E6%A1%A3%E6%96%87%E4%BB%B6%E8%B7%AF%E5%BE%84/) \{% endcontent-ref %\}

\{% content-ref url="../../" %\} [..](../../) \{% endcontent-ref %\}

\{% content-ref url="../../donate/" %\} [donate](../../donate/) \{% endcontent-ref %\}

```

参数 `url="../../"` url内填写文档的路径，以调用文档为基准，向上(../)或向下(/)写路径。

参数内容：使用MarkDown 超链接语法，\[文件名]\(文件路径)

#### 效果

<div data-gb-custom-block data-tag="content-ref" data-url='../../readthis/'>

[readthis](../../readthis/)

</div>

```

\{% content-ref url="../../" %\} [..](../../) \{% endcontent-ref %\}

```

<div data-gb-custom-block data-tag="content-ref" data-url='../../donate/'>

[donate](../../donate/)

</div>

```

\{% content-ref url="../../donate/" %\} [donate](../../donate/) \{% endcontent-ref %\}

\`\`\`
