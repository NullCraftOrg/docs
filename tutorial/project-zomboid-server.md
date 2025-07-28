---
description: Open a Project Zomboid server tutorial
---

# 🧟 僵尸毁灭工程开服教程

{% hint style="info" %}
本教程面向《灵工艺僵尸毁灭工程开服器》软件用户。\
如果你不是使用此软件来开服，那么本教程的内容可能不适用于你。
{% endhint %}

## 设置专用服务器

### 下载僵尸毁灭工程专用服务器

打开 Steam 进入 库 页面，更改显示的类型，勾选工具以便显示专用服务器下载。

{% hint style="info" %}
也可以使用 SteamCMD 下载，本文暂时以 Steam 客户端进行教学。
{% endhint %}

<div align="left"><figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_download_dedicated_server.png" alt="" width="289"><figcaption></figcaption></figure></div>

### 打开专用服务器目录

下载完毕后，右键 Project Zomboid Dedicated Server 打开文件所在目录。

<div align="left"><figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_find_dedicated_server.png" alt="" width="503"><figcaption></figcaption></figure></div>

### 放入开服工具至专用服务器目录内

将《灵工艺僵尸毁灭工程开服器》放入打开的专用服务器目录内并启动。

{% hint style="info" %}
如忽略此步骤，则需前往开服器的本体设置页面手动选择并设置专用服务器目录。
{% endhint %}

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_start.png" alt=""><figcaption></figcaption></figure>

## 创建并管理服务器

### 新建档案

打开《灵工艺僵尸毁灭工程开服器》，在档案管理页面新建一个服务器档案。

{% hint style="info" %}
如先前在游戏内建立过服务器，则会在此列表中显示并可用(未改变服务器缓存目录情况下)。
{% endhint %}

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_create_profile.png" alt=""><figcaption></figcaption></figure>

### 设置启动档案

选中一个已存在的档案，点击 "设为启动档案" 按钮或勾选列表前勾选框即可将此档案设置为开服启动档案。

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_select_profile.png" alt=""><figcaption></figcaption></figure>

### 设置服务器管理员密码(初次)

当服务器第一次启动时，会要求设置管理员账户(admin)登录密码，以此身份登录服务器可以进行管理。

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_enter_admin_password.png" alt=""><figcaption></figcaption></figure>

设置密码后要求再次重复输入之前设置的密码。

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_confirm_admin_password.png" alt=""><figcaption></figcaption></figure>

### 服务器启动中

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_start_server.png" alt=""><figcaption></figcaption></figure>

### 服务器启动完毕

当看到控制台内 `*** SERVER STARTED ***` 或由开服工具提示的 `服务器启动完毕` 则代表专用服务器已启动完毕。

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_start_over.png" alt=""><figcaption></figcaption></figure>

## 游戏内连接服务器

### 添加服务器

在加入游戏中的右侧的添加收藏夹中填写本地服务器信息。

* 服务器名称：自定义填写
* 服务器地址：本机则填写 127.0.0.1、公网则填写公网地址、内网穿透则填写穿透服务器地址。
* 服务器端口：未使用服务器穿透、转发则填写默认端口：`16261` 如使用或修改端口则填写对应端口。
* 昵称：自定义填写 或使用 admin 进行管理服务器。
* 密码：自定义填写

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_game_add_server.png" alt=""><figcaption></figcaption></figure>

添加到列表后，点击刷新按钮后可以正常读取服务器信息。

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_game_server_list.png" alt=""><figcaption></figcaption></figure>

加入服务器正常游玩。

<figure><img src="../.gitbook/assets/tutorial_project_zomboid_server_join_game.png" alt=""><figcaption></figcaption></figure>
