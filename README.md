Basic slider mainly developed for Blogger, as it currently does not provide with any native solution. It can work right with any other site.

# Use

Add both the CSS and the JS to the header of the blog/web page (inside the ```<head>``` tag). 
  
```html
<link href='https://cdn.rawgit.com/gomezportillo/blogger-slider/master/css/my-slider-x5.css' rel='stylesheet'/>
<script src='https://rawgit.com/gomezportillo/blogger-slider/master/js/ism-2.2.min.js'></script>
```

Then just use the classes defined in the files at follows.

```html
<div class="ism-slider slider-container" id="my-slider-x5">
  <ol>
    <li>
      <img src="image1" />
    </li>
    <li>
      <img src="image2" />
    </li>
  </ol>
</div>
```

It currently can manage up to 5 images per slider.

# Known issues

Use the rawgit site to import the JS as otherwise it will not be able to load the JS due to an error like ```Refused to execute script from ... because its MIME type (text/plain) is not executable, and strict MIME type checking is enabled```.

# Credits

Based on http://imageslidermaker.com/
