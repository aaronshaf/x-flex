## Install

```
npm install x-flex
```

```
bower install x-flex
```

## Browser Support

### Fully supported

* .flex-x
* .flex-order-x
* .flex-row
* [.flex-row-reverse](http://jsbin.com/EHILoMUG/1)
* .flex-column
* [.flex-column-reverse](http://jsbin.com/eGiHizE/1)
* [.align-items-start](http://jsbin.com/ijorizo/1)
* [.align-items-end](http://jsbin.com/ayULeBE/2/)
* [.align-items-center](http://jsbin.com/epIGugO/2/)
* [.align-items-baseline](http://jsbin.com/AWOLUjEZ/1)
* [.align-items-stretch](http://jsbin.com/uzOWOdoP/1)
* [.align-self-start](http://jsbin.com/obibEzE/1/)
* [.align-self-end](http://jsbin.com/AXOlUco/1/)
* [.align-self-center](http://jsbin.com/IWOtadoL/1/)
* [.align-self-baseline](http://jsbin.com/eKAfiHa/1/)
* [.align-self-stretch](http://jsbin.com/OcUjiCeB/1/)

Heads up: In IE10, .flex-column container requires explicit `height` or `top`/`bottom` property if it has flexed children.

### Partially supported

 | [IE 10](http://msdn.microsoft.com/en-us/library/ie/hh673531%28v=vs.85%29.aspx) | IE 11 | FF 25 | FF 26 | Ch 31 | Ch 32 | Sf 6 | Sf 7
--- | --- | --- | --- | --- | --- | --- | --- | ---
[.flex-wrap](http://jsbin.com/eyOSOhEK/2) | ✓ | ✓ | [✗](https://bugzilla.mozilla.org/show_bug.cgi?id=702508) | [✗](https://bugzilla.mozilla.org/show_bug.cgi?id=702508) | ✓ | ✓ | ✗ | ✓
[.flex-wrap-reverse](http://jsbin.com/oMepIziL/1) | ✓ | ✓ | [✗](https://bugzilla.mozilla.org/show_bug.cgi?id=702508) | [✗](https://bugzilla.mozilla.org/show_bug.cgi?id=702508) | ✗ | ✓ | ✗ | ✗
[.align-content-start](http://jsbin.com/UbaGiMAv/1/) | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓
[.align-content-end](http://jsbin.com/IBUpufA/1/) | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✓ | ✓
[.align-content-center](http://jsbin.com/afEYAGA/1/) | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓
[.align-content-space-between](http://jsbin.com/esIHijIv/1/) | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓
[.align-content-space-around](http://jsbin.com/upuRoxEN/1/) | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓
[.align-content-stretch](http://jsbin.com/IHeweLi/1/) | ✓ | ✓ | ✗ | ✗ | ✓ | ✓ | ✗ | ✓

## Further reading

* [2009 spec](http://www.w3.org/TR/2009/WD-css3-flexbox-20090723/) (w3.org)
* [2011 spec](http://www.w3.org/TR/2011/WD-css3-flexbox-20111129/)
* [2012 spec](http://www.w3.org/TR/css3-flexbox/) (latest)
* [“Old” Flexbox and “New” Flexbox](http://css-tricks.com/old-flexbox-and-new-flexbox/) (css-tricks.com)
* [Compatibility Table for Flexible Box Layout Module](http://caniuse.com/#feat=flexbox) (caniuse.com)
* [Some flex bugs in IE11](http://codepen.io/lerouxb/pen/jIkpD) (codepen.io)
* [A Complete Guide to Flexbox](http://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Solved by Flexbox](http://philipwalton.github.io/solved-by-flexbox/)
