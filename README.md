# singbox_ruleset
Кастомные наборы правил (ruleset) для Sing-box

Автоматически обновляемый репозиторий со скомпилированными правилами (`.srs`) для **sing-box**.  
Скрипт синхронизации запускается ежедневно, скачивает актуальные версии правил из апстрим-репозиториев, сохраняет их в корень ветки `main` и очищает кэш CDN jsDelivr.

## 📋 Список правил

Для использования в конфигурации sing-box (тип `remote`) копируйте ссылки из таблицы ниже:

| Имя файла | Ссылка для sing-box (CDN) | Источник| Комментарий |
| :--- | :--- | :--- | :--- |
| **adguard.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/adguard.srs` | [adguard-filter-list-srs](https://github.com/jinndi/adguard-filter-list-srs) | Списоки фильтрации рекламы и трекеров AdGuard. |
| **cheburnet.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/cheburnet.srs` | [geosite-cheburnet](https://github.com/jinndi/geosite-cheburnet) | Специфические домены и сервисы (Чебурнет). |
| **filter.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/filter.srs` | [fakeip-filter-srs](https://github.com/jinndi/fakeip-filter-srs) | Правила фильтрации доменов для работы с Fake-IP. |
| **proxy.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/proxy.srs` | [geosite-blocked](https://github.com/jinndi/geosite-blocked) | Списки заблокированных доменов, требующих аэропорта из РФ. |
| **ruip.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/ruip.srs` | [geoip-ru](https://github.com/jinndi/geoip-ru) | Чистые российские IP-адреса (без заблокированных подсетей). |
| **ru.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/ru.srs` | [category-ru](https://github.com/KaringX/karing-ruleset/blob/sing/geo/geosite/category-ru.json) | KaringX |
| **ipdetect.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/ipdetect.srs` | [category-ip-geo-detect](https://github.com/KaringX/karing-ruleset/blob/sing/geo/geosite/category-ip-geo-detect.json) | KaringX |
| **private.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/private.srs` | [private](https://github.com/KaringX/karing-ruleset/blob/sing/geo/geosite/private.json) | KaringX |
| **trackers.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/trackers.srs` | [category-public-tracker](https://github.com/KaringX/karing-ruleset/blob/sing/geo/geosite/category-public-tracker.json) | KaringX |
| **games.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/games.srs` | [category-games](https://github.com/KaringX/karing-ruleset/blob/sing/geo/geosite/category-games.json) | KaringX |
| **ai.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/ai.srs` | [category-ai-chat-!cn](https://github.com/KaringX/karing-ruleset/blob/sing/geo/geosite/category-ai-chat-!cn.json) | KaringX |
