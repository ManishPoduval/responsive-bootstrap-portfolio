# Webinar Materials

<br>

## [Presentation](https://docs.google.com/presentation/d/1GQLIIQauD_i1LXGxzw9vDAnVkJTTQowTDSpTyQPR-T4/edit#slide=id.p)

Feel free to use this [presentation](https://docs.google.com/presentation/d/1GQLIIQauD_i1LXGxzw9vDAnVkJTTQowTDSpTyQPR-T4/edit#slide=id.p) as a reference.

<br>


## What we'll be building

### A simple responsive portfolio in HTML, CSS and [Bootstrap](https://getbootstrap.com/)

[<img width="400" src="https://imgur.com/qNspGGE.png" />](https://manishpoduval.github.io/responsive-bootstrap-portfolio/)
<br>
[<img width="200" src="https://imgur.com/EZdpP3Y.png" />](https://manishpoduval.github.io/responsive-bootstrap-portfolio/)


## [Final Result](https://manishpoduval.github.io/responsive-bootstrap-portfolio/)

You can see the intended finished result [here](https://manishpoduval.github.io/responsive-bootstrap-portfolio/)

The final code is also available on codepen and repl

Codepen -  [Code](https://codepen.io/manish-poduval/pen/mdEzRdb?editors=1100) and the [Final Output](https://codepen.io/manish-poduval/full/mdEzRdb)
<br>
Repl - [Code](https://repl.it/@ManishPoduval4/Bootstrap-portfolio#index.html) and the [Final Output](https://bootstrap-portfolio.manishpoduval4.repl.co/)

<br>

----

## Dev Environment setup

### Sign up to any one of these online editors 

[**Repl**](https://repl.it/)

[<img width="200" src="https://imgur.com/8w78bQ6.png" />](https://repl.it/)
<br>

[**CodePen**](https://codepen.io/)

[<img width="200" src="https://imgur.com/R6qXOFS.png" />](https://codepen.io/)
<br>

[**CodeSandbox**](https://codesandbox.io/)

[<img width="200" src="https://imgur.com/GGufK7r.png" />](https://codesandbox.io/)
<br>

[**JSFiddle**](https://jsfiddle.net/)

[<img width="200" src="https://imgur.com/0z0mGD0.png" />](https://jsfiddle.net/)

##### We'll be using [Repl](https://repl.it/) for our webinar

<br>

---



## HTML starter code

##### Note: If you're using Repl, it already comes with a starter code once you create a project 

```
<!DOCTYPE html>
<html>
	<head>
		<meta  name="viewport"  content="width=device-width">
		<title>My Portfolio</title>
		<!-- Put bootstrap css link below -->
		
		<!-- Put your own css file link below -->
		
	</head>
	<body>
	     
	     <!-- Put external js file links below -->
	     
	</body>
</html>
```
<br>

---
# Bootstrap CSS & JS Links

### Visit Bootstrap's website [here](https://getbootstrap.com/)
#### Scroll down in the home page itself until you see the section that looks like the image below

  <img class="button" width="750" src="https://imgur.com/8hD2V7V.png">

#### Copy the css `<link>` tags and the js `script` tags and put them in your HTML starter code

The final version should look something like this

```
<!DOCTYPE html>
<html>
	<head>
		<meta  name="viewport"  content="width=device-width">
		<title>My Portfolio</title>
		<!-- Put bootstrap css link below -->
		<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
`
		<!-- Put your own css file link below -->
		
	</head>
	<body>
	     
	    <!-- Put external js file links below -->
		<!-- jQuery and JS bundle w/ Popper.js -->
		<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
		<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
	</body>
</html>
```

### Now we're ready to build our portfolio website

<br>

---
# Sections in our portfolio

#### Our Portfolio is mainly going to be comprised of 5 different sections 
##### We will be using Bootstrap components and classes for each of these sections

## Navbar 

  <img class="button" width="650" src="https://imgur.com/RCpRW2u.png">

The bootstrap documentation for Navbar is [here](https://getbootstrap.com/docs/4.5/components/navbar/)

The final code of our nav section will look like [this](https://gist.github.com/ManishPoduval/dae32e89f270a1b3ab863f58b3b8335c)


## Landing Section

  <img class="button" width="650" src="https://imgur.com/m95bU0q.png">

The final code of our landing section will look like [this](https://gist.github.com/ManishPoduval/ffa7334d784914f2510737a454085f28)

## About Me 

  <img class="button" width="650" src="https://imgur.com/el2ohKt.png">

The [Flex](https://getbootstrap.com/docs/4.3/utilities/flex/) classes we used for align things can we found [here](https://getbootstrap.com/docs/4.3/utilities/flex/)
  
 The [Spacing]((https://getbootstrap.com/docs/4.3/utilities/spacing/) ) classes use used can be found [here](https://getbootstrap.com/docs/4.3/utilities/spacing/) 

The final code of our about me section will look like [this](https://gist.github.com/ManishPoduval/53616f0b1a1af99440456734a4b618ec)

You can create some random paragraph if you'd like to from [here](https://www.lipsum.com/)

## Projects 

  <img class="button" width="650" src="https://imgur.com/tY2HEev.png">

The bootstrap documentation for Cards used for this section is [here](https://getbootstrap.com/docs/4.3/components/card/)

The final code of our projects section will look like [this](https://gist.github.com/ManishPoduval/378d149f61d01cfb83a5ee3174750a74)


## Contact 

  <img class="button" width="650" src="https://imgur.com/atRVFLN.png">

The bootstrap documentation for Buttons used for this section is [here](https://getbootstrap.com/docs/4.5/components/buttons/)

The final code of our projects section will look like [this](https://gist.github.com/ManishPoduval/990bcc82f3d2d656a4d68354d7271c25)

<br>

---

# Assets for the project

## Profile Image

<img src='https://avataaars.io/?avatarStyle=Circle&topType=Hat&accessoriesType=Wayfarers&facialHairType=Blank&clotheType=BlazerShirt&eyeType=EyeRoll&eyebrowType=FlatNatural&mouthType=Default&skinColor=Light'
/>

This is your dummy **profile image** we'll use for our page.
You can create your own from [GetAvataaars.com](https://getavataaars.com/) and get the img tag link. It's **FREE** 

Or copy this url and place it in the `src` attribute for the `img` tag.

```
https://avataaars.io/?avatarStyle=Circle&topType=Hat&accessoriesType=Wayfarers&facialHairType=Blank&clotheType=BlazerShirt&eyeType=EyeRoll&eyebrowType=FlatNatural&mouthType=Default&skinColor=Light
```

or use this img tag  as it is

```
<img src='https://avataaars.io/?avatarStyle=Circle&topType=Hat&accessoriesType=Wayfarers&facialHairType=Blank&clotheType=BlazerShirt&eyeType=EyeRoll&eyebrowType=FlatNatural&mouthType=Default&skinColor=Light'
/>
```

## Project Images

These are  **project section images** we'll use for our portfolio. 
All these images are from [Undraw](https://undraw.co/illustrations) . You can choose your own ones from there. It's **FREE**

#### Project 1
<img class="button" width="350" src="https://imgur.com/BI6Y4p3.png">

Copy this url and place it in the `src` attribute for the `img` tag 
```
https://imgur.com/BI6Y4p3.png
```

<br>

#### Project 2
<img class="button" width="350" src="https://imgur.com/HycMqLT.png">

Copy this url and place it in the `src` attribute for the `img` tag 
```
https://imgur.com/HycMqLT.png
```

<br>

#### Project 3
<img class="button" width="350" src="https://imgur.com/ZaRAvUQ.png">

Copy this url and place it in the `src` attribute for the `img` tag 
```
https://imgur.com/ZaRAvUQ.png
```

<br>

#### Project 4
<img class="button" width="350" src="https://imgur.com/jQZthWf.png">

Copy this url and place it in the `src` attribute for the `img` tag 
```
https://imgur.com/jQZthWf.png
```

<br>

## Sample Resume

##### You can use this sample resume link for the project

```
https://drive.google.com/file/d/16F8To75_-URmeFmPlcGVsRoIWrRK6Ce7/view
```

---

## Additional FREE Resources

<br>
Here are some additional resources to make you an awesome developer



[HTML cheat sheet](https://web.stanford.edu/group/csp/cs21/htmlcheatsheet.pdf)

[CSS cheat sheet](https://websitesetup.org/css3-cheat-sheet/)

[CSS Flexbox game](http://flexboxfroggy.com/)

Get free illustrations for your website  from 
[Undraw](https://undraw.co/illustrations) and 
[Illustrations]([https://illlustrations.co/](https://illlustrations.co/))

Free face avatars from 
[Get Avatars](https://getavataaars.com/)

Color Palletes for your website from 
[Happy Hues](https://www.happyhues.co/)

<br>

---

## Optional:  Add Background gradients to your site

You can find some really cool background gradients from this site [uigradients.com](https://uigradients.com/#MasterCard).

Go ahead and try them out :)

<br>
Choose your favourite gradient by toggling the arrows.  
Once you're on that site you need to click on the icon on the top right corner as shown in the image below.

<img width="700" height="400" src="https://imgur.com/7gjeXPi.png" >

<br>

This will show us a pop up with the css code for that background 

<img width="700" height="400" src="https://imgur.com/7263lSx.png" >

Copy the css code and paste it inside the `{}` brackets of your `body` in your css

<br>

```
body {
	background: #f46b45; /* fallback for old browsers */
	background: -webkit-linear-gradient(to right, #f46b45, #eea849); /* 	Chrome 10-25, Safari 5.1-6 */
	background: linear-gradient(to right, #f46b45, #eea849); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}
```
---