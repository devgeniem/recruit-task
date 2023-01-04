# React-native - photobrowser

This is a training spec for a photo browsing react-native app. The goal the application is to render a simple grid of images and allow navigation from each image to a details page. 

The application should use [JSONPlaceholder](http://jsonplaceholder.typicode.com) as a source for the photo content

## requirements

### general requirements

- get the images from [here](http://jsonplaceholder.typicode.com/photos) 
- the source code must be made available somehow
- the code must run after `npm install` and `react-native run-android`

You may use existing boilerplate - projects, however if you do, please link to that in the readme.

### the grid page
This is just a simple grid page. Load a reasonable amount of thumbnails from the photo api, paging is optional. 

### the details page
Clicking a thumbnail from the grid should navigate to a details page, showing the full image and title of the photo. 


## optional requirements

These are optional requirements that yield bonus points. 

- use [redux](http://redux.js.org/) or [mst](https://github.com/mobxjs/mobx-state-tree) or some other reasonable state management scheme.
- ES2017 syntax used in code
- use typescript

## Tips

Read the [JSONPlaceholder](http://jsonplaceholder.typicode.com) - page carefully, you'll find the example api calls there. If you do end up using a starter kit, remember to credit that and also make sure you have basic understanding of the packages involved. Always read `package.json`

You may also add features outside of the optional and hard requirements as long as you dont break any required functionality. If you do end up going above and beyond, write few words about the features you came up with.


