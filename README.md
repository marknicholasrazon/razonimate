# Razonimate

A library for creating scroll-based animations.

## Website Link

https://marknicholasrazon.github.io/razonimate/

## Installation

To install Razonimate, include the razonimate.js and razonimate.css files in your HTML file:

```html
<link rel="stylesheet" type="text/css" href="https://marknicholasrazon.github.io/razonimate/razonimate.css">
<script src="https://marknicholasrazon.github.io/razonimate/razonimate.js"></script>
```

## Usage

To use Razonimate, create an HTML element with the desired animation and set the data-razon attribute to the animation name and data-razon-duration to the duration of the animation in milliseconds:

```html
<p data-razon-duration="1000" data-razon="fade">fade</p>
```

Initiate the Razonimate library by creating a new instance and calling the init() method:

```javascript
const razonimate = new Razonimate();
razonimate.init();
```

## Install using NPM

```Linux
npm install razonimate --save
```

## Animations

Razonimate provides the following animations:

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

## Sample Code

```Linux
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<link rel="stylesheet" type="text/css" href="https://marknicholasrazon.github.io/razonimate/razonimate.css">
	<style type="text/css">
		p{
			padding: 20px;
			background-color: red;
			margin-bottom: 100px;
			width: fit-content;
		}
	</style>
</head>
<body>

<p data-razon-duration="2000" data-razon="fade">hello</p>
<p data-razon-duration="2000" data-razon="fade-right">hello</p>
<p data-razon-duration="2000" data-razon="zoom-in-left">hello</p>


<script src="https://marknicholasrazon.github.io/razonimate/razonimate.js"></script>
<script type="text/javascript">
	const razonimate = new Razonimate();
	razonimate.init();
</script>
</body>
</html>
```

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://marknicholasrazon.github.io/portfolio/)

Made with 💘 by Mark Nicholas Razon
