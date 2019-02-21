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
```

# Box Model

![CSS Box Model](cssboxmodel.png)
