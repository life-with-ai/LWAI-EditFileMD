# LWAI-EditFileMD

[Русский](#русский) | [English](#english)

## Русский

Понятный и функциональный локальный Markdown-редактор с предпросмотром для Windows.

Читайте документы, редактируйте Markdown-текст и работайте со структурой проектов в одном portable-приложении – без установки и регистрации.

### Для работы с документами и проектами

`LWAI-EditFileMD` создан для повседневной работы с локальными Markdown-документами, инструкциями, базами знаний и проектными материалами. Рабочие папки отображаются в дереве, документы открываются во вкладках, а сохранённая сессия помогает быстро вернуться к прежнему рабочему состоянию.

Для каждого документа доступны чтение, редактирование и разделённый режим. В разделённом режиме Markdown-текст и визуальное представление документа находятся рядом, поэтому изменения удобно проверять сразу.

Приложение не требует освоения сложной рабочей среды и готово к использованию сразу после распаковки архива.

### Основные возможности

- **Работа с проектами.** Подключение одной или нескольких папок, дерево файлов, вкладки и закрепление важных документов.
- **Три режима документа.** Чтение, редактирование или одновременное отображение Markdown-текста и визуального представления документа.
- **Поддержка Markdown.** Таблицы, списки задач, сноски, ссылки, локальные изображения, блоки кода и метаданные документа.
- **Сохранение и внешние изменения.** Автосохранение, ручное сохранение и контроль изменений из других приложений помогают защитить текущую работу.
- **Текстовые форматы.** Markdown, TXT, распространённые исходные и конфигурационные файлы открываются как обычный текст без исполнения содержимого.
- **Кодировки и переносы строк.** Приложение определяет поддерживаемые кодировки, позволяет конвертировать документы и сохраняет выбранный тип переносов строк.
- **Настраиваемый интерфейс.** Светлая, тёмная и системная темы, русский и английский языки, настройка шрифтов, цветов и оформления рабочих областей.
- **Встроенная помощь.** Руководство пользователя объясняет работу с приложением, а отдельная Markdown-справка показывает основные элементы разметки на примерах.
- **Сохранение в PDF.** Markdown и другие поддерживаемые текстовые документы можно сохранить в PDF без изменения исходного файла.

### Локальная работа без лишних сервисов

Документы остаются в выбранных пользователем папках на компьютере. Для основных функций не нужны учётная запись, сервер Life with AI или облачная синхронизация.

Приложение не содержит телеметрию, аналитику использования, рекламу или внешний сбор отчётов об ошибках. Настройки и рабочее состояние portable-версии хранятся локально в каталоге `data` рядом с приложением.

### Скачать

Актуальная версия – `1.12.0`: [GitHub Releases](https://github.com/life-with-ai/LWAI-EditFileMD/releases/latest).

Скачайте архив `LWAI-EditFileMD-1.12.0-windows-x64-portable.zip`. Файл с расширением `.sha256` позволяет проверить целостность загруженного архива.

### Быстрый старт

1. Скачайте архив `LWAI-EditFileMD-1.12.0-windows-x64-portable.zip`.
2. Полностью распакуйте архив на рабочий стол или в другую папку, в которой ваша учётная запись Windows имеет права на запись.
3. Откройте распакованную папку и запустите `LWAI-EditFileMD.exe`.
4. Добавьте одну или несколько рабочих папок либо откройте отдельный Markdown-файл и выберите удобный режим работы.

Для первого запуска рекомендуется использовать рабочий стол или другую пользовательскую папку. Размещение приложения в защищённой системной папке может помешать сохранению настроек и рабочего состояния.

Приложение работает в portable-режиме и не требует установки. EXE не имеет цифровой подписи, поэтому при первом запуске Windows может показать стандартное предупреждение для загруженного файла.

### Совместимость конфигурации

Конфигурация версии `1.11.0` совместима с версией `1.12.0`. Настройки и рабочее состояние можно перенести без повторной настройки приложения.

1. Закройте обе версии приложения.
2. Полностью распакуйте архив версии `1.12.0` в новую папку.
3. Скопируйте папку `data` из portable-папки версии `1.11.0` в папку версии `1.12.0` с заменой существующей пустой папки.
4. Запустите `LWAI-EditFileMD.exe`.

В папке `data` хранятся настройки приложения и состояние рабочей области. Пользовательские документы остаются в исходных папках и при переносе конфигурации не копируются.

### Системные требования

Для работы приложения требуются:

- Windows 8.1 x64 – проверено;
- Windows 10 x64 – проверено;
- Windows Server 2025 Standard 24H2 x64 – проверено;
- Windows 11 x64 – практическое тестирование не выполнялось;
- Microsoft Edge WebView2 Runtime.

Если приложение не запускается из-за отсутствия Microsoft Edge WebView2 Runtime, загрузите его с [официальной страницы Microsoft](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section), запустите установщик и завершите установку по инструкциям Microsoft.

### Безопасность и приватность

Приложение работает локально без аккаунта, телеметрии, сервера и облачной синхронизации. Активный HTML в Markdown фильтруется, удалённые ресурсы не загружаются, неподдерживаемые файлы не запускаются.

Подробности: [PRIVACY.md](PRIVACY.md) и [SECURITY.md](SECURITY.md).

### Лицензия

Приложение можно бесплатно использовать в личных, образовательных, профессиональных и коммерческих целях. Распространение дистрибутива, перепродажа, включение в сторонние пакеты, модификация, ребрендинг и замена логотипов запрещены. Полные условия приведены в [LICENSE](LICENSE).

Сторонние компоненты регулируются собственными лицензиями: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) и [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt).

### Поддержка

Ошибки и предложения функций: [SUPPORT.md](SUPPORT.md). Сообщения об уязвимостях: [SECURITY.md](SECURITY.md).

### Правообладатель

Life with AI – [life-with-ai.ru](https://life-with-ai.ru)

## English

A clear and capable local Markdown editor with preview for Windows.

Read documents, edit Markdown source, and work with project structures in one portable application – no installation or registration required.

### Work with documents and projects

`LWAI-EditFileMD` is designed for everyday work with local Markdown documents, instructions, knowledge bases, and project materials. Working folders are shown in a tree, documents open in tabs, and the saved session helps you quickly return to your previous workspace.

Every document supports reading, editing, and split mode. Split mode places the Markdown source and the visual document preview side by side, so changes can be checked immediately.

The application does not require a complex working environment and is ready to use as soon as the archive is extracted.

### Key features

- **Project workspace.** Add one or more folders, browse the file tree, use tabs, and pin important documents.
- **Three document modes.** Read, edit, or display the Markdown source and visual document preview side by side.
- **Markdown support.** Tables, task lists, footnotes, links, local images, code blocks, and document metadata.
- **Saving and external changes.** Autosave, manual saving, and external change handling help protect current work.
- **Text formats.** Markdown, TXT, and common source and configuration files open as plain text without executing their contents.
- **Encodings and line endings.** The application detects supported encodings, converts documents, and preserves the selected line ending format.
- **Customizable interface.** Light, dark, and system themes, Russian and English languages, and configurable fonts, colors, and workspace appearance.
- **Built-in help.** The user guide explains how to work with the application, while the separate Markdown reference demonstrates common syntax with examples.
- **Save to PDF.** Markdown and other supported text documents can be saved as PDF without changing the source file.

### Local work without unnecessary services

Documents remain in the folders selected by the user. The main features do not require an account, a Life with AI server, or cloud synchronization.

The application contains no telemetry, usage analytics, advertising, or external crash reporting. Portable settings and workspace state are stored locally in the `data` directory next to the application.

### Download

Current version – `1.12.0`: [GitHub Releases](https://github.com/life-with-ai/LWAI-EditFileMD/releases/latest).

Download `LWAI-EditFileMD-1.12.0-windows-x64-portable.zip`. The accompanying `.sha256` file can be used to verify the integrity of the downloaded archive.

### Quick start

1. Download `LWAI-EditFileMD-1.12.0-windows-x64-portable.zip`.
2. Extract the complete archive to the desktop or another folder where your Windows account has write access.
3. Open the extracted folder and run `LWAI-EditFileMD.exe`.
4. Add one or more working folders, or open an individual Markdown file and select the preferred working mode.

For the first launch, use the desktop or another user folder. Placing the application in a protected system folder may prevent settings and workspace state from being saved.

The application runs in portable mode and requires no installation. The EXE is not digitally signed, so Windows may display its standard warning for a downloaded file on first launch.

### Configuration compatibility

The version `1.11.0` configuration is compatible with version `1.12.0`. Settings and workspace state can be transferred without configuring the application again.

1. Close both versions of the application.
2. Extract the complete version `1.12.0` archive to a new folder.
3. Copy the `data` directory from the version `1.11.0` portable folder to the version `1.12.0` folder, replacing the existing empty directory.
4. Run `LWAI-EditFileMD.exe`.

The `data` directory contains application settings and workspace state. User documents remain in their original folders and are not copied when the configuration is transferred.

### System requirements

The following are required:

- Windows 8.1 x64 – tested;
- Windows 10 x64 – tested;
- Windows Server 2025 Standard 24H2 x64 – tested;
- Windows 11 x64 – practical testing has not been performed;
- Microsoft Edge WebView2 Runtime.

If the application does not start because Microsoft Edge WebView2 Runtime is missing, download it from the [official Microsoft page](https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section), run the installer, and complete the installation by following Microsoft's instructions.

### Security and privacy

The application works locally without an account, telemetry, a server, or cloud synchronization. Active HTML in Markdown is filtered, remote resources are not loaded, and unsupported files are not executed.

Details: [PRIVACY.md](PRIVACY.md) and [SECURITY.md](SECURITY.md).

### License

The application may be used free of charge for personal, educational, professional, and commercial purposes. Distribution of the package, resale, inclusion in third-party packages, modification, rebranding, and logo replacement are prohibited. Full terms are provided in [LICENSE](LICENSE).

Third-party components are governed by their own licenses: [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) and [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt).

### Support

For bug reports and feature requests, see [SUPPORT.md](SUPPORT.md). To report a vulnerability, see [SECURITY.md](SECURITY.md).

### Copyright holder

Life with AI – [life-with-ai.ru](https://life-with-ai.ru)
