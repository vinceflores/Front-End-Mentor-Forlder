# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/Finished/desktop.png)
![](/Finished/active.png)

### Links

- Live Site URL: [Add live site URL here](https://splendorous-caramel-4b820f.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

In this simple project i focused on mobile first approach which made the process smoother. This is because it is easier to position contents in a small container than in a larger screen especially when positioning for larger screens only take a few lines after a mobie first approach. 

### The CSS Code
```css
@import url('https://fonts.googleapis.com/css2?family=Aboreto&family=Big+Shoulders+Display:wght@700&family=Fraunces:opsz,wght@9..144,700&family=Lexend+Deca&family=Montserrat:wght@500;700&display=swap');
:root{
     --Bright-orange: hsl(31, 77%, 52%);
    --Dark-cyan: hsl(184, 100%, 22%);
    --Very-dark-cyan: hsl(179, 100%, 13%);
    --Transparent-white: hsla(0, 0%, 100%, 0.75);
    --Very-light-gray: hsl(0, 0%, 95%);
}
*, *::before,*::after{
    margin: 0;
  
    
}

html, body{
    max-width: 100%;
    overflow-x: hidden;
    
   
}
.orange{
    background-color: var(--Bright-orange);
}
.white{
    background-color: var(--Transparent-white-);
}

.gray{
    background-color: var(--Very-light-gray);
}
.Cyan{
    background-color: var(--Dark-cyan);
}
.darkCyan{
    background-color: var(--Very-dark-cyan);
}
.otext{
    color: var(--Bright-orange);
}
.ctext{
    color: var(--Dark-cyan);
}
.dtext{
    color: var(--Very-dark-cyan);
}
.active{
    display: none;
}
.container{
    margin-top: 200px;
     position:absolute;
     display: flex;
     flex-direction: column;
     gap: 0;
     justify-content: center;
     width: 345px;
     height: auto;
     top: 50%;
     left: 50%;
     transform: translate(-50%,-50%);
 }
 .borLeft{
    border-radius: 10px 10px 0 0;
 }
 .borRight{
    border-radius: 0 0 10px 10px;
 }
 div{
    position: relative;
     display: flex;
     flex-direction: column;
     justify-content: flex-start;
     height: 400px;
     align-items: flex-start;
     margin-bottom: 0;
 }
 .image{
    scale: 0.7;
    margin: 1.5rem 2rem 0 2rem;
 }
 h1{
    font-size: 48px;
    color: var(--Very-light-gray);
    font-family: 'Big Shoulders Display', cursive;
    font-weight: 700;
 }
 p{
    font-size: 15px;
    line-height: 1.5;
    color: var(--Transparent-white);
    font-family: 'Lexend Deca', sans-serif;
    width: 250px;
    font-weight: 400;
 }
 .marg{
    margin: 1rem 2rem 1rem 3rem;
 }
 button{
    height: 35px;
    width: 100px;
    margin: 1.5rem 2rem 1rem 3rem;
    background-color: var(--Very-light-gray);
    border-style: none;
    border-radius: 15px;
    border: 2px solid var(--Very-light-gray);
    cursor: pointer;
 }
 button:hover{
    background-color: transparent;
    color: var(--Very-light-gray);
 }
 @media (min-width: 900px){
    .container{
        margin-top: 0;
         position:absolute;
         display: flex;
         flex-direction: row;
         gap: 0;
         justify-content: center;
         width: 800px;
         height: auto;
    }
    h1{
        font-size: 56px;
        color: var(--Very-light-gray);
        font-family: 'Big Shoulders Display', cursive;
        font-weight: 700;
     }
    div{
        width: 32%;
        align-items: flex-start;
        padding-right: 1rem;

    }
    p{
        margin-right: 0;
        
    }
    .image{
        scale: 0.7;
        margin: 1.5rem 2rem 0 1rem;
     }
     .marg{
        margin: 1rem 2rem 1rem 1rem;
     }
     button{
        margin: 1.5rem 2rem 1rem 1rem;
     }
     .borLeft{
        border-radius: 10px 0 0 10px;
     }
     .borRight{
        border-radius: 0 10px 10px 0;
     }
}
```



### Continued development
I deefiinitely want to focus more on building modals and working with animations/ 
**Note: Delete this note and the content within this section and replace with your own plans for continued development.**


## Author

- Github - [@inceflores](https://github.com/vinceflores)
- Frontend Mentor - [@vinceflores](https://www.frontendmentor.io/profile/vinceflores)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

 
**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
