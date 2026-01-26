# Результаты тестирования VPN нод
Дата тестирования: 2026-01-26 18:53:36
Время выполнения: 129.9 секунд

## Статистика
- Всего проверено нод: 450
- Отфильтровано по пингу (> 100 мс): 65
- Успешных нод (ping+URL): 154
- Процент успеха: 34.2%

## Критерии отбора
1. **Ping тест**: TCP соединение должно устанавливаться быстрее 100 мс
2. **URL тест**: Успешный запрос через прокси к cp.cloudflare.com
3. **Тип подключения**: Поддерживается только Reality+TCP (для других типов нужен sing-box)

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
Все ноды в `good_nodes.txt` имеют пинг менее 100 мс и успешно проходят URL-тест.
Полный список всех нод доступен в [`nodes.txt`](nodes.txt).
