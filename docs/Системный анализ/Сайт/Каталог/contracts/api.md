## Каталог API

### api/catalog/get - Получить список продуктов в каталоге <a name="getCatalog"></a>

query parameters:

- aptekaID, required

response:

```
{
    "aptekaId": "ihwir-ajirr-ankr-nkar", # Идентификатор аптеки
    "products": [
        {
            "productId": 1, # Идентификатор товара
            "productName": "Аспирин" # Наименование товара
        }
    ]
}
```

Ошибки:

404 - Указанный ресурс не существует.