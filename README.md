##Routr

To get started:

```
npm install
```

  * Will install all your node components


```
bower install
```

  * Install front-end dependencies


```
gulp
```

  * Compiles sass, moves vendor javascript and css into the public folder

####Gulp tasks

```
gulp icons
```

  * moves fonts into `css/font` directory

```
gulp sass
```

  * compiles user sass in `resources/sass/user` and then compiles vendor sass in `resources/sass/vendor`

  * can also run `gulp sass:user` and `gulp sass:vendor` separately

```
gulp bower
```

  * grabs all the vendor js in bower_components

```
gulp clear
```

  * clears all css in the `public/css/vendor` and `public/js/vendor` directories

```
gulp watch
```

  * Starts the local web server and watches for changes in `resources/user` and `public/index.html`
 
##To Do:

  * API - drivers, trips, legs, admins
  * Interface
    * Sass - mixins, partials
    * clean up panel
    * Google Maps Controls

* Javascript - Angular, modules with map.js
* Map 
   * Clear route
   * change route color
   * choose start/end location
   * get circle/rectangle shapes working
   * add support for "legs"
