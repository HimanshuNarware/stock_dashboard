# 🧭 NotFound Component

The `NotFound.tsx` component is a **404 Error Page** for handling invalid or non-existent routes in your React application using React Router.

---

## 📁 File: `NotFound.tsx`

### ✅ Purpose

This component gracefully handles undefined routes by displaying a user-friendly **"404 - Page Not Found"** message and provides a link to navigate back to the homepage.

---

## ⚙️ Functionality

- Uses `useLocation` from `react-router-dom` to capture the current route.
- Logs a descriptive error message to the console when an invalid path is accessed.
- Displays a styled message and a redirect link to the homepage (`/`).

---

## 💡 Key Features

| Feature             | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| 🎯 `useLocation()`   | Tracks the route that triggered the 404.                                   |
| 🛠️ `useEffect()`     | Logs the invalid route access in the console.                              |
| 🎨 Tailwind Styling | Provides a centered, responsive, clean UI for the error message.            |
| 🔗 Home Link        | Gives the user an easy way to return to the homepage.                       |

---

## 🧱 UI Structure

```jsx
<div className="min-h-screen flex items-center justify-center bg-gray-100">
  <div className="text-center">
    <h1 className="text-4xl font-bold mb-4">404</h1>
    <p className="text-xl text-gray-600 mb-4">Oops! Page not found</p>
    <a href="/" className="text-blue-500 hover:text-blue-700 underline">
      Return to Home
    </a>
  </div>
</div>
