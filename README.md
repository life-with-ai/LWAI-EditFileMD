# LWAI-EditFileMD

[Русский](#русский) | [English](#english)

## Описание на русском

Редактор Markdown-файлов для чтения, редактирования и предварительного просмотра документов.

### Назначение

`LWAI-EditFileMD` объединяет работу с отдельными документами и папками проектов в одном рабочем пространстве. Файлы открываются во вкладках, структура рабочих папок отображается в дереве, а содержимое можно читать, редактировать и проверять в удобном режиме.

Приложение подходит для работы с инструкциями, базами знаний и другими проектными материалами.

### Быстрый старт

1. Скачайте архив `LWAI-EditFileMD-1.12.0-windows-x64-portable.zip` на странице [GitHub Releases](https://github.com/life-with-ai/LWAI-EditFileMD/releases/latest). Файл с расширением `.sha256` позволяет проверить целостность загруженного архива.
2. Полностью распакуйте архив на рабочий стол или в другую папку, в которой ваша учётная запись Windows имеет права на запись.
3. Откройте распакованную папку и запустите `LWAI-EditFileMD.exe`. Приложение работает в portable-режиме и не требует установки.
4. Добавьте одну или несколько рабочих папок либо откройте отдельный поддерживаемый файл.
5. Начните работу в разделённом режиме или выберите чтение либо редактирование.

Для первого запуска рекомендуется использовать рабочий стол или другую пользовательскую папку. Размещение приложения в защищённой системной папке может помешать сохранению настроек и рабочего состояния.

EXE не имеет цифровой подписи. При первом запуске Windows может показать стандартное предупреждение для загруженного файла.

### Основные возможности

- **Работа с проектами.** Подключение одной или нескольких папок, дерево файлов, вкладки и закрепление важных документов.
- **Три режима документа.** Чтение, редактирование или одновременное отображение Markdown-текста и визуального представления документа.
- **Поддержка Markdown.** Таблицы, списки задач, сноски, ссылки, локальные изображения, блоки кода, метаданные и другие элементы разметки.
- **Сохранение и внешние изменения.** Автосохранение, ручное сохранение и контроль изменений из других приложений помогают защитить текущую работу.
- **Текстовые форматы.** Поддерживаются Markdown (`.md`, `.markdown`), обычный текст (`.txt`), HTML и CSS (`.html`, `.htm`, `.css`), JavaScript и TypeScript (`.js`, `.mjs`, `.cjs`, `.jsx`, `.ts`, `.tsx`), структурированные данные (`.json`, `.xml`, `.svg`, `.yaml`, `.yml`), Python (`.py`, `.pyw`, `.pyi`), конфигурационные файлы (`.toml`, `.ini`, `.cfg`, `.conf`, `.properties`, `.env`, `.lock`), скрипты (`.ps1`, `.psm1`, `.psd1`, `.cmd`, `.bat`, `.sh`) и текстовые файлы ключей (`.pub`, `.ppk`). Их содержимое открывается как текст и не исполняется.
- **Конвертация кодировок.** Автоматическое определение, ручное переоткрытие и преобразование документов между поддерживаемыми кодировками.
- **Окончания строк.** Определение, сохранение и преобразование окончаний строк `LF` и `CRLF`.
- **Два языка интерфейса.** Интерфейс приложения доступен на русском и английском языках.
- **Темы и оформление.** Светлая, тёмная и системная темы, настройка шрифтов, цветов и рабочих областей.
- **Встроенная помощь.** Руководство пользователя объясняет работу с приложением, а отдельная Markdown-справка показывает основные элементы разметки на примерах.
- **Сохранение в PDF.** Markdown и другие поддерживаемые текстовые документы можно сохранить в PDF без изменения исходного файла.

### Совместимость конфигурации

Конфигурация версии `1.11.0` совместима с версией `1.12.0`. Настройки и рабочее состояние можно перенести без повторной настройки приложения.

1. Закройте обе версии приложения.
2. Полностью распакуйте архив версии `1.12.0` в новую папку.
3. Скопируйте папку `data` из portable-папки версии `1.11.0` в папку версии `1.12.0` с заменой существующей пустой папки.
4. Запустите `LWAI-EditFileMD.exe`.

В папке `data` хранятся настройки приложения и состояние рабочей области. Пользовательские документы остаются в исходных папках и при переносе конфигурации не копируются.

### Системные требования

- Windows 8.1 x64 – проверено;
- Windows 10 x64 – проверено;
- Windows Server 2025 Standard 24H2 x64 – проверено;
- Windows 11 x64 – практическое тестирование не выполнялось;
- Microsoft Edge WebView2 Runtime.

Если приложение не запускается из-за отсутствия Microsoft Edge WebView2 Runtime, загрузите его с [официальной страницы Microsoft](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section), запустите установщик и завершите установку по инструкциям Microsoft.

### Локальная работа и приватность

Документы остаются в выбранных пользователем папках на компьютере. Для основных функций не нужны учётная запись, сервер Life with AI или облачная синхронизация.

Приложение не содержит телеметрию, аналитику использования, рекламу или внешний сбор отчётов об ошибках. Настройки и рабочее состояние portable-версии хранятся локально в папке `data` рядом с приложением.

### Безопасность

Активный HTML в Markdown фильтруется, удалённые ресурсы не загружаются, а неподдерживаемые файлы не запускаются. Подробности приведены в [PRIVACY.md](PRIVACY.md) и [SECURITY.md](SECURITY.md).

### Лицензия и поддержка

Приложение можно бесплатно использовать в личных, образовательных, профессиональных и коммерческих целях. Распространение дистрибутива, перепродажа, включение в сторонние пакеты, модификация, ребрендинг и замена логотипов запрещены. Полные условия приведены в [LICENSE](LICENSE).

Сторонние компоненты регулируются собственными лицензиями: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) и [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt).

Порядок обращения за помощью и безопасный состав сообщения об ошибке приведены в [SUPPORT.md](SUPPORT.md). Порядок сообщения об уязвимости приведён в [SECURITY.md](SECURITY.md).

### Правообладатель

Life with AI – [life-with-ai.ru](https://life-with-ai.ru)

## Description in English

A Markdown file editor for reading, editing, and previewing documents.

### Purpose

`LWAI-EditFileMD` brings individual documents and project folders together in a single workspace. Files open in tabs, working-folder structure is displayed in a tree, and content can be read, edited, and reviewed in the most suitable mode.

The application is suitable for instructions, knowledge bases, and other project materials.

### Quick start

1. Download `LWAI-EditFileMD-1.12.0-windows-x64-portable.zip` from [GitHub Releases](https://github.com/life-with-ai/LWAI-EditFileMD/releases/latest). The accompanying `.sha256` file can be used to verify the integrity of the downloaded archive.
2. Extract the complete archive to the desktop or another folder where your Windows account has write access.
3. Open the extracted folder and run `LWAI-EditFileMD.exe`. The application runs in portable mode and requires no installation.
4. Add one or more working folders, or open an individual supported file.
5. Start in split mode, or select reading or editing.

For the first launch, use the desktop or another user folder. Placing the application in a protected system folder may prevent settings and workspace state from being saved.

The EXE is not digitally signed. Windows may display its standard warning for a downloaded file on first launch.

### Key features

- **Project workspace.** Add one or more folders, browse the file tree, use tabs, and pin important documents.
- **Three document modes.** Read, edit, or display the Markdown source and visual document preview side by side.
- **Markdown support.** Tables, task lists, footnotes, links, local images, code blocks, metadata, and other markup elements.
- **Saving and external changes.** Autosave, manual saving, and external change handling help protect current work.
- **Text formats.** Supported formats include Markdown (`.md`, `.markdown`), plain text (`.txt`), HTML and CSS (`.html`, `.htm`, `.css`), JavaScript and TypeScript (`.js`, `.mjs`, `.cjs`, `.jsx`, `.ts`, `.tsx`), structured data (`.json`, `.xml`, `.svg`, `.yaml`, `.yml`), Python (`.py`, `.pyw`, `.pyi`), configuration files (`.toml`, `.ini`, `.cfg`, `.conf`, `.properties`, `.env`, `.lock`), scripts (`.ps1`, `.psm1`, `.psd1`, `.cmd`, `.bat`, `.sh`), and text-based key files (`.pub`, `.ppk`). Their contents open as text and are not executed.
- **Encoding conversion.** Automatic detection, manual reopening, and document conversion between supported encodings.
- **Line endings.** Detection, preservation, and conversion of `LF` and `CRLF` line endings.
- **Two interface languages.** The application interface is available in Russian and English.
- **Themes and appearance.** Light, dark, and system themes, with configurable fonts, colors, and workspaces.
- **Built-in help.** The user guide explains how to work with the application, while the separate Markdown reference demonstrates common syntax with examples.
- **Save to PDF.** Markdown and other supported text documents can be saved as PDF without changing the source file.

### Configuration compatibility

The version `1.11.0` configuration is compatible with version `1.12.0`. Settings and workspace state can be transferred without configuring the application again.

1. Close both versions of the application.
2. Extract the complete version `1.12.0` archive to a new folder.
3. Copy the `data` directory from the version `1.11.0` portable folder to the version `1.12.0` folder, replacing the existing empty directory.
4. Run `LWAI-EditFileMD.exe`.

The `data` directory contains application settings and workspace state. User documents remain in their original folders and are not copied when the configuration is transferred.

### System requirements

- Windows 8.1 x64 – tested;
- Windows 10 x64 – tested;
- Windows Server 2025 Standard 24H2 x64 – tested;
- Windows 11 x64 – practical testing has not been performed;
- Microsoft Edge WebView2 Runtime.

If the application does not start because Microsoft Edge WebView2 Runtime is missing, download it from the [official Microsoft page](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section), run the installer, and complete the installation by following Microsoft's instructions.

### Local operation and privacy

Documents remain in the folders selected by the user. The main features do not require an account, a Life with AI server, or cloud synchronization.

The application contains no telemetry, usage analytics, advertising, or external crash reporting. Portable settings and workspace state are stored locally in the `data` directory next to the application.

### Security

Active HTML in Markdown is filtered, remote resources are not loaded, and unsupported files are not executed. Details are provided in [PRIVACY.md](PRIVACY.md) and [SECURITY.md](SECURITY.md).

### License and support

The application may be used free of charge for personal, educational, professional, and commercial purposes. Distribution of the package, resale, inclusion in third-party packages, modification, rebranding, and logo replacement are prohibited. Full terms are provided in [LICENSE](LICENSE).

Third-party components are governed by their own licenses: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) and [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt).

The support process and safe contents of a bug report are described in [SUPPORT.md](SUPPORT.md). The vulnerability reporting process is described in [SECURITY.md](SECURITY.md).

### Copyright holder

Life with AI – [life-with-ai.ru](https://life-with-ai.ru)
