/*** The CSS property I learned Today 20th feb***/


(element or tag)::marker{
    content: '+ ';
    .....
} => This pseudo-element selects the marker box of a list item, which typically contains a bullet or number. it works on any element or pseudo-element set to display: list-items, such as the <li> and <summary> elements

:visited{
    color: ...;
} => It applies once the link has been visited by the user. For privacy reasons, the sytles that can be modified using this selector are very limited. It applies only <a> and <area> elements that have an href attribute

sr-only class => You can use CSS to make elements with this class completely hidden from the visual page, but still be announced by screen readers.
The span[class~="sr-only"] selector will select any "span" element whose "class" includes "sr-only".

The :not() pseudo-selector is used to target all elements that do not match the selector - in this case, any of your span elements that do not have the sr-only class.

The [attribute="value"] selector targets any element that has an attribute with a specific value.

clip => This CSS property is used to define the visible portions of an element.
The clip-path => This property determines the shape the clip property should take

The :first-of-type pseudo-selector => is used to target the first element that matches the selector. 
The :last-of-type pseudo-selector => does the exact opposite - it targets the last element that matches the selector

Justify the content to the end of the flex direction, and make the element sticky => justify-content: flex-end;
          position: sticky;

The calc() function is a CSS function that allows you to calculate a value based on other values. For example, you can use it to calculate the width of the viewport minus the margin of an element:
.example {
  margin: 10px;
  width: calc(100% - 20px);
}

The :nth-of-type() pseudo-selector is used to target specific elements based on their order among siblings of the same type.

An absolute position takes the element out of that top-down document flow and allows you to adjust it relative to its container

The z-index property is used to create "layers" for your HTML elements

The ::before selector creates a pseudo-element which is the first child of the selected element, while the ::after selector creates a pseudo-element which is the last child of the selected element. These pseudo-elements are often used to create cosmetic content, which you will see later in this project.

The content property is used to set or override the content of the element. By default, the pseudo-elements created by the ::before and ::after pseudo-selectors are empty, and the elements will not be rendered to the page. Setting the content property to an empty string "" will ensure the element is rendered to the page while still being empty.

The @media at-rule, also known as a media query, is used to conditionally apply CSS. Media queries are commonly used to apply CSS based on the viewport width using the max-width and min-width properties.


Logical operators can be used to construct more complex media queries. The and logical operator is used to query two media conditions.

For example, a media query that targets a display width between 500px and 1000px would be:

@media (min-width: 500px) and (max-width: 1000px){

}


To use a variable, put the variable name in parentheses with var in front of them like this: var(--variable-name). Whatever value you gave the variable will be applied to whatever property you use it on.


variables are often declared in the :root selector. This is the highest level selector in CSS; putting your variables there will make them usable everywhere

Variables are primarily used with colors

z-index => The z-index CSS property sets the z-order of a positioned element and its descendants or flex items. Overlapping elements with a larger z-index cover those with a smaller one.