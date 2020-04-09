# Changing skins

## Changing Skins**:**

The colors used in Vuejs-Admin are applied by using SASS variables. So, it is very easy to change the skins for the template.

We have provided some skins for you to start.

To set a new skin for the template open `src/components/layouts/css/_customvariables.scss`

Its contents will look like:

```css
@import "skins/default"
```

The skin files are located in `src/components/layouts/css/skins`

Choose the skin you want to apply and replace default with that skin.

## Creating a New Skin:

As the skin files are just scss files to create a new skin you just need to copy a skin and change the color variables or just edit an existing one and apply it.

