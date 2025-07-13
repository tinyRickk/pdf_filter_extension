# 📄 PDF Keyword Filter Extension

This browser extension allows users to filter and view only the relevant sections of any PDF file based on **entered keywords**. Built with [PDF.js](https://mozilla.github.io/pdf.js/), this tool works across **Chrome**, **Edge**, and **Firefox** and runs on **any OS**.

---

## 🚀 Features

- 📝 Upload any PDF from your local device
- 🔍 Enter keywords (comma-separated) to display only the matching pages
- ⚡ Fast in-browser filtering with no backend
- 🎯 Works offline once installed

---


---

## 🖥️ How to Use (Development Mode)

1. Open **Chrome** (or Edge)
2. Go to `chrome://extensions/`
3. Enable **Developer Mode**
4. Click **“Load unpacked”**
5. Select the `extension/` folder

🦊 In **Firefox**:  
Go to `about:debugging#/runtime/this-firefox` → “Load Temporary Add-on” → Choose `manifest.json`

---

## ✅ Usage

1. Open the extension
2. Click **“Choose PDF”** to upload a file
3. Enter keywords in the input box (e.g., `security, quantum, encryption`)
4. Click **“Filter”**
5. Only the pages containing those keywords will be shown

---

## 🔧 Customization

You can:
- Replace or modify `pdf.js` for advanced PDF rendering
- Style the viewer with your own `CSS`
- Add features like export, print, or save filtered version

---

## 📦 Packaging for Web Store

1. Make sure `manifest.json` version is updated
2. Zip the contents of the `extension/` folder (not the folder itself)
3. Upload to the [Chrome Web Store](https://chromewebstore.google.com/) or [Firefox Add-ons](https://addons.mozilla.org/)

---

## 🔒 Privacy Notice

This extension works **completely offline**.  
No data is collected, stored, or sent anywhere.

---

## 🧑‍💻 Author

**Aman Gupta**  
📧 aman.ag220@gmail.com

---

## 📜 License

This project is licensed under the **GNU General Public License v3.0** (GPL-3.0).

You are free to use, modify, and distribute this software under the terms of the GPL.  
See the [LICENSE](./LICENSE) file for full license text or visit [gnu.org/licenses/gpl-3.0](https://www.gnu.org/licenses/gpl-3.0.html).

