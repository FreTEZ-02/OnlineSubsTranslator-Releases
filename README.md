# OnlineSubsTranslator

[Русский](#русский) · [English](#english) · [Releases](https://github.com/FreTEZ-02/OnlineSubsTranslator-Releases/releases)

## Русский

OnlineSubsTranslator — настольное приложение для ручного перевода субтитров. Редактор открывается в браузере. Можно импортировать субтитры с YouTube или из файла SRT, редактировать текст и тайминги и скачать готовый перевод в SRT. Есть распознавание речи через Whisper на устройстве.

### Скачать приложение

На [странице Releases](https://github.com/FreTEZ-02/OnlineSubsTranslator-Releases/releases) пока нет опубликованных сборок. Сборки для закрытого тестирования будут публиковаться в разделе **Assets** в зашифрованном виде. Ключ и шаги для расшифровки участники получают лично от владельца проекта.

| Система | Intel или AMD (64 бит) | ARM (64 бит) |
| --- | --- | --- |
| Windows | `win-x64.zip` | `win-arm64.zip` |
| macOS 13 Ventura или новее | `macos-x64.tar.gz` | `macos-arm64.tar.gz` (Apple Silicon, включая M1) |
| Linux | `linux-x64.tar.gz` | `linux-arm64.tar.gz` |

Ниже указаны окончания имён архивов после расшифровки. В начале имени будут название приложения и версия.

### Первый запуск

- **Windows.** Распакуйте ZIP целиком через **Извлечь всё**. В получившейся папке откройте `OnlineSubsTranslator.exe`. Тип процессора указан в **Параметры → Система → О системе → Тип системы**.
- **macOS.** Распакуйте архив в Finder и откройте `OnlineSubsTranslator.app`. Чип или процессор указан в меню Apple → **Об этом Mac**. Для сборок без подписи Developer ID и нотариального заверения macOS может запросить дополнительное подтверждение. Проверьте источник архива. [Инструкция Apple для первого запуска](https://support.apple.com/ru-ru/102445).
- **Linux.** Распакуйте архив и запустите `OnlineSubsTranslator` из получившейся папки. Если файловый менеджер не запускает файл, откройте терминал в этой папке и выполните `./OnlineSubsTranslator`. Команда `uname -m` покажет архитектуру. `x86_64` означает x64, а `aarch64` — arm64.

Редактор откроется в браузере по умолчанию. Если вкладка не открылась автоматически, откройте `http://127.0.0.1:4174/` в браузере. Язык редактора можно выбрать в верхней панели, **Русский** или **English**. Перед первым запуском Whisper откройте **Самопроверка → Проверить и восстановить**. Модели скачиваются при первом использовании, для этого нужен интернет.

### Перевод и экспорт

Вставьте ссылку на ролик, найдите и импортируйте дорожку субтитров или откройте SRT с компьютера. Выберите реплику, введите перевод и при необходимости измените тайминги. Нажмите **Скачать SRT**, чтобы сохранить заполненные реплики.

## English

OnlineSubsTranslator is a desktop app for translating subtitles by hand. The editor opens in your browser. You can import YouTube captions or an SRT file, edit the text and timing, and download your translation as an SRT. Whisper can also transcribe speech on your device.

### Download the app

No builds are published on the [Releases page](https://github.com/FreTEZ-02/OnlineSubsTranslator-Releases/releases) yet. Builds for closed testing will be published under **Assets** as encrypted downloads. Testers receive the decryption key and instructions directly from the project owner.

| System | Intel or AMD (64-bit) | ARM (64-bit) |
| --- | --- | --- |
| Windows | `win-x64.zip` | `win-arm64.zip` |
| macOS 13 Ventura or later | `macos-x64.tar.gz` | `macos-arm64.tar.gz` (Apple silicon, including M1) |
| Linux | `linux-x64.tar.gz` | `linux-arm64.tar.gz` |

The table lists archive filename endings after decryption. The app name and version come first.

### First launch

- **Windows.** Select **Extract All** to unpack the full ZIP. Open `OnlineSubsTranslator.exe` in the extracted folder. To check your processor type, open **Settings → System → About → System type**.
- **macOS.** Unpack the archive in Finder and open `OnlineSubsTranslator.app`. To check your chip or processor, open the Apple menu and choose **About This Mac**. For builds distributed without Developer ID signing and notarization, macOS may ask for extra confirmation. Verify the archive source. [Apple’s first-launch instructions](https://support.apple.com/en-us/102445).
- **Linux.** Unpack the archive and run `OnlineSubsTranslator` from the extracted folder. If the file manager does not launch it, open a terminal in that folder and run `./OnlineSubsTranslator`. Run `uname -m` to check your architecture. `x86_64` means x64 and `aarch64` means arm64.

The editor opens in your default browser. If the tab does not open automatically, go to `http://127.0.0.1:4174/` in your browser. Use the language menu at the top to choose **English** or **Русский**. Before using Whisper for the first time, open **Self-check → Check and repair**. An internet connection is needed to download the models on first use.

### Translate and export

Paste a video link and import a caption track, or open an SRT from your computer. Select a caption, enter its translation and adjust the timing as needed. Click **Download SRT** to save the translated captions.
