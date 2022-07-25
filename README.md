<p align="center"> <img src="https://user-images.githubusercontent.com/104512014/180820701-a47074fc-f127-4152-8962-e82ac73a7b9f.png" width="400px"/> </p>

# Order Summary Card Component

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). 


## Objective

The challenge is to build out the order summary card component and get it looking as close to the design as possible.<br>Create both the desktop and mobile layouts.<br>Users should be able to see hover states for interactive elements.

### Links

- [Live Site Link](https://emmaclarem.github.io/order-summary-component-frontend-mentor/)
- [Solution Link](https://www.frontendmentor.io/solutions/solution-using-css-flexbox-and-custom-properties-I1JOQ77iAE)

<img width=600 src=./images/order-summary-component-mockup.png>

## My process

### What I built with

- Semantic HTML5 markup
- CSS custom properties
- CSS logical properties
- Flexbox
- Minimal reliance on media queries


### What I Learned

I used the semantic HTML button element for the first time:
```html
<button>Proceed to Payment</button>
```
I created CSS custom properties at the top of my file for the first time, giving me easy access to all my colours:
```css
:root {
    --very-pale-blue: hsl(225, 100%, 98%);
    --pale-blue: hsl(225, 100%, 94%);
    --desaturated-blue: hsl(224, 23%, 55%);
    --bright-blue: hsl(245, 75%, 52%);
    --dark-blue: hsl(223, 47%, 23%);
}
```
I've begun using min() to set widths, to minimize reliance on media queries and create more responsive layouts:
```css
.card {
    width: min(450px, 90%);
}
```

### Continued development

Some areas I'd like to continue to develop are:

1. Better use of semantic HTML elements, not relying on divs for all sectioning 
2. Continuing to minimize reliance on media queries, experiment with mobile-first development 
3. Ensuring to check browser compatibility before using newer CSS properties
4. Lower specificity of CSS, more reusable components

### Useful resources

- [Conquering Responsive Layouts course by Kevin Powell](https://courses.kevinpowell.co/conquering-responsive-layouts) - This course has helped me really understand how to create elegant responsive layouts with minimal fuss. I'd highly recommend this free course to anyone who may be struggling or just wants to refine their knowledge of creating responsive layouts. His [YouTube channel](https://www.youtube.com/kepowob) is also a great resource with loads of amazing CSS content.


## Author

- Website - [emmaclarm.github.io](https://emmaclarem.github.io/)
- Frontend Mentor - [@emmaclarem](https://www.frontendmentor.io/profile/emmaclarem)
- LinkedIn - [Emma Miller](https://www.linkedin.com/in/emma-c-miller/)

