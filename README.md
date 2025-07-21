# Ginto Discord & GG Sans - BetterDiscord Theme

A clean and flexible BetterDiscord theme that replaces the default Discord font (`gg sans`) with a custom one based on **Ginto Discord** and **Nord** font families.

> 🎨 Designed by [Laval](https://github.com/TheLaval)  
> 💬 Contact: Discord ID `lavalmc`

---

## 🧠 Features

- ✅ Fully self-hosted fonts (no external APIs)
- 🖋️ Supports **Ginto**, **Nord**, and **GG Sans** font families
- ⚙️ Easy to switch font using a single CSS variable
- 🎯 Targets most Discord UI components
- 🧪 Built for full compatibility with Discord's current design

---

## 🖥️ Preview

Coming soon...

---

## ✍️ How to Use

1. **Download** the `ginto.theme.css` file  
2. **Place it** in your BetterDiscord themes folder
3. **Open Discord**, go to Settings → Themes  
4. **Enable** `Ginto Discord & GG Sans`

---

## 🛠️ Customize the Font

Open the theme file and look for this part:

```css
:root {
  --customFont:

  'GG Sans Bold' /* Change this to your desired font */

  , sans-serif;
  --font-primary: var(--customFont), "gg sans";
  --font-display: var(--customFont), "gg sans";
}
```

You can change 'GG Sans Bold' to any of the [fonts listed below](https://github.com/TheLaval/betterdiscord/edit/main/README.md#-available-fonts) 👇

Make sure the name exactly matches the available fonts names.

# 🔤 Available Fonts

## Ginto Discord Nord (Logo Font)

- Nord Bold
- Nord Bold Italic
- Nord Black Italic

## Ginto Discord

- Regular
- Regular Italic
- Medium
- Medium Italic

## GG Sans (Default Discord Font)

- GG Sans Bold
- GG Sans Bold Italic
- GG Sans Extra Bold
- GG Sans Extra Bold Italic
- GG Sans Medium
- GG Sans Medium Italic
- GG Sans Normal
- GG Sans Normal Italic
- GG Sans Semi Bold
- GG Sans Semi Bold Italic

# 📁 File Structure

betterdiscord/

├── GintoDiscord.theme.css

├── README.md

├── LICENCE.md

├── Nord/
│   │
│   ├── Bold.woff2
│   │
│   ├── Bold Italic.woff2
│   │
│   └── Black Italic.woff2
│
├── Discord/
│   │
│   ├── Regular.woff2
│   │
│   ├── Medium.woff2
│   │
│   └── ...
│
└── GG Sans/
    │
    ├── Bold.woff2
    │
    ├── Medium.woff2
    │
    └── ...

All fonts are included via GitHub using @font-face.

# ⚖️ License

See https://github.com/TheLaval/betterdiscord/blob/main/LICENCE.md

# 🌐 Links

BetterDiscord Theme Page (SOON)
[GitHub Repository](https://github.com/TheLaval/betterdiscord/tree/main)

# 💬 Credits

Made with ❤️ by [Laval](https://github.com/TheLaval)
