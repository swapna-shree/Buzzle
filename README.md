# 📰 Buzzle - Personalized News Platform

Buzzle is a full-stack web application that delivers real-time, curated news to users based on country and category. It features a responsive UI, seamless transitions, and clean code architecture using modern web technologies.

---

## 📁 Project Structure

```

Buzzle-main/
├── client/         # Frontend - React + Tailwind CSS
│   ├── public/     # Static assets
│   └── src/        # Source code (components, assets, styling)
├── server/         # Backend - Node.js + Express
├── README.md       # Documentation

````

---

## 🚀 Features

- 🌍 View top headlines by country (via `CountryNews.jsx`)
- 🗂 Explore all news topics (via `AllNews.jsx`)
- ⚡ Fast, responsive frontend powered by **Vite** and **Tailwind CSS**
- 🧩 Reusable components: Header, Footer, Loader, News Cards
- 🔌 API integration with NewsAPI (or similar)
- 💻 Clean developer experience with modular structure

---

## 🛠️ Tech Stack

### Frontend
- **React.js** (Functional Components + Hooks)
- **Vite** (fast dev server)
- **Tailwind CSS** (utility-first styling)
- **Axios** (for API calls)
- **Responsive UI** using Flex/Grid

### Backend
- **Node.js** + **Express.js**
- **Dotenv** (for environment variable management)
- **CORS** + **Middleware** setup
- External API integration (likely NewsAPI)

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Buzzle-main.git
cd Buzzle-main
````

### 2. Install Dependencies

#### Frontend:

```bash
cd client
npm install
```

#### Backend:

```bash
cd ../server
npm install
```

---

## 🌍 Environment Variables

Create a `.env` file in the `/server` directory:

```env
PORT=5000
NEWS_API_KEY=your_news_api_key_here
```

Replace `your_news_api_key_here` with a valid NewsAPI key or the key you use in the app.

---

## ▶️ Run the App

### Start Backend:

```bash
cd server
npm start
```

### Start Frontend:

```bash
cd ../client
npm run dev
```

Visit: [http://localhost:5173](http://localhost:5173)

---

## 📂 Folder Highlights

### `client/src/components/`

| Component            | Purpose                        |
| -------------------- | ------------------------------ |
| `Header.jsx`         | Navigation bar                 |
| `Footer.jsx`         | Page footer                    |
| `AllNews.jsx`        | Displays all news articles     |
| `CountryNews.jsx`    | Filters news by country        |
| `EverythingCard.jsx` | Displays individual news items |
| `Loader.jsx`         | Shows loading animation        |

### `client/src/assets/`

Includes background images and icons for UI.

---

## 🖼️ Screenshots

> Add UI screenshots here (optional).

---

## 🌐 Deployment

### Frontend

* Recommended: [Vercel](https://vercel.com/)

```bash
npm run build
# then deploy the `dist/` folder
```

### Backend

* Recommended: [Render](https://render.com/) or [Railway](https://railway.app/)

```bash
# create web service, set environment variable `NEWS_API_KEY`
```

---

## 📌 TODO

* [ ] Add user authentication
* [ ] Bookmark/save favorite articles
* [ ] Dark mode
* [ ] Comment system
* [ ] Progressive Web App (PWA) support

---

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feat/feature-name`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feat/feature-name`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Swapnashree Sahoo**
Project developed with 💙 and React

---

## 📜 License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for more details.

```

---

Let me know if you want:
- Markdown badges (Tech stack, status)
- GitHub Actions setup for deployment
- More detailed contribution guidelines
- Auto-generated documentation from code

I can help you polish this to a professional portfolio-ready level if you'd like.
```

