# 🐣 Node Express/MongoDB + React/Redux App
A basic clone of Twitter using - Node, Express, MongoDB, React and Redux using **create-react-app** with separate **API** `(express+mongo)` and **Frontend** `(react+redux)` folders. Uses Google's Material Design UI (`material-ui` package).

## 📝 Features
- [x] List all tweets
- [x] View single tweet
- [x] Post a tweet
- [x] Login / Register
- [x] Enable [CORS](https://enable-cors.org/index.html)
- [x] Progressive Web App features (Offline first, Service worker, Application shell)

## ▶️ Running
- Install NPM modules for **api** `cd api` and `npm install`
- Install NPM modules for **frontend** `cd frontend` and `npm install`
- Run **api** server `cd api` and `npm start` (runs on port configured under `api/src/config/index.js`)
- Run **frontend** server `cd frontend` and `npm start` (runs on port 3000 or your `PORT` environment, should automatically open in your browser)

## 📦 Packages Used

### API
- **bcrypt** (Library to help you hash passwords)
- **body-parser** (Parse incoming request bodies)
- **cookie-parser** (Parse Cookie header)
- **express** (Fast, unopinionated, minimalist web framework)
- **jsonwebtoken** (JSON Web Token implementation)
- lodash (Modular utilities)
- moment (Parse, validate, manipulate, and display dates)
- **mongoose** (MongoDB object modeling tool)

### Frontend
- classnames (A simple utility for conditionally joining classNames together)
- **immutability-helper** (Mutate a copy of data without changing the original source)
- **material-ui** (React Components that Implement Google's Material Design)
- moment (Parse, validate, manipulate, and display dates)
- **react** (Library for building user interfaces)
- **react-addons-css-transition-group** (React CSSTransitionGroup add-on)
- **react-dom** (React package for working with the DOM)
- **react-redux** (Official React bindings for Redux)
- **react-router-dom** (v4, A complete routing library for React)
- **react-tap-event-plugin** (Facebook's TapEventPlugin)
- **redux** (Predictable state container for JavaScript apps)
- redux-devtools-extension (Redux DevTools extension)
- **redux-thunk** (Thunk middleware for Redux)


## 🏗 Core Structure
    app
      ├── api (api.example.com)
      │   ├── src
      │   │   ├── config
      │   │   ├── models
      │   │   ├── routes
      │   │   ├── server.js
      │   │   └── index.js
      │   │
      │   └── package.json
      │
      ├── frontend (example.com)
      │   ├── public
      │   ├── src
      │   │   ├── actions
      │   │   ├── components
      │   │   ├── reducers
      │   │   ├── app.js
      │   │   └── index.js
      │   │
      │   └── package.json
      │
      ├── .gitignore
      └── README.md

## ⭐️ Resources
- [What is React.js and Why I recommend it to other JavaScript Developers?](https://www.linkedin.com/pulse/what-reactjs-why-i-recommend-other-javascript-sandip-das) (LinkedIn post)
- [Container Components](https://medium.com/@learnreact/container-components-c0e67432e005) (Medium article)
- [Thinking in Redux (when all you’ve known is MVC)](https://hackernoon.com/thinking-in-redux-when-all-youve-known-is-mvc-c78a74d35133) (Medium article)
- [CRUD with Redux](https://www.youtube.com/playlist?list=PLuNEz8XtB51KfnHc99GwscPy1UbLJyXHW) (Youtube playlist)
- [React Router v4](https://www.youtube.com/watch?v=UVQ0ATR0vpI&list=PLkuiMQfg5DujODRnZGKokmwHZrBqqUCr1&index=14) (Youtube video)
- [React Component Patterns by Michael ](https://www.youtube.com/watch?v=YaZg8wg39QQ&list=PLkuiMQfg5DujODRnZGKokmwHZrBqqUCr1&index=13) (Youtube video)
- [Universal JavaScript Web Applications with React - Luciano Mammino](https://www.youtube.com/watch?v=0VEwRFP8WtI&list=PLkuiMQfg5DujODRnZGKokmwHZrBqqUCr1&index=15&t=9s) (Advance topic, Youtube video)
- [Break Down Isomorphic and Universal Boilerplate: React-Redux server rendering](https://hackernoon.com/isomorphic-universal-boilerplate-react-redux-server-rendering-tutorial-example-webpack-compenent-6e22106ae285) (Advance topic, Medium article)
- [Collection of bunch of interesting React videos and related topic](https://www.youtube.com/playlist?list=PLkuiMQfg5DujODRnZGKokmwHZrBqqUCr1) (Youtube playlist)

