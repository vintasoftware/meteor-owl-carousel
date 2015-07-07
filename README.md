OwlCarousel
===========
>v.2.0beta

Touch enabled jQuery plugin that lets you create beautiful responsive carousel slider.
[Visit Owl Carousel landing page](http://www.owlcarousel.owlgraphic.com/)

###Features:
* Responsive
* Touch Events
* Mouse Slide Events
* Fully Customizable
* Choose the number of items to be displayed
* Multiple Sliders
* CSS3 3d Transitions
* Custimizable controls
* JSON 
* Custom events
* Helpful callbacks

> Tested on IE7, IE8, IE9, IE10, Chrome, Safari, Firefox, Opera, iPhone, iPad, Chrome on Google Nexus.


### More Demos
See what Owl can do:
* [With auto scaling images](http://owlgraphic.com/owlcarousel/demos/images.html)
* [Full Width](http://owlgraphic.com/owlcarousel/demos/full.html)
* [Custom Widths](http://owlgraphic.com/owlcarousel/demos/custom.html)
* [One Item](http://owlgraphic.com/owlcarousel/demos/one.html)
* [More demos](http://owlgraphic.com/owlcarousel/#more-demos)

### 1.Getting Started
```shell
mrt add owl-carousel
```

### 2.Set up your HTML
You don't need any special markup. All you need is to wrap your divs inside the container element <div class="owl-carousel">. Class "owl-carousel" is mandatory to apply proper styles that come from owl.carousel.css file.

```html
<div class="owl-carousel">
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  <div> Your Content </div>
  ...
</div>
```
### 3.Call the plugin
Now call the Owl initializer function and your carousel is ready.

```html
$(".owl-carousel").owlCarousel();
```

Addition
===========
### Methods Examples:
```html
owl.trigger('add.owl.carousel')
owl.trigger('replace.owl.carousel')
owl.trigger('refresh.owl.carousel')
owl.data('owl.carousel')
owl.data('owl.carousel')._items.length
```
