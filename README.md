# reactr

Reactr (reactor) (change the name? too cliche?) is a to make a self editable, portable documents. All that's needed is a  browser. 
Also gives a quick way to prototype views with a quick work cylce - easely setup mock data, create your components, no need to use a different editor, reload the browser at every change, or setup a sever.

# Why?

Appart for playing around with react and getting a somewhat usable CV. The main point of this is to:
- Get a lightweight way to create simple data driven documents. The use case for this is the CV.

# Current Version

Right now it's mainly a proof of concept v.0. A lot of work is still needed to make everything self editable. It is starting to be somewhat useable.

## How to use

Download the html. Start editing. Save changes. 

## Main Features

- Create documents with react.
- Create data driven documents. Every time you create a doc, you create a template.
- es6 compatible
- Self editable/modifiable.

## Todo

- Clean up styles
  - fix data editor - options//save
  - setup options list
  - dragable splitters

- Data Editor
  - Delete Array
  - Reorder Array

- Component Editor
  - Cleanup component list
  - Editor Controls
    - change editor settings - font/theme/etc..

- Settings
  - Move settings to an editable container

- app
  - move app to an editable container
  - add loader for the inital load

- components
  - add components namespaces 

- Dependencies 
  - For dev purposes the dependencies are local - save on reload time etc...
  - Change to be able to get forma CDN, inline them on export or downlad them for dev
