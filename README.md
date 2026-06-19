# singbox_ruleset
Кастомные наборы правил (ruleset) для Sing-box

Автоматически обновляемый репозиторий со скомпилированными правилами (`.srs`) для **sing-box**.  
Скрипт синхронизации запускается ежедневно, скачивает актуальные версии правил из апстрим-репозиториев, сохраняет их в корень ветки `main` и очищает кэш CDN jsDelivr.

## 📋 Список правил

Для использования в конфигурации sing-box (тип `remote`) копируйте ссылки из таблицы ниже:

| Имя файла | Ссылка для sing-box (CDN) | Исходный репозиторий | Описание / Комментарий |
| :--- | :--- | :--- | :--- |
| **adguard.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/adguard.srs` | [adguard-filter-list-srs](https://github.com/jinndi/adguard-filter-list-srs) | Списоки фильтрации рекламы и трекеров AdGuard. |
| **cheburnet.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/cheburnet.srs` | [geosite-cheburnet](https://github.com/jinndi/geosite-cheburnet) | Специфические домены и сервисы (Чебурнет). |
| **filter.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/filter.srs` | [fakeip-filter-srs](https://github.com/jinndi/fakeip-filter-srs) | Правила фильтрации доменов для работы с Fake-IP. |
| **proxy.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/proxy.srs` | [geosite-blocked](https://github.com/jinndi/geosite-blocked) | Списки заблокированных доменов, требующих аэропорта из РФ. |
| **ruip.srs** | `https://cdn.jsdelivr.net/gh/jinndi/singbox_ruleset@main/ruip.srs` | [geoip-ru](https://github.com/jinndi/geoip-ru) | Чистые российские IP-адреса (без заблокированных подсетей). |
