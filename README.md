## Install

```
npm install x-flex
```

```
bower install x-flex
```

## Browser Support

See the [tests](http://aaronshaf.github.io/x-flex/tests/).

 | [IE 10](http://msdn.microsoft.com/en-us/library/ie/hh673531%28v=vs.85%29.aspx) | IE 11 | FF 25 | FF 26 | Ch 31 | Ch 32 | Sf 6 | Sf 7
--- | --- | --- | --- | --- | --- | --- | --- | ---
.flex-x | ✓ | ✓ | ✓ |  ✓| ✓ | ✓ | ✓ | ✓
.flex-row | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓
[.flex-row-reverse](http://jsbin.com/EHILoMUG/1/edit?html,css,output) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓
.flex-column | ✓<sup>1</sup> | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓
[.flex-column-reverse](http://jsbin.com/eGiHizE/1/edit?html,css,output) | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓
.flex-order-x | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓
.flex-nowrap |   |   |   |   |   |   |   |  
[.flex-wrap](http://jsbin.com/eyOSOhEK/2/edit?html,css,output) |   |   |   |   |   |   |   |  
[.flex-wrap-reverse](http://jsbin.com/oMepIziL/1/edit?html,css,output) |   |   |   |   |   |   |   |  

### Heads up

1. Container requires explicit `height` or `top`/`bottom` property if it has flexed children.

## Further reading

* [2009 spec](http://www.w3.org/TR/2009/WD-css3-flexbox-20090723/) (w3.org)
* [2011 spec](http://www.w3.org/TR/2011/WD-css3-flexbox-20111129/)
* [2012 spec](http://www.w3.org/TR/css3-flexbox/) (latest)
* [“Old” Flexbox and “New” Flexbox](http://css-tricks.com/old-flexbox-and-new-flexbox/) (css-tricks.com)
* [Compatibility Table for Flexible Box Layout Module](http://caniuse.com/#feat=flexbox) (caniuse.com)
* [Some flex bugs in IE11](http://codepen.io/lerouxb/pen/jIkpD) (codepen.io)
* [A Complete Guide to Flexbox](http://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [Solved by Flexbox](http://philipwalton.github.io/solved-by-flexbox/)
