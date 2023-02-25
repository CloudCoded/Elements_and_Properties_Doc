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