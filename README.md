# Color Memory Project

Hello to [BigDevSoon](https://bigdevsoon.me/) 👋

Create a game inspired by Simon, where users can test their memory skills by remembering and reproducing the correct order of colors. Challenge yourself by implementing responsive design to ensure seamless gameplay across various devices and screen sizes.

## How to start

1. Start the project in our [app](https://app.bigdevsoon.me/) to get a feel for it.
2. Review the requirements listed below in this README.
3. Go through the design images on the [project's page](https://app.bigdevsoon.me/projects/color-memory) and import the `.fig` file into Figma to understand the layout and design elements.
4. Clone this repository or use [GitHub Codespaces](https://github.com/features/codespaces) to set up the project environment.
5. Choose your preferred technology stack and overwrite repository files as needed to set up your project structure. We included a few files and the `assets` folder for convenience, extracted from the design.
6. Begin coding, either using the Freerun mode to work on each card individually or the Speedrun mode to work at your own pace. Be sure to follow the guidelines outlined below.
7. Have a strong desire to learn and improve your skills as a Big Developer. 🚀

## Requirements

- [ ] Create a main circle-shaped component with four colors (green, red, blue, yellow). The component should be clickable and capable of highlighting one color at a time. The component should have two sizes: small for game rules and a default size for gameplay.
- [ ] Design a home page for the game with the following elements: a game rules icon on the left upper corner, a sound icon on the right upper corner, a centered "COLOR MEMORY" title, the circle-shaped component described above, and a "NEW GAME" button. These elements should be non-functional at this stage.
- [ ] Clicking the "NEW GAME" button should initiate a countdown with the numbers 3, 2, 1, followed by "START." The game title should change to "WATCH CLOSELY," and the game should show a random color sequence for the player to repeat using the circle-shaped component. The bottom of the screen should display the current score as "SCORE: X." After displaying the sequence, the title should change to "YOUR TURN," indicating that it is now the player's turn to repeat the color sequence with the circle-shaped component. Each game, the color sequence to repeat should start with one color and increment by one for subsequent turns. For example, on the first turn, the sequence will have one color to repeat, on the second turn it will have two colors, and so on (the same is true for the score). This cycle should repeat until the player fails to repeat the correct sequence.
- [ ] When the player fails to repeat the color sequence, a "GAME OVER" modal should appear, displaying "QUIT" and "TRY AGAIN" buttons. Clicking "QUIT" should close the modal and return to the home page, while clicking "TRY AGAIN" should close the modal and initiate a new game with the countdown sequence.
- [ ] After playing at least one game and returning to the home page after a game over, a "BEST SCORE: X" should be displayed in the left bottom corner, showing the player's highest score.
- [ ] Clicking the question mark icon in the left upper corner should display a "GAME RULES" modal. The modal should have an "OK" button to close it.
- [ ] Implement sound notifications that can be toggled on/off using the sound icon in the right upper corner. Play sound effects for each color signal shown by the game, as well as when the player repeats the colors. Additional sound effects, such as game over sounds, can be added for enhanced gameplay.
- [ ] Implement responsive web design for the game, ensuring proper alignment and scaling for desktop and tablet devices. On mobile devices, the modals' content should be arranged from top to bottom, while other elements should scale properly.
- [ ] Persist the best score even after browser refresh. Implement measures to prevent accidental double-clicks and handle edge cases appropriately.

## Guidelines

1. Aim for pixel-perfect implementation of the design. Use tools like [PixelParallel](https://chrome.google.com/webstore/detail/pixelparallel-by-htmlburg/iffnoibnepbcloaaagchjonfplimpkob?hl=en) or other techniques to ensure accuracy.
2. Write clean and efficient code. Use extensions like [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) for formatting and errors, and consider using [GitHub Copilot](https://github.com/features/copilot) and [VSCode](https://code.visualstudio.com/) as your code editor.
3. Follow a [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow). Keep your commits small and descriptive, organize your work into separate branches, and use pull requests for code reviews.

Remember, the cleaner and more accurate your code is, the faster you can finish and the better you'll feel about your work.
So let's make it happen! 💡

## Submitting project

Once you've completed the project and unlocked the Submit step in our app, it's time to deploy your project to [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or [GitHub Pages](https://pages.github.com/) (if you haven't done so already). Keep in mind that we've added a `<bds />` tag to the `index.html` file, and we'll check for it when you submit your Project URL. So don't forget to include it! You'll also need to provide the project title and the primary frontend technology used. Good luck!

## We're in Beta and getting better every day!

Hey there, Big Developer! We wanted to take a moment to thank you for participating in our project and helping us improve our platform. We're always looking for ways to make our app better, so if you have any feedback or suggestions, please feel free to let us know.

Happy coding! 🚀
