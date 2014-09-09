# xs.malihu-custom-scrollbar-plugin [![spm version](http://spmjs.io/badge/xs.malihu-custom-scrollbar-plugin)](http://spmjs.io/package/xs.malihu-custom-scrollbar-plugin)

---

An awesome spm package!

---

## Install

```
$ spm install xs.malihu-custom-scrollbar-plugin --save
```

## Usage

```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<link rel="stylesheet" href="/dist/xs.malihu-custom-scrollbar-plugin/3.0.4/jquery.mCustomScrollbar.css" />
</head>
<body>

<div id="content" style="width:400px; height: 200px; overflow: hidden;">
	<p>demo1</p>

	<p>demo2</p>

	<p>demo3</p>

	<p>demo4</p>

	<p>demo5</p>

	<p>demo6</p>

	<p>demo7</p>

	<p>demo8</p>

	<p>demo9</p>

	<p>demo10</p>

	<p>demo11</p>

	<p>demo12</p>

	<p>demo13</p>

	<p>demo14</p>

	<p>demo15</p>

	<p>demo16</p>

	<p>demo17</p>

	<p>demo18</p>

	<p>demo19</p>

	<p>demo20</p>
</div>

<script type="text/javascript" src="/sea-modules/seajs/2.3.0/dist/sea.js"></script>

<script type="text/javascript">
	seajs.config({
		base: '/dist/'
	});
</script>

<script type="text/javascript">
	seajs.use('app/1.0.0/index');
</script>

</body>
</html>
```

```js
$ = require('xs.jquery');

require('xs.malihu-custom-scrollbar-plugin')($);

$(function () {
	$('#content').mCustomScrollbar({
		axis: "yx",
		theme: "3d",
		scrollInertia: 200,
		scrollbarPosition: "outside"
	});
});
```
