# Third-party notices

Дата проверки: 3 августа 2026 года.

`EditFileMD` содержит сторонние программные компоненты. Эти компоненты принадлежат соответствующим правообладателям и распространяются на условиях собственных лицензий.

Полный перечень package records, заявленные лицензии, ссылки на исходные пакеты, copyright notices и тексты лицензий приведены в файле [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt).

## Основные компоненты

| Компонент | Версия | Назначение | Лицензия |
|---|---:|---|---|
| Tauri | 2.11.5 | Windows application shell | Apache-2.0 OR MIT |
| Tauri API | 2.11.1 | Интерфейс приложения | Apache-2.0 OR MIT |
| Tauri dialog plugin | 2.7.1 | Системные диалоги выбора файлов и папок | MIT OR Apache-2.0 |
| React / React DOM | 19.2.7 | Пользовательский интерфейс | MIT |
| CodeMirror packages | 6.x | Редактор Markdown и исходного текста | MIT |
| react-markdown | 10.1.0 | Отображение Markdown | MIT |
| remark-gfm | 4.0.1 | Поддержка GitHub Flavored Markdown | MIT |
| rehype-highlight | 7.0.2 | Подсветка кода | MIT |
| rehype-raw | 7.0.0 | Разбор встроенного HTML | MIT |
| rehype-sanitize | 6.0.0 | Фильтрация HTML | MIT |
| encoding_rs | 0.8.35 | Декодирование и кодирование поддерживаемых Unicode- и legacy-форматов | (Apache-2.0 OR MIT) AND BSD-3-Clause |
| chardetng | 1.0.0 | Эвристическое определение BOM-less legacy-кодировок | Apache-2.0 OR MIT |

## Codicons

В интерфейсе `EditFileMD` используются отдельные SVG-иконки из набора Codicons.

- Правообладатель: Microsoft Corporation и участники проекта Codicons.
- Официальный источник: <https://github.com/microsoft/vscode-codicons>.
- Лицензия: Creative Commons Attribution 4.0 International (CC BY 4.0) — <https://creativecommons.org/licenses/by/4.0/>.
- Официальный файл лицензии: <https://github.com/microsoft/vscode-codicons/blob/main/LICENSE>.

## Встроенные шрифты

В приложение локально встроены две гарнитуры. Они загружаются из ресурсов приложения без обращения к CDN и без установки в Windows.

### Cascadia Code

- Версия: `2407.24`.
- Назначение: редактор, исходный код и выделенный текст с рамкой.
- Правообладатель: Microsoft Corporation и участники проекта Cascadia Code.
- Официальный источник: <https://github.com/microsoft/cascadia-code/releases/tag/v2407.24>.
- Лицензия: SIL Open Font License 1.1.
- Полный текст лицензии: [LICENSE-CASCADIA-CODE.txt](LICENSE-CASCADIA-CODE.txt).

### Inter

- Версия: `4.1`.
- Назначение: область чтения обычного текста и Markdown.
- Правообладатель: The Inter Project Authors.
- Официальный источник: <https://github.com/rsms/inter/releases/tag/v4.1>.
- Лицензия: SIL Open Font License 1.1.
- Полный текст лицензии: [LICENSE-INTER.txt](LICENSE-INTER.txt).

## Полные тексты лицензий

В составе присутствуют компоненты под лицензиями MIT, Apache-2.0, ISC, BSD-2-Clause, BSD-3-Clause, MPL-2.0, Unicode-3.0, Zlib, 0BSD, CC0-1.0, MIT-0 и Unlicense, включая варианты двойного и множественного лицензирования. Полные сведения о каждом компоненте и применимые тексты приведены в [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt).

Исходные версии компонентов, распространяемых по MPL-2.0, доступны по точным package source links в [THIRD_PARTY_LICENSES.txt](THIRD_PARTY_LICENSES.txt). Исходный код этих компонентов не изменялся.

## Microsoft Edge WebView2 Runtime

Microsoft Edge WebView2 Runtime не включён в portable ZIP и используется как отдельно установленный системный компонент. Его установка, обновление и использование регулируются условиями Microsoft.

## Разделение лицензий

Собственная лицензия `EditFileMD` приведена в файле [LICENSE](LICENSE). Она не заменяет и не ограничивает права, предоставленные лицензиями сторонних компонентов.
