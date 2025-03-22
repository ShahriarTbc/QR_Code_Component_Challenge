# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### Screenshot

-PC screenshot :
![](./PC_screenshot.png)


-Phone screenshot:

![](./Phone_screenshot.png)



### Links

- Solution URL: (https://shahriartbc.github.io/QR_Code_Component_Challenge/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


### What I learned

For me it was very dificult to choose the right properties in css to get the body and the .card to work and be seen as the style guide declared.

At the end, i believe i did a good job with the things that i used.
Always open to any comments


```css
body{
  background-color: var(--lightGray);
  font-family: "Outfit", sans-serif;
  font-optical-sizing: auto;
  font-weight: 400;
  font-style: normal;
  display: flex;
  justify-content: center;
  align-items: center;
}

.card{
  background-color: var(--WhiteColor);
  padding: 18px;
  border-radius: 15px;
  width: 320px;
}

.card-body{
  padding: 20px 15px ;
  text-align: center;
}
.card-body h4{
  color: var(--darkBlue);
  font-size: 22px;
}
.card-body p{
  color: var(--grayisBlue);
  font-size: 15px;
}

```

### Continued development

I would like to make my own QR Generator so this could be used as a default template.

The qr code could be links to a document or something along those ways. Going to think about something useful that could come in handy.

### Useful resources

- [FLEXBOX FROGGY](https://flexboxfroggy.com/#es) - This helped me to understand better how to use flexbox.


## Author

- Frontend Mentor - [@sharierahmed11](https://www.frontendmentor.io/profile/sharierahmed11)

