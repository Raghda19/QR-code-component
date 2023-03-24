# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)



### Screenshot

![](C:\Users\HP\Desktop\Challenging Project\qr-code-component-main\challange1.html\screenshoot)




### Links

- Solution URL: C:\Users\HP\Desktop\Challenging Project\qr-code-component-main\challange1.html\QR-code.html
- Live Site URL:  https://raghda19.github.io/QR-code-component/



### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I thought by specifying the (min & max) width in ( the body inside the css file ) the default will not going to change for each size, BUT when i change the dimension to iPhone SE {that have 375 width (which is reqired as the min-width) for this project} the margin and the width of the content change as will -----it was a stuck point for me until thank godness , i remember that there is a css At-rules [@media] features that alow us to specify a specific part in the style sheet according to what we want.

So i added this code , see below:


```css
@media (min-width:375px) {
    body {
        display: flex;
        place-items: center;
        margin: 333.5px 10px 333.5px 0  ;
    }
    div {
        max-width: 300px;
    }
}
```



### Continued development
I neet to focus on those two areas:
-Display property.
-The CSS Functions (xp, rem, em, hv...etc)




## Author

- Website - [Raghda Mohamed](https://raghda19.github.io/QR-code-component/)
- Frontend Mentor - [@Raghda19](https://www.frontendmentor.io/profile/Raghda19)





