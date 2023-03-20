---
Title: Archive Template
Type: Template
---

<!DOCTYPE html>
<html lang="en">
<head>
<title>{post-title}{separator}{weblog-title}</title>
<meta charset="utf-8">
<link rel="icon" type="image/x-icon" href="https://raw.githubusercontent.com/george-probably/chachanidze.com/main/Images/favicon.png">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#288cf0">
<meta name="apple-mobile-web-app-status-bar-style" content="#288cf0">
<link rel="stylesheet" type="text/css" href="/style.css">
<style>
@import url('https://static.omg.lol/type/font-honey.css');
@import url('https://static.omg.lol/type/fontawesome-free/css/all.css');
@import url('https://fonts.bunny.net/css?family=open-sans:500,800&display=swap');
</style>
</head>

<body>

<header><h1 class="weblog-title"><a style="text-decoration:none; border-bottom:0px" href="{base-path}">{weblog-title}</a></h1></header>

<main>

<div class="flex-column">
<div class="nav-box"> {navigation} </div>
</div>

<div class="flex-column">

<div class="box">
{body}
</div>
</div>

<div class="flex-column">
<div class="box">
<h2> <i class="fa-solid fa-search"></i> Looking for something?</h2>
<form id="form"> 
<input type="search" id="query" name="search" placeholder="Search...">
<button aria-label="Search site"><i class="fa-solid fa-search"></i></button>
</form>
</div>

<div class="box">
<h2> "Where'd these boxes go?" </h2>
<p>You don't need them, silly! You're already on the archive page; the latest posts are just the top 5!</p>
</div>

<div class="box">
<h2> <i class="fa-solid fa-star"></i> Favourite Posts</h2>
<ul>
<li><a href='/2022/04/why-is-modern-software-so-bad'>Why is Modern Software So Bad?</a></li>
<li><a href='/2022/12/new-year-same-tired'>New Year, Same Tired</a></li>
<li><a href='/2023/01/who-are-you'>Who Are You?</a></li>
<li><a href='/2023/01/adding-more-whimsy-to-your-life'>Adding More Whimsy To Your Life</a></li>
</ul>
</div>

</main>
<footer>
<p>Made with <a href="https://weblog.lol">weblog.lol</a>. </br>kindness binds us</p>
</footer>
</body>
</html>