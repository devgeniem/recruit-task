# React - Photobrowser
This is a training spec for a photo browsing web application. The goal the application is to render a simple grid of images and allow navigation from each image to a details page.

The application should use JSONPlaceholder as a source for the photo content

## Requirements
* The application must use React
* The application must run on the latest Chrome version
* Get the images from [here](http://jsonplaceholder.typicode.com/photos)
* The source code must be made available somehow

### Grid view
This is just a simple grid page. Load a reasonable amount of thumbnails from the photo API, paging is optional. Please, do not use external image gallery packages/libraries. Do it yourself, it doesn't have to be that fancy.

### Details view / Image view
Clicking a thumbnail from the grid should navigate to a details page, showing the full image and title of the photo.


## Optional requirements
These are optional requirements that yield bonus points.

* Use [TypeScript](https://www.typescriptlang.org/)
* Use some kind of state management, preferably [Mobx](https://mobx.js.org/) or [Redux](https://mobx.js.org/). Either one is good.
* Create individual routes for each of the views. Make sure that browser navigation works flawlessly
* Use CSS-in-JS (Styled Components, Emotion, Radium, etc.)
* Use function components and hooks instead of class components
* The demo is accessible on the internet
* Write a couple of simple tests using Jest or a testing framework of your choice
* The source code has a README.MD detailing how to run the code locally
* User should see an error message, if something goes wrong with API. Implement simple error handling. No need to differentiate between error types.

## Tips
* Even if we're developing just a small demo app here, it's good to keep scalability in mind. You may want to consider:
  * Should I make API calls directly from components?
  * What data should I hold in store (Mobx, Redux, whatnot..), and what should I save in the local state?
  * How I should organize my project files?
* Use [React Create App](https://create-react-app.dev/). Here's [instructions on how to start a new Create React App project with TypeScript](https://create-react-app.dev/docs/adding-typescript/)
* Read the [JSONPlaceholder](http://jsonplaceholder.typicode.com/) page carefully, you'll find the example api calls there. As for the actual code, 

You may also add features outside of the optional and hard requirements as long as you dont break any required functionality. If you do end up going above and beyond, write few words about the features you came up with.