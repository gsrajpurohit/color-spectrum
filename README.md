# Color Box - jQuery colorbox plugin

### 1. Get a copy of the plugin
You can download the plugin from GitHub.

### 2. Load the required files
Inside the page's head tag include the colorbox's CSS file.
```
<link rel="stylesheet" type="text/css" href="css/colorbox.css" />
```

In the page's footer, just before, include the required JavaScript files.

```
<script src="js/colorBox.min.js"></script>
```

### 3. Create the HTML markup
`<div id="my-color-box"></div>`

### 5. Instantiate the ColorBox
```
<script type="text/javascript">
    jQuery( document ).ready(function( $ ) { 
        $( '#my-color-box' ).colorbox({ 
            duration: 1000, 
            trigger: 'click', // click/hover 
            position: 'top', // top/left/bottom/right 
            easing: 'slide', // fade/slide 
        }); 
    }); 
</script>
```
### Demo
[Demo](http://jsfiddle.net/g_s_rajpurohit/n6ts50y8/26/).

### Support
If you found a bug or have a feature suggestion, please email me on rajpurohitganpat@gmail.com.
If you need help with implementing the colorbox in your project feel free to contact me on rajpurohitganpat@gmail.com.

License The plugin is available under the [MIT license](https://opensource.org/licenses/MIT).
