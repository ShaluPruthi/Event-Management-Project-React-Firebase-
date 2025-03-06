# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Create Application using REACT + VITE
      npm create vite@latest

Enter into project  ~ cd my-project

Install npm(Node Package Manager)  ~ npm install
Run Application  ~ npm run dev

Also import some external packages from npm
  - This package serves as the entry point to the DOM and server renderers for React
        [npm i react-dom]
    
  - [npm i react-modal]
    
  - This package simply re-exports everything from react-router to smooth the upgrade path for v6 applications.
    Main component import from react-router is {useNavigate}
        [npm i react-router-dom]

    Router → Provides routing functionality.
    Routes → A wrapper component that holds all route definitions.
    Route → Defines individual paths and their corresponding components.

React Hooks ~
  - useState: Manages form input values and modal visibility. Manages state for event data and loading status.
  - useEffect: Fetches event data from Firebase when the component mounts.

To deal with realtime-database ~
  - FireBase realtime-database (https://console.firebase.google.com/u/0/project/event-30dec/database/event-30dec-default-rtdb/data).
  - "async await" is used to handle asynchronous operations like fetching data from an API using the "fetch" function.

    
