###Data Type for MAPS _(theme)_

1. ROADMAP
2. SATELITE
3. TERRAIN
4. ROADMAP + SATELITE
5. ROADMAP + TERRAIN

###Controlling using the Buttons

1. Zoom
2. Pan
3. MapType
4. Scale
5. Street View
6. Rotate
7. Overview Map

####Summary of ajax response

```javascript
$.ajax({
	data: {lat: '1', lan: '2'},
	type: POST,
	url: "http://localhost/gis/haloajax.php",
	success: function(result){
		$("#div1").html(result);
	}
});
```

```php
<?php echo 'Lat: '.$_REQUEST('lat').' '.'Lan: '.$REQUEST('lan'); ?>
```
