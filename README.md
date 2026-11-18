# Ocarina of Time - Dualscreen

A dual-screen mod for **Ship of Harkinian** on Android.
The game plays on one screen. Your items, buttons, map and gear sit on the other, like Ocarina of Time 3D.

It also runs on regular phones and foldables, with touch buttons.

**This is a fan project. It is not made or approved by Nintendo.**

<!-- TODO: picture of the Thor, both screens, 3DS look -->

---

## ⚠️ You need your own copy of the game

**This app has no game files in it.** You need your own Ocarina of Time ROM.

- Any version that [Ship of Harkinian supports](https://github.com/HarbourMasters/Shipwright#quick-start).
- Make the ROM from your own cartridge or disc.

**Please don't ask for ROMs.** They won't be shared here, and issues asking for them will be closed.

---

## Install

1. Download the newest **APK** from the [Releases](../../releases) page.
2. Open it on your device and allow the install.
3. Open the app. Allow **file access** when asked.
4. Pick your ROM when asked. **Pick it from outside the `SOH` folder**, for example from Download.
5. The first start takes a while. It builds the game data from your ROM.
6. On a dual-screen device, allow **"Display over other apps"** if asked. This shows the menu on the second screen.

### Already have Ship of Harkinian on Android?

This app uses the same app name inside Android as other Ship of Harkinian Android builds.
So it **can't install over them**. Uninstall the old one first.

Your **`SOH` folder stays** after an uninstall. That folder has your saves and game data.

### Back up your saves

Saves live in the **`SOH/Save`** folder on your device. Copy it somewhere safe now and then.

---

## What it works on

| Device | What you get |
|---|---|
| **AYN Thor** | Game on the top screen. Items, buttons and map on the bottom. |
| **Anbernic RG DS** | The same, on two 4:3 screens. L2 / R2 change pages. |
| **Galaxy Z Fold** | Unfolded: game on top, menu below, touch buttons at the sides. |
| **Regular phone** | Upright: game, menu and touch buttons. Sideways: full screen with touch buttons. |

- Needs Android, 64-bit (arm64).
- A controller works everywhere. It hides the touch buttons.

---

## The second screen

### 3DS look (the default)

- **PLAY page:** big **B** and **C** buttons. Tap or hold them to use your items.
- **Ocarina button:** play the Ocarina, even when it isn't on a C button.
- **Iron Boots and Hover Boots** switches.
- **ITEMS page:** all your items. Tap an item, then a C button. Or drag it onto one.

### N64 look

- The real pause-menu pages: **Items, Map, Quest, Equip**, drawn with the game's own art.
- Tap gear on Equip to wear it.
- Tap an item on Items, then pick a C button.
- The map shows where Link is, in the world and in dungeons.

The **Style** button switches between the two looks.

### Title and file select

Game-art scenes on the second screen. The fairies follow your finger.

### Controller

- **L1 / R1:** change page on the second screen. On the RG DS it's **L2 / R2**.

### Screen controls

- **⇅ button:** swap screens, or hide the second screen.
- **Hold Back** (about 1 second): cycles swap, hide, and back to normal.
- **L3 + R3:** press to hide or show the second screen. Hold to swap.

---

## Known issues

- **The Ocarina's music staff doesn't show.** You can still play songs. This was like that before our changes.
- **Items don't work inside Link's house.** That's the original game's rule.
- **RG DS:** the pause screen can show an old picture with anti-aliasing (MSAA) above 1. The app sets it to 1 for you once.
- **Texture packs:** use only **one** background pack at a time. Two can clash, like a white shop in Castle Town.

Found something else? Please report it. 💛

---

## Report a bug

Open an **[Issue](../../issues)**. Please include:

- your device and Android version
- the app version (shown in Android's app info)
- what happened, and where in the game

A screenshot or short video helps a lot.

---

## Credits

This mod stands on a lot of other people's work. Thank you all.

- **[Harbour Masters](https://github.com/HarbourMasters/Shipwright)**: Ship of Harkinian, the PC port of Ocarina of Time.
- **The [Zelda Reverse Engineering Team](https://github.com/zeldaret/oot)**: turned the N64 game back into readable code.
- **[Waterdish](https://github.com/Waterdish/Shipwright-Android)**: Ship of Harkinian on Android.
- **[Darkaxt](https://github.com/Darkaxt/Shipwright-Android-Dual-Screen-Bleeding-Edge)**: the dual-screen Android version this mod starts from.

**This mod:** TheYellowBee and OffensiveNeon.
The 3DS-style and N64-style second screens, phone and foldable layouts, the RG DS fixes, and screen swapping.

**Built with help from Claude** (Anthropic's AI). We test every release on real devices.

Licenses for the parts above: [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).

---

## Legal

The Legend of Zelda and Ocarina of Time are trademarks of Nintendo. This project is not linked to Nintendo.
No game data from the original game is included. You bring your own.
