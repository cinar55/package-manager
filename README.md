# ⚡ SoftHub — Package Manager

A simple software directory site powered by GitHub. Browse and download Windows applications at [cinar55.github.io/package-manager](https://cinar55.github.io/package-manager).

---

## 📦 How it works

Each program in this repo is stored as a `.yaml` file. The website reads these files automatically and displays them as a list with download links.

---

## 🗂️ YAML Format

Every program has its own `.yaml` file. The format is:

```yaml
AD: Program Name
ICON: 🔧
LINK: https://example.com/download
```

| Field  | Description                              | Example                        |
|--------|------------------------------------------|--------------------------------|
| `AD`   | Program name                             | `7-Zip`                        |
| `ICON` | Emoji or direct image URL                | `🗜️` or `https://...icon.png` |
| `LINK` | Download link                            | `https://7-zip.org/download`   |

---

## ➕ Request a Program

Want a program added to the list? **Open an Issue!**

1. Go to the [Issues](../../issues) tab
2. Click **New Issue**
3. Fill in the program name and download link
4. Submit — I'll add it as soon as possible

---

## 🌐 Website

The site is live at:

**[https://cinar55.github.io/package-manager](https://cinar55.github.io/package-manager)**

It loads all `.yaml` files from this repo automatically. No setup needed — just add a `.yaml` file and it appears on the site.

---

## 📁 Repository Structure

```
package-manager/
├── index.html         # The website
├── README.md          # This file
├── 7zip.yaml
├── VLC.yaml
├── OBS.yaml
└── ...
```
