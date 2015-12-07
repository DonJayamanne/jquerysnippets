# jQuery Code Snippets

Over 130 jQuery Code Snippets for JavaScript code.

Just type the letters 'jq' to get a list of all available jQuery Code Snippets.

![Image of Snippets](https://raw.githubusercontent.com/DonJayamanne/jquerysnippets/master/images/snippets.png)

# Snippets

<table>
<tr><td>Trigger</td><td>Description</td><td>Code</td></tr>
<tr style="vertical-align:top">
<td>func</td><td>An anonymous function.</td><td style="white-space:pre">```
function (${param}) {  }
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAfter</td><td>Insert content, specified by the parameter, after each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).after(${content});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAjax</td><td>Perform an asynchronous HTTP (Ajax) request.</td><td style="white-space:pre">```
$.ajax({
    type: "${method}",
    url: "${url}",
    data: "${data}",
    dataType: "${dataType}",
    success: function (response) {
        
    }
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAjaxAspNetWebService</td><td>Perform an asynchronous HTTP (Ajax) request to a ASP.NET web service.</td><td style="white-space:pre">```
$.ajax({
    type: "POST",
    contentType: "application/json; charset=utf-8",
    dataType: "${dataType}",
    url: "${url}",
    data: "${data}",
    success: function (response) {
        
    }
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAppend</td><td>Insert content, specified by the parameter, to the end of each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).append(${content});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAppendTo</td><td>Insert every element in the set of matched elements to the end of the target.</td><td style="white-space:pre">```
$(${content}).appendTo(${selector});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAttrGet</td><td>Get the value of an attribute for the first element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).attr(${attributeName});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAttrRemove</td><td>Remove an attribute from each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).removeAttr(${attributeName});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAttrSet</td><td>Set one or more attributes for the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).attr(${attributeName}, ${value});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAttrSetFn</td><td>Set one or more attributes for the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).attr(${attributeName}, function (index, attr) { 
     
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqAttrSetObj</td><td>Set one or more attributes for the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).attr({
    ${name}: ${value}
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqBefore</td><td>Insert content, specified by the parameter, before each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).before(${content});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqBind</td><td>Attach a handler to an event for the elements.</td><td style="white-space:pre">```
$(${selector}).bind(${eventType}, function (e) {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqBindWithData</td><td>Attach a handler to an event for the elements.</td><td style="white-space:pre">```
$(${selector}).bind(${eventType}, ${eventData}, function (e) {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqBlur</td><td>Bind an event handler to the "blur" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).blur(function (e) { 
    e.preventDefault();
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqChange</td><td>Bind an event handler to the "change" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).change(function (e) { 
    e.preventDefault();
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqClassAdd</td><td>Adds the specified class(es) to each of the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).addClass(${className});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqClassRemove</td><td>Remove a single class, multiple classes, or all classes from each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).removeClass(${className});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqClassToggle</td><td>Add or remove one or more classes from each element in the set of matched elements, depending on either the class's presence.</td><td style="white-space:pre">```
$(${selector}).toggleClass(${className});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqClassToggleSwitch</td><td>Add or remove one or more classes from each element in the set of matched elements, depending on either the class's presence or the value of the switch argument.</td><td style="white-space:pre">```
$(${selector}).toggleClass(${className}, ${switch});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqClick</td><td>Bind an event handler to the "click" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).click(function (e) { 
    e.preventDefault();
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqClone</td><td>Create a deep copy of the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).clone();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqCloneWithEvents</td><td>Create a deep copy of the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).clone(true);
```
</td><tr>
<tr style="vertical-align:top">
<td>jqCssGet</td><td>Get the computed style properties for the first element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).css(${propertyName});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqCssSet</td><td>Set one or more CSS properties for the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).css(${propertyName}, ${value});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqCssSetObj</td><td>Set one or more CSS properties for the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).css({
    ${propertyName}: ${value}
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqDataGet</td><td>Return the value at the named data store for the first element in the jQuery collection, as set by data(name, value) or by an HTML5 data-* attribute.</td><td style="white-space:pre">```
$(${selector}).data(${key});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqDataRemove</td><td>Remove a previously-stored piece of data.</td><td style="white-space:pre">```
$(${selector}).removeData(${element});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqDataSet</td><td>Store arbitrary data associated with the matched elements.</td><td style="white-space:pre">```
$(${selector}).data(${key}, ${value});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqDataSetObj</td><td>Store arbitrary data associated with the matched elements.</td><td style="white-space:pre">```
$(${selector}).data({
    ${key}: ${value}
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqDie</td><td>Remove event handlers previously attached using .live() from the elements.</td><td style="white-space:pre">```
$(${selector}).die(${eventType});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqDieAll</td><td>Remove event handlers previously attached using .live() from the elements.</td><td style="white-space:pre">```
$(${selector}).die();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqDieFn</td><td>Remove event handlers previously attached using .live() from the elements.</td><td style="white-space:pre">```
$(${selector}).die(${eventType}, ${handler});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqDocReady</td><td>Function to execute when the DOM is fully loaded.</td><td style="white-space:pre">```
$(document).ready(function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqDocReadyShort</td><td>Function to execute when the DOM is fully loaded.</td><td style="white-space:pre">```
$(function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqEach</td><td>A generic iterator function, which can be used to seamlessly iterate over both objects and arrays. Arrays and array-like objects with a length property (such as a function's arguments object) are iterated by numeric index, from 0 to length-1. Other objects are iterated via their named properties.</td><td style="white-space:pre">```
$.each(${collection}, function (indexInArray, valueOfElement) { 
     
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqEachElement</td><td>Iterate over a jQuery object, executing a function for each matched element. </td><td style="white-space:pre">```
$(${selector}).each(function (index, element) {
    // element == this
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqEmpty</td><td>Remove all child nodes of the set of matched elements from the DOM.</td><td style="white-space:pre">```
$(${selector}).empty();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqFadeIn</td><td>Display the matched elements by fading them to opaque.</td><td style="white-space:pre">```
$(${selector}).fadeIn();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqFadeInFull</td><td>Display the matched elements by fading them to opaque.</td><td style="white-space:pre">```
$(${selector}).fadeIn(${duration}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqFadeOut</td><td>Hide the matched elements by fading them to transparent.</td><td style="white-space:pre">```
$(${selector}).fadeOut();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqFadeOutFull</td><td>Hide the matched elements by fading them to transparent.</td><td style="white-space:pre">```
$(${selector}).fadeOut(${duration}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqFadeTo</td><td>Adjust the opacity of the matched elements.</td><td style="white-space:pre">```
$(${selector}).fadeTo(${duration}, ${opacity});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqFadeToFull</td><td>Adjust the opacity of the matched elements.</td><td style="white-space:pre">```
$(${selector}).fadeTo(${duration}, ${opacity}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqFind</td><td>Get the descendants of each element in the current set of matched elements, filtered by a selector, jQuery object, or element.</td><td style="white-space:pre">```
$(${selector}).find(${selector2});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqFocus</td><td>Bind an event handler to the "focus" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).focus(function (e) { 
    e.preventDefault();
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqGet</td><td>Load data from the server using a HTTP GET request.</td><td style="white-space:pre">```
$.get("${url}", ${data},
    function (data, textStatus, jqXHR) {
        
    },
    "${dataType}"
);
```
</td><tr>
<tr style="vertical-align:top">
<td>jqGetJson</td><td>Load JSON-encoded data from the server using a GET HTTP request.</td><td style="white-space:pre">```
$.getJSON("${url}", ${data},
    function (data, textStatus, jqXHR) {
        
    }
);
```
</td><tr>
<tr style="vertical-align:top">
<td>jqGetScript</td><td>Load a JavaScript file from the server using a GET HTTP request, then execute it.</td><td style="white-space:pre">```
$.getScript("${url}", function (script, textStatus, jqXHR) {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqHasClass</td><td>Determine whether any of the matched elements are assigned the given class.</td><td style="white-space:pre">```
$(${selector}).hasClass(${className});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqHeightGet</td><td>Get the current computed height for the first element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).height();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqHeightSet</td><td>Set the CSS height of every matched element.</td><td style="white-space:pre">```
$(${selector}).height(${value});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqHide</td><td>Hide the matched elements.</td><td style="white-space:pre">```
$(${selector}).hide();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqHideFull</td><td>Hide the matched elements.</td><td style="white-space:pre">```
$(${selector}).hide(${duration}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqHover</td><td>Bind two handlers to the matched elements, to be executed when the mouse pointer enters and leaves the elements.</td><td style="white-space:pre">```
$(${selector}).hover(function () {
        // over
        
    }, function () {
        // out
    }
);
```
</td><tr>
<tr style="vertical-align:top">
<td>jqHtmlGet</td><td>Get the HTML contents of the first element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).html();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqHtmlSet</td><td>Set the HTML contents of each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).html(${htmlString});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqInnerHeight</td><td>Get the current computed height for the first element in the set of matched elements, including padding but not border.</td><td style="white-space:pre">```
$(${selector}).innerHeight();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqInnerWidth</td><td>Get the current computed inner width for the first element in the set of matched elements, including padding but not border.</td><td style="white-space:pre">```
$(${selector}).innerWidth();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqInsertAfter</td><td>Insert every element in the set of matched elements after the target.</td><td style="white-space:pre">```
$(${target}).insertAfter(${selector});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqInsertBefore</td><td>Insert every element in the set of matched elements before the target.</td><td style="white-space:pre">```
$(${target}).insertBefore(${selector});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqKeyDown</td><td>Bind an event handler to the "keydown" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).keydown(function (e) { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqKeyPress</td><td>Bind an event handler to the "keypress" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).keypress(function (e) { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqKeyUp</td><td>Bind an event handler to the "keyup" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).keyup(function (e) { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqLoadGet</td><td>Load data from the server and place the returned HTML into the matched element.</td><td style="white-space:pre">```
$(${selector}).load("${url}", "${data}", function (response, status, request) {
    this; // dom element
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqLoadPost</td><td>Load data from the server and place the returned HTML into the matched element.</td><td style="white-space:pre">```
$(${selector}).load("${url}", "${data}", function (response, status, request) {
    this; // dom element
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqMap</td><td>Translate all items in an array or object to new array of items.</td><td style="white-space:pre">```
$.map(${arrayOrObject}, function (elementOrValue, indexOrKey) {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqMouseDown</td><td>Bind an event handler to the "mousedown" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).mousedown(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqMouseEnter</td><td>Bind an event handler to be fired when the mouse enters an element, or trigger that handler on an element.</td><td style="white-space:pre">```
$(${selector}).mouseenter(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqMouseLeave</td><td>Bind an event handler to be fired when the mouse leaves an element, or trigger that handler on an element.</td><td style="white-space:pre">```
$(${selector}).mouseleave(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqMouseMove</td><td>Bind an event handler to the "mousemove" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).mousemove(function (e) { 
    // values: e.clientX, e.clientY, e.pageX, e.pageY
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqMouseOut</td><td>Bind an event handler to the "mouseout" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).mouseout(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqMouseOver</td><td>Bind an event handler to the "mouseover" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).mouseover(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqMouseUp</td><td>Bind an event handler to the "mouseup" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).mouseup(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqNamespace</td><td>A namespace template. ref: http://enterprisejquery.com/2010/10/how-good-c-habits-can-encourage-bad-javascript-habits-part-1/</td><td style="white-space:pre">```
(function ( ${name}, $, undefined ) {
    // Private Property
    myPrivateProperty = "Private Property";
        
    // Public Property
    ${name}.myPublicProperty = "Publically Accessible Property";
        
    // Private Method
    function myPrivateMethod () {
        
    }
        
    // Public Method
    ${name}.myPublicMethod = function () {
        
    };  
}(window.${name} = window.${name} || {}, jQuery ));
```
</td><tr>
<tr style="vertical-align:top">
<td>jqOffsetGet</td><td>Get the current coordinates of the first element, or set the coordinates of every element, in the set of matched elements, relative to the document.</td><td style="white-space:pre">```
var offset = $(${selector}).offset();
var top = offset.top;
var left = offset.left;

```
</td><tr>
<tr style="vertical-align:top">
<td>jqOffsetParent</td><td>Get the closest ancestor element that is positioned.</td><td style="white-space:pre">```
var offset = $(${selector}).offsetParent();
var top = offset.top;
var left = offset.left;

```
</td><tr>
<tr style="vertical-align:top">
<td>jqOn</td><td>Attach an event handler function for one or more events to the selected elements.</td><td style="white-space:pre">```
$(${selector}).on(${events}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqOne</td><td>Attach a handler to an event for the elements. The handler is executed at most once per element per event type.</td><td style="white-space:pre">```
$(${selector}).one(${events}, function (e) {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqOneWithData</td><td>Attach a handler to an event for the elements. The handler is executed at most once per element per event type.</td><td style="white-space:pre">```
$(${selector}).one(${events}, ${data}, function (e) {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqOuterHeight</td><td>Get the current computed height for the first element in the set of matched elements, including padding, border, and optionally margin. Returns a number (without "px") representation of the value or null if called on an empty set of elements.</td><td style="white-space:pre">```
$(${selector}).outerHeight(${includeMargin});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqOuterWidth</td><td>Get the current computed width for the first element in the set of matched elements, including padding and border.</td><td style="white-space:pre">```
$(${selector}).outerWidth(${includeMargin});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqPlugin</td><td>Plugin template.</td><td style="white-space:pre">```
(function ($) {
    jQuery.fn.${pluginName} = function (settings) {
        var config = {'foo': 'bar'};
 
        if (settings) jQuery.extend(config, settings);
 
        this.each(function () {
            // element-specific code here
            
        });
 
        return this;
    };
})(jQuery);
```
</td><tr>
<tr style="vertical-align:top">
<td>jqPosition</td><td>Get the current coordinates of the first element in the set of matched elements, relative to the offset parent.</td><td style="white-space:pre">```
var position = $(${selector}).position();
var top = position.top;
var left = position.left;

```
</td><tr>
<tr style="vertical-align:top">
<td>jqPost</td><td>Load data from the server using a HTTP POST request.</td><td style="white-space:pre">```
$.post("${url}", ${data},
    function (data, textStatus, jqXHR) {
        
    },
    "${dataType}"
);
```
</td><tr>
<tr style="vertical-align:top">
<td>jqPrepend</td><td>Insert content, specified by the parameter, to the beginning of each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).prepend(${content});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqPrependTo</td><td>Insert every element in the set of matched elements to the beginning of the target.</td><td style="white-space:pre">```
$(${content}).prependTo(${selector});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqRemove</td><td>Remove the set of matched elements from the DOM.</td><td style="white-space:pre">```
$(${selector}).remove();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqRemoveExp</td><td>Remove the set of matched elements from the DOM.</td><td style="white-space:pre">```
$(${selector}).remove(${expression});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqReplaceAll</td><td>Replace each target element with the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).replaceAll(${target});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqReplaceWith</td><td>Replace each element in the set of matched elements with the provided new content and return the set of elements that was removed.</td><td style="white-space:pre">```
$(${selector}).replaceWith(${newContent});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqResize</td><td>Bind an event handler to the "resize" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).resize(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqScroll</td><td>Bind an event handler to the "scroll" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).scroll(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqScrollLeftGet</td><td>Get the current horizontal position of the scroll bar for the first element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).scrollLeft();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqScrollLeftSet</td><td>Set the current horizontal position of the scroll bar for each of the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).scrollLeft(${value});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqScrollTopGet</td><td>Get the current vertical position of the scroll bar for the first element in the set of matched elements or set the vertical position of the scroll bar for every matched element.</td><td style="white-space:pre">```
$(${selector}).scrollTop();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqScrollTopSet</td><td>Set the current vertical position of the scroll bar for each of the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).scrollTop(${value});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSelect</td><td>Bind an event handler to the "select" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).select(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSelectTrigger</td><td>Bind an event handler to the "select" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).select();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqShow</td><td>Display the matched elements.</td><td style="white-space:pre">```
$(${selector}).show();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqShowFull</td><td>Display the matched elements.</td><td style="white-space:pre">```
$(${selector}).show(${duration}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSlideDown</td><td>Display the matched elements with a sliding motion.</td><td style="white-space:pre">```
$(${selector}).slideDown();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSlideDownFull</td><td>Display the matched elements with a sliding motion.</td><td style="white-space:pre">```
$(${selector}).slideDown(${duration}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSlideToggle</td><td>Display or hide the matched elements with a sliding motion.</td><td style="white-space:pre">```
$(${selector}).slideToggle();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSlideToggleFull</td><td>Display or hide the matched elements with a sliding motion.</td><td style="white-space:pre">```
$(${selector}).slideToggle(${duration}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSlideUp</td><td>Display the matched elements with a sliding motion.</td><td style="white-space:pre">```
$(${selector}).slideUp();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSlideUpFull</td><td>Display the matched elements with a sliding motion.</td><td style="white-space:pre">```
$(${selector}).slideUp(${duration}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSubmit</td><td>Bind an event handler to the "submit" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).submit(function (e) { 
    e.preventDefault();
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqSubmitTrigger</td><td>Bind an event handler to the "submit" JavaScript event, or trigger that event on an element.</td><td style="white-space:pre">```
$(${selector}).submit();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqTextGet</td><td>Get the combined text contents of each element in the set of matched elements, including their descendants.</td><td style="white-space:pre">```
$(${selector}).text();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqTextSet</td><td>Set the content of each element in the set of matched elements to the specified text.</td><td style="white-space:pre">```
$(${selector}).text(${textString});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqToggle</td><td>Display or hide the matched elements.</td><td style="white-space:pre">```
$(${selector}).toggle();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqToggleFull</td><td>Display or hide the matched elements.</td><td style="white-space:pre">```
$(${selector}).toggle(${duration}, function () {
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqToggleSwitch</td><td>Display or hide the matched elements.</td><td style="white-space:pre">```
$(${selector}).toggle(${showOrHide});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqTrigger</td><td>Execute all handlers and behaviors attached to the matched elements for the given event type.</td><td style="white-space:pre">```
$(${selector}).trigger(${eventType});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqTriggerHandler</td><td>Execute all handlers attached to an element for an event.</td><td style="white-space:pre">```
$(${selector}).triggerHandler(${eventType});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqTriggerHandlerWithData</td><td>Execute all handlers attached to an element for an event.</td><td style="white-space:pre">```
$(${selector}).triggerHandler(${eventType}, { ${name}: ${value} });
```
</td><tr>
<tr style="vertical-align:top">
<td>jqTriggerWithData</td><td>Execute all handlers and behaviors attached to the matched elements for the given event type.</td><td style="white-space:pre">```
$(${selector}).trigger(${eventType}, { ${name}: ${value} });
```
</td><tr>
<tr style="vertical-align:top">
<td>jqUnbind</td><td>Remove a previously-attached event handler from the elements.</td><td style="white-space:pre">```
$(${selector}).unbind(${eventType});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqUnbindAll</td><td>Remove a previously-attached event handler from the elements.</td><td style="white-space:pre">```
$(${selector}).unbind();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqUnload</td><td>Bind an event handler to the "unload" JavaScript event.</td><td style="white-space:pre">```
$(${selector}).unload(function () { 
    
});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqValGet</td><td>Get the current value of the first element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).val();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqValSet</td><td>Set the value of each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).val(${value});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqWidthGet</td><td>Get the current computed width for the first element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).width();
```
</td><tr>
<tr style="vertical-align:top">
<td>jqWidthSet</td><td>Set the CSS width of each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).width(${value});
```
</td><tr>
<tr style="vertical-align:top">
<td>jqWrap</td><td>Wrap an HTML structure around each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).wrap("<${wrappingElement}></${wrappingElement}>");
```
</td><tr>
<tr style="vertical-align:top">
<td>jqWrapAll</td><td>Wrap an HTML structure around all elements in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).wrapAll("<${wrappingElement}></${wrappingElement}>");
```
</td><tr>
<tr style="vertical-align:top">
<td>jqWrapInner</td><td>Wrap an HTML structure around the content of each element in the set of matched elements.</td><td style="white-space:pre">```
$(${selector}).wrapInner("<${wrappingElement}></${wrappingElement}>");
```
</td><tr>
</table>

## Source

[Github](https://github.com/DonJayamanne/jquerysnippets)

All snippets have been taken from the [Visual Studio 2015 jQuery Code Snippets Extension](https://github.com/kspearrin/Visual-Studio-jQuery-Code-Snippets). Credit given where due.
        
## License

[MIT](https://raw.githubusercontent.com/DonJayamanne/jquerysnippets/master/LICENSE)
