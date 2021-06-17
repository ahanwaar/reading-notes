# Design web pages with CSS
## What is CSS?
CSS (Cascading Style Sheets) allows you to create great-looking web pages.

## What is CSS for?
- Changing the color and size of headings and links.
- Create layout — for example turning a single column of text into a layout with a main content area and a sidebar for related information.
- Adding Effects such as animation. 

## What is CSS rule?
![text](https://puzzleweb.ru/en/images/css/1_1.png)

## Three Ways to Insert CSS
- External CSS
- Internal CSS
- Inline CSS

### External CSS
- With an external style sheet, you can change the look of an entire website by changing just one file!
- An external style sheet can be written in any text editor, and must be saved with a .css extension.
- The external .css file should not contain any HTML tags.
- Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section, such as the following:

```
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

### Internal CSS
- An internal style sheet may be used if one single HTML page has a unique style.
- The internal style is defined inside the <style> element, inside the head section, such as the followong:
  
  
```
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: linen;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
  
  
### Inline CSS
- An inline style may be used to apply a unique style for a single element.
- To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
  
 ```
<!DOCTYPE html>
<html>
<body>

<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>

</body>
</html>
```
  
  
## CSS Cheat sheet
![text](https://www.theblogmarket.co/wp-content/uploads/2014/11/css-cheat-sheet.png)

 
  
  
  

