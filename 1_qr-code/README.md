# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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

Quick build of a vertically and horizontaly centered card containing an image (QR code), headline and text.

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/qr-code-challenge-with-raw-htmlcss-LMIW5A43Rq#comment-64066ae3d994ad821c701ec3](https://www.frontendmentor.io/solutions/qr-code-challenge-with-raw-htmlcss-LMIW5A43Rq#comment-64066ae3d994ad821c701ec3)
- Live Site URL: [https://falco-boehnke.github.io/frontend-mentor-challenges/1.%20QR%20Code/](https://falco-boehnke.github.io/frontend-mentor-challenges/1.%20QR%20Code/)

## My process
- Plan out html components
    - Realize you forgot some containers / wrappers
- Check starter code and assets
- Implement html items
- Think about CSS classes that might be needed
- Create and link css
    - Implement thought about css code
- Realize it doesn't work and start fiddling with it
- Find workaround solution and implement
- Submit to see progress over time and after feedback

### Built with

- Semantic HTML5 markup
- CSS 
- (Flexbox)
- CSS Grid

### What I learned

- Centering can be done using `text-align: center` on css containers, but it feels semantically wrong. After feedback implemented a **grid solution** instead. Also experimented with
**flex** but centering vertically would require limiting the height of the card while keeping `100dvh` as height for main container.

- Learned `alt` attribute should be always used on images for accessibility
    - Should use landmark html for same reason

- Learned that `vh` as height unit might cause issues if scrollbars or mobile spacings are an issue (address bar at the bottom), because `vh` does only take into consideration the actual viewport, not if other items are partially obscuring viewport height.

- Was reminded to relearn URL pathings, specifically absolute and relative:
 ```
    // RELATIVE
    '/images/xyz.jpg':  search at root of domain
    './images/xyz.jpg': search FROM current folder in images folder
    'images/xyz.jpg':   search FROM current folder in images folder, in that way identical to ./
    
    // ABSOLUTE
    'https://falco-boehnke.github.io/frontend-mentor-challenges/1.%20QR%20Code/images/image-qr-code.png': Absolute path
 ```

- Learned I am way worse at writing html and css than I thought, so far mostly used it to fix or adapt existing projects.

### Continued development

I want to find more ways to center a div, especially if they are behaving differently on mobile / desktop and have quirks.


### Useful resources

- [On Filepaths](https://www.w3schools.com/html/html_filepaths.asp) - Fresh up url path conventions
- [Kevin Powell for CSS learning](https://www.youtube.com/@KevinPowell) - Amazing channel for all issues CSS

## Author

- Website - [Falco Boehnke](https://falco-boehnke.github.io/frontend-mentor-challenges/)
- Frontend Mentor - [@Falco-Boehnke](https://www.frontendmentor.io/profile/Falco-Boehnke)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments
Thanks for helpful feedback to: 

- Atif Iqbal - https://www.frontendmentor.io/profile/atif-dev

