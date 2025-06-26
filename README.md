# Demonstration Video

[Link to the video](https://sdrive.cnrs.fr/s/sPJmor4KHaf7N8Z "Link to the demonstration video")

# SystemX Usage Guide

## Pre-requisites

| Requirement            | Details                                         |
|------------------------|-------------------------------------------------|
| **Browser**            | Firefox Desktop (version 48 or newer)          |
| **Supported OS**       | Windows 10/11, macOS, and Linux                 |
| **Internet Connection**| Stable connection required                      |

---

## Installation Guide

1. ~~Download the extension from:~~

2. Open Firefox and type `about:addons` in the address bar.

3. Click the gear icon ⚙ at the top right of the Add-ons page.

4. Select **"Install Add-on From File…"**.

5. Browse and select the `.xpi` file, then click **Open**.

6. Confirm the installation when prompted by Firefox — click **“Add”**.

7. *(Optional)* Pin the extension to the taskbar.

---

## Usage Guide

1. Navigate to one of the supported websites:
   - [ASSETS 2025 website](https://assets25.sigaccess.org/)
   - [Mock News article](https://article-tagthunder.netlify.app/) *(Best with 7 zones)*
   - [Mock News Website](https://news-tagthunder.netlify.app/)
   - *(Other websites may work, but may not run properly due to size/constraints)*

2. Click the extension icon and check if the server status is **"available"**.
   - If not, try again later.

3. *(Optional)* Configure:
   - Number of zones
   - Keywords
   - N-gram size

4. Click **"Start"** and wait up to a minute or two.

5. After loading finishes, configure:
   - **Skimming Mode**: Overview of the webpage once vocalization starts.
   - **Scanning Mode**: Navigate and receive vocal feedback.

6. **Enable Vocalization:**
   - **Windows**: `Ctrl + Alt + J`
   - **Mac**: `Cmd + ⌥ + J`

7. **Enter/Exit a Zone:**
   - Press `Ctrl` (or `Cmd` on Mac) and **Left Click** to enter.
   - Same + **Right Click** to exit.

---

## Important Notes

- The TagThunder tree is limited to **depth 1** due to performance constraints.
- Only **English** pages are fully supported for vocalization.
  - Other languages may be vocalized with incorrect English pronunciation.
- Use **5–8 distinct zones** for best results.
  - If zones are too similar, reload the page and increase the number of zones.

- For scanning strategies:
  - **Target Only**, **Origin-Target**, **Proximity**
  - Direction/distance are measured from the **cursor position** to the **zone’s center**, not edges.
  - Stay within a **30° angle** from the zone’s center for reliable navigation.

---

## Common Issues

### What if I don’t hear any sound?

1. Check if Firefox is blocking audio in the **URL bar**.
2. Restart sound:
   - Press `Ctrl + Alt + J` (or `Cmd + ⌥ + J`) **twice**.
3. If it still doesn’t work, the page might not be supported due to **Content Security Policy** limitations.

---
