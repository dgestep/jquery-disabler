jquery-disabler
===============

Disabler can be applied on an HTML container, such as a DIV tag, or on individual UI elements and disable or 
set the contents of the container to read-only and back again.  If acting on an HTML container, the Disabler 
widget performs a deep-dive scan of each element inside the container and disables or marks the element as 
read-only.   When disabled or set to read-only, all events are removed and all clickable elements become not 
clickable.  When enabled or a read-only operation is undone, all removed events are put back and all clickable 
elements that were modified by this plugin regain their click events.

By using special data attributes and CSS classes, pages can instruct the Disabler plugin to hide elements when 
disabling, ignore disable requests on certain elements, and change the element to display as text rather than 
disabling.  Disabler also supports the disabling of all jQuery UI widgets.
