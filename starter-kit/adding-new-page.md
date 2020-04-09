# Adding new page

From Full package if you would like to use any plugin, then you can make use of Starter Kit

Let us assume to use a particular plugin like google maps, then you should add plugin name and version in package.json file. For instance,

Copy this code from full package`"vue2-google-maps:0.7.9"`paste it in package.json file of starter kit .

Run the below command to get the dependencies from package.json

`yarn install`

Import as VueGoogleMaps from full package into Starter kit

## **Then you need to follow below steps.** <a id="then-you-need-to-follow-below-steps"></a>

**Route.js:**

The routes for the Template are declared in the file`routes.js`. this file is called in the`main.js`file, in the vue instance declaration.

```text
{
path: '/vuegooglemaps',component: resolve =
>
 require(['./components/vuegooglemaps.vue'], resolve)

                                      or

component: resolve =
>
 require(['./components/...../vuegooglemaps.vue'], resolve)
}
```

**Note :**

Path should be according to your file placement like above

Folder\_name is your folder name

```text
         meta: {
        title: "Gmpas",  
                  }
```

Note: We already have an example in src /route.js file and there is a one index file in components

**Menu.js:**

Here you need to set file name and path

```text
eg:
    {
    name: 'Google maps', 
>
     appearing name in left menu 

    link: '/vuegooglemaps', 
>
        file name 

    icon: 'fa fa-maps', 
>
  If you want to add icon then you can add here.
},
```

Now, you can see google maps plugin. In the same way you can make any changes as required

