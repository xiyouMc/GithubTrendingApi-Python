获取 Trending 列表
-----------

### 1. 获取 Trending 列表

#### 接口功能

> 指定时间和语言获取 Github Trending 的所有数据

#### URL

> [https://python.0x2048.com/v1/trending?since=daily&language=java](https://python.0x2048.com/v1/trending?since=daily&language=java)

#### 支持格式

> JSON

#### HTTP请求方式

> GET

#### 请求参数

|参数|必选|类型|说明|
|:----- |:-------|:-----|----- |
|since |ture |string|trending 的类型，如 daily、week |
|language |false |int |请求的语言|

#### 返回字段

|返回字段|字段类型|说明 |
|:----- |:------|:----------------------------- |
|id | int |返回结果状态。0：正常；1：错误。 |
|company | string | 所属公司名 |
|category | string |所属类型 |

#### 接口示例

> 地址：[http://www.api.com/index.php?name=可口可乐&type=1](http://www.api.com/index.php?name=可口可乐&type=1)

{
"state": 0,
"company": "可口可乐",
"category": "饮料"
}
