# Simple Video Background

> Video background using only HTML and CSS

A full-screen video background for a landing page using only HTML and CSS. The video section uses height:100vh to cover the entire screen and the HTML video markup uses the parameters "autoplay muted loop".


## Table of Contents


> Try `clicking` on each of the `anchor links` below so you can get redirected to the appropriate section.

- [Video Parameters](#video-parameters)
- [CSS Styles](#css-styles)
- [Contact Details](#contact-details)
- [Inspiration](#inspiration)


## Video Parameters


```html
<div class="video-container">

	<video src="video.mov" autoplay muted loop></video>

</div>
```


## CSS Styles


```css
.showcase {
	position: relative;
	height: 100vh;
	display: flex;
	flex-direction: column;
	align-items: center;
	justify-content: center;
	text-align: center;
	padding: 0 20px;
	color: #fff;
}

.video-container {
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	overflow: hidden;
	background: var(--primary-color) url('./cover.jpg') no-repeat center center/cover;
}

.video-container:after {
	content: '';
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: rgba(0,0,0,0.6);
}

.video-container video {
	min-width: 100%;
	min-height: 100%;
	object-fit: cover;
	position: absolute;
	top: 50%;
	left:50%;
	transform: translate(-50%, -50%);
}
```


## Contact Details


> :computer: [https://pagapiou.com](https://pagapiou.com)

> :email: [hello@pagapiou.com](mailto:hello@pagapiou.com)

> :iphone: [LinkedIn](https://www.linkedin.com/in/agapiou/)

> :iphone: [Instagram](https://www.instagram.com/panos_agapiou/)

> :iphone: [Facebook](https://www.facebook.com/panagiotis.agapiou)


## Inspiration


- **[Traversy Media](https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA)**
