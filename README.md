# React Tic Tac Toe

Quick start:

```
$ yarn # npm install
$ yarn build # npm run build
````

## Development

Run Webpack in watch-mode to continually compile the JavaScript as you work:

```
$ yarn watch # npm run watch
```

Concepts and Techniques Used
React Hooks: The project extensively utilizes React hooks, such as useState and useEffect, to manage state and side effects. The state hooks allow us to maintain the game's state, including the current player, the board status, and the game's outcome. The effect hooks enable performing actions based on state changes, such as checking for a winner or updating the game status.

Functional Components: The components in this project are written as functional components, leveraging the new syntax introduced in React. Functional components are simpler and easier to understand, as they don't require managing a separate this context.

State Management: The state of the game is managed using React's useState hook. By updating the state, the components re-render, reflecting the changes in the UI. This approach ensures a declarative and efficient way of handling state.

Conditional Rendering: The project demonstrates conditional rendering techniques to display different UI elements based on the game state. For example, it shows different messages based on whether a player has won or if the game is a draw.

Event Handling: React's event handling mechanism is used to capture user interactions, such as clicking on the game board. These events trigger state updates, leading to re-rendering and reflecting the changes in the UI.
