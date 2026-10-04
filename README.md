# HimikVPN

Android VPN-приложение. Версия **0.2.0-beta**, Android 7.0+.

## Скачать и установить

- [ARM64 — 57,5 МБ](https://github.com/pop0truas/HimikVPN/releases/download/v0.2.0-beta/HimikVPN-0.2.0-beta-arm64.apk): для современных Android-телефонов.
- [Универсальный APK — 247,7 МБ](https://github.com/pop0truas/HimikVPN/releases/download/v0.2.0-beta/HimikVPN-0.2.0-beta.apk): ARM64, ARMv7, x86, x86_64.
- [Контрольные суммы SHA-256](https://github.com/pop0truas/HimikVPN/releases/download/v0.2.0-beta/SHA256SUMS.txt).
- [Описание релиза и лицензии](https://github.com/pop0truas/HimikVPN/releases/tag/v0.2.0-beta).

Установите APK обычным способом Android. При первом подключении подтвердите системный запрос VPN. Пакет `ru.himikvpn.preview` сохранён для обновления предыдущей preview-версии.

## Возможности и ограничения

Реальный Android VPN service с XTLS/libXray, VLESS TLS/REALITY, HTTPS-проверка через VPN, доступ к backend, Android Keystore, ползунок подключения и стеклянные панели. Покупки открываются на существующем сайте/в боте.

Универсальный APK прошёл на эмуляторе тест реального локального VLESS/REALITY-туннеля и HTTPS через VPN, недоступного сервера, отключения, шифрованного хранилища и HTTPS-запроса к backend из WebView. Опубликованные APK проверены по SHA-256.

**Экспериментальная beta с debug-подписью.** Физический телефон и полный вход/подписка реального клиента ещё требуют проверки. Hysteria2 и нативный Google/Apple/Telegram OAuth не включены. Постоянного системного kill switch нет: завершение процесса может восстановить прямой доступ к сети. Смена сетей и ограничения батареи остаются непроверенными. Glass-материал реализован в web UI, не нативным Apple Liquid Glass.

Репозиторий предназначен для распространения APK и документации. Лицензии и ссылки на исходники встроенного ядра приложены к релизу в `THIRD_PARTY_NOTICES.zip`.
