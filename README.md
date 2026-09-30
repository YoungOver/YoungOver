### Проекты

Каждый репозиторий собирается одной командой, проходит тесты в CI и описывает в README, что измерено и как это повторить.

#### Веб-продукты

| | |
|---|---|
| [**krot**](https://github.com/YoungOver/krot) | Туннели к localhost: edge и агент на Go с мультиплексированием потоков, авторизация с ротацией refresh-токенов, кабинет на React 19 с инспектором запросов и WebGL-лендингом. [Демо](https://youngover.github.io/krot/) |
| [**web-studio**](https://github.com/YoungOver/web-studio) | Десять сайтов на React 19, TypeScript, Tailwind 4, shadcn/ui, GSAP и React Three Fiber |
| [**threejs-viz**](https://github.com/YoungOver/threejs-viz) | Анимации товаров и 3D-интерьеры на Three.js, детерминированная запись видео |
| [**web-qa-autotests**](https://github.com/YoungOver/web-qa-autotests) | Аудит сборок на Playwright: ошибки JS, сеть, SEO, доступность |

#### Системы на Go

| | | |
|---|---|---|
| [**logbroker**](https://github.com/YoungOver/logbroker) | Брокер сообщений: сегментированный журнал, разреженный индекс, sendfile, групповой fsync, группы потребителей | 1,22 млн сообщ./с, перезапуск на 9,4 ГБ за 2,4 с |
| [**tsdb-gorilla**](https://github.com/YoungOver/tsdb-gorilla) | Хранилище временных рядов: сжатие Gorilla, шардированная память, WAL с групповым коммитом | 10 млн точек/с, 0,4–3 байта на точку |
| [**orderbook-engine**](https://github.com/YoungOver/orderbook-engine) | Движок сопоставления заявок: однопоточные циклы, журнал с восстановлением после сбоя, SSE | 3,6 млн заявок/с в ядре |
| [**geo-dispatch**](https://github.com/YoungOver/geo-dispatch) | Индекс местоположения курьеров: UDP-пинги по 17 байт, шардированная сетка, поиск ближайших | 467 тыс. пингов/с при 25 тыс. запросов/с |

#### Встраиваемые системы и инженерия

| | |
|---|---|
| [**foc-g431**](https://github.com/YoungOver/foc-g431) | Бездатчиковое векторное управление двигателем на STM32G431: регистры без HAL, наблюдатель потока и ФАПЧ, запуск с демпфированием, тесты против модели двигателя |
| [**esp32-greenhouse**](https://github.com/YoungOver/esp32-greenhouse) | Контроллер теплицы на ESP32: прошивка с веб-интерфейсом и MQTT, схема из кода |
| [**cad-engineering**](https://github.com/YoungOver/cad-engineering) | Конструирование кодом: сборки на CadQuery, чертежи по ЕСКД, развёртки, DXF |

#### Автоматизация и данные

| | |
|---|---|
| [**python-automation**](https://github.com/YoungOver/python-automation) | Telegram-бот для записи на aiogram 3, асинхронный парсер в Excel, Google Sheets |
| [**shorts-factory**](https://github.com/YoungOver/shorts-factory) | Конвейер «текст → вертикальное видео»: озвучка, анимированные кадры, ffmpeg |
| [**data-analytics**](https://github.com/YoungOver/data-analytics) | Финансовая модель в Excel с живыми формулами, отчёт по продажам на pandas |
| [**html5-pipe-puzzle**](https://github.com/YoungOver/html5-pipe-puzzle) | Головоломка на Canvas 2D для промо-страниц и Telegram Mini Apps |

<p>
<img src="https://raw.githubusercontent.com/YoungOver/krot/main/docs/hero.png" width="49%">
<img src="https://raw.githubusercontent.com/YoungOver/foc-g431/main/docs/response.png" width="49%">
<img src="https://raw.githubusercontent.com/YoungOver/logbroker/main/docs/bench.png" width="49%">
<img src="https://raw.githubusercontent.com/YoungOver/tsdb-gorilla/main/docs/bench.png" width="49%">
</p>
