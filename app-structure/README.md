# App structure

## **index.html**

This is the starting point of the project. It contains the vue app instance.

## **app.vue**

This is the component that gets loaded into the index.html when vue app is started.

`app.vue` also contains preloader component and route-view to load basic pages and the main layout.

## **layout.vue**

This gets loaded into app.vue when main paths are accessed.

This contains the main layout including the header, left-menu and the right-side content including the right-side menu.

## main.js

This is the starting of the vue app. The vue app is instantiated at the end of this file. This file also contains the routes of the app to which it should re-direct and is controlled by the vue-router. The vue-router configuration is also done in this page.

