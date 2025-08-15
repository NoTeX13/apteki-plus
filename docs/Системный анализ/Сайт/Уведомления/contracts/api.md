## Уведомления api

### api/v1/mindbox/user-subscriptions [GET] - получить информацию об уведомлениях пользователя 

query parameters: -

```
{
    "data": {
        "subscriptions": [
            {
                "name": "string", # наименование способа уведомления
                "title": "\u0421\u043c\u0441 \u0443\u0432\u0435\u0434\u043e\u043c\u043b\u0435\u043d\u0438\u044f", # название уведомления
                "value": true, # флаг активности уведломления
            }
        ]
    }
    "status": "success"
}
```

### api/v1/mindbox/user-subscriptions [PUT] - обновить информацию об уведомлениях пользователя  
<a id="putSub"></a>

request body:
```
{
    subscriptions: [
        {
            name: "sms", 
            title: "Смс уведомления", 
            value: true
        }
    ]
}
```

response:
```
{
    "data": {
        "subscriptions": [
            {
                "name": "string", # наименование способа уведомления
                "title": "\u0421\u043c\u0441 \u0443\u0432\u0435\u0434\u043e\u043c\u043b\u0435\u043d\u0438\u044f", # название уведомления
                "value": true, # флаг активности уведломления
            }
        ]
    }
    "status": "success"
}
```

nnnn <a id="getSub"></a>  