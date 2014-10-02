SpyScroller
===========

```
var sections = document.querySelectorAll('[class*="controls"]');
    SpyScroller.addItems(sections);
    document.addEventListener(SpyScroller.EVENTS.CHANGE,function(event){
      console.log(event.details.item);
    });
```
