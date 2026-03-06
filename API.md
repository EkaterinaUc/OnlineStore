## Задание 2: проектирование API

### Решение

Пример запроса с привязкой к локации пользователя: 
``` GET /api/v1/partner-stores?city=samara ```    
HTTP запрос: 
``` GET https://api.petrushka-green.ru/api/v1/partner-stores?city=samara ```  
Пример ответа: 
```{
  "stores": [
    {
      "id": 1,
      "name": "METRO",
      "logo_url": "https://cdn.petrushka.ru/logos/metro.png",
      "delivery": {
        "type": "scheduled",
        "time_from": "21:00",
        "time_to": "23:00",
        "date": "today"
      },
      "redirect_url": "https://metro.ru"
    },
    {
      "id": 2,
      "name": "Ашан",
      "logo_url": "https://cdn.petrushka.ru/logos/auchan.png",
      "delivery": {
        "type": "scheduled",
        "time_from": "18:00",
        "time_to": "20:00",
        "date": "today"
      },
      "redirect_url": "https://auchan.ru"
    },
    {
      "id": 3,
      "name": "ВкусВилл",
      "logo_url": "https://cdn.petrushka.ru/logos/vkusvill.png",
      "delivery": {
        "type": "express",
        "time_from": "20",
        "time_to": "60"
      },
      "redirect_url": "https://vkusvill.ru"
    },
    {
      "id": 4,
      "name": "Виктория",
      "logo_url": "https://cdn.petrushka.ru/logos/victoria.png",
      "delivery": {
        "type": "scheduled",
        "time_from": "17:00",
        "time_to": "19:00",
        "date": "today"
      },
      "redirect_url": "https://victoria.ru"
    }
  ]
}```
