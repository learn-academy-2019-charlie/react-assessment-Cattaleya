# React Assessments

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Here is a list of pros and cons to using the React library to build your application -- but some of them are false. Remove the false statements from the list:


- React is a modern, efficient answer to complex UI applications
- React is a flexible library that plays the role of V in an MVC framework

 
 #### 2. What are "smart"(logic) and "dumb"(display) components? Explain the difference and also add why we bother to make the distinction between them.
 
 
 //Your Answer component with a state is a smart component, a component without a state is a dumb component
 
 
 //Googled Answer smart and dumb components are used to It to build many small parts, and then join them together to form entire applications. 
 
 
#### 3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?
 
 
 //Your Answer installing a global: when we want to run specific programming langueges such as react 
 
 
 //Googled Answer
 
 Smart component on the other hands keep track of state and concern with how things work. Container component still receives data or function via props and can pass it to another smart component or dumb component as props. Container component pattern is class-based components and have constructor() functions
 
 dumb component: This component is often just Javascript functions and only has a render() method. It also does not have any state or lifecycle hooks. However, it still can receive some data and function from the parents via props. const header = (props) => {
 yarn install is used to install all dependencies for a project. ... These have been replaced by yarn add and yarn add --dev . For more information, see the yarn add documentation.
 
 
#### 5. There are three mistakes in this code that would cause it to break our application. Find the mistakes and fix them:

    import React, { Component } from 'react';

    class extends RecipesComponent {
      constructor(props){
        super(props)
        this.state = {
          recipes=[],
            name1: 'Meatballs',
            name2: 'Mac & Cheese'
      
        }
      }

      render() {
          let recipes = this.state.recipes.map(function(recipe){
          
            return(
              <li key={recipe.name}>{recipe.name}</li>
          })
           return(
            <ul>
            {recipes}
          </ul>
          })

    export default Recipes;

#### 6. Name three html input types. (NOTE: text is the default type - so it doesn't count in this case)
 
 //Your Answer
 <input type='sumit'>
 
 //Googled Answer
 
 <input type='button'>
 <input type='color'>
 <input type='date'>
 
 
 #### 7. How would you explain state to a friend who doesn't know code?
 
 
 //Your Answer
 state is the function that is run by acomponent 
 
 //Googled Answer
 
 React states are objects that are managed within a component. We can use the state object to represent instances of our visual displays.
 
 #### 8. What is the difference between component state and props? Your answer should include a short explanation of both.
 
 
 //Your Answer
 state is the parent component that just reference the props. 
 
 
 //Googled Answer
 
 What's the difference between state and props in React? In a React component, props are variables passed to it by its parent component. State on the other hand is still variables, but directly initialized and managed by the component. ... Of course a component can also initialize the state without looking at props.
 
   
#### 9. Write a paragraph or so about your experience with building tic-tac-toe. Some topics to start with might be: things you learned about yourself, concepts from React that stood out to you, something about pair programming (if you paired), or the experience of building something in code from scratch.
Based on my experience I did enjoy working with the people in my group due the fact we were all on the same level of knowledge. I got the opportunity to be part of the project as the driver rather than just watching. It was interesting seeing the similarities between myself and my classmates in the sense where our strugglers were. 