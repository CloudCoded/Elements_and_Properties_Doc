/*** The CSS property I learned Today 20th feb***/


(element or tag)::marker{
    content: '+ ';
    .....
} => This pseudo-element selects the marker box of a list item, which typically contains a bullet or number. it works on any element or pseudo-element set to display: list-items, such as the <li> and <summary> elements

:visited{
    color: ...;
} => It applies once the link has been visited by the user. For privacy reasons, the sytles that can be modified using this selector are very limited. It applies only <a> and <area> elements that have an href attribute