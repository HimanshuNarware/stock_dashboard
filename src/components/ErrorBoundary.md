# ErrorBoundary Overview
The ErrorBoundary component catches JavaScript errors anywhere in its child component tree and logs those errors. It also displays a fallback UI instead of crashing the component tree.

## Features
- Catches Errors: Automatically catches any JavaScript errors in the component tree.

- Fallback UI: You can provide a fallback UI via the fallback prop or use a default fallback UI.

- Error Reset: Includes a "Try Again" button that allows users to reset the error state and try again.

- Logging: Logs errors to the console with componentDidCatch