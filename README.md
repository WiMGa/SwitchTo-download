# SwitchTo

[English](#english) · [Русский](#русский)

---

## English

SwitchTo is a keyboard layout switcher for Windows that fixes your typing for you: text typed in the wrong
layout (`ghbdtn` → «привет») and typos. Russian, Ukrainian and English.

### Download and install

**[Download SwitchTo for Windows](https://github.com/WiMGa/SwitchTo-download/releases/latest/download/WiMGa.SwitchTo-win-Setup.exe)**
(Windows 10/11, 64-bit, ~117 MB, no administrator rights needed).

1. Run the downloaded `WiMGa.SwitchTo-win-Setup.exe`.
2. If Windows shows a blue "Windows protected your PC" window (SmartScreen), click **More info**, then
   **Run anyway**. SwitchTo is new and not yet signed with a paid certificate, so Windows does not know it yet.
3. SwitchTo installs and starts by itself: a layout flag icon appears in the system tray (next to the clock).
   On the first start it needs about a minute to prepare its dictionaries.

SwitchTo starts with Windows. Updates arrive by themselves: a new version downloads in the background and is
installed while you are away from the keyboard (or right away: tray menu → **«Проверить обновление»**, Check for update).

The SwitchTo interface (tray menu and windows) is in Russian; the menu items below are given as they appear, with a translation.

### What it does

- **Switches the layout with one key:** right Shift — English, right Ctrl — Russian, right Alt — Ukrainian.
- **Fixes text typed in the wrong layout** when you press Space: `ghbdtn` → «привет», `руддщ` → "hello".
- **Fixes typos** when you press Space: «задествовать» → «задействовать». A hint near the cursor shows what was replaced.
- **Beeps** when a word does not look like any known word.
- **Learns from you:** a word you keep as typed is remembered; a replacement you undo is not made again.
- **Leaves password fields alone:** in password fields SwitchTo does not fix anything and does not record what you type.
- **Shows the benefit:** tray → **«Статистика…»** (Statistics) — how much was fixed and how much time it saved you.

### Keys and tray menu

- **Backspace right after a replacement** — undo it. The text returns exactly as you typed it, and SwitchTo
  remembers not to do it again.
- **Ctrl+Alt+Backspace** — mark a SwitchTo mistake ("it did the wrong thing here"). You can add a few words.
  This is the most useful help you can give us.
- Tray → **«Почему так?…»** (Why?) — the latest decisions with reasons; you can also check any text there.
- Tray → **«Пауза — не исправлять»** (Pause — do not fix) — turn corrections off for a while.
- Tray → **«Добавить слово в словарь…»** (Add word to dictionary) — teach SwitchTo a word it does not know.

### What is sent and how to turn it off

SwitchTo sends typing statistics (counters), the misspelled words with their replacements and a few words
around each mistake. The rest of your text and window titles are not sent. Data is tied to the installation,
not to you, and is stored in the EU (Frankfurt).

Tray → **«Что отправляется…»** (What is sent) shows exactly what goes out. To stop sending, clear the
**«Отправлять статистику и ошибки»** (Send statistics and errors) check box at the top of that window — it takes
effect immediately.

### Uninstall

Windows Settings → Apps → SwitchTo → Uninstall.

---

## Русский

SwitchTo — переключатель раскладки для Windows, который исправляет за Вас: текст, набранный не в той раскладке
(`ghbdtn` → «привет»), и опечатки. Русский, украинский, английский.

### Скачать и установить

**[Скачать SwitchTo для Windows](https://github.com/WiMGa/SwitchTo-download/releases/latest/download/WiMGa.SwitchTo-win-Setup.exe)**
(Windows 10/11, 64 бита, ~117 МБ, права администратора не нужны).

1. Запустите скачанный `WiMGa.SwitchTo-win-Setup.exe`.
2. Если Windows покажет синее окно «Windows защитила ваш компьютер» (SmartScreen) — нажмите
   **«Подробнее»**, затем **«Выполнить в любом случае»**. Программа новая и пока без платной подписи,
   поэтому Windows её ещё «не знает».
3. SwitchTo установится и запустится сам: иконка флажка раскладки появится в трее (у часов).
   При первом запуске он около минуты готовит словари.

SwitchTo запускается вместе с Windows. Обновления приходят сами: новая версия скачивается в фоне и ставится,
когда Вы отошли от компьютера (или сразу — меню трея **«Проверить обновление»**).

### Что делает

- **Переключает раскладку одной клавишей:** правый Shift — English, правый Ctrl — русская, правый Alt — українська.
- **Исправляет текст, набранный не в той раскладке,** на пробеле: `ghbdtn` → «привет», `руддщ` → «hello».
- **Исправляет опечатки** на пробеле: «задествовать» → «задействовать». Подсказка у курсора показывает, что заменено.
- **Сигналит**, если слово не похоже ни на одно известное.
- **Учится у Вас:** слово, которое Вы оставляете как есть, запоминает; замену, которую Вы отменяете, больше не делает.
- **Не трогает поля пароля:** в них SwitchTo ничего не исправляет и не записывает набранное.
- **Считает пользу:** трей → **«Статистика…»** — сколько исправлено и сколько времени сэкономлено.

### Клавиши и меню трея

- **Backspace сразу после замены** — отменить её. Текст вернётся как был набран, и SwitchTo запомнит, что так
  делать не нужно.
- **Ctrl+Alt+Backspace** — отметить ошибку SwitchTo: «тут он сделал не то». Можно дописать пару слов.
  Это самая полезная помощь для нас.
- Трей → **«Почему так?…»** — последние решения с причинами; там же можно проверить любой текст.
- Трей → **«Пауза — не исправлять»** — временно выключить исправления.
- Трей → **«Добавить слово в словарь…»** — научить SwitchTo слову, которого он не знает.

### Что отправляется и как выключить

SwitchTo отправляет статистику набора (счётчики), слова ошибок с заменами и несколько слов вокруг ошибки.
Остальной текст и заголовки окон не отправляются. Данные привязаны к установке, а не к Вам, и хранятся в ЕС
(Франкфурт).

Трей → **«Что отправляется…»** показывает всё как есть. Чтобы не отправлять, снимите галочку
**«Отправлять статистику и ошибки»** вверху этого окна — действует сразу.

### Удалить

Параметры Windows → Приложения → SwitchTo → Удалить.
