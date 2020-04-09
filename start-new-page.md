# Start new page

Open the blank.vue file in `/src/components` folder.

It has the following structure:

```markup
<template>
    <div>
    </div>
</template>
<script>
import Vue from "vue";

export default {
    // ===Component name
    name: "blank",
    // ===Props passed to component
    props: {},
    // ===Components used by this component
    components: {},
    // ===Code to be executed when Component is mounted
    mounted() {},
    // ===Computed properties for the component
    computed: {},
    // ===Component data
    data() {
        return {

        }
    },
    // ===Component methods
    methods: {

    }
}
</script>
<!-- styles -->
<!-- adding scoped attribute will apply the css to this component only -->
<style scoped></style>
```

Place your html content inside the div in template.

_Note: Each template must only have one root element and one script tag._

Then add your code in the script tag.

Then give the appropriate route in `routes.js` file If you needed add the component to the router.

**Note:**

To add a route to left side menu you will have to edit the `menu.js` file.

