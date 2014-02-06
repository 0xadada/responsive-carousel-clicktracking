# Responsive Carousel Click Tracking

An extension for the filamentgroup responsive-carousel to enable Google Analytics click tracking.

This plugin will simply push tracking parameters into Google Analytics `_gaq` object. 


## Getting Started

* Add Google Analytics
* Add jQuery
* Add [Filamentgroup responsive-carousel](https://github.com/filamentgroup/responsive-carousel/) javascript and CSS.
* Add Filamentgroups responsive-carousel javascript and CSS
* Add this responsive-carousel.clicktracking.js
** Modify the `data-clicktracking-*` parameters to be passed int the `_gaq`.

In your web page:

```html
<script src="jquery.js"></script>
<script src="responsive-carousel.js"></script>
<script src="responsive-carousel.clicktracking.js"></script>
<link href="responsive-carousel.css" rel="stylesheet">

<div class="carousel"
    data-click-tracking
    data-click-tracking-next="User action,image_arrow,next"
    data-click-tracking-prev="User action,image_arrow,prev">
    <div>
        <!-- carousel item content here -->
    </div>
    <div>
        <!-- carousel item content here -->
    </div>
</div>

```

### Demos

Check out the [`test/functional/`](http://ronaldjadams.github.com/responsive-carousel-clicktracking/test/functional/) directory for demos.

## Authors

* [Ron. Adams](https://github.com/ronaldjadams - [@ronaldjadams](http://twitter.com/ronaldjadams)
* Created at [Nara Logics](http://nara.me/)

## Licence

Copyright 2014 Ron. Adams

Licensed under the MIT License
