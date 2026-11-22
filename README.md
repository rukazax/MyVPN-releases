# MyVPN

**RU** · [English](#english)

[![Последний APK](https://img.shields.io/github/v/release/rukazax/MyVPN-releases?label=APK&color=22c55e)](https://github.com/rukazax/MyVPN-releases/releases/latest)

Клиент изолированного каскадного VPN для Android: телефон → свой вход → зарубежный выход → интернет.
Исходники живут в закрытом репозитории; здесь — только готовые сборки, чтобы приложение можно было
поставить без доступа к коду.

## Скачать

**[Скачать последнюю версию APK](https://github.com/rukazax/MyVPN-releases/releases/latest)**

Прямая ссылка на текущую сборку:
`https://github.com/rukazax/MyVPN-releases/releases/latest/download/MyVPN-1.2.5-android-arm64-v8a.apk`

## Установка

1. Скачайте `MyVPN-<версия>-android-arm64-v8a.apk` — нужен Android 8.0 и новее, 64-битный процессор.
2. Разрешите установку из этого источника (Android спросит при первом запуске APK).
3. Откройте MyVPN и нажмите большую кнопку. Ключи выдадутся автоматически — отдельный пользователь на устройство.

Проверка файла: `sha256sum MyVPN-1.2.5-android-arm64-v8a.apk` должен совпасть со строкой в `SHA256SUMS-1.2.5.txt` из того же релиза.

## Что умеет

| Возможность | Как это выглядит |
|---|---|
| Плитка в шторке | Включает и выключает туннель, приложение открывать не нужно |
| Ключи на устройство | Отдельный пользователь, пароль и адрес выдаются при первом запуске |
| Перебор маршрутов | Reality (два входа) → SSH → AmneziaWG → RIVET |
| Раздельный туннель | Выбор приложений: только выбранные или все кроме выбранных |
| Темы | Светлая и тёмная включаются по системной настройке |
| Связь с автором | Строка «GitHub автора» внизу экрана ведёт на [github.com/rukazax](https://github.com/rukazax) |

## English

[![Latest APK](https://img.shields.io/github/v/release/rukazax/MyVPN-releases?label=APK&color=22c55e)](https://github.com/rukazax/MyVPN-releases/releases/latest)

An Android client for an isolated cascade VPN: phone → own entry → foreign exit → the internet.
The source lives in a private repository; this one holds ready-to-install builds only.

### Download

**[Download the latest APK](https://github.com/rukazax/MyVPN-releases/releases/latest)**

Direct link to the current build:
`https://github.com/rukazax/MyVPN-releases/releases/latest/download/MyVPN-1.2.5-android-arm64-v8a.apk`

### Install

1. Download `MyVPN-<version>-android-arm64-v8a.apk` — Android 8.0+ on a 64-bit CPU is required.
2. Allow installs from this source when Android asks.
3. Open MyVPN and press the big button. Keys are issued automatically, one user per device.

Verify: `sha256sum MyVPN-1.2.5-android-arm64-v8a.apk` must match `SHA256SUMS-1.2.5.txt` from the same release.

### Features

- Quick Settings tile: toggles the tunnel without opening the app.
- Per-device credentials issued on first launch.
- Route fallback: Reality (two entry points) → SSH → AmneziaWG → RIVET.
- Per-app split tunneling.
- Automatic light and dark theme.
- Author link at the bottom of the screen: [github.com/rukazax](https://github.com/rukazax)

#vpn #android #reality #xray #amneziawg #rivet
