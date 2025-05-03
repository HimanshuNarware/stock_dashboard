# Tailwind CSS Custom Configuration

This file contains custom Tailwind CSS configuration using the `@layer` directive for base styling, theming, and global variables.

## 🔧 Technologies Used

- **Tailwind CSS** – Utility-first CSS framework.
- **Custom Color Variables** – Defined for theming purposes (light and dark modes).

---

## ⚙️ Custom Layer Definitions

### `@layer base`

Defines base styles and CSS variables for the application:

#### Global CSS Variables

- `--background`: Sets the background color for light and dark modes.
- `--foreground`: Text color for light and dark modes.
- `--primary`, `--secondary`, `--accent`: Theme color definitions.
- `--destructive`: Used for destructive actions (e.g., delete buttons).
- `--sidebar-background`, `--sidebar-foreground`: Variables for sidebar colors.

#### Color Modes

- **Light Mode (`:root`)**: Default light mode settings.
- **Dark Mode (`.dark`)**: Overrides for dark mode when `.dark` class is applied to the root element.

---

### 🖋️ Global Styles

#### Reset Borders

```css
* {
  @apply border-border;
}
body {
  @apply bg-background text-foreground;
}
