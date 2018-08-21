# click-outside-an-element-to-trigger-an-event (jQuery)
if we click anywhere on page except a particular  section (div) , an event will be triggered. Used mainly for dismissing modal popup

<code>
$(document).click(function(e) {
if (!$(event.target).closest(".className").length) {
 //event goes here
}
});
 </code>
