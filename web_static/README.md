# HTML and CSS Basics

This README provides a fundamental overview of HTML (HyperText Markup Language) and CSS (Cascading Style Sheets) concepts for beginners. It covers essential topics that will help you understand web development and create web pages effectively.

## Table of Contents

1. [What is HTML](#what-is-html)
2. [How to Create an HTML Page](#how-to-create-an-html-page)
3. [What is a Markup Language](#what-is-a-markup-language)
4. [What is the DOM](#what-is-the-dom)
5. [What is an Element/Tag](#what-is-an-element-tag)
6. [What is an Attribute](#what-is-an-attribute)
7. [How Does the Browser Load a Webpage](#how-does-the-browser-load-a-webpage)
8. [What is CSS](#what-is-css)
9. [How to Add Style to an Element](#how-to-add-style-to-an-element)
10. [What is a Class](#what-is-a-class)
11. [What is a Selector](#what-is-a-selector)
12. [How to Compute CSS Specificity Value](#how-to-compute-css-specificity-value)
13. [Box Properties in CSS](#box-properties-in-css)

---

### What is HTML

HTML (HyperText Markup Language) is a standard markup language used for creating web pages. It defines the structure and content of a web page using elements and tags. HTML documents are interpreted by web browsers to display text, images, links, and other media on the internet.

### How to Create an HTML Page

To create an HTML page, you need a simple text editor like Notepad or a code editor like Visual Studio Code. You write the HTML code in a `.html` file, save it, and open it in a web browser to view the page.

### What is a Markup Language

A markup language like HTML uses tags to define the structure and content of a document. Tags are enclosed in angle brackets (< >) and provide instructions to web browsers about how to display content.

### What is the DOM

The DOM (Document Object Model) is a programming interface for web documents. It represents the structure of an HTML document as a tree of objects. Developers can use the DOM to manipulate HTML and XML documents dynamically, making web pages interactive.

### What is an Element/Tag

An element or tag is a fundamental building block of an HTML document. It represents various types of content like headings, paragraphs, images, links, and more. Elements are defined by opening and closing tags, e.g., `<p>content</p>`.

### What is an Attribute

Attributes provide additional information about an HTML element. They are always specified in the opening tag and are used to configure or modify an element's behavior or appearance.

### How Does the Browser Load a Webpage

When you enter a URL in a web browser, it sends a request to a web server. The server responds by sending back HTML, CSS, JavaScript, and other assets. The browser then processes these resources, rendering the webpage on your screen.

### What is CSS

CSS (Cascading Style Sheets) is a stylesheet language used to control the presentation and layout of web pages. It allows you to apply styles like colors, fonts, spacing, and positioning to HTML elements.

### How to Add Style to an Element

You can add style to HTML elements by using CSS rules. CSS rules consist of a selector (to target elements) and a declaration block (to define styles). For example:

```css
p {
    color: blue;
    font-size: 16px;
}
```

### What is a Class

A class is a reusable identifier in HTML and CSS. You can assign a class to multiple elements to apply the same styling or behavior to all of them. Classes are defined in HTML using the `class` attribute and selected in CSS with a period, e.g., `.my-class`.

### What is a Selector

A selector is a pattern used to select HTML elements you want to style with CSS. Selectors can target elements by tag name, class, ID, or other attributes. They specify which elements the CSS rules should apply to.

### How to Compute CSS Specificity Value

Specificity is a way to determine which CSS rule takes precedence when multiple rules target the same element. It's based on the selector's components (ID, class, tag name, etc.). A higher specificity value means a rule is more specific.

### Box Properties in CSS

Box properties in CSS control the dimensions and layout of elements. Common box properties include `width`, `height`, `margin`, `padding`, `border`, and `box-sizing`. Understanding these properties is crucial for controlling the size and spacing of elements on a webpage.
