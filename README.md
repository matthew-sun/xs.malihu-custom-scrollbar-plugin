# xs.malihu-custom-scrollbar-plugin [![spm version](http://spmjs.io/badge/xs.malihu-custom-scrollbar-plugin)](http://spmjs.io/package/xs.malihu-custom-scrollbar-plugin)

---

An awesome spm package!

---

## Install

```
$ spm install xs.malihu-custom-scrollbar-plugin --save
```

## Usage

```js
var $ = require('jquery');

require('xs.malihu-custom-scrollbar-pluginr')($);

$(function(){
	$('#content').mCustomScrollbar({
		axis: "yx",
		theme: "3d",
		scrollInertia: 200,
		scrollbarPosition: "outside"
	});
});
```
