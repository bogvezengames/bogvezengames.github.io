# Bog Vezen Games — GitHub Pages

Static website for UFO DRIFT: Space Arcade. Owner: bogvezengames.

## Публикуване

1. Влез в GitHub → New repository. Owner: bogvezengames. Repository name: bogvezengames.github.io. Избери Public и Add README. Create repository.
2. Разархивирай предоставения ZIP. В хранилището: Add file → Upload files. Качи ВСИЧКИ файлове от архива директно в корена; index.html трябва да е до README.md, а не в подпапка. GitHub не разархивира ZIP. Commit changes.
3. Settings → Pages → Source: Deploy from a branch → Branch: main → Folder: / (root) → Save.
4. Изчакай успешна deployment задача. Провери https://bogvezengames.github.io/ и https://bogvezengames.github.io/privacy.html без вход (например Incognito). Възможно е публикуването да отнеме до 10 минути.
5. Едва след проверката използвай тези адреси в Play Console като Developer website и Privacy policy. Това НЕ публикува играта в Google Play.

## Текущ статус

Сайтът описва вътрешната тестова версия с Google demo ads. Политиката е конкретна за текущия тест, НЕ е окончателно описание на бъдещата production реклама. Преди public release: довършване/проверка на consent, privacy options, аудитория и настройки, сверяване с Data safety и обновяване на политиката. Няма нов AAB с интегриран policy линк в този комплект.

Няма app-ads.txt с измислен publisher ID. За да го добавим: AdMob → Apps → View all apps → app-ads.txt → How to set up app-ads.txt → Copy. Изпрати точния предоставен от AdMob ред. Той се публикува като app-ads.txt в корена на СЪЩОТО хранилище. Не изпращай парола или secret keys.

Няма публичен Install бутон, защото играта още не е публично пусната. След launch добавяме проверения Play URL. Изображенията от gameplay са демонстрационни кадри от рендера на v0.30, не physical-device captures.

Сайтът не използва външни шрифтове, JavaScript, analytics, login или контактни форми. Контактът е mailto:bogvezen@gmail.com. Не качвай Android source, AAB, APK или upload ключа в това публично хранилище — само този сайт.

Официални инструкции: https://docs.github.com/en/pages/quickstart
AdMob: https://support.google.com/admob/answer/9363762
