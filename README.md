# api_Rocket

| Information       | Return          | 
| ------------- |:-------------:|
| ``` Author ``` |[Redpiar](https://t.me/Redpiar)|
| ```Telegram ``` |[Telegram](https://t.me/BotesForTelegram)| 
| ```Version ``` |1.2.0|
| ```Functions ``` |13/24|

Наш модуль был создан под API бота [TonRocket](https://t.me/tonRocketBot)

давайте пройдемся по разделам

1. Установка
2. Описание
3. Описание функций и их "return"
4. Примеры

> Установка

pip install api-Rocket

ожидаем окончания установки после чего проверяем:

```python
import api_Rocket

client = api_Rocket.Client(token="your token", proxies=None)
ver = client.api_version()
print(ver)
```
