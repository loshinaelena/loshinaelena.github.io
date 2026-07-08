<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Landing</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{

    font-family:Inter,sans-serif;
    background:#fff;
    color:#111;
}

.hero{

    min-height:100vh;

    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;

    padding:60px 20px;
}

.avatar{

    width:72px;
    height:72px;

    border-radius:50%;

    overflow:hidden;

    margin-bottom:60px;

    box-shadow:0 10px 30px rgba(0,0,0,.15);
}

.avatar img{

    width:100%;
    height:100%;
    object-fit:cover;
}

.container{

    max-width:1100px;
    text-align:center;
}

h1{

    font-size:72px;
    line-height:1.07;
    font-weight:700;
    letter-spacing:-2px;
}

.gray{

    color:#BDBDBD;
    font-weight:400;
}

.button{

    display:inline-flex;
    align-items:center;
    gap:14px;

    margin-top:55px;

    background:linear-gradient(180deg,#6ED4FF,#2EA8FF);

    color:#fff;

    text-decoration:none;

    padding:22px 48px;

    border-radius:100px;

    font-size:32px;

    font-weight:600;

    transition:.25s;

    box-shadow:
    0 12px 40px rgba(0,170,255,.35),
    inset 0 1px 1px rgba(255,255,255,.7);

}

.button:hover{

    transform:translateY(-3px);

    box-shadow:
    0 20px 50px rgba(0,170,255,.45);
}

.telegram{

    width:34px;
    height:34px;
}

.bottom{

    margin-top:75px;

    font-size:36px;
    line-height:1.35;
    font-weight:700;
}

.orange{

    color:#FF5A00;
}

@media(max-width:900px){

h1{

font-size:50px;

}

.button{

font-size:24px;

padding:18px 36px;

}

.bottom{

font-size:26px;

}

}

@media(max-width:600px){

.avatar{

margin-bottom:40px;

}

h1{

font-size:36px;

letter-spacing:-1px;

}

.button{

font-size:20px;

padding:16px 28px;

}

.bottom{

font-size:20px;

}

}

</style>

</head>

<body>

<section class="hero">

<div class="avatar">

<img src="avatar.jpg" alt="">

</div>

<div class="container">

<h1>

Елена Лошина, продуктовый дизайнер,
проектирую high-load сервисы для людей, а не для презентаций.
<span class="gray">
C2C, B2C, ритейл
</span>

</h1>

<a href="https://t.me/madellena" class="button">

<svg class="telegram" viewBox="0 0 24 24" fill="white">
<path d="M9.99 15.21 9.62 20c.53 0 .76-.23 1.03-.5l2.47-2.37 5.12 3.75c.94.52 1.6.25 1.84-.87L23.4 4.3c.34-1.38-.5-1.92-1.42-1.58L1.77 10.5C.43 11.03.45 11.78 1.55 12.12l5.17 1.61L18.7 6.16c.57-.38 1.1-.17.67.21"/>
</svg>

Написать в тг

</a>

<div class="bottom">

<span class="orange">5+ лет в продуктах.</span>


</div>

</div>

</section>

</body>
</html>
