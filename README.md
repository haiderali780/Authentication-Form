# Dummy Login Form

This is a dummy login form built with React that demonstrates the use of local storage, the useReducer hook, the React Context API, side effects, forwardRef, useImperativeHandle, and the useEffect hook.

## Features
- **Local storage**: The login form saves the user's email and password to local storage when the user logs in, so that the user doesn't have to re-enter their credentials on subsequent visits to the site.
- `useReducer hook`: The login form uses the useReducer hook to manage the state of the email and password input fields. This allows for more complex state management without the need for Redux.
- **React Context API**: The login form uses the React Context API to pass data and functions down to child components without the need for props drilling.
- **Side effects**: The login form uses the useEffect hook to check the validity of the email and password inputs every 500ms. If both inputs are valid, the form becomes submitable. The useEffect hook is also used to clear the timeout when the component is unmounted.
- `forwardRef`: The login form uses the forwardRef function to pass a ref to a child component.
- `useImperativeHandler()`: The login form uses the useImperativeHandle hook to expose a child component's methods to the parent component.

## How to use
1. Clone the repository and navigate to the directory:
- **git clone https://github.com/haiderali780/dummy-login-form.git**
- **cd dummy-login-form**
2. Install the dependencies:
**npm install**
3. Start the development server:
**npm start**
4. The login form will be available at **http://localhost:3000**.

## License
This project is not licensed.
