<!DOCTYPE html>
<html lang="ru">
<head>
	<meta charset="UTF-8">
	<meta name="description" content="моя первая верстка сайта">
	<meta name="keywords" content="верстка,сайт,просто верстка">
	<title>Киномонстр</title>
	<link rel="stylesheet" href="/my-site/css/style.css">
</head>
<body>
	<div class="main">
		<div class="header">
			<div class="logo">
				<div class="logo_text">
					<h1><a href="">Киномонстр</a></h1>
					<h2>Кино - наша страсть!</h2>
				</div>
			</div>
			
			<div class="menubar">
				<ul class = "menu">
					<li class = "selected"><a href="#">Главное меню</a></li>
					<li><a href="#">Фильмы</a></li>
					<li><a href="#">Сериалы</a></li>
					<li><a href="#">Рейтинг фильмов</a></li>
					<li><a href="#">Контакты</a></li>
				</ul>
			</div>
		</div>
		<div class="site_content">
			<div class="sitebar_container">
				<div class="sidebar">
					<h2>Поиск</h2>
					<from method="post" action="#" id = "search">
						<input type="search" name="search_field" placeholder="ваш запрос" />
						<input type="submit" class="btn" value="Найти" />
					</from>
				</div>
				<div class="sidebar">
					<h2>Вход</h2>
					<from method="post" action="#" id = "login">
						<input type="search" name="login_field" placeholder="Логин" />
						<input type="password" name="password_field" placeholder="Пароль" />
						<input type="submit" class="btn2" value="войти" />
					</from>
					<div class="podpis">
						<b><a href="#">Забыли пароль?</a></b> | <b><a href="#">Регистрация</a></b> 
					</div>
				</div>
			</div>
		</div>
	</div>
</body>
</html>
