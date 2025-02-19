# Welcome!

Welcome to Condor's React.js basic assessment challenge!

This task is meant to assess your proficiency in React fundamentals including state management, context API, and custom hooks.

You may only use the packages that are already installed. Usage of any other package might invalidate the test, and **will invalidate it if it interacts with state or context management**.

Please do note that it's expected of you to develop the code for any solution. **Importing any hooks, or utilities to solve the tasks requierements stated bellow, will invalidate your submission**.

If you must, you may add a css library. We encourage you to use Tailwind, which is already intalled and configured.

Available scripts:

- `npm run app`: To run the react app.

Finally, in the folder `./src/types` you can find the interfaces needed. Feel free to edit them as you see fit.

## The task

Using react and the APIs referenced in the resources section, create a small application that allows users to toggle between light and dark themes and maintains a list of items.

For the app to comply with the company standards, the following requirements must be met:

- The app's theme, on the first visit, should load from the user's browser configuration.
- The app's theme of the app must persist.
- The app's persistence handler should be extracted in its own file.
- The app's theme has to be able to be consumed from every/any level or component.
- List items should be able to be created, and deleted.
- The app must be responsive down to 300px.

Also, the following features are listed as _nice to have_:

- List items can be sorted in a asceding or descending way.
- List items can be ordered alphabeticaly.
- List items can be ordered in a custom manner.
- List items can be edited and saved.
- List items persist.

## Evaluation Criteria

Along with the things we'll be looking at (stated at the root's README.md), we'll also be looking at:

- Correct implementation and usage of context.
- Correct use of state in components.
- Code organization and cleanliness.
- Proper usage of JSX and React principles.
- Proper creation and usage of a custom hook.
- Persistence of theme
- Functionality for item creation/removal.

## Resources

- [React](https://reactjs.org/)
- [Axios](https://axios-http.com/docs/intro): Fetch client
- [JSON Server](https://github.com/typicode/json-server#getting-started)
