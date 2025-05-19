# Toyhouse Live Editor

A local environment for creating and previewing **Toyhouse HTML/CSS** layouts.
Use this with **any code editor or IDE** (like VS Code, Atom, etc).

---

## 🌱 Who Is This For?

This was originally made for personal use.
If you're **new to coding**, you might prefer these easier online tools:

* [circlejourney’s Toyhouse Editor](https://th.circlejourney.net/)
* [Playhouse by cheeriko](https://playhouse.cheeriko.com/)

---

## 📦 Requirements

* You **must have [Node.js](https://nodejs.org/) and npm** installed.

---

## ⚠️ Notes

This is **not an exact replica** of Toyhouse's layout.
Some visuals (like icons) may look slightly off, but they **won’t affect how your layout works on Toyhouse.**

---

## ❤️ Credits
I'd like to give special thanks for the following resources for aiding this project:
* User page layout HTML: [Auroreon on Toyhouse](https://toyhou.se/14041524.pseudo-toyhouse-user-pages-)
* Character page layout HTML: [circlejourney’s Toyhouse Editor](https://th.circlejourney.net/)

---

##  Getting Started

### 1. 📁 Open your terminal in this project folder

Install required dependencies:

```bash
npm install
```

### 2.  Build and start the local server

```bash
npm run build
npm run dev
```

### 3.  Open the preview

* Visit `http://localhost:5173/` to preview a **User Page**
* Visit `http://localhost:5173/character` to preview a **Character Page**

---

## 🎨 User Pages – CSS Editing

1. Go to: `src/styles/`
2. The default file is: `style.css`

To use a different file:

* Open `index.html`
* Scroll to the bottom or search for `</head>` (around line 686)
* Replace this line:

```html
<link href="/src/style.css" rel="stylesheet">
```

With your custom file:

```html
<link href="/src/styles/your-file-name.css" rel="stylesheet">
```

---

## 🎨 User Pages – HTML Profile Content

1. Go to: `src/html/`
2. Default file is: `sample.html`

To use a different file:

* Open `index.html`
* Search for `02B.2 User Profile Content` (around line 1039)
* Replace:

```html
<div include-html="/src/html/sample.html"></div>
```

With:

```html
<div include-html="/src/html/your-file-name.html"></div>
```

---

## 🕴️ Character Pages – CSS Editing

1. Go to: `src/styles/`
2. Default file is: `style.css`

To use another file:

* Open `character.html`
* Search for `CHARACTER CSS HERE` (around line 19)
* Replace:

```html
<link href="/src/style.css" rel="stylesheet">
```

With:

```html
<link href="/src/styles/your-file-name.css" rel="stylesheet">
```

---

## 🕴️ Character Pages – HTML Profile Content

1. Go to: `src/html/`
2. Default file is: `sample.html`

To switch it out:

* Open `character.html`
* Search for `CHARACTER PROFILE CONTENT HERE` (around line 330)
* Replace:

```html
<div include-html="/src/html/sample.html"></div>
```

With:

```html
<div include-html="/src/html/your-file-name.html"></div>
```

---

## ❓ Need Help?

If you run into any issues, feel free to [open an issue](https://github.com/quexios/toyhouse-live-editor/issues). Feel free to contact me on [Toyhou.se](https://toyhou.se/Ghoulless) as well!

---
