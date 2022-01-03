```
<!DOCTYPE html>
<html lang="eng">
<head>
    <meta charset="utf-8">
    <title>Login form</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="form">
    <form action="/">         
        <h1> Welcome!</h1>
        <div>
            <input type="field" name="login" placeholder="Login"  requared>
        </div>
        <div>
            <input type="password" name="pass" placeholder="Password" requared>
        </div>
        <div class="centerAlign">
        <label>
            <input class="remember" type="checkbox" name="remember" checked>
            Remember me
        </label>
        </div>
        <div>
            <button>Log in</button>
        </div>
    </form>
</body>
</html>
Onboarding:
<!DOCTYPE html>
<html lang="eng">
    <head>
        <meta charset="UTF=8">
        <title>Onboarding</title> 
        <link rel="stylesheet" href="style.css">
        <style>
            img{
                width: 100%;
                height: 320px;
            }
        </style>
    </head>
    <body>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1641100952221-7c77e8211b15?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1964&q=80" alt="Tourist">
            <div class="TitleAndText">
                <h1>Tourist cycle</h1>
                <p>The best travel agencies in one place.</p>
            </div>
            <button>More</button>
        </div>
    </body>
</html>
Styles:
body{
    background-color: rgb(240, 240, 255);
} 
form, .card{
     padding: 48px 48px 48px 48px;
     margin: auto;
     width: 480px;
     background-color: white;
     box-shadow: 0px 10px 30px rgba(235, 219, 255, 0.39);
 }
 .TitleAndText{
     margin: 16px 0px;
 }
 h1 {
     font-family: Poppins, sans-serif;
     font-size: 32px;
     font-weight: 700;
     text-align: center;
     margin: 0;
 }
 p{
    font-family: Poppins, sans-serif;
    font-size: 16px;
    font-weight: 300;
    text-align: center;
    margin: 0;
 }
 placeholder{
     font-family: Poppins, sans-serif;
     font-size: 16px;
 }
 input {

     padding-left: 16px;
     margin-bottom: 8px;
     height: 48px;
     width: 100%;
     font-family: Poppins;
     font-size: 16px;
     border: 1px solid rgb(227, 223, 255);
 }
 input:hover{
     border: 1px solid rgb(212, 208, 243);
 }
 label{
     margin-bottom: 16px;
     font-family: Poppins;
     font-size: 14px;
 }
 .remember{
     text-align: right;
     width: 16px;
     border-radius: 30px;
     border: 1px solid rgb(227, 223, 255);
 }
.centerAlign input, .centerAlign label{
    vertical-align: middle;
}
button{
    font-family: Poppins;
    background: rgb(0, 0, 0);
    color: white;
    font-size: 16px;
    margin-top: 16px;
    padding: 8px;
    height: 56px;
    width: 100%;
}
```