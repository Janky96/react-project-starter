# React Project Starter
React is a library that needs many other dependencies to function well, this README focuses on helping me and you to build the perfect project suitable for your needs

## Initialize and Must haves
Build the React project using Vite, use TypeScript preferrably, so you will be type-safe
[Typescript cheatsheet](https://react-typescript-cheatsheet.netlify.app/)

```Bash
npm create vite@latest
```

Every dependency we will see we will find it here
[npm js link]([/guides/content/editing-an-existing-page](https://www.npmjs.com/))

#### Routing
Obviously we will need pages and routing in our react project, so we need react-router-dom
react-router-dom
[react-router-dom docs](https://reactrouter.com/home)

```Bash
npm i react-router-dom
```

### Absolute imports
Using absolute imports instead of relative ones is really important for a clean project, to use absolute imports follow this guide
[Absolute imports Medium Guide](https://medium.com/@johnbernalfsd/how-to-add-absolute-imports-to-vite-4-with-typescript-5-5d789bc7d791)


### Store management
Instead of prop drilling, we need a store management library, yes, we can use Context, but it can be bothersome sometimes. I really like using Zustand instead of redux or other libraries, it's straightforward and light

[Zustand documentation](https://github.com/pmndrs/zustand)

```Bash
npm i zustand
```


### Calling APIs
There are two good libraries that can help us when we call APIs, axios and tanstack-query
Axios will help us to make calls easier, tanstack-query is good so we can manage the data that we fetched easily (we can know if it's still loading, if it needs to be refetched, etc.)

[Axios documentation](https://axios-http.com/docs/example)
[useQuery documentation](https://tanstack.com/query/latest/docs/framework/react/guides/dependent-queries#usequery-dependent-query)

```Bash
npm i axios
npm i @tanstack/query-core
```

## Structuring the project
Unfortunately is easy to make a mess with a React project, so it's important to have a good folder structure, usually I follow this pattern
[Bulletproof react project structure](https://github.com/alan2207/bulletproof-react/blob/master/docs/project-structure.md)


## Design
For our project we can use plain css, css modules, component libraries, tailwind

### Plain css
If you intend to use plain css, I reccomend to at least use css modules, so you will have the scope of the file just to your desired component
[CSS Modules docs](https://create-react-app.dev/docs/adding-a-css-modules-stylesheet/)


### Component libraries
Profesionally in Italy as a component library I have used just MUI, I don't like it that much, but it surely is widely used, so it's worth learning
[MUI docs](https://mui.com/material-ui/getting-started/)



### Tailwind
This is the good compromise of old css and new way of doing it

[Tailwind docs](https://tailwindcss.com/docs/configuration)


If you have used Vite to initialize the project follow this

[Initialization Tailwind with Vite React](https://tailwindcss.com/docs/guides/vite)


### Icons, fonts, colors and images
Good Google fonts are Lato, Roboto, Montserrat, Open Sans


For icons I tend to prefer Phosphor
[Phosphor docs](https://phosphoricons.com/)


When I am searching for a color I go here
[Open Color](https://yeun.github.io/open-color/)
