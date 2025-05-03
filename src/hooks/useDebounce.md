# `useDebouncedCallback` Hook Documentation

The `useDebouncedCallback` hook provides a debounced version of a callback function. It delays the execution of the callback until after a specified delay time has passed since the last time the debounced function was called. This is useful for limiting the frequency of expensive operations, such as API calls, user input handling, etc.

## Features

- **Debouncing**: Prevents a callback from being called too frequently by delaying its execution until after a specified delay.
- **Customizable Delay**: You can specify the delay time (in milliseconds) between successive calls.
- **Optimized for performance**: Uses `useRef` and `useCallback` to ensure minimal re-renders.

## Usage

### Parameters

- **`callback`**: The function to debounce. It will be called after the specified delay when there are no further calls within that time.
- **`delay`**: The delay time in milliseconds, which determines how long to wait after the last call before executing the callback.

### Return Value

The hook returns a debounced version of the `callback` function. You can call this debounced function in your component just like the original `callback` function.

