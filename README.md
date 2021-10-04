# 
# The purpose of this project is to create a chrome extension that can make any web page go dark mode. 

*** 

# To Use:
1. Clone the project down to your machine

1. Open your chrome based browser

1. Navigate to   *chrome://extensions/*
    
    (if using other browsers based in chrome, you will be redirected)

1. Enable developer mode, located in the top right of browser window
    
    A few button options should now be in the browser window top left.

1. Select 'Load Unpacked'

1. Select the directory for the extension

    Now the extension is loaded into your browser, you can enable it on web pages.

1. Navigate to a webpage, click the extensions icon (looks like a puzzle piece) 

    click the dark mode extension :)





# The manifest file is the setup for the chrome extension

# Components of the manifest file

## the manifest_version
    
    specifies the verions of chrome to interact with
    is adviced to be 3

## background 
    
    JavaScript code that's run in a separate instance in the browser, 
    and it's mostly used for listening to events and handling a 
    browser wide state.
    
    1. service worker
        
          Code that is injected into the context of the webpage (regular web code html, css, js)

## permissions 
    
    The apis within chrome the app will be accessing

## action 
    
    The components that will be rendered in the extension
    
    1. Popups

        The content displayed when the user opens the extension


## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
