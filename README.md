# PostKeeper App

The app is powered by a custom context called PostContext, encapsulated within the postContext.js file. This context provides functionality for adding and resetting saved posts, maintaining consistency with the given output behavior. A custom hook is also implemented to simplify access to the context across various components, minimizing redundancy by eliminating the need to repeatedly import and use the context directly.

## Key Features:

- **Save and Manage Posts**: Users can easily save their preferred images with one click and view all saved images using the "Saved Posts" button.
- **Reset Functionality**: A reset button is provided to allow users to unsave all images instantly.
- **Custom Context Provider**: A custom context provider manages saved posts, providing a clean and centralized approach to app state management.
- **Custom Hook**: The hook is used to extract the context value, making the components more readable and easier to maintain.

This project showcases the effective use of React Context API and hooks for efficient state management in a gallery-based application.
