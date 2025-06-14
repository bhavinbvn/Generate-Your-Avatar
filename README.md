
# 👤 Avatar Generator App

A fun and simple **ReactJS** app that lets you generate unique avatars using the [DiceBear Avatars API v7](https://www.dicebear.com/). Pick your favorite style, generate random avatars, and download them in a single click.

---

## 🚀 Features

- 🎨 Choose from multiple avatar styles (Bottts, Avataaars, Micah, etc.)
- 🔄 Generate random avatars with each click
- 💾 Download the avatars as SVG files
- 💡 Clean UI with React functional components and Hooks

---

## 📸 Demo

![Demo Screenshot](./demo.png)

---

## 🛠️ Tech Stack

- **ReactJS** (with Hooks)
- **Vite** (for fast development)
- **Axios** (for downloading SVG)
- **DiceBear API v7**

---

## 📂 Project Structure

```
avatarApp/
├── public/
├── src/
│   ├── Components/
│   │   └── Avatar.jsx
│   ├── Styles/
│   │   └── Avatar.css
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── index.html
├── package.json
└── README.md
```

---

## 🧑‍💻 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/avatarApp.git
cd avatarApp
```

### 2. Install dependencies
```bash
npm install
```

### 3. Start the app
```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) to view it in the browser.

---

## 🌐 DiceBear API Update (v7)

DiceBear has changed the API endpoint from:

```
https://avatars.dicebear.com/api/:style/:seed.svg
```

To:

```
https://api.dicebear.com/7.x/:style/svg?seed=:seed
```

✅ This app is updated to work with DiceBear v7.

---

## 📦 API Styles Used

- `bottts`
- `avataaars`
- `micah`
- `identicon`
- `jdenticon`
- `gridy`
- `human` *(if supported in v7, else replace with valid one)*

Visit [DiceBear Styles](https://www.dicebear.com/styles/) for more options.

---

## 📸 Screenshot

![App Screenshot](./screenshot.png)

---

## 📃 License

This project is open-source and free to use under the [MIT License](LICENSE).

---

## 💬 Contact

For any suggestions or issues, feel free to open an [Issue](https://github.com/your-username/avatarApp/issues) or reach out.

---

## 🌟 Show your support

Give a ⭐️ if you like this project!
