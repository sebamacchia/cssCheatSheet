# cssCheatSheet

The most complete and compact CSS cheat sheet in the entire world!

# Adding CSS methods

## Inline style

direct in the html (NO!)

```html
<tag style="property: value;"></tag>
```

## Embedded Style

```html
<head>
  <style type="text/css">
    selector {
      property: value;
    }
  </style>
</head>
```

## External Style Sheet

```html
<head>
  <link rel="stylesheet" type="text/css" href="style.css" />
</head>
```

# Syntax

```css
selector {
  property: value;
  }
}
```

# Selectors

```css
*  /* all elements */
tag  /* all tag elements */
tag *  /* all tag elements within tag */
tag tag2 /* all tag2 elements within tag */
tag, tag2 /* all tag and tag2 elements*/
tag > tag2 /*tag2 is a child of tag*/
tag + tag2 /*tag2 preceded by tag*/
.class /*Elements with class ‘class’*/
tag.class /*All tags with class ‘class’*/
#id /*Element with id ‘id’*/
tag#id /*Tag with id ‘id’*/
```

# Pseudo-selectors

```css
:active /*Adds style to active element*/
:after /*Adds content after element*/
:before /*Ads content before element*/
:first­-child /*Adds style to first child*/
:first-letter /*Adds style to first character*/
:first-line /*Adds style to first line*/
:focus /*Adds style to focused element*/
:hover /*Adds style when mouse is over*/
:link /*Adds style to unvisited link*/
:visited /*Adds style to visited link*/
```

# Box Model

![CSS Box Model](cssboxmodel.png)

# Boxes

```css
margin
    margin-top
    margin-right
    margin-bottom
    margin-left

padding
    padding-top
    padding-right
    padding-bottom
    padding-left

border
    border-top
    border-right
    border-bottom
    border-left

border-color
    border-top-color
    border-right-color
    border-bottom-color
    border-left-color

```
