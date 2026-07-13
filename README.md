# uBlock Origin Filters for YouTube
A curated set of **cosmetic filters** designed to declutter and enhance your YouTube browsing experience by removing distractions and unwanted UI elements.

## 🎯 Purpose
This filter list aims to clean up YouTube's cluttered interface. Inspired by community-driven efforts to streamline YouTube's increasingly busy layout.

## 🛠️ How to Use

### uBlock Origin (full version)
1. **Install [uBlock Origin](https://ublockorigin.com/)** (available for Chrome, Firefox, Edge, and more).
2. Open the uBlock Origin dashboard (click the extension icon → ⚙️ *Dashboard*).
3. Go to the **"Filter lists"** tab.
4. Scroll down to the **"Custom"** section.
5. Paste the raw URL of this filter list:
   ```
   https://raw.githubusercontent.com/houssemko/Ublock-Origin-filters-for-Youtube/main/Youtube-Declutter.txt
   ```
   If you're using Adblock Plus, use this URL instead:
   ```
   https://raw.githubusercontent.com/houssemko/Ublock-Origin-filters-for-Youtube/refs/heads/main/YouTube%20Declutter%20(Adblock%20Plus%20syntax).txt
   ```
6. Click **"Apply changes"**.

### uBlock Origin Lite (uBOL / Manifest V3)
uBO Lite added support for custom filters and subscribing to external filter lists. It still cannot run scriptlet injection (`##+js(...)`), so a small number of filters in this list won't work in uBOL.

1. **Install [uBlock Origin Lite](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh)**.
2. Open the uBO Lite dashboard (click the extension icon → *Dashboard* icon).
3. Go to the **"Custom filters"** pane.
4. Add this filter list URL:
   ```
   [https://github.com/houssemko/Ublock-Origin-filters-for-Youtube/blob/main/youtube-declutter-Ubo-lite.txt](https://raw.githubusercontent.com/houssemko/Ublock-Origin-filters-for-Youtube/refs/heads/main/youtube-declutter-Ubo-lite.txt)
   ```
5. Save/apply the custom filters.
6. Go to the **"Filtering mode"** section, find `youtube.com`, and set it to **Optimal** (or **Complete** if some filters still don't apply). Cosmetic filters won't take effect on Basic mode.

## 📦 What's Included
- Hides YouTube Shorts.
- Cleans up the homepage.
- Increases the number of videos on the homepage.

### ⚠️ Known limitation on uBO Lite
Two filters that suppress a mouseover color-sampling effect on the description box rely on scriptlet injection (`##+js(...)`), which uBO Lite does not support (no arbitrary JS string injection under Manifest V3). This effect will still appear for uBOL users; everything else in the list functions the same across both versions.

## 🙏 Credits
- [**na-parse/naparse-ublock-origin**](https://github.com/na-parse/naparse-ublock-origin) — Most of the filters come from their great work.
- [**Mnky313/uBlock_YouTube_Filters**](https://github.com/Mnky313/uBlock_YouTube_Filters)

## 📄 License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
