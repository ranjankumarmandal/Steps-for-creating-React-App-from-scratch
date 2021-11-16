# Steps for creating React App from scratch

1. Setup React: npx create-react-app 
2. Install Dependencies: npm i axios react-router-dom@5.0.0 react-transition-group
3. Clean up - remove anwanted files and cleanup for unwanted lines in any files
4. Create 'Navbar.js' component and add this to 'App.js' main component
5. Setup React Router - add (BrowserRouter, Switch, Route components imported from react-router-dom to 'App.js' component)
6. Create 'Home.js' & 'About.js' components, add them to Route in 'App.js' main component and Link them in 'Navbar.js' component
7. Create react Context, Global State (ex - contactContext.js, ContactState.js, contactReducer.js)
8. Add <ContactState> component to 'App.js' main component
9. Now create Components as per requirement, useContext(contactContext) react-hook and call the related global state variables, methods to pass any values and to make any effect in application through this component
10. Now add this component to 'Home.js' component. and follow the same step for so on.
