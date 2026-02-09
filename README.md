# 📖 Book Finder

**Live Demo:** https://book-finder1240.netlify.app/

A modern, responsive web application built with **React 19** and **Vite**, allowing users to explore millions of books using the **Open Library API**. Search for your favorite titles, dive into detailed book descriptions, and maintain a personalized wishlist.

---

## ✨ Features

- **🔍 Smart Search**: Real-time book search with a 600ms debounce to optimize API calls and improve performance.
- **📄 Detailed Book Pages**: Explore rich metadata including descriptions (Markdown supported), authors, subjects, and first publication dates.
- **💖 Persistent Wishlist**: Save books you're interested in! The wishlist is powered by React Context and persists in your browser's `localStorage`.
- **🚀 High Performance**: Built with Vite for lightning-fast development and optimized build bundles.
- **🎨 Premium UI/UX**: 
  - Styled with **Tailwind CSS 4**.
  - Smooth hover animations and glassmorphism-inspired cards.
  - Interactive toast notifications via `react-hot-toast`.
- **📱 Fully Responsive**: Optimized for desktop, tablet, and mobile viewing.

---


<img width="1892" height="907" alt="1" src="https://github.com/user-attachments/assets/e3f95bc7-f007-45cf-aa0e-13a5d4216458" />

<img width="1898" height="903" alt="2" src="https://github.com/user-attachments/assets/0a352b74-f405-4b20-84da-4b1c224201bf" />

<img width="1897" height="902" alt="3" src="https://github.com/user-attachments/assets/9399f6f1-99dd-4a1c-9851-c7a8dca9ac4f" />

<img width="1900" height="911" alt="4" src="https://github.com/user-attachments/assets/7fad90d7-4796-4911-bddf-52b0da64dd6c" />

## 🛠️ Tech Stack

- **Frontend**: [React 19](https://react.dev/)
- **Bundler**: [Vite 7](https://vitejs.dev/)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **Routing**: [React Router 7](https://reactrouter.com/)
- **State Management**: React Context API
- **Icons**: [React Icons](https://react-icons.github.io/react-icons/)
- **API**: [Open Library Search API](https://openlibrary.org/developers/api)

---

## 🚀 Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed (LTS version recommended).

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/shuaibsiddiqui768/book-finder.git
   cd book-finder
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```

4. **Build for production**:
   ```bash
   npm run build
   ```

---

## 📂 Project Structure

```text
src/
├── assets/         # Images and static assets
├── components/     # Reusable UI components (Navbar, Footer, BookCard, etc.)
├── context/        # WishlistContext for global state management
├── pages/          # Main application views (Home, About, Wishlist, Details)
├── App.jsx         # Main application routing and layout
└── main.jsx        # Entry point
```

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## 👤 Author

**Shuaib Akhtar Siddiqui**
- GitHub: https://github.com/shuaibsiddiqui768
- LinkedIn: https://www.linkedin.com/in/sasiddiqui21/

---

**Happy Reading!** 📚✨

