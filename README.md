# getmdl-file

File for material-design-lite.

## Example

### head

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<link rel="stylesheet" href="https://code.getmdl.io/1.2.1/material.indigo-pink.min.css">
<link rel="stylesheet" href="/src/css/getmdl-file.css">

<script defer src="https://code.getmdl.io/1.2.1/material.min.js"></script>   
<script defer src="/src/js/getmdl-file.js"></script>
```

### body

```html
<div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label mdl-textfield--file">
	<input class="mdl-textfield__input" id="file" type="text" disabled>
	<label class="mdl-textfield__label" for="file">File</label>
	<div class="mdl-button mdl-button--primary mdl-button--icon mdl-button--file">
		<i class="material-icons">attach_file</i><input type="file" name="file">
	</div>
</div>
```
