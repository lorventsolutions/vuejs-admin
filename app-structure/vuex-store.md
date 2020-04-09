# Vuex store

## Vuex Store:

The store for the vuex is located in the `store/store.js`

The contents of the store are:

### 1\) State:

The state contains the following information:

#### a\)User data:

The store serves as the provider of the user data to the entire app. Changing the user details in state will change the user details in the app.

The provided details are:

```javascript
name: "Ayesha",//user name
picture: "src/assets/img/authors/prf4.png",//link to the user image
job: "Project Manager"// user designatioin
```

#### b\) Calendar Events:

The events in the calendar are also stored in the state so that they can be accessed in all places.

### 2\)Mutations:

The mutations for the state are located in the file `store/mutation.js`

The mutation are used to change the state of the store.

## Accessing the state:

You can access the store in components by using the `this.$store` value.

Eg:

To find if left menu is open:

`this.$store.state.left_open`

The same goes for commiting mutations.

Eg:

`this.$store.commit('left_menu', "close");`

