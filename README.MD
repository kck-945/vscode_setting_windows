# VS Code Background Settings

This repo contains a ready‑to‑use **`settings.json`** that lets Visual Studio Code display rotating background images.  
Follow the two quick steps below to get it working and learn how to add your own pictures.

---

## 1 Enable the Background extension and apply the settings

| Step | Action |
|------|--------|
| **1. Install the extension** | In VS Code press **Ctrl + Shift + X** (Extensions), search for **“background”** by *shyykoserhiy*, and click **Install**. |
| **2. Open `settings.json`** | Go to **File → Preferences → Settings** (or **⚙️ → Settings**). In the upper‑right corner click **“Open Settings (JSON)”** (✏️ icon) — you can also reach it via **Text Editor → Font → Edit in settings.json**. |
| **3. Paste the repo file** | Copy **`settings.json`** from this repository and replace (or merge) your own `settings.json`, then save. |

VS Code will reload its configuration and immediately show the background images.

---

## 2 Add or change background pictures

Inside your `settings.json` you’ll find the array:

```json
"background.customImages": [
  "/C:/Users/User/Desktop/background_photo/1.JPG",
  "/C:/Users/User/Desktop/background_photo/2.JPG",
  "/C:/Users/User/Desktop/background_photo/3.JPG"
]
