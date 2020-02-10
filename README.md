# qdoll_svr

## 芯片初始化工具接口

URL prefix 统一为： http://qdollsvr.mengmax.fun/
### 获取娃娃的种类列表
END Point: character/genre_list

Method: GET

Response Example:
```JSON
{
    "status": 200,
    "data": [
        {
            "id": 1,
            "img_url": "https://studiofiles.oss-cn-shanghai.aliyuncs.com/img/Screenshot%20from%202020-01-20%2010-50-14.png",
            "genre": "7001",
            "name": "毛绒玩具可爱菲儿布洋娃娃"
        },
        {
            "id": 2,
            "img_url": "https://studiofiles.oss-cn-shanghai.aliyuncs.com/img/Screenshot%20from%202020-01-20%2010-55-04.png",
            "genre": "7002",
            "name": "LIVHEART羊公仔抱枕毛绒玩具"
        },
        {
            "id": 3,
            "img_url": "https://studiofiles.oss-cn-shanghai.aliyuncs.com/img/Screenshot%20from%202020-01-20%2011-23-56.png",
            "genre": "7003",
            "name": "可爱超萌仓鼠年吉祥物毛绒玩具"
        }
    ]
}
```


### NFC芯片数据入库

END Point: character/uuids

Method: POST

Content-type: application/json

Request body (example):
```JSON

```
