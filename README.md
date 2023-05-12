<!DOCTYPE html>
<html>

<head>
    <title>landing page</title>
    <style type="text/css">
        *{padding: 0;margin: 0;box-sizing: border-box;}
        header{
            width: 100%;
            height: 100vh;
            background:linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)),url(bg.jpg);
            background-size:cover ;
            font-family: sans-serif;
        }
        nav{
            width: 100%;
            height: 100px;
            color:white;
            display: flex;
            justify-content:space-around;
            align-items: center;
        }
        .logo a{
            text-decoration: none;
            color:white;
            font-size: 2em;
            letter-spacing: 2px;
        }
        .menu a{
            text-decoration: none;
            color: white;
            padding: 10px 10px;
            font-size: 20px;
            position: relative;
        }
        .registration a{
            text-decoration: none;
            color:white;
            padding: 10px 20px;
            font-size: 20px;
            background: indianred;
            border-radius: 8px;
            transition: 0.4s;
        }
        .login a{
            text-decoration: none;
            color: white;
            padding: 10px 20px;
            font-size: 20px;
            background: indianred;
            border-radius: 8px;
            transition: 0.4s;

        }
        .text{
            max-width: 650px;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            text-align: center;
            color: white;
        }
        .text span{
            letter-spacing: 3px;

        }
        .text h1{
            font-size:4em;
        }
        .text a{
            text-decoration: none;
            background: indianred;
            color: white;
            padding: 10px 20px;
            letter-spacing: 5px;
        }

    </style>
</head>

<body>
    <header>
        <nav>
            <div class="logo">
               <a href="landingpage.html"> Books centeral</a>
            </div>
            <div class="menu">
                <a href="landingpage2.html">b.tech books </a>
                <a href="landingpage2.html">bsc books</a>
                <a href="landingpage2.html">BA books</a>
                <a href="landingpage2.html">other types of books</a>
                <a href="landingpage2.html">contact to us</a>
            </div>
            <div class="login">
                <a href="landingpage2.html">log In</a>
            </div>
            <div class="registration">
                <a href="landingpage2.html">registration</a>
            </div>
            <section class="text">
                <span> read and learn</span>
            
                <h1>welcome to books centeral </h1>
                <br>
                <a href="landingpage2.html">find your books</a>
            </section>


        </nav>
    </header>
</body>

</html>
