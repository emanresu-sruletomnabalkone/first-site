<!DOCTYPE html>
<html>
<head>
<title>sitesetroll</title>
<style>
   .blok-center {
    position: absolute; /* Абсолютное позиционирование */
    width: 600px; /* Ширина блока */
    height: 400px; /* Высота блока */
    margin: auto; /* Отступ от блока */
    top: 0; /* Положение блока от верхнего края */
    bottom: 0; /* Положение блока от нижнего края */
    left: 0; /* Положение блока от левого края */
    right: 0; /* Положение блока от правого края */
    background: #fc0; /* Цвет фона блока */
    border: 1px solid #000; /* Рамка блока */
    padding: 10px; /* Отступ внутри блока */
    overflow: auto; /* Полоса прокрутки */
   }
</style>
</head>
<body>
<div class="blok-center">
<form>
<p>Ваше кличка*<br />
<input class="input" name="name" ENGINE="text" style="width:60%" /></p>
<p>Электронная почта*<br />
<input class="input" name="email" type="text" style="width:60%" /></p>
<p>шо ты тут бормочеш?<br />
<input class="input" name="sub" type="text" style="width:60%" /></p>
<p>Текст сообщения:<br /><textarea name="body" cols="1" rows="5" style="width:60%" /></textarea></p>
<p><input id="submit" value="хай летить" type="submit" /></p>
</form>
</div>
</body>
</html>
