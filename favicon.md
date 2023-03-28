# Фавикон
Фавиконка для Гугла: https://developers.google.com/search/docs/appearance/favicon-in-search?hl=ru  
Фавиконка для Яндекса: https://yandex.ru/support/webmaster/search-results/create-favicon.html  
Фавиконка для Apple: https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html  

## Фавикон для Яндекс
- помещаем файл с именем favicon в корень сайта (можно поместить в отдельный каталог, укажите его в href)
- размеры файла: 120×120 (рекомендуемый), 32×32, 16×16px
- форматы: SVG (рекомендуемый), ICO, GIF, JPEG, PNG, BMP (анимация не поддерживается)
- код общий:
  - от Яндекса: `<link rel="icon" href="https://example.com/favicon.ico" type="image/x-icon">`
  - код для IE: `<link rel="shortcut icon" href="https://example.com/favicon.ico" type="image/x-icon">`
- href: в адресе сайта для кириллицы используйте Punycode
- type: image/svg+xml (SVG), image/png (PNG), image/jpeg (JPEG), image/gif (GIF), image/x-icon или image/vnd.microsoft.icon (ICO), image/bmp (BMP)
- после размещения иконки проверяем её на доступность https://webmaster.yandex.ru/tools/server-response/ (https://example.com/favicon.ico)

## Фавикон для Гугл
Гугл работает со следующими rel: icon, apple-touch-icon, apple-touch-icon-precomposed, shortcut icon
- код общий:
  - от Гугла: `<link rel="icon" href="/path/to/favicon.ico">`
- href: адрес может быть как относительным так и абсолютным
- и значок и главная страница сайта должны быть доступны для сканирования
- значок сайта должен быть квадратным с размерами, кратными 48 пикселям, например 48 x 48, 96 x 96, 144 x 144 и т.д.
- SVG поддерживается, размеры не важны
- Поддерживаются все форматы: https://en.wikipedia.org/wiki/Favicon#Image_file_format_support
