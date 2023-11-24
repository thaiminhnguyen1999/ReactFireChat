# ReactFireChat (Create-React-App x Firebase)

[![Netlify Status](https://api.netlify.com/api/v1/badges/9a181807-27ec-4c35-947c-f5966b7c7f04/deploy-status)](https://app.netlify.com/sites/reactfirechat-test/deploys) [![Visual Studio Code](https://img.shields.io/badge/--007ACC?logo=visual%20studio%20code&logoColor=ffffff)](https://code.visualstudio.com/) [![JavaScript](https://img.shields.io/badge/--F7DF1E?logo=javascript&logoColor=000)](https://www.javascript.com/) [![Npm](https://badgen.net/badge/icon/npm?icon=npm&label)](https://https://npmjs.com/) ![Terminal](https://badgen.net/badge/icon/terminal?icon=terminal&label) [![Windows](https://badgen.net/badge/icon/windows?icon=windows&label)](https://microsoft.com/windows/)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

You can use it through three websites: [ReactFireChat (Offical Website)](https://reactfirechat.languagedevstudy.com), [ReactFireChat (Netlify)](https://reactfirechat-test.netlify.app) and [ReactFireChat (Cloudflare Pages)](https://reactfirechat.pages.dev)

## How to use?

You can use this React application directly by [clicking here](https://reactfirechat-test.netlify.app)

Or if you want to edit this project then you can do the following:

```sh
git clone -b clone-branch https://github.com/thaiminhnguyen1999/ReactFireChat
cd ReactFireChat
npm i
```

And if you want to run the React app then just enter the command:

```sh
npm start
```

## Project Structure

```
ReactFireChat
├── README.md
├── LICENSE
├── package.json
├── package-lock.json
├── node_modules
├── public
│   ├── img
│   ├── favicon.ico
│   ├── index.html
|   ├── logo192.png
|   ├── logo512.png
|   ├── manifest.json
│   └── robots.txt
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    |── reportWebVitals.js
    └── setupTests.js
```

## Firebase
The project uses Firebase. So before running the `npm start` command add the Firebase project configuration first.

### How to add Firebase project configuration?

First, visit the website firebase.google.com.

<img src='./public/img/z4625828859374_8978935b2bc94bcf322a74c1c547b9a1.jpg'>

Then press the `Get Started` button and you will be taken to another page.

<img src='./public/img/z4625857464480_cc3f9d98a28b99933279d0e87c58b6e1.jpg'>

Select `Add Project` then enter a name for your Firebase Project and press `Continue`.

<img src='./public/img/z4625857464718_73bd24b20c2a5df8c48fcd9d33b2ee4a.jpg'>

Google will ask if you want to add Google Analytics to your Firebase project? In my opinion, it can be turned on but can't be turned on, so I don't turn it on (If not, click the button to the left of the word `Enable Google Analytics for this project`) and press `Continue`

<img src='./public/img/z4625857464471_e625629e54bfbb19097d78f4106dc0a2.jpg'>

Now wait a bit for Firebase to create the project. After complete, press `Continue`

<img src='./public/img/z4625857422840_2b44c5230885b680a538d81da55c7412.jpg'>

Click the `</>` icon to continue.

<img src='./public/img/z4625857421759_f4bafc08f5f75baa2bbc4d3b28aef495.jpg'>

Now enter the app name in `My web app` and press `Register app`

<img src='./public/img/z4625857366807_13fb34a247ef5db97457b46d889eb9ef.jpg'>

Under `Add Firebase SDK`, copy the part inside 
```
const firebaseConfig = {
  
};
```
and paste the code inside the file [ReactFireChat/src/App.js (Line 12).](https://github.com/thaiminhnguyen1999/ReactFireChat/blob/clone-branch/src/App.js)

Finally, save the file and you can use it.
