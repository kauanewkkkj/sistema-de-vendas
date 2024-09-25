# sistema-de-vendas
*{
margin: 0;
padding: 0;
box-sizing: border-box;
}

body{
font-family: Arial, Helvetica, sans-serif;
background-color:bisque;
color:#fff;
}

header{
background-color: lightpink;
color:#fff;
padding: 10px 20px;
}

.navbar{
display: flex;
justify-content: space-between;
align-items: center;
}

.logo h1{
font-size: 24px;
}

.nav-links{
    list-style-type: none;
    display: flex;
    gap: 20px;
}

.nav-links li{
    margin: 0;
}

.nav-links a {
text-decoration: none;
color: #fff;
font-size: 18px;
transition: color 0.3s;
}

.nav-links a:hover{
color: blueviolet;
}

.login-btn{
    background-color: lightpink;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.login-btn:hover{
background-color: darkmagenta;
}

main{
    padding: 20px;
    text-align: center;
}

footer{
    margin-top: 20px;
    text-align: center;
    color: black;
}

@media (max-width:768px){
.nav-links{
    flex-direction: column;
    align-items: center;
}

.nav-links li{
    margin-bottom: 10px;

}
}












