# **CSS**

1. **What is CSS**
        - *(Cascading Style Sheets) allows you to create great-looking web pages*
2. **CSS Syntax**
        - *CSS is a rule-based language — you define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page*
        - Selector *HTML element*
        - Declarations *uses curly braces {}, which take the form of properties and values. Before the colon we have property and after the colon we have value*
        - Values *can be color or font-size*
        - 
3. **CSS Modules**
        - CSS Specifications - *All web standards technologies (HTML, CSS, JavaScript, etc.) are defined in giant documents called specifications (or "specs")*
        - Browser support information - *Once CSS has been specified then it is only useful for us in developing web pages if one or more browsers have implemented it. This means that the code has been written to turn the instruction in our CSS file into something that can be output to the screen.*
        - Browser compatibility - *The browser support status is shown on every MDN property page in a section named "Browser compatibility".*

## **How to add CSS**

 **3 ways to insert CSS**
        - External CSS - *Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.*
        - Internal CSS - *The internal style is defined inside the  style element, inside the head sdTo use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.*
        - Multiple Style Sheets - *If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.*
        - Cascading Order - *All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority. So, an inline style has the highest priority, and will override external and internal styles and browser defaults.*

## **CSS color Property**

- **Example** body {
    color: red;
}

- color *(Specifies the text color)*
- initial *(Sets this property to its default value)*
- inherit *(Inherits this property from its parent element)*

- **Example**
body {color: rgb(201, 76, 76);}


## [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

## [Myers Web Reset Stylesheet](https://meyerweb.com/eric/tools/css/reset/)
