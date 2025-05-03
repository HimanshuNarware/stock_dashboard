# `useIsMobile` Hook

The `useIsMobile` hook is a custom React hook designed to detect if the user's device screen size is below a specified mobile breakpoint. It listens for window resizing events and provides a boolean value indicating whether the screen size is considered "mobile."

## Features

- **Mobile Detection**: Returns `true` if the window width is less than the defined mobile breakpoint (default is 768px).
- **Dynamic Resizing**: Listens for window resize events and updates the state accordingly.
- **Use of `matchMedia`**: Utilizes the `matchMedia` API to efficiently detect changes in screen size without the need for constant polling.

## Installation

This hook does not require any additional installation, as it relies on React's built-in APIs and `matchMedia`.

