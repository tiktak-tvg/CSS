## Цвет текста с помощью имен цветов HTML.
#### Стиль подключается при помощи атрибута style и раскрашиваем по тегам.

```
<!DOCTYPE html>
<head>
<meta charset="UTF-8">
<title>Document</title>
</head>
<body>
	<h1 style="color:DarkGreen;">Как задать цвет текста с помощью названий цветов HTML?</h1>
	<h2 style="color:DarkRed;">Добавьте атрибут стиля к текстовому элементу, который вы хотите раскрасить.</h2>
	<h3 style="color:DarkBlue;">Вы можете использовать более чем 140 именованных цветов.</h3>
</body>
</html>
```
#### Стиль подключается при помощи атрибута style.
```
<!DOCTYPE html>
<head>
<meta charset="UTF-8">
<title>Document</title>
<style>
h1 {
    color:DarkGreen;
}
h2 {
    color:DarkRed;
}
h3 {
    color:DarkBlue;
}
</style>
</head>
<body>
	<h1 style="color:DarkGreen;">Как задать цвет текста с помощью названий цветов HTML?</h1>
	<h2 style="color:DarkRed;">Добавьте атрибут стиля к текстовому элементу, который вы хотите раскрасить.</h2>
	<h3 style="color:DarkBlue;">Вы можете использовать более чем 140 именованных цветов.</h3>
</body>
</html>
```
## Цвет текста с использованием цветовых кодов RGB, RGBA или HEX.

```
<!DOCTYPE html>
<head>
<meta charset="UTF-8">
<title>Document</title>
</head>
<body>
	<h1 style="color:rgb(50,150,200);">Способы внедрения стилей</h1>
	<h2 style="color:rgba(220,30,100,1);">Способы внедрения стилей</h2>
	<h3 style="color:#1A8D7E">Способы внедрения стилей</h3>
</body>
</html>
```

```
<!DOCTYPE html>
<head>
<meta charset="UTF-8">
<title>Document</title>
<style>
	h1 {
	color:rgb(50,150,200);
}
	h2 {
	color:rgba(220,30,100,1);
}
	h3 {
	color:#1A8D7E;
}
</style>
</head>
<body>
	<h1>Способы внедрения стилей</h1>
	<h2>Способы внедрения стилей</h2>
	<h3>Способы внедрения стилей</h3>
</body>
</html>
```

## Цвет текста с использованием цветовых кодов HSL или HSLA.

[Примеры цветов HSL](https://www.w3.org/TR/css-color-4/#named-colors)

```
<!DOCTYPE html>
<head>
<meta charset="UTF-8">
<title>Document</title>
</head>
<body>
	<h1 style="color:hsl(200,100%,40%);">Цветовые коды HSL и HSLA</h1>
	<p  style="color:hsla(200,100%,40%,0.9); font-size:24px;">HSL (оттенок, насыщенность, яркость) — это представление цветовой модели RGB в цилиндрических координатах</p>
	<p  style="color:hsla(200,100%,40%,0.6); font-size:24px;">Цветовые значения HSLA представляют собой расширение цветовых значений HSL с альфа-каналом, который определяет непрозрачность цвета.</p>
</body>
</html>
```

## Фоновый цвет – Background Color.
#### Цвет фона для определенного элемента HTML.

```
<!DOCTYPE html>
<head>
<meta charset="UTF-8">
<title>Document</title>
</head>
<body>
<p>Название цвета "YellowGreen":</p>
	<h2 style="background-color:rgb(154, 205, 50);">rgb(154, 205, 50)</h2>
	<h2 style="background-color:#9ACD32;">#9ACD32</h1>
	<h2 style="background-color:hsl(80, 61%, 50%);">hsl(80, 61%, 50%)</h2>

	<p>Значения RGBA цвета "YellowGreen" с различной прозрачностью:</p>
		<h2 style="background-color:rgba(154, 205, 50, 0.2);">rgba(154, 205, 50, 0.2)</h2>
		<h2 style="background-color:rgba(154, 205, 50, 0.5);">rgba(154, 205, 50, 0.5)</h2>
		<h2 style="background-color:rgba(154, 205, 50, 0.8);">rgba(154, 205, 50, 0.8)</h2>

		<p>Значения HSLA цвета «YellowGreen» с различной прозрачностью:</p>
			<h2 style="background-color:hsla(80, 61%, 50%, 0.2);">hsla(80, 61%, 50%, 0.2)</h2>
			<h2 style="background-color:hsla(80, 61%, 50%, 0.5);">hsla(80, 61%, 50%, 0.5)</h2>
			<h2 style="background-color:hsla(80, 61%, 50%, 0.8);">hsla(80, 61%, 50%, 0.8)</h2>
	</body>
</html>
```
















