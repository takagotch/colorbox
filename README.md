### colorbox
---
https://github.com/jackmoore/colorbox

```
npm install jquery-colorbox
```

```js
$(selector).colorbox({key:value, key:value, key:value});

$('a.gallery').colorbox({rel:'gal'});
$('a#login').colorbox();
$.colorbox({href:"thankyou.html"});
$.colorbox({html:"<h1>Welcome</h1>"});
$().colorbox({rel: 'gal', title: function(){
  var url = $(this).attr('href');
  return '<a href="' + url + '" target="_blank">Open In New Window</a>';
}});
```

```
```

