# filemanager

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).



### Discreption (explanstion)

The design and thoughts I have thought about goes like this-:

1: A basic user auth login to get their own data to see.
2: after successfull login the session is going to renew in every one hour without asking user, this will
    not bother user to continue session every time and also the new session will get created automatically
    this will help to secure the user data
3: Once user logins in successfull an Home page UI will code which will consit of several components like           below:-
   A: Navbar where the app name will show up, with a search field, by which user can search up for there documents / images etc..,In b=navbar whatever user is opening will show up like Recent>Images>atsappimage>this.jpg
   B: Celow that the most important component will show up ehich will having single row with horizontal  scroll
      where the first option will be of recents, What recent will do :-
      B1: What ever user downloads or opens in his / here device will show there only in a grid of 2*2
      B2: Once user clicks on recent below all the recent files will get open which user can check or preview
   C: The second one will be of Download option where user can see all his / her downoaded files
      Whatever user has downloaded will shown up in that option with 2*2 files of recent downloads once user clicks on that all the recent downloads will shown up
   D: The third one will be Images, Once user will click there a new grid will how up where all the images will     be shown Like:
      D1: Whats app images,facebood images and etc...
   E: One more will be video which will work simillar as Images 
      There will be much more options also but for explanations I am taking this
 4: Once user opens any options the images or videos or docs will have some functionallity like
    A:Multiple select user can delete the files or can share the file
    I will do the sharing with Vue.js Social sharing
    
 5:creating new folder option will also be there in Navbar so that user can create that 
 6: At last there will be anoption to share this app which will work like below
    A:As it is a web application once user clicks on share button / icon the url of the app will c=be copied in clipboard and a model will open having several option to share via like -- facebook,whats app...

### SO above is my thought process to do it as here my laptop is not in good contition to work on otherwise I have fully completed it