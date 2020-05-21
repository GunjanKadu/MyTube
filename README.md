<h1 align="center"> About</h1>
This repository is the source code for Building Youtube in React


<h1 align="center">Screenshots</h1>
UI-wise this application looks **almost exactly like the original Youtube application**


<h1 align="center">How to run this application</h1>
This application loads information using the [Youtube Data API v3](https://developers.google.com/youtube/v3/docs/).

To use it, you need to set up a [Youtube Data v3 API key](https://productioncoder.com/build-youtube-in-react-part-19/) and run the project with `npm` or `yarn`.

<h1 align="center">Below, you'll find a step by step explanation</h1>

<h2 align="center">Getting a Youtube Data API key</h2><br/>
1. Head over to the [Google developers console](https://console.developers.google.com)<br/>
2. Create a new project by clicking on `Select project` drop down right next to the logo. Click the `New Project` button an give it a speaking name.<br/>
3. Select your project by choosing it in the `Select Dropdown` directly next to the logo in the header.<br/>
4. Click the `Enable APIs and Services` button<br/>
5. Search for `youtube data`<br/>
6. Click on the `Youtube Data API v3`<br/>
7. Click the blue enable button<br/>
8. In the dashboard, click `Credentials` on the left sidebar<br/>
9. Click the `Create Credential` button<br/>
10. Which API are you using: `Youtube Data API v3`<br/>
11. Where will you be calling the API from: `Web browser`<br/>
12. What data are you accessing: `Public data`<br/>
13. Click the `What credentials do I need button`<br/>
14. **Copy the API key, and paste it into `src/App.js`**<br/>
```
const API_KEY = 'AIzaxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx';
```
<h2 align="center">Install the dependencies</h2>
Install the dependencies by running
```
npm install
```

If you are using [yarn](https://yarnpkg.com/lang/en/), please run
```
yarn install
```
<h2 align="center">Running the application</h2>
**To run the application, execute**
```
npm start
```
or with [yarn](https://yarnpkg.com/lang/en/)
```
yarn start
```

<h1 align="center">Tests</h1>
This project contains an extensive suite of tests and makes use of [Jest](https://jestjs.io/) and [Enzyme](https://github.com/airbnb/enzyme).

Run all tests by executing.

```
npm test
```

You can also use [yarn](https://yarnpkg.com/lang/en/) to run the tests.
```
yarn test
```

<h1 align="center">Features</h1>
This application includes the major features of Youtube such as<br/>
* home feed with infinite scroll<br/>
* trending videos<br/>
* searching for videos<br/>
* watching videos<br/>
* displaying comments and video details

<h1 align="center">Used technologies</h1><br/>
* [React / create-react-app](https://github.com/facebook/create-react-app)<br/>
* [Redux](https://redux.js.org/)<br/>
* [Redux-saga](https://redux-saga.js.org/)<br/>
* [Redux-reselect](https://github.com/reduxjs/reselect)<br/>
* [Jest](https://jestjs.io/)<br/>
* [Enzyme](https://airbnb.io/enzyme/)<br/>
* [Semantic UI](https://react.semantic-ui.com/)<br/>
* CSS Grid / Flexbox

