---
description: EasyDDNS Update
---

# 更新日志

## 下载最新版本的《简单动态域名服务》

{% embed url="https://nullcraft.org/d/97" %}

## 更新记录

### v1.4.1.1104 (2024-11-04)

<mark style="color:blue;">**`[更新]`**</mark>

* 可自定义设置获取 IP 地址 API 接口
* 对部分错误进行整理并应用错误码 可访问 [错误码](https://docs.nullcraft.org/software/easyddns/errorcode) 查看详细信息
* Cloudflare DNS 解析使用自封装 SDK 重写

<mark style="color:orange;">**`[优化]`**</mark>

* 测试 IP 地址时展示更多的数据(返回、接口、用时)
* 华为云 DNS 解析 (自鉴权实现) 上的错误归类优化

### v1.3.0.925 (2024-09-25)

<mark style="color:blue;">**`[更新]`**</mark>

* IPv6(AAAA) 记录类型解析支持

<mark style="color:orange;">**`[优化]`**</mark>

* 添加解析时支持中文字符域名
* 添加解析窗口控件排列优化

<mark style="color:red;">**`[修复]`**</mark>

* 腾讯云解析主机记录未能正确指向问题
* 定时同步无法保存启用状态问题

### v1.2.0.917 (2024-09-17)

<mark style="color:blue;">**`[更新]`**</mark>

* 解析支持变更 TTL 值
* 部分 UI 状态的保存/恢复

<mark style="color:orange;">**`[优化]`**</mark>

* 优化解析记录判断
* 优化 API 请求防止造成重复的性能、时间浪费

### v1.1.0.915 (2024-09-15)

<mark style="color:blue;">**`[更新]`**</mark>

* 新增服务商：腾讯云 DNS 解析
* 新增服务商：Cloudflare DNS 解析

### v1.0.0.912 (2024-09-12) <a href="#v0.0.1.1213-2023-12-13" id="v0.0.1.1213-2023-12-13"></a>

<mark style="color:purple;">**`[发布]`**</mark>

* 支持服务商：阿里云DNS解析
* 通过远程服务获取本机IP地址
