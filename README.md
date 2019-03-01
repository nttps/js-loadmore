# js Function Button Load more..
[![StyleCI](https://github.styleci.io/repos/173066745/shield?branch=master)](https://github.styleci.io/repos/173066745)

****JS Button Load more****


### Including files:

```html
<script src="../dist/btnloadmore.min.js"></script>
```

### How to use

You need to do is call the plugin inside a $(document).ready function:


```html
<div class="contents">
    <div> 1 </div>
    <div> 2 </div>
    <div> 3 </div>
    <div> 4 </div>
    <div> 5 </div>
    <div> 6 </div>
    <div> 7 </div>
    <div> 8 </div>
    <div> 9 </div>
</div>
```

```javascript
$(document).ready(function(){
    $('.contents').btnLoadmore();
});
```

### Options

```javascript
$('.contents').btnLoadmore({
    showItem : 2,
    whenClickBtn : 1,
    textBtn : 'Load more ...'
});

```

### Method
 * `showItem` : set number for show element.
 * `whenClickBtn` : set number for show element when click button.
 * `textBtn` : set text on click button.
 * `classBtn` : set custom class button  .
 
