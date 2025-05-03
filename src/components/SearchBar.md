# SearchBar Component

The `SearchBar` component is a functional React component that provides a search input field with debounced input handling. It's designed to search for stocks and improve user experience by reducing the number of re-renders and API calls through debouncing.

## Features

- **Debounced Search**: Utilizes a custom `useDebouncedCallback` hook to delay the execution of the search function by 300 milliseconds after the user stops typing.
- **Controlled Input**: Uses React’s `useState` hook to control the input value, ensuring that the component behaves predictably.
- **Focus on Mount**: The input is automatically focused on mount, enhancing the user experience.
- **Submit Handler**: Handles form submission with an optional custom `onSearch` function to trigger the search when the user presses "Enter" or clicks the submit button.
- **Customizable**: Accepts a `placeholder` prop to change the input field's placeholder text.

## Installation

Ensure you have the necessary dependencies installed for this component:

```bash
npm install lucide-react
