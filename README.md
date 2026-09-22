# daily-quote-api 免费每日一言 API

无需注册、无需 Key、支持 CORS 跨域的中文名言接口。

## 接口

- 每日一言：`GET https://www.shop186.com/api/daily`
- 随机一句：`GET https://www.shop186.com/api/quote`
- 主题随机：`GET https://www.shop186.com/api/quote?theme=lizhi`

主题可选：lizhi励志 / dushu读书 / rensheng人生 / youqing友情 / aiqing爱情 / shijian时间 等 22 个。

## 返回示例

```json
{
  "errno": 0,
  "data": {
    "id": 3521,
    "text": "希望是坚韧的拐杖，忍耐是旅行袋",
    "author": "罗素",
    "url": "https://www.shop186.com/mingyan/3521.html"
  },
  "from": "句悦集 https://www.shop186.com"
}
```

完整接口文档：https://www.shop186.com/api/

数据来源：[句悦集](https://www.shop186.com/mingyan/) 收录的 2 万余条名人名言。
