# htmlsimples
um design simples com html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <style>

        #grad {
          height: 2000px;
          background-image: linear-gradient(to bottom right, lightblue, darkviolet);
         }
    </style>
</head>

<body id="grad">
    
    <form action="">
     <label for="nome">User</label>
     <input type="email" name="nome" placeholder="email do usuario" class="preencher">
     <label for="senha">Senha</label>
     <input type="password" name="senha" placeholder="senha do usuario" class="preencher">
     <input type="submit" name="entrar" class="acesso">
    </form>
</body>

</html>



css 

input{
    display: block;
    width: 250px;
    margin: 10px;
    height:20px;
}

form{
    margin-top:200px;
    margin-left:700px;
}
