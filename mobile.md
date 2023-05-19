# Мобильные устройства
Оптимизация сайта под мобильные устройства.  
Подготовка сайта к показу на мобильных устройствах.  
Рекомендации Яндекса: https://yandex.ru/support/webmaster/recommendations/mobile-site.html

Для адаптации сайта под мобильные устройства существует несколько вариантов решений:
- Адаптивный дизайн: верстка подстраивается под разные ширины экранов устроств
- Динамический дизайн: сервер отправляет разный HTML и CSS код в зависимсти от устройства
- Мобильная версия сайта: находится на поддомене `m.`, `mob.`, `mobile.` или подобных. Структуры сайтов основного и мобильного должны совпадать.

Рекомендации от Яндекс, по созданию сайта под мобильные устройства:
- Сайт должен быть доступен для мобильного индексирующего робота Яндекса: Mozilla/5.0 (iPhone; CPU iPhone OS 8_1 like Mac OS X) AppleWebKit/600.1.4 (KHTML, like Gecko) Version/8.0 Mobile/12B411 Safari/600.1.4 (compatible; YandexMobileBot/3.0; +http://yandex.com/bots)
- Не запрещать сканирование CSS и JS файлов участвующих в адаптации сайта
- Сайт должен отправлять 200 от сервера
- Не используйте технологии Flash, Silverlight, Applet
- Элементы и тексты сайта должны быть максимально видны на мобильных устройствах
- Не должно быть горизонтальных прокруток
- Сайт должен хорошо показываться и быть эффективным на ширине от 375px

Проверяем страницу на мобильную адаптацию:
- Переходим в Вебмастер > Интсрументы > Проверка мобильных страниц
- Вставляем страницу для проверки
- Нажать по кнопке проверить

Проверяем сайт на мобильную адаптацию:
- Переходим в Вебмастер > Диагностика > Диагностика сайта
- В блоке `Рекомендации` проверяем пункт `Сайт не оптимизирован для мобильных устройств`

## Проверка Яндекса на мобильность сайта
- Яндекс желает показывать для мобильных устройств, мобильную версию сайта (поддомен)
- Мобильная версия сайта и десктопная должны быть мобилопригодны
- Структура сайта и контент у мобильной версии сайта должны совпадать с десктопной, у мобильной версии можно убрать некторые элементы дизайна и информации
- Если верстка сайта адаптивная, то разместите мета-тег: `<meta name="viewport" content="width=device-width, initial-scale=1">`
- Если есть две версии сайта мобильная и десктопная и они совпадают, то разместите мета-тег: `<link rel="alternate" media="only screen and (max-width: 640px)" href="http://m.example.com/" />` href должен вести на аналогичную мобильную версию
- Можно воспользоваться редиректом и перенаправить пользователя с десктопной версии на мобильную, учитывая User-agent устройства пользователя