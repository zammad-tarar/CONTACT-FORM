# Frontend Mentor - Contact Form Solution

This is my solution to the [Contact Form Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/contact-form--G-hYlqKJj). Frontend Mentor challenges help developers improve their coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview

### The Challenge

Users should be able to:

- Complete the form and see a success message upon successful submission.
- Receive form validation messages if:
  - A required field has been missed.
  - The email address is not formatted correctly.
- Complete the form using only their keyboard.
- Have inputs, error messages, and the success message announced on their screen reader.
- View the optimal layout for the interface depending on their device's screen size.
- See hover and focus states for all interactive elements on the page.

### Screenshot

![Screenshot of the project](./screenshot.jpg)

_Add a screenshot of your solution here._

### Links

- [Solution URL](#) - Add solution URL here.
- [Live Site URL](#) - Add live site URL here.

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- JavaScript for form validation

### What I Learned

This project helped me reinforce my knowledge of:

- Building accessible forms.
- Using semantic HTML for better user experience.
- Implementing client-side form validation with JavaScript.
- Creating responsive layouts using CSS Grid and Flexbox.

Here’s a snippet of my form validation code:

```js
const form = document.getElementById('contact-form');
form.addEventListener('submit', (e) => {
  e.preventDefault();
  // Validate form inputs
});
```

### Continued Development

I plan to:

- Improve the form’s accessibility by ensuring it works seamlessly with screen readers.
- Implement server-side validation for enhanced security.
- Experiment with different form UI enhancements.

### Useful Resources

- [MDN Web Docs - Form Validation](https://developer.mozilla.org/en-US/docs/Learn/Forms/Form_validation)
- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [A11Y Project - Form Accessibility](https://www.a11yproject.com/posts/how-to-improve-your-form-accessibility/)

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://twitter.com/yourusername)

---

I hope you like my solution! Feel free to reach out for feedback or collaboration. 😊


