Timepicker for Twitter Bootstrap 3.x
=======

A simple timepicker component for Twitter Bootstrap.

PS: do not use minified version for now.


## Common Issues

#### Q: Modal dialog covers the timepicker when used inside some modal content
A: When the timepicker field has to be loaded inside some modal dialog content, change the template for timepicker to modal. 
````
 $('#timepicker-24hr').timepicker({
    template: 'modal',
  });
  ````
  
