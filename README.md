# jquery-swipe

a lightweight, mobile only, swipe plugin with jquery.

## Demo
- http://xiangming.github.io/jquery-swipe/

## Installation

### bower
```bash
bower install jquery-swipe --save
```

### manual

donwload the min file to your project, and link
```javascript
<script type="text/javascript" src="jquery.swipe.min.js"></script>
```

## Basic Usage
Include the latest jQuery library and `jquery.swipe.js`

````html
<div id="swipebox">Swipe Here!</div>
````

```javascript
$(function(){
    $('#swipebox')
        .swipeEvents()
        .bind("swipeLeft",  function(){ $('#swipebox').html("Swipe Left"); })
        .bind("swipeRight", function(){ $('#swipebox').html("Swipe Right"); })
        .bind("swipeDown",  function(){ $('#swipebox').html("Swipe Down"); })
        .bind("swipeUp",    function(){ $('#swipebox').html("Swipe Up"); });
});
```
