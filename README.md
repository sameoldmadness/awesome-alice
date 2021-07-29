# Awesome Alice

Библиотеки и ресурсы для [Яндекс.Диалогов](https://dialogs.yandex.ru)

## Оглавление

* [Разработка](#разработка)
  * [SDK](#sdk)
    * [JS](#js)
    * [Python](#python)
    * [PHP](#php)
    * [Go](#go)
    * [Kotlin](#kotlin)
    * [C#](#c)
  * [Тестирование](#тестирование)
  * [Конструкторы и платформы](#конструкторы-и-платформы)
  * [Обработка естественного языка (NLP)](#обработка-естественного-языка)
* [Примеры и навыки](#примеры-и-навыки)
  * [Примеры](#примеры)
  * [Open-source навыки](#open-source-навыки)
* [Видео](#видео)  
* [Чаты](#чаты)
* [Прочее](#прочее)

## Разработка

### SDK

#### JS

- [fletcherist/yandex-dialogs-sdk](https://github.com/fletcherist/yandex-dialogs-sdk)
- [skoif/Yandex-Dialogs](https://github.com/skoif/Yandex-Dialogs)
- [vitalets/alice-renderer](https://github.com/vitalets/alice-renderer) - Библиотека для формирования ответов в навыках Алисы
- [alexander-karpov/yandex-dialoger](https://github.com/alexander-karpov/yandex-dialoger) - Ещё библиотека для написания навыков Алисы
- [vitalets/alice-types](https://github.com/vitalets/alice-types) - Тайпинги для протокола запросов/ответов в навыках Алисы

#### Python

- [Dikower/Alice_SeaBattle_YandexHackathone](https://github.com/Dikower/Alice_SeaBattle_YandexHackathone/blob/master/alice_sdk.py)
- [mahenzon/aioAlice](https://github.com/mahenzon/aioalice) - asyncio библиотека для Python 3.6+
- [borzunov/alice_scripts](https://github.com/borzunov/alice_scripts)
- [avidale/dialogic](https://github.com/avidale/dialogic) (бывшая tgalice) - общая обёртка для навыков в Алисе и Салюте, ботов в Telegram, ВК и Facebook на Python 3.6+
- [format37/alice](https://github.com/format37/alice) - сокращенный пример aiohttp сервера

#### PHP

- [mesilov/yandex-dialogs-php-sdk](https://github.com/mesilov/yandex-dialogs-php-sdk.git)
- [jeyroik/php-yandex-alisa-advanced](https://github.com/jeyroik/php-yandex-alisa-advanced)
- [jeyroik/alice-extas](https://github.com/jeyroik/alice-extas)
- [Danil005/php-yandex-alisa](https://github.com/Danil005/php-yandex-alisa)
- [thesoultaker48/yandex-dialogs-php](https://github.com/thesoultaker48/yandex-dialogs-php)
- [zz-anton/ru.foralice.yandex-dialogs-api-hide-my-oauth](https://github.com/zz-anton/ru.foralice.yandex-dialogs-api-hide-my-oauth) - скрипт для работы сервиса [ImgAdmin](https://imgAdmin.forAlice.ru) с безопасным использованием конфиденциального идентификатора OAuth пользователя. В коде реализованы методы для работы с изображениями через API Яндекс.Диалогов.

#### Go

- [toby3d/dialogs](https://github.com/toby3d/dialogs)
- [bbrodriges/mielofon](https://github.com/bbrodriges/mielofon)
- [AlekSi/alice](https://github.com/AlekSi/alice)
- [azzzak/alice](https://github.com/azzzak/alice) - Библиотека с упором на скорость и простоту разработки

#### Kotlin

- [SavinMike/alice-kotlin-bot](https://github.com/SavinMike/alice-kotlin-bot)
- [Just AI Conversational Framework](https://github.com/just-ai/jaicf-kotlin/tree/master/channels/yandex-alice)

#### C#
- [alexvolchetsky/yandex.alice.sdk](https://github.com/alexvolchetsky/yandex.alice.sdk)
- [granstel/Yandex.Dialogs.Models](https://github.com/granstel/Yandex.Dialogs.Models)

### Тестирование

- [popstas/yandex-dialogs-client](https://github.com/popstas/yandex-dialogs-client) - Тестирование навыков с автотестами
- [alice-nearby](https://github.com/azzzak/alice-nearby) - Утилита с веб-интерфейсом для локального тестирования навыков
- [Симулятор Яндекс Станции](https://station.aimylogic.com/) - Голосовой симулятор в браузере для тестирования навыков
- [Тест прокси](https://dialogs.yandex.ru/store/skills/42f51951-test-proksi) - Навык алисы, проксирует запросы на указанный адрес
- [Эмулятор Алисы](https://github.com/vb64/test.helper.yandex.alice.flask) - Для юнит-тестов навыков, реализованных как приложение python/flask
- [alice-tester](https://github.com/vitalets/alice-tester) - Библиотека для автоматического тестирования навыков под  Node.js
- [alice-cloud-proxy](https://github.com/vitalets/alice-cloud-proxy) - Универсальная [облачная функция](https://cloud.yandex.ru/docs/functions/concepts/function) для проксирования запросов на заданный урл. Позволяет тестировать локальную версию навыка прямо в приложениях с Алисой.
- [alice-dev.vitalets.xyz](https://alice-dev.vitalets.xyz/) - Отладка навыков прямо на устройстве без публикации в каталоге. Работает через веб-интерфейс в браузере и специальный навык "Инструменты разработчика".


### Конструкторы и платформы

- [verter](https://www.verter.online/) - Создание навыков без программирования
- [alfabot](http://alfabot.xyz/) - Конструктор навыков
- [dialogflower](https://dialogflower.com/) - Google Dialogflow для Яндекс Алисы
- [aimylogic](https://app.aimylogic.com) - Визуальный конструктор навыков
- [pipe.bot](https://pipe.bot/) - Конструктор ботов с поддержкой Алисы
- [Tortu](https://tortu.io/) - Инструмент для проектирования (дизайна) навыков
- [aimytellme](https://app.aimytellme.com) - Конструктор новостных навыков для Алисы
- [alicebot.pro](https://alicebot.pro) - Cоздание навыков без программирования
- [DeepPavlov](https://deeppavlov.ai/) - Библиотека для разработки диалоговых систем
- [ImgAdmin](https://imgadmin.foralice.ru/) - Администратор изображений для системы Яндекс.Диалоги / Навыки Алисы

### Обработка естественного языка
- [сущности](https://github.com/denismosolov/alice-entities-library) - Содержит описания сущностей, которые могут вам пригодиться при написании грамматики.

## Примеры и навыки

### Примеры

- [yandex/alice-skills](https://github.com/yandex/alice-skills) - Примеры от Яндекса
- [jeyroik/php-yandex-alisa-simple](https://github.com/jeyroik/php-yandex-alisa-simple) - Пример на PHP
- [seralexeev/alice-dotnet](https://github.com/seralexeev/alice-dotnet) - Пример на С# и .NET Core
- [sameoldmadness/alice-ts](https://github.com/sameoldmadness/alice-ts) - Пример на TypeScript
- [surik00/aioAlice](https://github.com/surik00/aioalice/tree/master/examples) - Примеры на Python + aioAlice
- [borzunov/alice_scripts](https://github.com/borzunov/alice_scripts#%D0%9F%D1%80%D0%B8%D0%BC%D0%B5%D1%80%D1%8B) - Примеры на Python + alice_scripts
- [AlexSuperStar/Yandex-Alisa-PHP-Example](https://github.com/AlexSuperStar/Yandex-Alisa-PHP-Example) - Пример минимального кода на PHP
- [vitalets/alice-skill-starter](https://github.com/vitalets/alice-skill-starter) - Быстрый старт навыка для Алисы на Node.js
- [demo-alice-translate-skill](https://github.com/avidale/demo-alice-translate-skill) - простой навык ["Крот-полиглот"](https://dialogs.yandex.ru/store/skills/622af903-krot-poliglot) на Python и Yandex cloud functions с использованием встроенных интентов, хранилища состояния, и связки с API Яндекс.Переводчика.
- [alice-jaicf-template](https://github.com/just-ai/alice-jaicf-template) - Шаблонный проект на Kotlin
- [granstel/Templates.Chatbot](https://github.com/granstel/Templates.Chatbot) - Шаблонный проект на C# (Алиса, Telegram, Chat2Desk)

### Open-source навыки

- [popstas/yandex-dialogs-whatis](https://github.com/popstas/yandex-dialogs-whatis) - Пример на yandex-dialogs-sdk, навык [Вторая память](https://dialogs.yandex.ru/store/skills/00203e6e-vtoraya-pamya)
- [ShoshinNikita/radio-t-bot](https://github.com/ShoshinNikita/radio-t-bot) - Пример на Go, навык [Радио-Т](https://dialogs.yandex.ru/store/skills/59f0e8df-radio-t-hitech-podkast-vyhodnogo-dnya)
- [let-robots-reign/RussianHistory_Quiz](https://github.com/let-robots-reign/RussianHistory_Quiz) - Пример на Python, навык [Викторина по истории России](https://dialogs.yandex.ru/store/skills/3af72151-viktorina-po-istorii-rossii)
- [xoposhiy/prog-eng-alice](https://github.com/xoposhiy/prog-eng-alice) – Пример на C#, Навык Алисы для изучения программистского английского
- [vb64/bulls_cows](https://github.com/vb64/bulls_cows) - Пример на Python/Flask, для развертывания на [GoogleAppEngine Standard Environment](https://cloud.google.com/appengine/docs/standard/) навык [логическая игра быки и коровы](https://alice.ya.ru/s/59166701-101b-44b3-b7e3-b7e078036890)
- [x6b726173/alice-word-by-word](https://github.com/x6b726173/alice-word-by-word) - Пример на Python/aiohttp [aioalice](https://github.com/surik00/aioalice), навык [игра Слово за слово](https://alice.ya.ru/s/9d5dad53-1dd3-4f14-805a-6bc374ec579d)
- [DenisNP/AliceHook](https://github.com/DenisNP/AliceHook) - навык на C# для связывания Алисы с вебхуками [Мой Исполнитель](https://dialogs.yandex.ru/store/skills/85384c00-moj-ispolnitel)
- [denismosolov/oliver](https://github.com/denismosolov/oliver) - приватный навык на PHP для управления брокерским счётом: покупка и продажа акций на бирже и т.д. Использует [Тинькофф Инвестиции OpenAPI](https://github.com/TinkoffCreditSystems/invest-openapi)
- [StopChangingTheName/alice-skills](https://github.com/StopChangingTheName/alice-skills) - Полноценный навык ["Знатоки истории"](https://dialogs.yandex.ru/store/skills/1424e7f5-ege-po-istorii) на Python
- [granstel/FillInTheTextBot](https://github.com/granstel/FillInTheTextBot) - исходный код навыка ["Занимательные истории"](https://dialogs.yandex.ru/store/skills/12ef2083-sochinyal); C#, .net core 3.1

## Умный дом

- [popstas/yandex-dialogs-smarthome-mqtt](https://github.com/popstas/yandex-dialogs-smarthome-mqtt) - Пример Provider Adapter API для управления MQTT устройствами
- [munrexio/yandex2mqtt](https://github.com/munrexio/yandex2mqtt) - Мост из Яндекс УД в MQTT на Node.js
- [subnetsRU/alice-command-skill](https://github.com/subnetsRU/alice-command-skill) - Навык позволяет выполнять несколько сценариев умного дома

## Видео

- [Школа Алисы - официальный канал на YouTube](https://www.youtube.com/channel/UCzQZwJjg0_1RyYPWB9sc4Wg)
- [Новая платформа уже здесь / Владимир Гриненко - WSD в Петербурге 2019](https://youtu.be/_0psqory6rk?t=22984)
- [Алиса, пойдём во фронтенд! / Никита Дубко - FrontendConf 2019](https://youtu.be/yjTH8-O3CMA)
- [Как и зачем разрабатывать свой скилл для Алисы / Виталий Потапов - AstanaJS 2019](https://youtu.be/zNMSjGv4kIQ)


## Чаты

- https://t.me/yadialogschat - Сообщество разработчиков Яндекс.Диалогов
- https://t.me/station_yandex - Чат для пользователей Яндекс.Станции
- https://t.me/yandex_phone - Чат для пользователей Яндекс.Телефон
- https://t.me/yandexdb - Новости и полезная информация про Яндекс.Станцию, Dexp Smartbox, Irbis A
- https://t.me/yandexflood - Флудилка для пользователей Яндекс Станции
- https://t.me/NewAliceSkills - Автоматический сканер новых навыков
- https://t.me/yandexcloud_chat - Чат для вопросов по Яндекс.Облаку

## Прочее

- [Неофициальный FAQ](https://docs.google.com/document/d/1SWxcIL0eKaMCIiuym6DQ4CtascBwm4IU1EL-Oxc2ldk/edit#heading=h.x6xi4enam35v)
- [aliceskill](https://aliceskill.ru/) - Неофициальный каталог навыков
- [alice.voice-ui.ru](https://alice.voice-ui.ru) - Неофициальный каталог навыков с сортировкой по новизне
- [Связка аккаунтов Алиса и Яндекс.Паспорт (OAuth2)](https://github.com/mokaton/wild-alice/blob/master/alice-oauth2-account-associate.md) - инструкция как сделать связку аккаунтов для Алисы без своего OAuth2-сервера
- [alice-protocol](https://github.com/vitalets/alice-protocol) - JSON схемы запросов и ответов в навыках Алисы.
- [yadialogsbot](https://t.me/yadialogsbot) - Телеграм чат-бот для мониторинга позиции в каталоге @yadialogsbot
- [alice-asset-manager](https://github.com/vitalets/alice-asset-manager) - Node.js API для загрузки изображений и звуков в навык Алисы.
- [Что умеет Dialogflow?](https://habr.com/ru/post/502688/) - Tutorial по Dialogflow
