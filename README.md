# day2-task

window object:-
window is the first thing thats get loaded into a browser.it has properties like length, innerWidth, innerHeight, name, if it has been closed, its parents, and more.
The window object is the topmost object of the DOM hierarchy.
syntax:
window.property_name;

document object:-
The document actually gets loaded inside the window object and has properties available to it like title, URL, cookie, etc.The document  is your html, aspx, php, or other document that will be loaded into the browser.by accessing document object we can access the the elements in the html page

syntax:
document.property_name;
          
   
                  Document  object                                         window object
         -It is loaded inside window                           -it is the first object loaded in the window
         
         -object of window property                            -object of the browser

         -We can access the document from a                    -We can access the window from the window only.
          window using the window. document     
          
         -example                                               -example
           document.url (returns the url of                       window.close() (it closes the
                         the document)                                            the current window)
          
           document.head (returns head element                    window.outerwidth (returns the width of the 
                           of document)                                               outside of the browser window)
