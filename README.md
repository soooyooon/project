# project
<html>
<head>
<title> Форма </title>
</head>
<h1> Розкажіть трішки про себе </h1>
<body>
<form> 
<fieldset>
<legend>Коротко про себе</legend>

Ім'я:<br>
<input type="text" name="firstname"><br>
Прізвище:<br>
<input type="text" name="lastname"><br>

<p>Стать<br></p>
<input type="radio" name="gender" checked> Чоловік<br>
<input type="radio" name="gender" checked> Жінка<br>
<input type="radio" name="gender" checked> Інше<br>
<p> Вік <input type="text" name="username"> років </p>
<input type="submit" value="Відправити">
</fieldset>

<br>
<fieldset>
	<legend>Детальніше про себе</legend>
	<input type="radio" name="gender" checked> Молодий чоловік<br>
    <input type="radio" name="gender" checked> Дівчина<br>
    <p><input type="text" name="username"> Дата народження</p>
    <p><input type="text" name="username"> Сімейний стан</p>
    <p><input type="text" name="username"> Соціальний статус</p>
    <p><input type="text" name="username"> Місце проживання</p>

    Що ви зазвичай робите на вихідних?<br>
    <input type="checkbox" name="text"> Гуляю<br>
    <input type="checkbox" name="text"> Ходжу на рибалку<br>
    <input type="checkbox" name="text"> Граю в ігри <br>


    <p>Рохповісти про форми в книзі присвяченій HTML:<br></p>
    <select name="text">
    	<option> Сайт 1</option>
    	<option> Сайт 2</option>
    	<option> Сайт 3</option>
    	<option> Сайт 4</option>
    </select>

    <p> Скільки книг ви прочитали за своє життя?</p>
    <input type="radio" name="select" checked> 0-10<br>
    <input type="radio" name="select" checked> 10-20<br>
    <input type="radio" name="select" checked> 20-40<br>
    <input type="radio" name="select" checked> 50+<br>

<p>Додати коментарі:<br></p>
<p><textarea name="comment"></textarea></p>
 <select name="text">
    	<option> Перша позиція</option>
    	<option> Друга позиція</option>
    	<option> Третя позиція</option>
    </select>
</fieldset>


    <fieldset>
    	<legend>І на завершення</legend>
    	<p>Email:<br></p>
    	<p><input type="text" name="username"></p>
    </fieldset>
    <input type="submit" value="Надіслати">
    <input type="reset" value="Оновити">


</form>
</body>
