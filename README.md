# Coded by
- Kenneth Espaldon

# Built With
- HTML
- CSS
- Flexbox

# What I've Learned
- Making the 'container' class a flexbox won't work on the elements (Order summary heading, the info, annual plan section, and the buttons) if I wrap a div around them when they're already nested inside of the main element. This is because the main element would refer to the div instead of the elements inside of it which is what I actually want to refer to. Recall that the 'main' element is basically a div but with more meaning.
- I have to specifically set the font family for the button because the button ignores the font family I set to the body. After some googling, I've learned that form elements don't inherit font settings.
- Setting the background size for the 'illustration-hero' class to contain will make the overflow property work incorrectly. If the background size is set to contain then the top part of the background will ignore the overflow property and leave a somewhat pointed corner.
- Set the min-width value of the container to the width value of the container to make sure that the container doesn't get smaller than its width value.
- Setting the background size property to 100% for the 'illustration hero' background means increasing the image width to 100% and maintaining the image ratio. The height also increase as a result. background-size: 100%; is equivalent to background-size: 100% auto;.
- I set the max-width for the mobile version to 550px to avoid the desktop version from being altered by flexbox. 
- I learned that you can use 'vw' and 'vh' to set the background size.