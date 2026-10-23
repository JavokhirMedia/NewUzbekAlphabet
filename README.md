# Özbekça (yangi) — klaviatura tartibi / keyboard layout

Yangi özbek lotin alifbosi (2026-yil 21-oktabr qonuni: **Ö Ğ Ş Ç**) uçun macOS va Windows klaviatura tartibi. Örnatuvçi — bitta fayl; örnatişda harflar qaysi tugmalarda bölişini özingiz tanlaysiz.
Keyboard layout for the new Uzbek Latin alphabet (**Ö Ğ Ş Ç**) for macOS and Windows. One installer per OS; you pick the key scheme during installation.

## Yuklab oliş / Download

**[Releases → eng songgi versiya / latest release](https://github.com/JavokhirMedia/NewUzbekAlphabet/releases/latest)**

| Fayl / File | Tizim / OS |
|---|---|
| `UzbekNew-<ver>.pkg` | macOS 12+ (Intel va Apple Silicon) |
| `UzbekNew-Setup-<ver>.exe` | Windows 10 / 11 (x64) |

## Ikki sxema / Two schemes

Tartib oddiy **US QWERTY**; faqat yangi harflar qöşilgan. Örnatişda bittasini tanlaysiz (ikkalasini ham örnatiş mumkin).

| Harf | **1 · Option / AltGr + harf** | **2 · Alohida tugmalar** |
|---|---|---|
| ş Ş | Option/AltGr + **S** | **;** |
| ç Ç | Option/AltGr + **C** | **'** |
| ö Ö | Option/AltGr + **O** | **[** |
| ğ Ğ | Option/AltGr + **G** | **]** |
| ʼ (tutuq belgisi) | Option/AltGr + **'** | **\\** |

- **Sxema 1**: qolgan hamma narsa standart US. macOS'da Option, Windows'da AltGr (öng Alt). Bosh harf — Shift bilan.
- **Sxema 2**: Turk Q klaviaturasi uslubi, tez terish uçun. Siljigan `[ { ] } ; : ' " \ |` belgilar Option/AltGr + öşa tugmaga ötadi. Option/AltGr + S/C/O/G ham işlayveradi. Tartib nomi: «Özbekça (yangi) – alohida tugmalar».
- Caps Lock ikkala sxemada bosh harf beradi.

## Örnatiş / Install

### macOS
1. `UzbekNew-<ver>.pkg` ni oçing. Paket imzolanmagan (Apple Developer ID yöq), şuning uçun macOS birinçi marta toʻxtatadi: **System Settings → Privacy & Security** → pastda **Open Anyway** (yoki Finder'da Control-klik → Open).
2. Örnatuvçida sxemani belgilang → **Install** (parol söraladi).
3. Tartib avtomatik ravişda Input Sources'ga qöşiladi. <kbd>⌃</kbd> + <kbd>Space</kbd> bilan **Özbekça (yangi)** ga öting va sinang: <kbd>⌥</kbd>+<kbd>S</kbd> → ş.
4. Agar menyuda körinmasa: tizimdan çiqib qayta kiring, keyin System Settings → Keyboard → Input Sources → Edit… → **+** → qidiruvga «Özbekça» → Add.

Olib taşlaş: `/Library/Keyboard Layouts` dagi `UzbekNew*.bundle` ni öçiring va qayta kiring.

### Windows
1. `UzbekNew-Setup-<ver>.exe` ni işga tuşiring. Imzolanmagan: SmartScreen çiqsa **More info → Run anyway**.
2. Sxemani tanlang → **Install**. «Tartibni mening kiritiş tillarimga qöşiş» belgisi yoqiq bölsin.
3. Tizimdan çiqib qayta kiring (Sign out → Sign in). <kbd>Win</kbd> + <kbd>Space</kbd> bilan **Özbekça (yangi)** ga öting.
4. Körinmasa: Settings → Time & Language → Language & region → Uzbek (Latin) → Keyboards → Add a keyboard.

Olib taşlaş: Settings → Apps → «Özbekça (yangi) klaviatura» → Uninstall.

---
English, in short: download the installer for your OS, run it (both are unsigned, so allow it once: macOS Privacy & Security → Open Anyway; Windows SmartScreen → Run anyway), choose a key scheme, install. On macOS the layout is added to your input sources automatically; on Windows sign out and back in, then switch with Win + Space.

Muammo yoki taklif: [Issues](https://github.com/JavokhirMedia/NewUzbekAlphabet/issues). MIT.
