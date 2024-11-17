---
description: errorCode
---

# 错误码

### 通用错误码 (Error)

通常出现于未知的错误和软件上的错误

<table data-full-width="false"><thead><tr><th width="117">错误码</th><th>错误信息</th><th>描述</th></tr></thead><tbody><tr><td>ER001</td><td>未知错误</td><td>发生错误但未进行归类</td></tr></tbody></table>

### 访问错误系列 (Access Error)

通常出现于请求对应解析服务商时返回的错误

<table data-full-width="false"><thead><tr><th width="109">错误码</th><th width="187">错误信息</th><th width="336">描述</th><th align="center">来源</th></tr></thead><tbody><tr><td>AE001</td><td>鉴权认证失败</td><td>检查鉴权信否正确、过期、无效</td><td align="center">服务商返回</td></tr><tr><td>AE002</td><td>未找到鉴权信息</td><td>对应服务商内无法填写的鉴权信息</td><td align="center">服务商返回</td></tr><tr><td>AE003</td><td>鉴权信息不匹配</td><td>鉴权的 ID/KEY 信息不匹配</td><td align="center">服务商返回</td></tr><tr><td>AE011</td><td>主机记录不存在</td><td>无法找到对应的域名记录信息</td><td align="center">服务商返回或数据错误</td></tr><tr><td>AE012</td><td>记录无效或格式错误</td><td>记录解析类型不导致无法成功提交</td><td align="center">服务商返回</td></tr><tr><td>AE013</td><td>域名属于其他用户</td><td>当前账户中找不到需要解析的域名信息</td><td align="center">服务商返回</td></tr><tr><td>AE014</td><td>记录的值不正确</td><td>解析类型内填写的值不符合规范</td><td align="center">服务商返回</td></tr></tbody></table>

