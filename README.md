# Responsive Carousel Click Tracking

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

A jQuery plugin for the [Filamentgroup responsive-carousel](https://github.com/filamentgroup/responsive-carousel/) to enable Google Analytics click tracking.

This plugin will simply push tracking parameters into Google Analytics `_gaq` object. 


## Getting Started

* Add Google Analytics to page
* Install (Easy)
  * `bower install responsive-carousel-clicktracking` if you're using [Bower](http://bower.io)
* Install (Manually)
  * Add jQuery
  * Add [Filamentgroup responsive-carousel](https://github.com/filamentgroup/responsive-carousel/)
* Add dependencies and this responsive-carousel.clicktracking.js to page
* Modify the `data-clicktracking-*` parameters to be passed int the `_gaq`.

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

Check out the `test/functional/` directory for demo (requires dependencies installed).

## Authors

* [0xADADA](https://github.com/0xADADA) - [@0xADADA](http://twitter.com/0xADADA)
* Created at [Nara Logics](http://nara.me/)

## License

Copyright 2014 0xADADA

Licensed under the MIT License
