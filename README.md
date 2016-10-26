# Image upload Preview

#### A light and easy use of preview a image uploaded. 

## Usage

simply include `imgUploader.js` then 

```javascript
imgUploader.listen('#uploader');
```

for example

```html
<input id="uploader" type="file">
<div id="preview"></div>

<script src="imgUploader.js"></script>
<script>
imgUploader.config({ prvBox:'preview' })
	       .listen('#uploader');
</script>
```

we can put our preview box any where just give it a class or id.

![show](http://o6x2vif88.bkt.clouddn.com/preview-uploader.png)

## More configurations

You can use `config()` to customalize your preview box.

```html
<script>
imgUploader.config({
    prvBox: 'J_preview',
    width: 200,
    height: 200,
    isAbsPosition: true
}).listen('#uploader');
</script>
```

Attribute `isAbsPostion`  means whether to use absolute positioning(set it 'true' to have higher a performance but make the preview box to be a absolute position box).

welcome pr to improve this project & enjoy it.

## LISENCE
MIT