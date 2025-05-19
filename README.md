<!DOCTYPE html>
<html>
    <head>
        <title>UTAMA</title>
    </head>
    <style>
        /*CSS HEADER*/
        *{
            box-sizing: content-box;
            margin: 50;
        }
        .header{
            background-image: url("banner\ \(1\).jpg");
            overflow: hidden;
        }
        .header img{
            width: 25%;
            margin: 20px;
            float: left;
            max-width: 200px;
        }
        .header .font{
            font-size: 10mm;
            width: 65%;
            margin-top: 30px;
            float: left;
        }
        /*CSS MENU*/
        .menu ul{
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: rgb(242, 31, 196);
        }
        .menu li{
            float: left;
        }
        .menu a{
            text-decoration: none;
            display: block;
            color: rgb(241, 239, 234);
            padding: 20px;
        }
        .menu a:hover{
            color: black;
            font-weight: bold;
            background-color: rgb(242, 190, 235);
        }
        /*CSS CONTENT*/
        /*CSS FOOTER*/
        .kaki{
            text-align: center;
            border: solid rgb(60, 66, 63);
            background-color: rgb(242, 31, 196);
            padding: 10px;
            margin-top: 20px;
        }
    </style>
    <body>
        <!--HEADER HTML-->
        <div class="header">
            <img src="kvpjb.jpg"><!--logo kvpjb-->
            <div class="font"><!--class font-->
                <marquee direction="up"><font>Laman Web Pertama Saya</font></marquee>
            </div>
        </div>
        <!--MENU HTML-->
        <div class="menu">
        <ul>
            <li><a href="index.html">Utama</a></li>
            <li><a href="jommasukdagang.html">Jom Masuk Dagang</a></li>
            <li><a href="tentangsaya.html">Tentang Saya</a></li>
            <li><a href="hubungisaya.html">Hubungi Saya</a></li>
        </ul>
        </div>
        <!--CONTENT HTML-->
        <div class="content">
            <center>
                <img src="photosendiri.jpg">
            </center>
        </div>
        <!--FOOTER HTML-->
        <div class="kaki">
            <font>Copyright &copy; Laman Web Pertama Saya 2024</font>
        </div>
    </body>
</html>
