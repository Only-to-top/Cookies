# Cookies

```js
var cookieOptions = { expires: 7, path: '/' };
if ($.cookie('visit') == undefined) {
    setTimeout(function () {
        $.cookie('visit', true, cookieOptions);
        $.fancybox.open({
            src: '#firstModal',
            type: 'inline',
            modal: true,
        });
    }, 4000);
};
```
