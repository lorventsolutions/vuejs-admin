# Changing Layouts

Changing the Layout to your desired one involves changing some names and commenting or commenting out some code in the file named with layout.vue

**1\)Boxed Layout:**

To get the boxed layout comment out the following line:

```markup
<style lang="scss" src="./components/layouts/css/boxed.scss"></style>
```

**2\) Fixed Menu:**

To get the Fixed Menu comment out the following line:

```markup
<style lang="scss" src="./components/layouts/css/fixed-menu.scss"></style>
```

**3\) compact-menu:**

To get the Compact-Menu change the following line in `layout.vue`:

```javascript
import left_side from "./components/layouts/left-side/compact-menu/left-side.vue";
```

and set the left menu width in `fixed-menu.scss` to `100px`

4**\) centered-logo:**

To get the centered-logo comment out the following line:

```markup
<style lang="scss" src="./components/layouts/css/centered-logo.scss"></style>
```

**5\) Fixed Header:**

To get the fixed header import the `vueadmin_header` from fixed-header.vue like this:

```javascript
import vueadmin_header from "./components/layouts/header/fixed-header.vue"
```

**Note:**_There are three header vue files available:_

* header.vue
* fixed-header.vue
* no-header.vue

