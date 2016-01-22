Very usefull/cute modal based on fancyzoom.

## Features

 * The zoom will close when clicking outside the zoom box area.
 * Hitting esc key will close the zoom window.
 * Passing an option of closeOnClick: true into the fancyZoom function will close the zoom when the contents are clicked as well. This works great for image galleries.
 * Insanelly smaller and optimized. (Min js: 3.9kb; gzipped: 1.44 kb), images: 3.6k
 * Resize images to full modal size.
 * Works in IE
 * Load ajax content inside the modal.
	```javascript
	$('a.zoom').fancyZoom({
	  url: '/modal.html'
	});
	```

 * Shows background when modal comes up. (Styleable)
 * Indicator loading in ajax pages. (Styleable)
 * You can define multiple targets

### Usage
#### Minimalist example

```javascript
$('a.zoom').fancyZoom();
```

#### Advanced example
```javascript
  $('a.zoom').fancyZoom({
    modal: '#customModal',
    width: 320,
    height: 300,
    url: '/page.html',
    closeOnClick: true   
  });
```

###Demo

You can see the [demo page](http://reflejo.github.com/fancyzoomng/)

by Martín Conte Mac Donell <Reflejo@gmail.com> - [@fz](https://twitter.com/fz)
