# Random name generator
This small application was developed as a part of a technical test.

### Requirements
The app should allow the user to add and remove names to and from a list, and then press a button to randomly pick a name from the list. The same name should not be picked twice in a row. The name picked should be displayed in an easy way to read for the user.

It should also fit the following criteria:
- Must compile without errors
- Includes some form of state management
- Compiled code should run on Internet Explorer 11+
- Should utilise Webpack

### Technical decisions made
To fulfil the requirements, several technical decisions were made:
- Redux state management was implemented using Redux Toolkit
- The application logic and presentation were covered by integration and unit tests using Jest
- Material-UI was used for the presentation
- A custom Webpack config was used instead of CRA
