# lliiiiii9999.github.io
thais_ultimati
<!DOCTYPE html>
<html lang="en">
<head>
<body bgcolor=#c0c0c0>
<Body Background= "" Text="blue" Background-size="100%">
<Background-image: 
 
 <meta charset="UTF-5">

<style>   
.header__superior{
    max-width: 1200px;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
}
.logo img{
    width: 250px;
}

.search input{
    width: 300;
    padding: 10px;
}

body{
            margin: 0;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 20px;
        }
        .menu-wrapper {
            padding: 0;
            list-style: none;
            width: 100%;
            height:140px;
            padding: 0px  20px;
            background:#023877;

        }      

        .principal-menu  {
            max-width: 1200px;
            margin:auto;
            height: 100%;

        }

        .principal-menu > li > a{
            display: block;
            padding: 30px 45px;
            width: 100px;
        }

        nav{
          height: 100%;  
        }

        nav> ul{
            height:100%;
            display:flex;
        }

        nav > ul > li{
            height:100%;
            list-style: none;
            position: relative;
        }
        nav > ul > li> a{
            width: 100%;
            height: 100%;
            display: flex;
            color:white;
            align-items: center;
            padding: 14px;
            text-transform: uppercase;
            font-size: 14px;
            transition: all 300ms ease;
        }
        nav > ul > li a:hover{
            transform: scale(1.1);
            background: #0074c7;
            box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.5);

        }

        nav ul li ul{
            width: 150px;
            display: flex;
            flex-direction: column;
            background: #fff;
            box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.5);
            position:absolute;
            top:90px;
            left:-5px;
            
            opacity: 0;
            z-index: 10;
            transition:all 300ms ease ;
        }

        nav ul li ul:hover{
            visibility: visible;
            opacity: 1;
            top:70px;
        }
        @media screen and (max-width:720px){
            .search input{
                display:none;
            }
            .header__superior{
                padding: 10px;
            }
            .logo img{
                width: 200px;
            }
            nav >ul{
                flex-direction: column;
                background-color:#023877 ;
                position: fixed;
                left:158px;
                width: 100%;
                height: 300px ;
                transition: all 300ms ease;
                z-index: 100;
                opacity: 0;
                visibility: hidden;
            }
            nav>ul> li >a:hover{
                transform: scale(1);
            }
            nav ul li ul{
                left: 90px;
            }

            nav> ul> li{
                top:50px;
            }

            nav> ul>li:first-child a{
                background-position: 20px;
            }
        }



      

    </style>

</head>
<body bgcolor=#c0c0c0>

    <header>

        <Center><h1>Proyecto tecnico del area de informatica 
        </h1></Center>

        <hr>
        <div class= "header__superior">
            <div class="logo">
                <img src="Imagen de WhatsApp 2024-06-03 a las 04.57.14_fd61e57b.jpg">
            </div>
            <div class="search">
                <input type="search" placeholder="¿ que desea  hacer?">
            </div>
        </div>
         
        
        
          <div class="menu-wrapper">   
            <nav>
            <ul class="principal-menu">
                <li><a href="#">INICIO</a></li>
                <li><a href="#">DISEÑO Y DESARROLLO WEB</a>
                    <ul class="sub-menu">
                     
                        <li><a href="segunda_pagina/index2.html">TRIMESTRE 1</a></li>  
                        <li><a href="">TRIMESTRE 2</a></li>    
                        <li><a href="">TRIMESTRE 3</a></li>
                        <li><a href="">SUPLETORIO</a></li>   
    
                         
             
                    </ul>
                </li>
                <li><a href="#">SISTEMAS OPERATIVOS Y REDES</a>
                    <ul class="sub-menu">
                        <li><a href="">TRIMESTRE 1</a></li>  
                        <li><a href="">TRIMESTRE 2</a></li>    
                        <li><a href="">TRIMESTRE 3</a></li>
                        <li><a href="">SUPLETORIO</a></li>   
                    </ul>
                </li>
                <li><a href="#">PROGRAMACION Y BASE </a>
                <ul class="sub-menu">
                        <li><a href="">TRIMESTRE 1</a></li>  
                        <li><a href="">TRIMESTRE 2</a></li>    
                        <li><a href="">TRIMESTRE 3</a></li>
                        <li><a href="">SUPLETORIO</a></li>   
         
            </ul> 
            </li> 
            <li><a href="#">SOPORTE TECNICO</a>
                <ul class="sub-menu">
                    <li><a href="">TRIMESTRE 1</a></li>  
                    <li><a href="">TRIMESTRE 2</a></li>    
                    <li><a href="">TRIMESTRE 3</a></li>
                    <li><a href="">SUPLETORIO</a></li>   
                </ul>
            </li>

            <li><a href="#">APLICACIONES OFIMATICAS LOCALES Y EN LINEA</a>
                <ul class="sub-menu">
                    <li><a href="">TRIMESTRE 1</a></li>  
                    <li><a href="">TRIMESTRE 2</a></li>    
                    <li><a href="">TRIMESTRE 3</a></li>
                    <li><a href="">SUPLETORIO</a></li>   
                </ul>
            </li>

          </nav>
          </div>

    </header>

    
</body>
</html>
