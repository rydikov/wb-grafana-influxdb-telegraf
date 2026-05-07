1. docker compose up
2. Открываем Grafana (ip контроллера:3000) -> Data sources -> InfluxDB -> Test. Должно быть ок
3. Открываем Explore -> Тестируем получение данных. Должен появиться mqtt_consumer в выборе FROM при нажатии и topic::tag в WHRE. GROUP BY можно очистить.
4. Создаем Dashboard и на нём добавляем панель.