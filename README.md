На основе ежедневных данных о курсах валют ЦБ (https://www.cbr-xml-daily.ru/daily_json.js) необходимо создать Web-сервис с использованием ASP.Net Core, который реализует 2 API метода:

GET /currencies — должен возвращать список курсов валют с возможностью пагинации

GET /currency/ — должен возвращать курс валюты для переданного идентификатора валюты

Можно использовать любые NuGet-пакеты.
Конкретная реализация получения, хранения и возврата данных, а также их формат могут быть выбраны на усмотрение разработчика.
