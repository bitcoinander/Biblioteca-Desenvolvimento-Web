# Biblioteca-Desenvolvimento-Web
- Em Desenvolvimento

@oanderoficial 

# 1 Tag de vídeo 

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tag de Vídeo</title>
</head>
<body>
    <video width="320" height="240" controls>
        <source src="" type="video/mp4">
    </video>
</body>
</html>

```

# 2 Tag de Audio 

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tag de Audio</title>
</head>
<style>
#color{
    background-color: rgb(174, 0, 255);
}
</style>
<body>
    <div>
        <audio id="color" controls>
     <source src="" type="audio/mpeg">
        </audio>
    </div>
    
</body>
</html>

```

# 3- tag figure e figurecaption

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tag figure e figurecaption</title>
</head>
<body>
    <div>
        <figure>
            <img src="wallpaper03.jpg" width="900" height="520" alt="imagem" >
            <figcaption> Aqui ficaria a legenda</figcaption>
        </figure>
    </div>
</body>
</html>

```

# 4- atributos required e placeholder

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atributos required e placeholder.</title>
</head>
<body>
    <div>
        <form>
            
            <label>Nome</label>
            <input type="text" name="name" required placeholder="Digite aqui">
            <input type="submit" name="enviar">
        </form>
    </div>
    
</body>
</html>

```

# 5- atributo type email e autofocus

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atributo type email e autofocus</title>
</head>
<body>
    <div>
        <h3> Preencha o formulário para receber informações!</h3>
        <form>
            <label>E-mail:</label>
            <input type="email" name="email" required placeholder="Digite aqui o seu E-mail" autofocus>
            <label> Nome</label>
            <input type="text" name="name" required placeholder="Digite aqui o seu Nome">
            <input type="submit" name="Enviar">
        </form>
    </div>
    
</body>

```

# 6- atributo content editable

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Atributo content editable</title>
</head>
<body>
    <div>
        <p contenteditable="true">Esse é um parágrafo editável.</p>
    </div>
</body>
</html>

```

# 7-tag detail e summary

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tag detail e summary</title>
</head>
<body>
    <details open="open">
        <summary>Cachorro</summary>
        <p>É um mamífero de 4 patas </p>
    </details>
</body>
</html>

```

# 8- tag detalist

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tag detalist</title>
</head>
<body>
    <form>
        <p>Animais:</p>
        <input list="animais" name="animal">
        <datalist id="animais">
            <option value="Cachorro"></option>
            <option value="Gato"></option>
            <option value="Cavalo"></option>
            <option value="Elefante"></option>
        </datalist>
    </form>
    
</body>
</html>

```
# 9- tag progress

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>tag progress</title>
</head>
<body>
    <p> Loading</p>
    <progress value="60" max="100"></progress>
    
</body>
</html>

```
