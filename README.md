## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![image](https://user-images.githubusercontent.com/44249712/129511263-f246cff5-816a-4806-ba81-5256f9a04858.png)

### Links

- Live Site URL: https://modest-beaver-9fe663.netlify.app/

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### Challenges faced
1. How to overlap a background color on top of image
2. Unless you're setting the whole background, use img tag
3. Feel like I'm misusing height/width/max-width/max-height

### Lessons learned
1. Way I did it was to wrap the image in a div then use a pseudo element for the div and set the background color with z-index >= 1.
2. mix-blend-mode: multiply will blend the elements background with the content of parent. Had to set opacity though.
