# Технические факторы
Техническая оптимизация сайта.

- Используется протокол HTTPS,
- Отсутствуют замечания и ошибки в SSL-сертификате Да,
- При переходе с HTTP на HTTPS проведена проверка, и ни одна из внутренних ссылок не ведет на текущие страницы HTTP,
- Выбрано главное зеркало сайта, настроен редирект,
- Настроен редирект на страницы со слешем или без,
- Найдены все случайные 302 редиректы и заменены на 301 редирект,
- Отсутствуют дубли главной страницы `/index.html` или `/index.php`,
- Добавить мета-тег `rel="canonical"`,
- Добавить фавикон для сайта (желательно SVG),
- Дизайн адаптивный, можно просматривать в смартфоне и планшете,
- Грамотно настроена страница `404`,
- Таблицы имеют "резиновую" верстку - при изменении ширины экрана контент в таблицах читабельный,
- В robots.txt используется параметр Clean-param для избавления от дублей: https://yandex.ru/support/webmaster/robot-workings/clean-param.html,
- На страницах отсутствуют битые ссылки,
- Используется GZIP сжатие данных на сервере,
- Изображения сжаты для уменьшения их веса,
- Настроено кэширование,
- Используется "ленивая загрузка" изображений, скриптов и CSS,
- На сайте используется единая кодировка (как правило, UTF-8),
- В код сайта добавлены географические метатеги,
- Технические страницы закрыты от индексации,
- В заголовке Expires указан нужный срок истечения актуальности контента,
- Для обеспечения работоспособности и надежности сайта выбран надежный хостинг,
- Настроены заголовки Last Modified и If-Modified-Since для передачи поисковым роботам даты внесения изменений на страницах и ускорения переиндексации https://pr-cy.ru/news/p/8595-glavnoe-o-last-modified-chto-eto-kak-nastroit-i-proverit,

Дополнительно Tech Usability:
- Все элементы страницы находятся на своих местах, верстка не «плывет»,
- Выдержана единая стилистика текста (шрифты, цвет, размер, абзацы, межстрочный интервал, поля),
- Страница корректно отображается на устройствах с различным разрешением при вертикальном и горизонтальном просмотре, можно проверить сервисами:
  - I love adaptive: http://iloveadaptive.com/ru/,
- Страница проходит тесты на пригодность для мобильных устройств:
  - Яндекс: https://webmaster.yandex.ru/site/tools/mobile-friendly/,
  - Google: https://search.google.com/test/mobile-friendly?hl=ru,
- Страница корректно отображается при открытии на разных платформах и в разных браузерах. Можно проверить вручную или сервисами:
  - Browsershots: https://browsershots.org/,
  - Browserling: https://www.browserling.com/,
- На сайте валидный HTML и CSS код:
  - HTML: https://validator.w3.org/,
  - CSS: https://jigsaw.w3.org/css-validator/,
- Код JavaScript не содержит ошибок: https://codebeautify.org/jsvalidate,
- Микроразметка не содержит ошибок:
  - Валидатор Google: https://developers.google.com/search/docs/appearance/structured-data?hl=ru,
  - Валидатор Яндекс: https://webmaster.yandex.ru/tools/microtest/,
- При проверке в Google PageSpeed https://developers.google.com/speed?hl=ru отсутствуют серьезные замечания, сайт набирает не меньше 50 баллов для мобайла и десктопа. Также скорость загрузки можно оценить инструментом Test My Site от Google https://www.thinkwithgoogle.com/intl/en-gb/marketing-strategies/app-and-mobile/mobile-tools-to-optimize-site-and-app/ и в панели Яндекс.Вебмастера,
- На всех страницах сайта установлены коды Яндекс.Метрики и Google Analytics проверить корректность можно с помощью Tag Assistant by Google https://chrome.google.com/webstore/detail/tag-assistant-legacy-by-g/kejbdjndbnbjgmefkgdddjlbokphdefk?hl=ru,

## Разное
- Лаконичное и емкое название домена, короткое, простое и запоминающееся (в идеале совпадать с названеим бренда),

## Ссылки
- https://blog.promopult.ru/seo/skorost-zagruzki-sajta-i-kak-ee-uvelichit.html
- https://blog.promopult.ru/seo/kak-nastroit-mikrorazmetku-schema-org.html
- https://blog.promopult.ru/seo/pagespeed-insights.html
