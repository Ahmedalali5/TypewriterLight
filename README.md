# Typewriter Light

A floating, amber-lit typewriter guide for Windows. A fixed ruler sits just under the line you are typing on, while the lever (the little typebar) and its light column slide along with the text caret.

An always-on-top typing companion that appears wherever there is a text cursor.

## Features

- **Works anywhere** — follows the text caret in Microsoft Word, Windows Notepad, web browsers, and any other window that shows a typing caret.
- **Browser support** — Chrome, Edge, Comet, Brave, Firefox, Opera and Vivaldi: page fields, forms, contenteditable areas and the address bar.
- **Fixed ruler, moving lever** — the ruler stays in place; only the lever, the cursor marker and the light beam move as you type.
- **Hover to hide** — the overlay fades away when the mouse pointer passes over it and comes back when you move away.
- **Mechanical sounds** — optional key strikes, carriage return and margin bell, with a volume control.
- **Adjustable appearance** — rail width and thickness, module size, vertical offset, light intensity, opacity, glow, beam width, warmth and color (yellow / blue / red).
- **Motion tuning** — lever follow speed, carriage-return speed, strike depth and duration.
- **Global hotkey** — default `Ctrl+Alt+T` to toggle the overlay.
- **Start with Windows** and system-tray controls.
- **Privacy first** — no document text, keystrokes, page URLs or window titles are ever recorded.

## Install (Windows)

1. Open the **Releases** page and download `TypewriterLight-win-x64.zip`.
2. Extract it anywhere, for example `C:\Program Files\TypewriterLight` or a folder in your user profile.
3. Run `TypewriterLight.exe`.

No .NET installation is required — the build is self-contained. Administrator rights are not needed.

### Requirements

- Windows 10 or Windows 11, 64-bit (x64).

### Notes

- The executable is not code-signed, so Windows SmartScreen may show a warning on first launch. Choose **More info → Run anyway**.
- Settings are stored in `%APPDATA%\TypewriterLight\settings.json`.
- Logs are written to `%LOCALAPPDATA%\TypewriterLight\logs`.
- Keep the whole extracted folder together; the application is not a single-file executable.

## Usage

- Start typing in any supported field; the typewriter appears under the active line.
- Move the mouse over the ruler to make it fade out; move away to bring it back.
- Press `Ctrl+Alt+T` (default) to toggle the overlay.
- Use the tray icon to open settings or exit.

## Privacy

Typewriter Light reads only the geometry of the text caret (its on-screen position). It never reads, stores or transmits document content, typed text, page URLs, window titles or clipboard data.

## License

Freeware. Provided "as-is", without warranty of any kind. The binaries may be redistributed unmodified.

---

## نبذة بالعربية

أداة «الآلة الكاتبة» العائمة لويندوز: مسطرة ثابتة أسفل سطر الكتابة، مع ذراع ومؤشر وحزمة ضوء تتحرك مع مؤشر الكتابة أثناء الطباعة. تعمل في أي برنامج فيه حقل نص (Word، Notepad، المتصفحات وغيرها)، وتختفي عند مرور مؤشر الفأرة فوقها، مع أصوات ميكانيكية اختيارية وإعدادات مظهر وحركة كاملة. لا تحتاج تثبيت .NET ولا صلاحيات مدير، وتعمل على Windows 10/11 إصدار 64-bit.
