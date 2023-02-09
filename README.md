
# Razonimate

## Introduction

Razonimate makes it simple and straightforward. The library provides a set of animation properties that you can use to control the behavior of your animations, such as duration, easing, and scale.

To get started with Razonimate, simply include the library in your HTML file and call the Razonimate function on your target element, passing in the desired animation properties. Whether you're a seasoned web developer or just starting out, Razonimate is a great choice for adding dynamic and engaging animations to your web pages.

## Getting Started

### Installation

Razonimate can be installed using npm:

```linux
npm install razonimate
```

Or you can include the library in your HTML file:

### css
```html
<link rel="stylesheet" type="text/css" href="https://unpkg.com/razonimate@1.0.2/razonimate.css">
```

### JavaScript

Fixed Animations
```javascript
<script src="https://unpkg.com/razonimate@1.0.2/razonimate.js"></script>
```

Custom Animation
```javascript
<script src="https://unpkg.com/razonimate@1.0.2/custom-razonimate.js"></script>
```

## Usage

In order to utilize Razonimate in your web development projects, it is necessary to include the library in your HTML file. You have the option of either selecting a pre-defined animation or creating a target element. The Razonimate function can then be invoked on the target element, along with the specified animation properties.

**Here's an example for fixed animation:**

```javascript
<div data-razon-duration="2000" data-razon="fade">
  Hello World!
</div>

<script>
    const razonimate = new Razonimate();
    razonimate.init();
</script>
```

This example demonstrates the implementation of Razonimate for a pre-defined animation. The ```div``` element contains two data attributes, ```data-razon-duration``` and ```data-razon```.

The ```data-razon-duration``` attribute specifies the duration of the animation, which is set to 2000 milliseconds. The ```data-razon``` attribute specifies the type of animation to be performed, which is set to "fade".

The script section declares a new instance of the Razonimate class and initializes it using the ```init()``` method. This sets up the library and makes it ready to perform the animation on the target element, which is the ```div``` element in this case.

When the page loads, the animation defined by the data attributes will be triggered, and the text "Hello World!" will fade in over a duration of 2000 milliseconds.

**Here's an example for custom animation:**

```javascript
<div id="target">
  Hello World!
</div>

<script>
  const element = new Razonimate('#target', {
    backgroundColor: 'red',
    opacity: 1,
    textColor: 'white',
    duration: 2000,
    easing: 'ease-in-out',
    offsetX: -100,
    offsetY: 0,
    scale: 1
  }); 
</script>
```

This example demonstrates the implementation of Razonimate for a custom animation. The ```div``` element is the target element and has an ID of "target".

The script section declares a new instance of the Razonimate class, passing in the target element and an object that defines the animation properties as arguments.

## Animation properties

The Razonimate function accepts an object with several properties to control the animation. Here are the properties:

- **`backgroundColor`**
- **`opacity`**
- **`textColor`**
- **`duration`**
- **`easing`**
- **`offsetX`**
- **`offsetY`**
- **`scale`**

Razonimate provides the following attributes to the data-razon animation:

- fade
- fade-left
- fade-right
- fade-up
- fade-down
- fade-up-left
- fade-up-right
- fade-down-left
- fade-down-right
- flip-left
- flip-right
- flip-up
- flip-down
- zoom-in
- zoom-in-up
- zoom-in-down
- zoom-in-left
- zoom-in-right
- slide-up
- slide-down
- slide-left
- slide-right
- rotate-left
- rotate-right
- shuffle-left
- shuffle-right
- skew-left
- skew-right


## Conclusion

With Razonimate, you can easily add animations and transitions to your web pages. Whether you want to use pre-defined animations or create

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://marknicholasrazon.github.io/portfolio/)

Made with 💘 by Mark Nicholas Razon
