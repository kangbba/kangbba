# Jin Hyung KANG (aka Sayne)

Game & Software Developer. Unity, mobile, and web. Based in Seoul, working remote.

- 30+ mobile titles shipped with six publishers (2019~2025):
  - 🇫🇷 Voodoo
  - 🇻🇳 Amanotes
  - 🇫🇷 Homa Games
  - 🇵🇱 BoomBit
  - 🇺🇸 Lion Studios
  - 🇰🇷 Supercent
- Solo-developed **The Secret Of Greenwood Isle**, a story adventure, over one year and released it on Steam and STOVE
- Currently building and running **Modu Dining**, a live multilingual restaurant menu service with an LLM translation pipeline

Portfolio, including a WebGL game you can play right in the browser: **[developersayne.dev](https://developersayne.dev)**

## Selected work

| Project | Year | What it is |
|---|---|---|
| **Demolding 3D** | 2020 | Development lead. Published by Homa Games. 2M+ estimated downloads (AppMagic). |
| **K-Games 3D** | 2021 | Development lead. Published by BoomBit. CPI under $0.05 in testing. |
| **The Secret Of Greenwood Isle** | 2025~26 | Solo development, one year. Released on [Steam](https://store.steampowered.com/app/3790450/The_Secret_Of_Greenwood_Isle/) and STOVE. |
| **Modu Dining** | 2026~ | Live restaurant web service. Next.js, Supabase, LLM pipeline. [modudining.com](https://www.modudining.com) |

## Code

Most of my shipped work is under publisher contracts or commercial releases, so those sources stay private. The public part lives in these repositories:

- [greenwood-isle-excerpts](https://github.com/kangbba/greenwood-isle-excerpts): story engine and UI widget excerpts from my Steam release. Composite elements on UniTask, dependency-injected engine seams, idempotent reactive widgets.
- [hell-keeper-excerpts](https://github.com/kangbba/hell-keeper-excerpts): script source of a released mobile game (ONE Store), art/audio assets excluded, playable as WebGL on my portfolio site.
- [bangawer-voice-translator-excerpts](https://github.com/kangbba/bangawer-voice-translator-excerpts): a custom ESP32 translator device with its Flutter app in one repo. BLE chunked audio streaming, ESP-ADF pipelines, stream-based app layer.
- [modu-dining-excerpts](https://github.com/kangbba/modu-dining-excerpts): source excerpts from Modu Dining, the live service above. A type-driven menu data engine that stays edit-safe across AI re-publishes, an LLM extraction schema tied to TypeScript by a compile-time witness, and a DAG scheduler for the translation pipeline.

## Stack

- **Games**: Unity, C#, UniRx, UniTask, DOTween, WebGL builds
- **Mobile**: Android (Java/Kotlin), Flutter. Release ops on App Store Connect, Google Play Console, Steamworks
- **Web**: Next.js, TypeScript, Tailwind, Supabase, Vercel
- **Hardware**: Arduino, ESP32 (ESP-IDF, ESP-ADF)

## Contact

sayneinteractive@gmail.com
