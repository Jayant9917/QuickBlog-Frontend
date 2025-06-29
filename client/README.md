## This is a practice Project for RaectJS


# QuickBlog Client

A modern, responsive blogging platform built with React, Vite, and TailwindCSS. QuickBlog allows users to browse, search, and read blog posts across various categories, with a clean UI and smooth navigation.

## Features

- Browse blogs by category (Technology, Startup, Lifestyle, Finance, etc.)
- View detailed blog posts
- Search for blogs
- Responsive design for all devices
- Newsletter subscription form
- Animated UI with [motion](https://motion.dev/)
- Admin login button (UI only)
- Comment system (data-driven, UI only)

## Tech Stack

- [React 19](https://react.dev/)
- [Vite](https://vitejs.dev/) (for fast development and build)
- [TailwindCSS 4](https://tailwindcss.com/) (for styling)
- [React Router v7](https://reactrouter.com/)
- [motion](https://motion.dev/) (for animations)
- ESLint (with React and hooks plugins)

## Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- npm (v9 or higher)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd QuickBlog/client
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Start the development server:**
   ```bash
   npm run dev
   ```
   The app will be available at [http://localhost:5173](http://localhost:5173) by default.

### Build for Production
```bash
npm run build
```
The production-ready files will be in the `dist/` folder.

### Preview Production Build
```bash
npm run preview
```

### Lint the Code
```bash
npm run lint
```

## Folder Structure

```
client/
├── public/           # Static assets (favicons, svg, etc.)
├── src/
│   ├── assets/       # Images and static JS data (blogs, comments, etc.)
│   ├── components/   # Reusable React components (Navbar, Footer, BlogCard, etc.)
│   ├── pages/        # Page components (Home, Blog)
│   ├── App.jsx       # Main app component with routes
│   ├── main.jsx      # React entry point
│   └── index.css     # TailwindCSS and global styles
├── index.html        # App entry HTML
├── package.json      # Project metadata and scripts
├── vite.config.js    # Vite configuration
└── ...
```

## Customization
- **Blog data**: Edit `src/assets/assets.js` to add, remove, or modify blog posts, categories, and comments.
- **Branding**: Replace images in `src/assets/` and update the logo as needed.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

## License

This project is for educational/demo purposes. Please contact the author for other uses.
