# Frontend Mentor - GitHub user search app solution

This is a solution to the [GitHub user search app challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/github-user-search-app-Q09YOgaH6). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Search for GitHub users using GitHub API
- Switch between light and dark themes
- **Bonus**: Have the correct color scheme chosen for them based on their computer preferences. _Hint_: Research `prefers-color-scheme` in CSS.

### Links

- Solution URL: [Solution](https://github.com/fabioAlcocer/git-hub-API)
- Live Site URL: [Live](https://api-github-search.netlify.app/)

## My process

### Built with

- HTML5 markup
- SCSS
- Mobile-first workflow
- ES8 JS

### What I learned

Some new things I learned in this project was how to have the correct color scheme chosen based on the users computer preferences.I also learned how to change the color of placeholder text in firefox and I learned how to reformat a date.

See code snippets below:

```css
@media (prefers-color-scheme: dark) {
}
```
### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl/DateTimeFormat) - Here you can find the appropriate syntax for formatting a date to the correct style based on country, i.e 'en-GB'
- [Stack overflow](https://stackoverflow.com/questions/56300132/how-to-override-css-prefers-color-scheme-setting) - This is a good thread on how to override css prefers-color-scheme setting. What I have taken from this is how write a condition based on the computers color preferences using window.matchmedia.

## Author

- GitHub - [@alcocerSejas](https://github.com/fabioAlcocer/)
