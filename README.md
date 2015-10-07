# IE-polyfill-
A collection of polyfill for Internet Explorer
### addEventListener-polyfill.js
It's a polyfill to avoid the lack of *addEventListener* method on IE8. It simply override the method and you can easily use it in all browser you want!

**USAGE**

Standard usage
```javascript
element.addEventListener("mouseover", callback)
```

### getElementsByClassName-polyfill.js
It's a polyfill to avoid the lack of *getElementsByClassName* method on IE8. It is based on *querySelectorAll* feature.
> querySelectorAll Internet Explorer 8 only supported CSS2 selectors.

**USAGE**

```javascript
document.getElementsByClassName('my-css-class')
```
or it can be used with more than 1 class
```javascript
document.getElementsByClassName('my-css-class my-other-class')
```
