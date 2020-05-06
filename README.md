# React

A list of commands to create a React web application.

## Initial setup

Use the following command to setup a prebuilt single page app. A preconfigured web package will be included.

```
npx create-react-app my-app
```

## Server-side-rendering

**[Next.js](https://nextjs.org/)** is a popular and lightweight framework for static and server‑rendered applications built with React. It includes styling and routing solutions out of the box, and assumes that you’re using **Node.js** as the server environment. An intuitive page-based routing system (with support for dynamic routes).


## Testing

Use **[Enzyme](https://enzymejs.github.io/enzyme/docs/api/)** to test Components' outputs and can manipulate, traverse and simulate runtime.

```
npm install --save-dev enzyme enzyme-adapter-react-16
```

## Managing state

Use **[Redux](https://react-redux.js.org/)** to manage the Components' state

```
npm install react-redux
````

Link to a good blog on why to use **[Redux](https://blog.logrocket.com/when-and-when-not-to-use-redux-41807f29a7fb/)**

Can use **Redux Saga** as well.

## Styling

**[Radium](https://formidable.com/open-source/radium/)** is a set of tools to manage inline styles on React elements. It gives you powerful styling capabilities without CSS
```
npm install --save radium
```
**[React Motion](https://github.com/chenglou/react-motion)** used for animating Components 

```
npm install --save react-motion
```
