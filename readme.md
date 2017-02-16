## PostCSS Easings

Custom easing functions for PostCSS! :chart_with_upwards_trend:

## Installation

```
npm install postcss-easings
```

## Usage

Wherever you've configured PostCSS:

```
var easings = require('postcss-easings')
```

This:
```css
.ease-in-sine {
  transition: opacity 300ms easeInSine;
}

.ease-out-sine {
  transition-timing-function: easeOutSine;
}
```

Compiles to:
```css
.ease-in-sine {
  transition: opacity 300ms cubic-bezier(0.47, 0, 0.745, 0.715);
}

.ease-out-sine {
  transition-timing-function: cubic-bezier(0.39, 0.575, 0.565, 1);
}
```

## Available Functions:

* [easeInSine](http://easings.net/#easeInSine)
* [easeOutSine](http://easings.net/#easeOutSine)
* [easeInOutSine](http://easings.net/#easeInOutSine)
* [easeInQuad](http://easings.net/#easeInQuad)
* [easeOutQuad](http://easings.net/#easeOutQuad)
* [easeInOutQuad](http://easings.net/#easeInOutQuad)
* [easeInCubic](http://easings.net/#easeInCubic)
* [easeOutCubic](http://easings.net/#easeOutCubic)
* [easeInOutCubic](http://easings.net/#easeInOutCubic)
* [easeInQuart](http://easings.net/#easeInQuart)
* [easeOutQuart](http://easings.net/#easeOutQuart)
* [easeInOutQuart](http://easings.net/#easeInOutQuart)
* [easeInQuint](http://easings.net/#easeInQuint)
* [easeOutQuint](http://easings.net/#easeOutQuint)
* [easeInOutQuint](http://easings.net/#easeInOutQuint)
* [easeInExpo](http://easings.net/#easeInExpo)
* [easeOutExpo](http://easings.net/#easeOutExpo)
* [easeInOutExpo](http://easings.net/#easeInOutExpo)
* [easeInCirc](http://easings.net/#easeInCirc)
* [easeOutCirc](http://easings.net/#easeOutCirc)
* [easeInOutCirc](http://easings.net/#easeInOutCirc)
* [easeInBack](http://easings.net/#easeInBack)
* [easeOutBack](http://easings.net/#easeOutBack)
* [easeInOutBack](http://easings.net/#easeInOutBack)

## Thanks
All of these functions are taken from [http://easings.net/](http://easings.net/)
