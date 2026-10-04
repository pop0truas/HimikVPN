# HimikVPN

Android 7.0+. Версия **0.3.0-beta**.

- [Скачать ARM64 APK — 57,5 МБ](https://github.com/pop0truas/HimikVPN/releases/download/v0.3.0-beta/HimikVPN-0.3.0-beta-arm64.apk)
- [Универсальный APK — 247,4 МБ](https://github.com/pop0truas/HimikVPN/releases/download/v0.3.0-beta/HimikVPN-0.3.0-beta.apk)
- [Релиз, контрольные суммы и лицензии](https://github.com/pop0truas/HimikVPN/releases/tag/v0.3.0-beta)

Установите APK обычным способом Android. При первом подключении подтвердите запрос VPN. Пакет ru.himikvpn.preview сохранён для обновления предыдущей версии.

Кнопки, переключение вкладок и блоки аккаунта переделаны по apple-design. Реальный Android VPN service с XTLS/libXray поддерживает VLESS TLS/REALITY и Hysteria2, TLS/SNI/IPv6/ALPN, Salamander и переключение портов. Есть HTTPS-доступ к backend и Android Keystore. Покупки открываются на сайте/в боте.

Сборки TypeScript/web/Android прошли; один реальный Hysteria2-тест на эмуляторе подтвердил TLS/Salamander, protected sockets, HTTPS200 через VPN и отключение. До этой версии были проверены VLESS/REALITY, недоступный сервер, Keystore и backend WebView. SHA-256 опубликованных APK совпадают.

**Debug-beta.** Физический телефон, полный вход/подписка клиента и переключение сетей ещё требуют проверки. Переключение портов отдельно не проверялось. pinSHA256, небезопасный TLS, Gecko и realm-ссылки отклоняются. Явные Xray pcs/vcn поддерживаются, но pcs имеет другие правила проверки сертификата. Нативный OAuth и постоянный системный kill switch недоступны. Glass реализован в web UI.

Репозиторий распространяет APK и документацию. Лицензии и исходники ядра — в THIRD_PARTY_NOTICES.zip из релиза.
