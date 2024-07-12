<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Insert title here</title>
<style>
	body {
		margin: 0;
		font-family: Arial, sans-serif;
		background-color: #f5f5f5;
	}
	header {
		width: 100%;
		background: url('/img/pado.png') no-repeat center center;
		background-size: cover;
		border-bottom: 1px solid #eee;
		box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
	}
	.head {
		width: 100%;
		max-width: 1400px;
		margin: 0 auto;
		display: flex;
		flex-direction: column;
		align-items: center;
		padding: 20px 0;
	}
	.head-top {
		display: flex;
		justify-content: space-between;
		align-items: center;
		width: 100%;
		padding: 0 20px;
		box-sizing: border-box;
	}
	.logo img {
		width: 150px;
		border-radius: 50%; /* 둥글게 만들기 */
	}
	.title {
		margin: 0;
		font-size: 55px; /* 글씨 크기 크게 */
		font-weight: bold; /* 글씨 진하게 */
		color: black;
	}
	.search-bar {
		display: flex;
		align-items: center;
		gap: 10px;
	}
	.search-bar input[type="text"] {
		width: 300px;
		padding: 10px;
		border: 1px solid #ccc;
		border-radius: 4px;
	}
	.search-bar button {
		padding: 10px 20px;
		border: none;
		background-color: #007BFF;
		color: white;
		border-radius: 4px;
		cursor: pointer;
	}
	.search-bar button:hover {
		background-color: #0056b3;
	}
	.nav {
		width: 100%;
		padding: 10px 0;
		background-color: #f9f9f9;
	}
	.nav ul {
		display: flex;
		justify-content: center;
		gap: 130px;
		list-style: none;
		margin: 0;
		padding: 0;
	}
	.nav ul li a {
		text-decoration: none;
		color: #000;
		font-weight: bold;
		padding: 10px 15px;
		border-radius: 4px;
		transition: background-color 0.3s, color 0.3s;
	}
	.nav ul li a:hover {
		background-color: #007BFF;
		color: white;
	}
</style>
</head>
<body>
<header>
	<div class="head">
		<div class="head-top">
			<div class="logo">
				<img src="/img/busan.png" alt="Logo">
			</div>
			<h1 class="title">온  나  부  산</h1>
			<div class="search-bar">
				<input type="text" placeholder="검색어를 입력하세요">
				<button type="button">검색</button>
			</div>
		</div>
		<div class="nav">
			<ul>
				<li><a href="/tourList">🚗관광명소</a></li>
				<li><a href="/foodList">🍽맛집</a></li>
				<li><a href="/festivalList">✨축제·행사</a></li>
				<li><a href="/recommand">🔎AI코스추천</a></li>
				<li><a href="">🚌시티투어</a></li>
				<li><a href="/showTheWay">📝관광지도</a></li>
			</ul>
		</div>
	</div>
</header>
</body>
</html>