## Assignment Instuctions
Please answer the following questions through your research. A recommendation would be to review
YouTube or other material online for walk-throughs of fundamentals.
>  Reiterating: I’m not looking for a comprehensive overview but more of a “here is what you need to know to deliver minimum functionality with this component”
>  We will determine how to style this formally based on the outcome of our GIT projects. That said – minimalistic and clear is ideal: Simple headers, paragraphs, and images will suffice, along with some basic layout work (margin, padding, etc).


 --- things in [[brackets]] should be expanded on further ---
1. What is your component?
    - a library for building user interfaces through components
3. What is its purpose?
    - creating reusable components to give developers more flexibility and make more robust interfaces
5. Why is it important?
    -  
7. How does it integrate into the MERN Stack?
React provides the front end framework within the mern stack
    - What are the steps to integrate it?
    - What are its dependencies?
         - 
    - Are there any considerations for configuration? If so, what are the most common and how
        are the done?
9. Common Functionality
    - Purpose
    - Description
    - Example
## Key Points
- Introduction to React and its importance in the MERN stack.
    - 
- Setting up a React project (create-react-app).
    - install node js <link>
    - in terminal navigate to directory and run ` npx create-react-app [app-name] `
    - if you get a 404 error, run `npm uninstall -g create-react-app` and rerun ` npx create-react-app [app-name] ` to make sure the newest version is installed correctly
    - it will prompt to install necessary packages - enter `y` and it will install them and create the app, this might take a few minutes
    - run `cd [app-name]` to navigate to the app's directory
    - run `npm start` to open your web app on a local server
    - the page is populated with default files that will can edit to create your app
    - if you want to create an empty app, without all the files create-react-app installs, you can create your folder and populate the files yourself
        - [[ file organization and neccessary files ]]
        -  w node + npm installed, run `npm start`
- Dependencies
    - packages that are used in the react project
    - listed in the packages-lock.json file
    - [[ how to intall and use ]]
    - [[ example ]]
- Components
    - components are independent reusable bits of code that return HTML.
    - class components extend React. Components to give it access to React.Components functions while function components are similar, but use less code and can't access React.Components functions 
```
//class component

class Car extends React.Component {
  render() {
    return <h2>Hi, I am a Car!</h2>;
  }
}
//function component ofd the same code

function Car() {
  return <h2>Hi, I am a Car!</h2>;
}

```
- Props
	- - props are the arguments passed in to react components, or properties. The function like JS arguments and HTML attributes
```
function Car(props) { 
  return <h2>I am a { props.brand }</h2>; 
}

const myElement = <Car brand="Ford" />; //calls Car fucntion and set brand value to Ford
//will return "I am a Ford"
```
- State Management
	-
- Hooks and lifecycle methods.
     - 
- Routing with React Router.
- State management with Context API or Redux.
- Best practices for React development.
