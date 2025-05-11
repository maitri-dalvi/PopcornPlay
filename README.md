# 🍿 Popcorn Play

**Popcorn Play** — your cozy corner on the internet to search and explore movies effortlessly!  
Fast, responsive, and aesthetic, Popcorn Play helps you find your favorite flicks, track trends, and keep movie nights magical. 🎬✨

---

## 🧰 Tech Stack

- ⚛️ **React 19** — Functional and fast frontend library
- ⚡ **Vite** — Lightning-fast development and build tool
- 🎨 **Tailwind CSS v4** — Utility-first CSS framework for rapid UI
- 🌊 **Flowbite** — Prebuilt Tailwind components for speedier development
- 🧠 **Appwrite** — End-to-end backend server for database
- 🎞️ **TMDb API** — To fetch real-time movie data

---

## 🚀 Features

### 🔍 Smart Movie Search
Type away! Our **debounced search** ensures your experience is smooth & performance-friendly.

> Implemented **debounce** to delay the API call until the user stops typing — this optimizes search results and avoids unnecessary requests to the api.

### 📈 Trending Movies
Wanna know what everyone’s watching? 🍿

> Track **clicks** on movie cards using **Appwrite's database**. Based on the number of clicks, PopcornPlay dynamically generates a **Trending Now** section — updated in real time! 🔥

### 💻 Fully Responsive UI
Whether you're on your phone, tablet, or widescreen TV, Popcorn Play adjusts perfectly.

### 🎨 Smooth UI with Flowbite
Used **Flowbite** components for a consistent and beautiful interface.

---

## ⚙️ How to Run Locally

```bash
git clone https://github.com/yourusername/popcorn-play.git
cd popcorn-play
npm install
npm run dev
```