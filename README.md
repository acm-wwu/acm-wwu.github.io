# acm-wwu.github.io

Club website for the WWU branch of ACM. Last updated: 6.6.2020

### Gallery

The gallery is a clown fiesta dumpster fire and if anyone wants to change it so that it's not ass in the future, please be my guest. Currently, all thumbnails are thrown into a CSS grid. We use a jank library called lightgallery for responsive lightboxes (since mobile first design thinking is important but I'm also really really lazy and don't want to do it myself). 

The thumbnails are forced into 350x350 squares through CSS, which squashes most of them, and although their github page says it supports any type of markdown, lightgallery will flip the fuck out if you try to throw stuff in a div to make proper thumbnails. 

##### Adding a new image

Throw your image into the gallery folder in the directory. Copy paste existing code starting from the <a> tag in the gallery-grid div and change the file name so that it matches your image. Your thumbnail mileage may vary but at least it's not too hard.

It's also good practice to set image alt text for the visually impaired/those using screen readers. WAI-ARIA attributes would be sick if you're a filthy tryhard, but at the very least set some alt text.

Again, if anyone in the future would like to find a better library, be my guest. 

### Designers

Any future additions or ammendments to the website should probably adhere to [WWU's branding style guide](https://designsystem.wwu.edu/). Feel free to break this if you know what you're doing, but the general idea is that the website should feel like it's a part of western's domain since we're a WWU club. 

### Developers

haha good luck sifting through my spaghetti code you unlucky fuckers!!! im sorry!!!

##### External Libraries/Frameworks/Resources Used for Reference
- jQuery
- Animate On Scroll (AoS)
- GSAP
- lightgallery
- Font Awesome
- Bootstrap (I don't think it's ever used though - I should probably take this out at some point)





