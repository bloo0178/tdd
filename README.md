# Test-Driven Development Workflow (Sample) 

This project was built to gain additional experience with TDD workflows in the context of React, as well as additional experience with Jest and Enzyme. 

https://testdriven.io/blog/tdd-with-react-jest-and-enzyme-part-two/ 

# Final Thoughts

At this point we have:

- Employed Test-driven Development, along with Enzyme and Jest, to structure our application and write our tests.
- Used CSS Variables to allow for variable reuse and reassignment for responsive design.
- Written a reusable React component that we were able to render with individual functions and in multiple styles.
- Used React's PropTypes for type-checking throughout the application.

## Next steps:

- You may have noticed a quirk if you play with the calculator, that the . key doesn't work quite as expected. You know what to do: Write a test first, debug, and then write the code to pass the test.

- Another quirk you have come across is that if you click a key following an operation (doesn't matter which key), the displayValue doesn't quite update the way we would expect if we are trying to mimic the experience of using an average calculator. Compare this calculator with another calculator, isolate the differences in the experience, write some tests for the new outcomes, lastly updating the calculator functionality to get the tests green.

- Try experimenting with the CSS

- Add a loading transition or an event listener for keyboard events to the application for a better user experience.