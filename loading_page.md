HTML:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login VM</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="login">
        
        <h1 class="text-center">Bem vindo à VMinvestimentos</h1>

        <form class="needs-validation">
            <div class="form-group was-validated">
                <label class="form-label" for="email">Email de Acesso</label>
                <input class="form-control" type="email" id="email" required>
                <div class="invalid-feedback">
                    Seu email de acesso por favor!
                </div>
            </div>
            <div class="form-group was-validated">
                <label class="form-label" for="senha">Senha</label>
                <input class="form-control" type="senha" id="senha" required>
                <div class="invalid-feedback">
                    Sua senha de acesso por favor!
                </div>
            </div>
            <div class="form-group form-check">
                <input class="form-check-input" type="checkbox" id="check">
                <label class="form-check-label" for="check">Lembrar pra mim</label>
            </div>
            <input class="btn btn-success w-100" type="submit" value="Entrar">
        </form>
    </div>
</body>
</html>

CSS:

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #7c7c7c;
}

.login{
    width: 360px;
    height: min-content;
    padding: 20px;
    border-radius: 12px;
    background-color: aliceblue;
}

.login h1 {
    font-size: 36px;
    margin-bottom: 25px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

.login form{
    font-size: 20px;
}

.login form .form-group {
    margin-bottom: 12px;
}

.login form input[type="submit"]{
    font-size: 20px;
    margin-top: 15px;
}

.btn{
    background-color: black;
}

.btn:hover{
    background-color: #383838;
}