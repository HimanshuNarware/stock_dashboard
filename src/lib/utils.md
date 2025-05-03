# 🔧 `cn` Utility Function

Combines and merges class names using `clsx` and `tailwind-merge`.

---

## 📄 Purpose

This function simplifies the conditional application of Tailwind CSS class names, ensuring that class conflicts (e.g., `p-2` vs `p-4`) are resolved correctly.

---

## 📦 Imports

```ts
import { clsx, type ClassValue } from "clsx";
import { twMerge } from "tailwind-merge";
