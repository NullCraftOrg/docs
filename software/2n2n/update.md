---
description: 2n2n Update
---

# 更新日志

## 下载最新版本

{% embed url="https://nullcraft.org/d/39" %}

## 更新记录

### 客户端:v3.1.2.320 (2025-03-20)

<mark style="color:orange;">**`[客户端:修复]`**</mark>

* 检测节点在线延迟失败问题

<mark style="color:red;">**`[客户端:优化]`**</mark>

* 部分控件对齐问题优化
* n2n返回日志的日期改为更为易读格式

<mark style="color:green;">**`[客户端:安全]`**</mark>

* SHA256: d969069c7492d32dce420c0bcce3cf71041fdad3298f0aa66819b66e911acda9

### 超级节点:v3.1.1.309 (2025-03-09)

<mark style="color:red;">**`[超级节点:修复]`**</mark>

* 跟随 Windows 启动时无法正常读取环境问题

<mark style="color:green;">**`[超级节点:安全]`**</mark>

* SHA256: 0a2542c10578f011253c8edd11af6bd83ca38ad58f98f5369e4c2783a8256a84

{% hint style="info" %}
**提示**

从此版本开始 2n2n 的客户端与超级节点版本号、更新日志分开说明
{% endhint %}

### 超级节点:v3.1.0.308 (2025-03-08)

<mark style="color:blue;">**`[超级节点:更新]`**</mark>

* 软件的配置保存与读取
* 支持跟随 Windows 启动
* 支持启动时自动开启超级节点服务

<mark style="color:green;">**`[超级节点:安全]`**</mark>

* SHA256: d4c45dcaf18bc0878761d969525a7d38684cb0dd2b955a95fe114da1e823ab17

### v3.1.1.217 (2025-02-17)

<mark style="color:red;">**`[修复]`**</mark>

* 等待退出动画打断未正常恢复问题(不影响功能正常工作)

<mark style="color:green;">**`[安全]`**</mark>

* 客户端 SHA256: f50b0239638408874ee26b366e77f8280dc03d3057750b5c6fa3bba6996229cc
* 服务端 SHA256: 63c01863dd36fbe584f99fb69caef8912e6ebd6aa1dd27aae7623b4ebc83cb71

### v3.1.0.112 (2025-01-12)

<mark style="color:blue;">**`[更新]`**</mark>

* 超级节点服务端可视化工具

<mark style="color:green;">**`[安全]`**</mark>

* 客户端 SHA256: e7b7b84aa071f20182d5c5f606c0edb9ca083a6aedc6d217fd0451d6d5f77512
* 服务端 SHA256: 63c01863dd36fbe584f99fb69caef8912e6ebd6aa1dd27aae7623b4ebc83cb71

### v3.0.1.111 (2025-01-11)

<mark style="color:blue;">**`[更新]`**</mark>

* 管理节点支持修改已添加的节点信息

<mark style="color:red;">**`[修复]`**</mark>

* 未正确选择节点时启动组网异常报错
* 未正确选择协议时启动组网异常报错

<mark style="color:green;">**`[安全]`**</mark>

* SHA256: e7b7b84aa071f20182d5c5f606c0edb9ca083a6aedc6d217fd0451d6d5f77512

### v3.0.0.105 (2025-01-05)

{% hint style="info" %}
**提示**

更新此版本需要更新 .NET 至 **.NET8**
{% endhint %}

<mark style="color:blue;">**`[更新]`**</mark>

* .NET 版本升级至 .NET8
* 整体框架 80%以上代码进行了重构
* 档案的快速分享/导入功能
* 档案只读状态(需要手动设置)
* 节点现在有更好的管理窗口了
* 更多的组网状态通知
* 移除了一些不必要的功能

<mark style="color:orange;">**`[优化]`**</mark>

* 档案读取减少了读写次数(2-3次 -> 1次)
* 档案选择读取/写入速度提升

<mark style="color:green;">**`[安全]`**</mark>

* SHA256: SHA256:b5f0e69dae39f3a6a9d0abb523c52bd9dad63b82e3dd814250141bc0ad4aa592

***

### v2.0.3.315 (2024-03-15)

<mark style="color:orange;">**`[优化]`**</mark>

* 读取/写入档案时的速度优化以及减少硬盘读写次数。

<mark style="color:red;">**`[修复]`**</mark>

* 档案读取后不正常解除组件状态。

### v2.0.2.309 (2024-03-09)

<mark style="color:blue;">**`[更新]`**</mark>

* [档案文件设置为只读模式后，软件仅读取。](https://nullcraft.org/d/83)

### v2.0.1.602 (2023-06-02)

<mark style="color:blue;">**`[更新]`**</mark>

* 无Tap适配器时，提示安装，并且支持自动安装(需要管理员身份)。

<mark style="color:orange;">**`[优化]`**</mark>

* 优化一些逻辑

### v2.0.0.511 (2023-05-11)

<mark style="color:blue;">**`[更新]`**</mark>

* 整体项目重构，版本号从 2.0 开始更新。

### v**1.1.0.1209 (2021-12-09)**

<mark style="color:blue;">**`[更新]`**</mark>

* n2n协议版本更新至3.1

### v**1.0.1.1108 (2021-11-08)**

<mark style="color:blue;">**`[更新]`**</mark>

* 无 TAP 适配器时自动安装

### **v1.0.0.1014 (2021-10-14)**

<mark style="color:purple;">**`[发布]`**</mark>
