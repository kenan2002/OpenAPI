# session_channel.leave

离开临时讨论组。

## 请求方式

```
POST {base_url}/session_channel.leave
```

## 请求参数

**需要登录**

| 参数名称 | 参数类型 | 参数是否必须？ | 说明 | 样例 |
|:--------:|:--------:|:--------------:|------|------|
| `session_channel_id` | `string` | 是 | 临时讨论组 id | =bw52O |

## 响应

### 204
### 错误响应

```javascript
{
  "code": // error code,
  "error": "unexpected error"
}
```

<!-- generated by gen_doc.js -->
