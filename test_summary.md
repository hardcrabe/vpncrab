# Результаты тестирования VPN нод
Дата тестирования: 2026-01-26 19:33:07
Время выполнения: 145.0 секунд

## Статистика
- Всего проверено нод: 450
- Отфильтровано по пингу (> 100 мс): 62
- Отфильтровано по времени ответа (> 2000 мс): 61
- Успешных нод (все критерии): 172
- Процент успеха: 38.2%
- Среднее время ответа успешных нод: 671.8 мс

## Критерии отбора
1. **Ping тест**: TCP соединение должно устанавливаться быстрее 100 мс
2. **URL тест**: Успешный запрос через прокси к cp.cloudflare.com
3. **Время ответа**: Ответ от cp.cloudflare.com должен приходить быстрее 2000 мс
4. **Тип подключения**: Поддерживается только Reality+TCP (для других типов нужен sing-box)

## Источники
Ноды были загружены из следующих источников:
- https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS_mobile.txt
- https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/main/Vless-Reality-White-Lists-Rus-Mobile-2.txt
- https://raw.githubusercontent.com/igareck/vpn-configs-for-russia/main/Vless-Reality-White-Lists-Rus-Mobile.txt

## Как использовать
1. Рабочие ноды сохранены в файле [`good_nodes.txt`](good_nodes.txt)
2. Скопируйте любую строку из этого файла
3. Вставьте в поддерживаемый клиент (Nekoray, v2rayN и т.д.)
4. Подключитесь и пользуйтесь!

## Примечание
Этот файл и [`good_nodes.txt`](good_nodes.txt) обновляются автоматически каждый раз при запуске скрипта.
Все ноды в `good_nodes.txt` имеют:
- Пинг менее 100 мс
- Время ответа URL менее 2000 мс
- Успешно проходят URL-тест через Reality+TCP

Полный список всех нод доступен в [`nodes.txt`](nodes.txt).
