# Left menu

The Left-side Navigation menu of Vuejs-admin is comprised of a few sub components.

The left menu user profile is a component located at `src/components/layouts/left-side/left-profile/user_profile.vue`

Then the links in the left menu are generated from a loop.

The loop uses three components to generate the menu structure.

**1\) vueMenu:**

The main container for the menu

**2\) SubMenu:**

The container for the sub menu components

**3\) MenuItem:**

The router link component generated

The data for the link come from `menu.js` file. To change the content of the left menu you have to edit the `menu.js` file.

