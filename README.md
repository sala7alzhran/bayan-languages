# Bayan language packs

Dictionaries for the languages of the **Bayan (بيان)** keyboard that do not ship with the app. The app comes with
English and Arabic; when you turn another language on, the keyboard downloads its pack here, so it can suggest and
correct words in that language.

قواميس لغات لوحة مفاتيح **بيان** التي لا تأتي مع التطبيق. يأتي التطبيق بالإنجليزية والعربية، وعند تشغيل لغة أخرى
تُنزَّل حزمتها من هنا لتقترح اللوحة كلماتها وتصحّحها.

| Language | File | Source | License |
|----------|------|--------|---------|
| French (Français) | `packs/fr.nxd.gz` | AOSP LatinIME word list | Apache License 2.0 |
| German (Deutsch) | `packs/de.nxd.gz` | AOSP LatinIME word list | Apache License 2.0 |
| Spanish (Español) | `packs/es.nxd.gz` | AOSP LatinIME word list | Apache License 2.0 |
| Italian (Italiano) | `packs/it.nxd.gz` | AOSP LatinIME word list | Apache License 2.0 |
| Portuguese (Português) | `packs/pt.nxd.gz` | AOSP LatinIME word list | Apache License 2.0 |
| Turkish (Türkçe) | `packs/tr.nxd.gz` | AOSP LatinIME word list | Apache License 2.0 |
| Indonesian (Bahasa Indonesia) | `packs/id.nxd.gz` | FrequencyWords (OpenSubtitles 2018) | CC BY-SA 4.0 |
| Malay (Bahasa Melayu) | `packs/ms.nxd.gz` | FrequencyWords (OpenSubtitles 2018) | CC BY-SA 4.0 |
| Filipino | `packs/tl.nxd.gz` | FrequencyWords (OpenSubtitles 2018) | CC BY-SA 4.0 |
| Russian (Русский) | `packs/ru.nxd.gz` | AOSP LatinIME word list | Apache License 2.0 |
| Persian (فارسی) | `packs/fa.nxd.gz` | FrequencyWords (OpenSubtitles 2018) | CC BY-SA 4.0 |
| Urdu (اردو) | `packs/ur.nxd.gz` | FrequencyWords (OpenSubtitles 2018) | CC BY-SA 4.0 |

Each file is a gzip of a Bayan dictionary (`.nxd`): words and how often they are used, no sentences.
`packs.json` lists each pack with its size and SHA-256; the keyboard checks the hash of what it downloads.

## Sources

- **AOSP LatinIME word lists**, Android Open Source Project, Apache License 2.0 —
  https://android.googlesource.com/platform/packages/inputmethods/LatinIME/+/refs/heads/main/dictionaries/
- **FrequencyWords** by Hermit Dave, built from OpenSubtitles 2018, content under CC BY-SA 4.0 —
  https://github.com/hermitdave/FrequencyWords. The packs made from it are shared under CC BY-SA 4.0.
