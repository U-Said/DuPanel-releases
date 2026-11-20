# DuPanel

Dual-pane file manager in the spirit of Total Commander — for Windows, macOS, Linux and Android. One program, native on every system. Free, no ads, no data collection.

[Русский ниже ↓](#русский)

## Download

| Platform | File |
|---|---|
| **Windows 10/11** (Intel/AMD) | [DuPanel-Windows.zip](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-Windows.zip) |
| **Windows 11 on ARM** (Snapdragon: Surface Pro 11/12, Copilot+ PCs) | [DuPanel-Windows-arm64.zip](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-Windows-arm64.zip) |
| **macOS 12 or later** (Apple Silicon and Intel) | [DuPanel-macOS.zip](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-macOS.zip) |
| **Linux** (x64, desktops with GTK 3) | [DuPanel-Linux.tar.gz](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-Linux.tar.gz) |
| **Android 8.0+** (almost every phone) | [DuPanel-arm64.apk](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-arm64.apk) |
| Android, universal | [DuPanel.apk](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel.apk) |

The links always point to the latest version. All versions are in [Releases](https://github.com/U-Said/DuPanel-releases/releases).

## What it does

- **Two panels** with tabs, drive buttons, a clickable path line, columns (name, extension, size, date, attributes), natural sorting, quick search by typing, a name filter and folder history.
- **Total Commander keys:** F3 view, F4 edit, F5 copy, F6 move, F7 new folder, F8 delete, Alt+F7 search, Ctrl+M multi-rename, Insert / Space / Shift+arrows / Num+ / Num− to select. Every key can be reassigned.
- **Safe file operations:** progress with cancel, a question for every name conflict (replace, skip, rename, older only), a moved file is deleted only after its copy is complete, nothing is written half-way under the real name.
- **ZIP archives as folders:** open, copy in and out, pack, unpack, test.
- **Network:** FTP and FTPS, SFTP (password or key, host key check), SMB network folders.
- **Viewer (F3):** text and code in any encoding, hex, pictures, audio and video, PDF, Markdown, tables (CSV), Word/Excel/EPUB text, fonts, archive contents. Built-in text editor.
- **Tools:** file search by name and content, multi-rename with preview and undo, folder comparison and synchronization, checksums, folder sizes, attributes, properties.
- **Your look:** light and dark theme, color presets, your own colors and font sizes, toolbar and vertical bar with your buttons and programs.
- English and Russian interface.

## Install and update

**Windows.** Unpack the zip into any folder (for example `C:\Programs\DuPanel`) and run `DuPanel.exe`. Settings live next to it in `DuPanel.json` — the program is portable. To update, replace the folder contents.
**macOS.** Unpack, move DuPanel to Applications. The first time, right-click → Open (the app is not notarized).
**Linux.** Unpack, run `./dupanel`; `./install.sh` adds it to the applications menu. The built-in player needs libmpv (`sudo apt install libmpv2`).
**Android.** Open the APK on the phone and allow installing from this source. On first start DuPanel asks for access to all files — it needs it to manage files. The new 1.06 replaces the older DuPanel 1.12 for Android: uninstall the old one first if Android refuses to install over it.

[Privacy policy](https://u-said.github.io/dupanel-privacy/) — DuPanel collects nothing; files go only to servers you connect to yourself.

---

## Русский

Двухпанельный файловый менеджер в духе Total Commander — для Windows, macOS, Linux и Android. Одна программа, родная на каждой системе. Бесплатно, без рекламы и без сбора данных.

### Скачать

| Система | Файл |
|---|---|
| **Windows 10/11** (Intel/AMD) | [DuPanel-Windows.zip](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-Windows.zip) |
| **Windows 11 на ARM** (Snapdragon: Surface Pro 11/12, Copilot+ PC) | [DuPanel-Windows-arm64.zip](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-Windows-arm64.zip) |
| **macOS 12 и новее** (Apple Silicon и Intel) | [DuPanel-macOS.zip](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-macOS.zip) |
| **Linux** (x64, рабочие столы с GTK 3) | [DuPanel-Linux.tar.gz](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-Linux.tar.gz) |
| **Android 8.0+** (почти любой телефон) | [DuPanel-arm64.apk](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel-arm64.apk) |
| Android, универсальный | [DuPanel.apk](https://github.com/U-Said/DuPanel-releases/releases/latest/download/DuPanel.apk) |

Ссылки всегда ведут на последнюю версию. Все версии — в [Releases](https://github.com/U-Said/DuPanel-releases/releases).

### Что умеет

- **Две панели** с вкладками, кнопками дисков, строкой пути с переходом по частям, колонками (имя, тип, размер, дата, атрибуты), естественной сортировкой, быстрым поиском набором имени, фильтром и историей папок.
- **Клавиши Total Commander:** F3 просмотр, F4 правка, F5 копировать, F6 переместить, F7 папка, F8 удалить, Alt+F7 поиск, Ctrl+M групповое переименование, Insert / Пробел / Shift+стрелки / Num+ / Num− для выделения. Любую клавишу можно переназначить.
- **Надёжные операции:** прогресс с отменой, вопрос при каждом совпадении имён (заменить, пропустить, переименовать, только более старые), перемещаемый файл удаляется только после полной копии, ничего не пишется наполовину под настоящим именем.
- **ZIP-архивы как папки:** открыть, копировать внутрь и наружу, упаковать, распаковать, проверить.
- **Сеть:** FTP и FTPS, SFTP (пароль или ключ, проверка ключа сервера), сетевые папки SMB.
- **Просмотр (F3):** текст и код в любой кодировке, hex, картинки, аудио и видео, PDF, Markdown, таблицы CSV, текст Word/Excel/EPUB, шрифты, содержимое архивов. Встроенный редактор текста.
- **Инструменты:** поиск по имени и содержимому, групповое переименование с предпросмотром и отменой, сравнение и синхронизация папок, контрольные суммы, размеры папок, атрибуты, свойства.
- **Свой вид:** светлая и тёмная тема, готовые наборы цветов, свои цвета и размеры шрифтов, панель инструментов и вертикальная панель со своими кнопками и программами.
- Интерфейс на русском и английском.

### Установка и обновление

**Windows.** Распакуйте архив в любую папку (например, `C:\Programs\DuPanel`) и запустите `DuPanel.exe`. Настройки лежат рядом, в `DuPanel.json` — программа портативная. Для обновления замените содержимое папки.
**macOS.** Распакуйте и перенесите DuPanel в «Программы». В первый раз — правый щелчок → «Открыть» (программа не нотаризована).
**Linux.** Распакуйте, запустите `./dupanel`; `./install.sh` добавит её в меню программ. Встроенному плееру нужна libmpv (`sudo apt install libmpv2`).
**Android.** Откройте APK на телефоне и разрешите установку из этого источника. При первом запуске DuPanel попросит доступ ко всем файлам — без него файловый менеджер не может работать. Новая версия 1.06 заменяет прежний DuPanel 1.12 для Android: если Android не ставит её поверх, сначала удалите старую.

[Политика конфиденциальности](https://u-said.github.io/dupanel-privacy/) — DuPanel ничего не собирает; файлы уходят только на серверы, к которым вы подключаетесь сами.

© 2026 Umed SAIDOV
