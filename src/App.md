# 🚀 App Component

This is the main entry point of the React application. It sets up global providers, routing, and toast notifications.

---

## 🔧 Technologies Used

- **React Router** (`react-router-dom`) – Handles client-side routing.
- **React Query** (`@tanstack/react-query`) – Manages data fetching and caching.
- **Toaster & Sonner** – UI toast notifications.
- **TooltipProvider** – Enables tooltip support globally.

---

## 🌐 Component Hierarchy

<App> ├─ QueryClientProvider │ └─ TooltipProvider │ ├─ Toaster (UI toast messages) │ ├─ Sonner (Enhanced toast experience) │ └─ BrowserRouter │ └─ Routes │ ├─ "/" → <Index /> │ └─ "*" → <NotFound /> ``