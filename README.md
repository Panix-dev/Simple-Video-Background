# Repository Title Goes Here

> Subtitle or Short Description Goes Here

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


## Table of Contents

> If your `README` has a lot of info, section headers might be nice.

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

> :email: [hello@pagapiou.com](hello@pagapiou.com)


## Inspiration

- **[Traversy Media](https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA)**
