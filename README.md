<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
	<title>урок_2</title>
</head>
<body>

<script type="text/javascript">

var xhr = new XMLHttpRequest();
xhr.open('GET', 'https://dl.dropboxusercontent.com/u/53408179/phones.json', false);
xhr.send();
if (xhr.status != 200) {
alert('ошибка');
} else {
JSON.parse(xhr.responseText) = new obj{};
document.write (obj.name);
}

</script>
</body>
</html>
