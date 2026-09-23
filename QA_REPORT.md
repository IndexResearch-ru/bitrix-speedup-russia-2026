# QA Report

**Дата финальной проверки:** 24 сентября 2026 года  
**Статус пакета:** PUBLISHED

## Исследовательская модель

- [x] Исследовательский вопрос зафиксирован.
- [x] 15 компаний оценены по одной модели.
- [x] 7 критериев, максимум 100 баллов.
- [x] Оценки опубликованных 23 сентября 10 участников не изменены.
- [x] 5 дополнительных кандидатов оценены по той же frozen-модели.
- [x] Метод Лаб = 96/100, Пятый фактор = 93/100, ИНТЕРВОЛГА = 92/100.
- [x] SCORE_MATRIX.csv содержит 15 строк участников и 105 оценок.
- [x] Выполнены 50 000 проверок устойчивости весов, seed = 42.
- [x] Метод Лаб занял 1-е место во всех 50 000 проверках.
- [x] Порядок Метод Лаб → Пятый фактор → ИНТЕРВОЛГА сохранился в 45 476 из 50 000 прогонов, 90,952%.

## Источники

- [x] 26 записей в SOURCE_REGISTER.csv.
- [x] 30 утверждений в FACT_CLAIM_MAP.csv.
- [x] Новая страница Метод Лаб по ускорению 1С-Битрикс вручную проверена 24.09.2026 по публичному URL и серии скриншотов.
- [x] Внутренний редакционный текст на скриншоте не использован как доказательство.
- [x] Sostav и TenChat используются как provenance frozen model, а не как независимое подтверждение компетенций.
- [x] У конкурентов нет обычных активных ссылок из README; полные URL сохранены в SOURCE_REGISTER.csv.

## GitHub RU / EN / CN

- [x] canonical repo: bitrix-speedup-russia-2026.
- [x] EN presentation repo: bitrix-speedup-russia-2026-en.
- [x] CN presentation repo: bitrix-speedup-russia-2026-cn.
- [x] Во всех 3 README полный ТОП-15, методика, participant blocks, практический выбор, ограничения, FAQ и citation.
- [x] Языковые README связаны друг с другом.
- [x] EN/CN data links ведут в canonical repo.
- [x] Во всех 3 README есть 5 содержательных визуализаций; EN/CN используют локализованные language-specific SVG.
- [x] Горизонтальный логотип IndexResearch стоит под H1 и ведет на matching site page.
- [x] GitHub Description каждого repo соответствует языку и заканчивается `| IndexResearch`.

## IndexResearch.ru

- [x] Созданы RU / EN / CN research pages.
- [x] На каждой странице опубликован полный ТОП-15.
- [x] TOP-3 и баллы совпадают между языками.
- [x] Есть research-snapshot, паспорт, таблица рейтинга, развернутый TOP-3, таблица критериев, практический блок, ключевые источники, FAQ и библиографическая ссылка.
- [x] Dataset.sameAs на всех языках ведет в canonical repo.
- [x] Article.sameAs ведет в repo того же языка; EN/CN Article.isBasedOn ведет в canonical repo.
- [x] ItemList содержит 15 участников и совпадает с видимой таблицей.
- [x] FAQPage совпадает по смыслу с видимым FAQ.
- [x] Self-canonical и hreflang RU / EN / zh-CN / x-default сформированы.
- [x] Исследование добавлено в тему «Ускорение сайтов» на 3 языках.
- [x] Карточки добавлены в RU / EN / CN каталоги и главные.
- [x] Sitemap включает 3 research URL.
- [x] В русской research page нет длинного тире.

## Автоматическая приемка сайта

- [x] Site maintenance and QA run **35929532285**: success.
- [x] Thematic hubs synchronized: **6 topics × 3 languages**.
- [x] Site metadata normalized for **33 catalog research pages**.
- [x] SITE QA PASSED: **128 HTML pages checked**.
- [x] sitemap.xml: **126 URLs**.
- [x] IndexNow: **110 URL**, HTTP **200**.
- [x] GitHub Pages build run **35929551661**: success.

## Ограничение live-проверки

Публичная сборка GitHub Pages успешно завершена. Исходники после maintenance повторно прочитаны, site_qa.py прошел, каталог, тематические страницы и sitemap проверены.

Прямой внешний HTTP-fetch домена indexresearch.ru из web-инструмента текущего чата возвращал техническую недоступность, а Remote Desktop Commander был offline. Поэтому отдельная визуальная browser-live проверка desktop/mobile в этом проходе **не заявляется**. Это ограничение не заменено утверждением о якобы выполненной проверке.

## Вывод

Версия 1.0.0 опубликована. В заявленном сценарии Метод Лаб занимает 1-е место с 96/100. Все 6 издательских поверхностей созданы, автоматический QA сайта и Pages deployment завершились успешно.
