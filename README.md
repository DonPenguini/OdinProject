# OdinProject

## HTML

    -type ! on the first line on github to get the boilerplate

    -for comments, we could use the shortcut ctrl + / 

    -The HTML <"mark"> element defines text that should be marked or highlighted

    -The HTML <"del"> element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:

    -The HTML <"sub"> element defines subscript text. 

    -The HTML <"sup"> element defines superscript text

    -In the anchor tag, put target="_blank_" with rel="noopener noreferrer".(for opening in a new page)

     The noopener value prevents the opened link from gaining access to the webpage from which it was opened.
     The noreferrer value prevents the opened link from knowing which webpage or resource has a link (or 
     ‘reference’) to it. It also includes the noopener behaviour and thus can be used by itself as well.

     Why do we need this added behaviour for opening links in new tabs? Security reasons. The prevention of 
     access that is caused by noopener prevents phishing attacks where the opened link may change the original
     webpage to a different one to trick users. This is referred to as tabnabbing. Adding the noreferrer 
     value can be done if you wish to not let the opened link know that your webpage links to it.

## CSS

-We can add multiples classes to a single element as a space-separated list, such as           class="alert-text severe-alert". Since whitespace is used to separate class names like this, you should never use spaces for multi-worded names and should use a hyphen instead. But elements can only have one ID and cannot be repeated on a single page and should not contain any whitespace.
-For class Selectors, use '.' and for ID selectors, use '#'
