<h1 align="center">Login form (HTML/CSS)</h1>

<h3 align="center">This is a simple login form that you can easily customize and adapt to your needs. Link to the demo of this project: <a href=" ">Page</a>
</h3>
<p align="center">
  <img src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103" >
</p>
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" title="html" width="50" height="50"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" title="css" width="50" height="50"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-line.svg" title="photoshop" width="50" height="50"/>
</p>

## The goal of the work
The purpose of an HTML and CSS login form is to allow the user to authenticate to a website or web application. This is especially important for sites that require the protection of personal data, such as user information or banking data.

When the user fills out the login form, he enters his login (username) and password, and sends these data to the server for verification. If this data is correct, then the server allows the user to access the protected sections of the site or application.

The goal of a login form is not only to authenticate the user, but also to provide a user-friendly experience. It should be simple and clear, with clear labels for each input field, as well as client-side data validation so that the user knows that he is entering the correct data before sending it to the server.

A well-designed login form can enhance the security of a website and create a positive user experience.

## Rules for creating a beautiful login form
There are many ways to make a beautiful login form, and a lot depends on your design preferences. However, here are some tips for creating a beautiful login form:

Use a pretty background. You can use an image, texture, or gradient to add depth and interest to the login form background.

Create an impactful headline. The heading can be highlighted in a separate block, using a large and clear font. You can also add animation to the title to make it stand out.

Use pretty fonts. Choose fonts that work well together and display clearly on all devices. You can also use different font sizes for different login form elements.

Use colors. Choose colors that go with the overall style of your site. For example, you can use the colors of your logo or brand. Use different shades for different form elements to create an interesting and eye-catching design.

Add icons and images. Icons can help the user quickly determine what to enter in each field. Images can be used to create an interesting background or to represent your brand or product.

Use animation. Animation can make the login form more interactive and effective. For example, you can add animation to a submit button or a password input field.

It is important to remember that a beautiful login form design should not interfere with its functionality and usability. The login form should be intuitive and easy to complete so that users have no trouble logging into your site or app.

## Task statement
<p>A simple experiment with <b>css & html</b> and its possibilities.</p>
<p>A demo implementation of this template can be viewed at this link:<a href="https://heorhiizemlianko.github.io/3D-Layer-Image-Hover-Effect/3dimaje.html"> <b>login form</b> </a></p>

## Schematic representation of the HTML structure
```
html
├── head
│   ├── meta
│   ├── title
│   └── link
└── body
    └── divloginbox
        ├── img.avatar
        ├── h1
        └── form
```

## Schematic representation of the CSS structure
```
css
├── body
├── .loginbox
├── .avatar
├── h1
├── .loginbox input
├── .loginbox p
└── .loginbox a
```

## Code from the project
- HTML
```html
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Login Form Design</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="loginbox">
	<img src="worker.jpg" class="avatar">
		<h1>Login In</h1>
		<form>
			<p>Username</p>
			<input type="text" name="" placeholder="Username" value="">
			<p>Password</p>
			<input type="password" name="" placeholder="Password" value="">
			<input type="submit" name="" value="Sign In">
			<a href="#">Lost your Password?</a><br>
			<a href="#">Don't have an account?</a>
		</form>	
	</div>
</body>
</html>
```
- CSS
```css
body{
	margin: 0;
	padding: 0;
	background: url(back.jpg);
	background-size: cover;
	font-family: sans-serif;
}
.loginbox{
	width: 320px;
	height: 420px;
	background: #000;
	color: #fff;
	top: 50%;
	left: 50%;
	position: absolute;
	transform: translate(-50%,-50%);
	box-sizing: border-box;
	padding: 70px 30px;
}

.........

.loginbox input[type="submit"]:hover{
	cursor: pointer;
	background: #483D8B;
	color: #fff;
}
.loginbox a{
	text-decoration: none;
	font-size: 12px;
	line-height: 20px;
	color: darkgrey;
}
.loginbox a:hover{
	cursor: pointer;
	color: #483D8B;
}
```
