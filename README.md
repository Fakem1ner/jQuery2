# jQuery 2 - jQuery without all the extras - for those who know JavaScript and want to simplify their work.

## Functions
### $(selector)
Gets all objects on the page by selector and returns them in AdvancedObject format

#### Examples
$('.class') - gets all objects with class '.class'
$('#id') - gets all objects with id '#id'

### .get()
Returns a collection of elements in default format

#### Examples
$('.class').get() - gets all objects with class '.class' is default format

### .event(event, function(item) {})
Adds an event to all objects and calls a function on it. Inside the function, you can access the item variable

#### Examples
$('.class').event('click', function(item) {
  // some actions with item by click
});

### .continue(function(item) {})
Executes some code for each objects

#### Examples
$('.class').continue(function(item) {
  // some actions with item
});
