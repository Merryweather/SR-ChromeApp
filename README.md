# SR ChromeApp 
**Chrome extension to play live radio from Sveriges Radio (Swedish Radio).**
Is built with React.js.

To transform the react JSX to plain javascript, supported by Chrome plugins, we use babel.js with babel-plugin-transform-react-jsx.
To run the tranformation you have to have Node and npm installed, and then run the command:

`npm run transform`

This will tranform the `radio.jsx` in the Addon/JSX folder, and output it in the Addon/Build folder to `radio.js`.
