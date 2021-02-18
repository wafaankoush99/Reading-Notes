# HTML Images; CSS Color & Text

## IMAGES

**Images Should**


- Be relevant
- Convey information
- Convey the right mood
- Be instantly recognisable
- Fit the color palette

**stoCk photos**

- [istockphoto.com](www.istockphoto.com)

- [gettyimages.com](www.gettyimages.com)

- [veer.com](www.veer.com)

- [sxc.hu](www.sxc.hu)

- [fotolia.com](www.fotolia.com) 

***

```css
<img src="imagessource.jpg" 
alt="A Description" 
title="more information." />
```

`<img` This is an empty element (which means there is
no closing tag).

it has 2 attributes:
1. src : tells the browser where i can find img
2. alt : description of the img

// 3. title : give additional information


I use width and height attribute to change the size of img in pixels

// you can place the img in your code anywhere suitable // inside the p.. inside the start of a p ... or in the middle of p


another attribute :

`<algin>` used to indicate how the other parts of a page should flow around an image .. and it takes left and right values 
also there are three values inside algin tag like top middle & bottom 

// top :  first line of the text with the top of the image.

// middle : first line of the text with the middle of the image.

// bottom : first line of the text with the bottom of the image. 


**three rules for CreatIng Images**

1. saVe Images In the right extension jpg, gif, or png 
2. saVe Images at the rIght sIze and 
3. correct resolution


to ensure that the img in the right size and resolution u can use editors like adobe photoshop .


// other softWare :  Adobe Fireworks- Pixelmator -PaintShop -Pro Paint.net
// online edItors: www.photoshop.com - www.pixlr.com-www.splashup.com - www.ipiccy.com.



**Images often come with captions**

```html
<figure>
<img src="images/otters.jpg" alt="Photograph of
two sea otters floating in water">
<br />
<figcaption>Sea otters hold hands when they
sleep so they don't drift away from each
other.</figcaption>
</figure>
```

***


## COLOURS

There are three way to specifie the color text or background : rgbv values & hex code & color name (//There are 147 predefined color)

you can change the opacity using opacity tag

// notes:
//  CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA. 

// CSS3 also allows you to specify colors as HSL values,
//with an optional opacity value. It is known as HSLA.

***

## TEXT

The **font-family** property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.
You can specify a list of fonts separated by commas so that, if the user does not have your first choice of typeface installed, the browser can try to use an alternative font from the list

**font-size**


@font-face allows you to use a font, even if it is not installed on the computer of the person browsing, by allowing you to specify a path to a copy of the font, which will be downloaded if it is not on the user's machine.


```css
@font-face {
font-family: 'ChunkFiveRegular';
src: url('fonts/chunkfive.eot');}
h1, h2 {
font-family: ChunkFiveRegular, Georgia, serif;}
```



```
.credits {
font-weight: bold or normal;}
```

```
.credits {
font-style: italic or bold or oplique;}
```

```
h1 {
text-transform: uppercase;}
h2 {
text-transform: lowercase;}
.credits {
text-transform: capitalize;}
```

```
a {
text-decoration: none or underline or or overline or through or blink ;}
```


In CSS, the **line-height** property sets the height of an entire line of text, so the difference between the **fontsize** and the line-height is equivalent to the leading 

```
{
word-spacing: 1em;}
```

```
h1 {
text-align: left;}
p {
text-align: justify;}
.credits {
text-align: right or centre;}
```

// justify This indicates that every line in a paragraph, except the last line, should be set to take up the full width of the containing box

```
#six-months {
vertical-align: text-top;}
#one-year {
vertical-align: baseline;}
#two-years {
vertical-align: text-bottom;}
```

The text-indent property allows you to indent the first line of text within an element. The amount you want the line indented by can be specified in a number
of ways but is usually given in pixels or ems.

The text-shadow property has become commonly used despite lacking support in all browsers
***


*sources:*
*ducket javascript |*
*ducket HTML CSS*

[HomePage](https://wafaankoush99.github.io/Reading-Notes/READMEcode201.html)  


contact wafadirawe@gmail.com




































