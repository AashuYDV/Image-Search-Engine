# 🔍 React Image Search App

A dynamic, responsive image search engine built with **React** and the **Unsplash API**. This web app allows users to search and browse high-quality images with a sleek UI and a seamless experience. Built with modern tools like Vite, functional components, and React Hooks.

![App Screenshot](./public/demo.png)

---

## 🚀 Live Demo

🔗 [Try the App](https://imageforall.netlify.app/)



---

## 📂 Folder Structure

```plaintext
image-search-react/
├── public/
│   └── index.html             # HTML template
├── src/
│   ├── App.jsx                # Main component
│   ├── ImageCard.jsx         # Individual image component
│   ├── main.jsx              # Entry point with ReactDOM
│   └── index.css             # Global styling
├── package.json              # Project dependencies and scripts
└── README.md                 # Project documentation
```

---

## 🛠️ Tech Stack

| Tool/Library   | Description                         |
|----------------|-------------------------------------|
| React          | UI library for component-based views |
| Vite           | Fast dev server & bundler           |
| Unsplash API   | Image source                        |
| JavaScript     | Logic & event handling              |
| CSS            | Styling and layout                  |

---

## 🔐 API Integration

This app uses the [Unsplash Developer API](https://unsplash.com/developers).

> 📌 Replace the sample API key in `App.jsx`:

```javascript
const API_KEY = "YOUR_UNSPLASH_API_KEY";
```

You can obtain your own key by creating a developer account at [Unsplash](https://unsplash.com/developers).

---

## 🧪 Getting Started

### 📦 Installation

```bash
git clone https://github.com/your-username/image-search-react.git
cd image-search-react
npm install
```

### ▶️ Running the App

```bash
npm run dev
```

Visit: [http://localhost:5173](http://localhost:5173)


## 🚀 Deployment

You can deploy this project using any static hosting service:

- **Vercel** – perfect for React + Vite
- **Netlify** – drag and drop the `dist/` folder
- **GitHub Pages** – with router setup

### 🔧 Build for Production

```bash
npm run build
```

This will generate a `dist/` folder for deployment.

---

## 🔮 Future Enhancements

- ♾️ Infinite scroll instead of button-based pagination
- 🌑 Dark mode toggle
- 🔥 Trending search tags and history
- ❤️ Favorite images with localStorage or Firebase
- 📥 Download or share buttons per image

---

## 👨‍💻 Author

**Aashutosh Yadav**  
Frontend Developer • React Enthusiast • UI/UX Explorer  
📫 [LinkedIn](https://www.linkedin.com/in/aashutosh-yadav-8635011a0/)  


---

## 📄 License

Licensed under the **MIT License**.  
Feel free to use, fork, and contribute to the project.

---

## 🙏 Acknowledgments

- [Unsplash](https://unsplash.com) — for the free API and image access  
- UI design inspired by neumorphism and clean design trends  
- Built with React, Vite, and ❤️
