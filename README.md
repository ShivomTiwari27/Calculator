# Calculator Web App

A simple and responsive calculator web application built using HTML, CSS, and JavaScript.

## Overview

This project demonstrates the creation of a basic calculator that performs simple arithmetic operations. The design is sleek and responsive, making it suitable for both desktop and mobile devices.

## ScreenShots
![Calculator-3](https://github.com/user-attachments/assets/8f823ae7-a45a-4194-9161-69a6511b615f)
![Calculator-2](https://github.com/user-attachments/assets/e6c50e0b-357b-470a-93df-8a735b29500b)
![Calculator-1](https://github.com/user-attachments/assets/9c4f8f54-a71b-4ca8-8de6-e245502bd8b2)


## Links
- Live Site Url: [Live Site](https://shivomtiwari27.github.io/Calculator/)
- Sorce Code : [Source Code](https://github.com/ShivomTiwari27/Calculator)

## Features

- **Arithmetic Operations**: Supports addition, subtraction, multiplication, and division.
- **Responsive Design**: The calculator adjusts to different screen sizes for optimal usability.
- **Error Handling**: Displays an error message for invalid inputs and clears the display after a short delay.

## What I Learned

In this project, I gained experience with:

- **HTML & CSS**: Structuring and styling the calculator layout to be visually appealing and user-friendly.
- **JavaScript**: Implementing functionality for basic arithmetic operations and handling user input effectively.
- **Error Handling**: Ensuring the calculator gracefully handles errors and provides feedback to the user.
- **Responsive Design**: Applying CSS techniques to create a responsive user interface that works on various devices.

### Code Snippet: Arithmetic Operation Handling

```javascript
function calculate(){
  try{
    display.value = eval(display.value);
  }
  catch(error){
    display.value = "Error";
    setTimeout(()=> display.value = "", 2000);
  }
}
```

This code snippet demonstrates how the calculator processes arithmetic operations and handles errors. The eval function is used to evaluate the expression entered by the user, and in case of an invalid expression, an error message is displayed for 2 seconds before clearing the display.

## Continued Development

Further enhancements for this calculator project could include:

- **Advanced Functionality**: Expanding the calculator to handle scientific functions like trigonometry, logarithms, and exponentiation.
- **History Tracking**: Adding a feature to record and display a history of previous calculations.
- **Dark Mode**: Implementing a dark mode for improved usability in different lighting conditions.
- **Animations**: Incorporating animations for button presses and screen transitions to improve user experience.

## Useful Resources

Here are some resources that were instrumental in developing this project:

- **[MDN Web Docs - JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)**: Comprehensive documentation on JavaScript fundamentals.
- **[CSS-Tricks](https://css-tricks.com/)**: A great site for learning and mastering CSS techniques.
- **[W3Schools](https://www.w3schools.com/)**: Offers tutorials on web development, including HTML, CSS, and JavaScript.
- **[YouTube - Bro Code](https://www.youtube.com/@BroCodez)**: The YouTube channel that inspired and guided the creation of this project.

## Author

- **GitHub**: [ShivomTiwari27](#)

## Acknowledgments

Special thanks to the following:

- **Bro Code**: For providing excellent tutorials and inspiration throughout this project. Check out their [YouTube channel](https://www.youtube.com/@BroCodez).
- **MDN Web Docs**: For offering in-depth and reliable documentation that was critical to the development process.
- **CSS-Tricks**: For providing advanced CSS insights that helped enhance the design.
