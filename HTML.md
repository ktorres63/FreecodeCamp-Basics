+ The fieldset element is used to group related  inputs and labels together in a web form. fieldset elements are **block-level elements** meaning that they appear on a new line 
+ There's another way to associate an input element's text with the element itself. You can next the test within a label element and add a for attribute with the same value as the input element's id attribute
```<input id ="loving" type="checkbox"><label for="loving">Loving</label>```
+ All pages should begin with <!DOCTYPE html> this special string is known as a declaration and esures the browser tries to meet industry-wide specifications
+ You can set browser behavior by adding self-closing meta elements in the head, Tell the browser to parse the markup into multiple languages by creating a meta element as a child of the head element
```<meta attribute ="value">```
* You can add style to an element by specifying it in the style element and setting a property for it like this
```html
element{
	property: value;
}
```
+ You can add the same group of styles to many elements by creating a list of selectors. Each selector is seprarated with commas like this
```css
selector1, selector2{
	property: value;
}
```


+ For the styling of the page to look simillar on mobile as it does on a desktop or laptop, you need to add a meta element with a special content attribute
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```
+ The div element is used mainly for design layout purposes unlike the other content elements you have used to far
+ Comments in css look like this
```css
/* comment here */
```
+ If you want to center the div horizontally. You can do this by setting its margin-left and margin-right properties to auto.

```css
div{
	margin-left:auto;
	margin-right:auto;
}
 ```
+ So far you have been using type selectors to stye elements. A class selector is defined by a name with a dot directly in front of it, like this
```css
.class-name{
	styles
}
```
+ To apply the class's styling to the div element, add a class attribute to the div element's opening tag and set its value to menu
```<div class="menu">```

+ You coul use an image forthe background of the page with background-image property and set its value to url(https://....jpg)
```css
body {
	background-image:url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg)
}
```


+ article elements commonly contain multiple elements that have related information. 
+ you can style all the p elements nested anywhere in elements with a class named item like this:
```css
.item p{}
```
* If you want to show p elements in the same line you should use 
```css
.item p{
	display:inline-block;
}
```

We can use padding instead padding-left,padding right, padding-top,padding-bottom

```css
.menu{
	padding-left: 20px;
	padding-right: 20px;
	padding-top: 20px;
	padding-bottom: 20px;
}
```

```css
.menu{
	padding: 20px;
}
```

We can use an hr element to display a divider between sections of different content
```<hr>```

To reduce the gaps between p elements we use 
```css
.item p{
	margin-top: 5px;
	margin-bottom: 5px;
}
```






