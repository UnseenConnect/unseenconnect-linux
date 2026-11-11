# UnseenConnect — Linux

| | |
|--|--|
| [📦 Скачать .deb](https://github.com/UnseenConnect/unseenconnect-linux/releases/latest/download/UnseenConnect-linux-x64.deb) | Рекомендуется · Debian / Ubuntu · amd64 |
| [Архив tar.gz](https://github.com/UnseenConnect/unseenconnect-linux/releases/latest/download/UnseenConnect-linux-x64.tar.gz) | Портативная сборка |

UnseenConnect — приложение для **Linux** для удобного управления прокси-серверами на базе ядра Xray. Простой интерфейс, работа из трея, импорт подписки и быстрое подключение к нужному серверу.

---

## Установка (.deb)

1. Скачайте **UnseenConnect-linux-x64.deb** по кнопке выше.
2. Установите пакет:

```bash
sudo apt install ./UnseenConnect-linux-x64.deb
```

3. Запустите **UnseenConnect** из меню приложений или командой `unseenconnect`.
4. Вставьте ссылку на подписку или конфиг `vless://`.
5. Выберите сервер и нажмите **Подключить**.

> Нужен **Debian / Ubuntu x64** (или совместимый дистрибутив) с GTK 3. Для иконки в трее ставится `libayatana-appindicator3-1`.

---

## Портативная сборка

1. Скачайте **UnseenConnect-linux-x64.tar.gz**.
2. Распакуйте и запустите:

```bash
tar -xzf UnseenConnect-linux-x64.tar.gz
cd UnseenConnect
./unseen_connect
```

Для VPN-режима (TUN) один раз выдайте права ядру Xray:

```bash
sudo setcap cap_net_admin,cap_net_raw+ep ./xray/xray
```

---

## Возможности

* Импорт подписки и конфигов в один клик
* Системный прокси и полноценный VPN-режим (TUN)
* Список серверов с пингом и выбором лучшего узла
* Автообновление подписки и автоподключение
* Работа в фоне из системного трея
* Автоматическое обновление приложения
* Тёмная тема, поддержка нескольких языков

## Поддерживаемые протоколы

* **VLESS (Reality)**
* **VMess**
* **Trojan**
* **Shadowsocks**
* **SOCKS**

---

UnseenConnect не собирает ваши данные — всё хранится только на вашем компьютере.

Приложение **не продаёт VPN-подписки**. Серверы вы подключаете самостоятельно у своего провайдера. Используйте сервис в соответствии с законодательством вашей страны.

| **Telegram** | [t.me/unseen\_vpn](https://t.me/unseen_vpn) |
| ------------ | ------------------------------------------ |
| **Сообщить о проблеме** | [GitHub Issues](https://github.com/UnseenConnect/unseenconnect-linux/issues) |
| **Windows-версия** | [unseenconnect-desktop](https://github.com/UnseenConnect/unseenconnect-desktop) |
| **Android-версия** | [unseenconnect-android](https://github.com/UnseenConnect/unseenconnect-android) |
