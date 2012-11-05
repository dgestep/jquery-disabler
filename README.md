jquery-disabler
===============

You may think that disabling elements on an HTML page is as simple as assigning <code>disabled="disabled"</code> to every 
element or by invoking a jQuery selector such as <code>$("input").attr("disabled","disabled");</code>, 
but it's not that simple.  What about links or click events assigned to DIV's or tables?  When disabling content on a page, 
you may not want those links or clickable elements to function anymore.  Or... maybe instead of disabling your page, you would rather
have a display-only version of the contents of your page without having to write two versions of your page; one read-only and the other not.
This is where the jQuery Disabler widget can help you out. 

The jQuery Disabler widget can be applied on an HTML container (such as a DIV tag) or on individual UI elements and disable or 
set the contents of the container to read-only, and back again.  If acting on an HTML container, the Disabler 
widget performs a deep-dive scan (evaluates descendants of descendants) of each element inside the container and disables or sets the element as 
read-only. When disabled or set to read-only, all events are removed from the elements and those elements that
usually respond to clicks (such as hyperlinks) become unresponsive.  When an enabled or a read-only operation is undone, 
all removed events are put back and all elements that usually respond to clicks become responsive again.

By using special data attributes and CSS classes, pages can instruct the Disabler plugin to hide elements when 
disabling, ignore disable requests on certain elements, and change the element to display as text rather than 
disabling.  Disabler also includes support for all of the jQuery UI widgets.

The jQuery Disabler widget is open source and can be downloaded from my GitHub page.  You are free to use it as-is or you can
download it and modify it for your own use cases.

