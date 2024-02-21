## HTML

 * **HyperText Markup Language** (HTML) is the most basic building block of the web. It defines the meaning & structure of web content.
 * "Hypertext" refers to links that connect web pages to one another, either within a single website or between websites.
 * HTML uses "markup" to annotate text, images & other content for display in a Web browser.
 * HTML markup includes special "elements" such as `<head>`, `<title>`, `<body>`, `<header>`, `<footer>`, `<article>`, `<section>`, `<div>`, `<p>`, `<img>` and many others.

## Instruction

 * Named every HTML file into **lowercase (without any space)**, we can use **hyphen (-)**.
 * Every HTML file start with `<html>` & end with `</html>` elements.

 * To directly open our HTML file result, We will use a vscode extention called "live server", which will show us real-time changes in browser whichever we made into our program.
 * We can use this extention by Pressing `Right Click` & selecting **Open With Live Server** (it will open our HTML document into browser & show us its real-time changing effects).
 
 * To know, if we have errors in our web page or not, We can see it on a **Markup Validation Service** (https://validator.w3.org/) website, & select **Validate by File Upload**, then choose our HTML file & click on `Check`.
 * If we had made some errors, it'll show us as an error & a warning.

 * It can show a warning as, **Consider adding a `lang` attribute to the `html` start tag to declare the language of this document**, basically its showing to add language in which our web page is, which can be solve by add `lang="en"` in html element, like `<html lang="en">`, **en** represent English language.
 * It can show an error as, **The character encoding was not declared, Proceeding using `windows-1252`**, its showing to add Character Encoding in which our web page is, which can be solve by add metadata of chacter-set as `charset="UTF-8"` in meta element, like `<meta charset="UTF-8">`, **UTF-8** is one of Character Encoding Types.
 * It can show an error as, **Start tag seen without seeing a doctype first, Expected `<!DOCTYPE html>`**, this should have in each HTML document. We have to add it in each program before `<html>` element.

## `<head>...</head>`

 * This element contains such details which are not shown on our web page. For example, metadata, title, etc.
 * Here `<style>...</style>` element is use for changing background color, text color & size of font (generally, it's part of **CSS**).

## `<body>...</body>`

 * Everything we see on a web page, it's mention in this element. For example, heading, paragraph, image, etc.
 * `<h1>...</h1>` is used for write a Heading Text on Web Page.
 * `<p>...</p>` is used for writing a Paragraph on Web Page.