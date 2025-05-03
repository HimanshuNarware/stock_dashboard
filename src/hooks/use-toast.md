# `useToast` Hook Documentation

The `useToast` hook provides a customizable toast notification system for your React application. It allows you to add, update, dismiss, and remove toast notifications with ease.

## Features

- **Toast Management**: Adds, updates, dismisses, and removes toast notifications.
- **Toast Limit**: Controls the maximum number of toasts displayed at once (default: 1).
- **Automatic Dismissal**: Toasts automatically dismiss after a set delay.
- **Custom Actions**: Supports custom action buttons in each toast.
- **Global State Management**: Uses a reducer and state management to manage toast notifications globally across the app.

## Constants

- **`TOAST_LIMIT`**: The maximum number of toasts displayed at once. Default is `1`.
- **`TOAST_REMOVE_DELAY`**: Delay in milliseconds before a toast is removed. Default is `1000000`.

## Types

- **`ToasterToast`**: Represents a toast notification object with properties such as `id`, `title`, `description`, and `action`.
- **`State`**: Represents the state of all active toasts.
- **`Action`**: Defines the possible actions for managing toasts (e.g., `ADD_TOAST`, `UPDATE_TOAST`, `DISMISS_TOAST`, `REMOVE_TOAST`).

## Action Types

The following action types are supported:

- **`ADD_TOAST`**: Adds a new toast notification.
- **`UPDATE_TOAST`**: Updates an existing toast notification.
- **`DISMISS_TOAST`**: Dismisses a toast (can specify a `toastId`).
- **`REMOVE_TOAST`**: Removes a toast from the state entirely (can specify a `toastId`).

## Reducer

The `reducer` function manages the state updates for toast notifications. It handles the following actions:

1. **`ADD_TOAST`**: Adds a new toast to the state, ensuring the total number of toasts does not exceed the `TOAST_LIMIT`.
2. **`UPDATE_TOAST`**: Updates the properties of an existing toast.
3. **`DISMISS_TOAST`**: Dismisses a toast (or all toasts) and triggers the removal process.
4. **`REMOVE_TOAST`**: Permanently removes a toast from the state.
