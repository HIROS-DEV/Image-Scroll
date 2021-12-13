# Image-Scroll

## ScreenShot of the project (Desktop)

<img src="images/desktop.png"/>

## Detail of the project

This is simple hover animation with CSS.
I used below youtube video as a reference.
But this project is a little bit more advance.

https://www.youtube.com/watch?v=hkZUbOQaa9g

## Purpose of the project

Learn to simple hover animation.

## Demo (Sorry, this project is only works in desktop. Not responsive)

https://hiros-dev.github.io/Image-Scroll/

## What did I learn from this project?

<p>CSS Hover animation</p>

## Impressions
Simple, but elegance effect I think.
I definitely will use my future project.

<div class="wrapper">
			<div class="container">
				<div class="box1"></div>
			</div>

			<div class="container">
				<div class="box2"></div>
			</div>
		</div>
    
    <style>
    .wrapper {
	width: 100%;
	height: 100vh;
	display: flex;
	justify-content: space-evenly;
	align-items: center;
}

.container {
	background-image: url('./images/mac.png');
	width: 459px;
	height: 371px;
    position: relative;
}

.box1 {
	width: 420px;
	height: 240px;
    position: absolute;
    overflow: hidden;
    top: 20px;
    left: 20px;
	background-image: url('./images/img1.png');
    background-position: top;
    background-size: cover;
    cursor: pointer;
    transition: ease-in-out 6s;
}

.box1:hover {
    background-position: bottom;
}

.box2 {
	width: 420px;
	height: 240px;
    position: absolute;
    overflow: hidden;
    top: 20px;
    left: 20px;
	background-image: url('./images/img2.png');
    background-position: top;
    background-size: cover;
    cursor: pointer;
    transition: ease-in-out 6s;
}

.box2:hover {
    background-position: bottom;
}
    </style>

Thank you for reading. And, happy coding!!!
