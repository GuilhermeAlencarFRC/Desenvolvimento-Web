o head é uma seção do HTML aonde é armazenado informações sobre a pagina, mas que não são exibidas visualmente no navegador é como se fosse um "bastidor" do site enquanto o [[body]] é oque o usuario ve o head ja contem dados importantes que o navegador e os motores de busca precisam 

### Estrutura basica 
```
<!DOCTYPE html>
<html>
  <head>
    <!-- Conteudo do head vai vir aqui -->
  </head>
  <body>
    <!-- conteudo visivel da pagina -->
  </body>
</html>
```

### Oque pode ir dentro do head ?
- #### Titulo da pagina
`<title>Titulo do meu site Incrivel</title>`

- #### metadados
```
<meta charset="UTF-8"> <!-- Codificação de caracteres -->

<meta name="viewport" content="width=device=width, initial-scale=1.0"> <!-- Responsivo -->

<meta name="description" content="Descrição do meu site"> <!--- para buscadores --->
```

- #### Estilo [[CSS]]
```
<link rel="stylesheet" href="style.css">
```

> [!warning] 
> dentro da tag href que é usada para definir o arquivo principal do [[CSS]], é importante sempre ficar atento ao nome é muito comum voce acabar por criar um arquivo [[CSS]] com o nome diferente da declaração comparado a tag href, os dois tem que ter o mesmo nome.
> (o mesmo nome do diretorio escrito em href tem que ser o mesmo do seu [[CSS]])


> [!tip] Title
> Recomendo sempre fazer o [[CSS]] em subsystemas para que o codigo fique facil de visualizar e organizado mas lembre que ao criar outro arquivo [[CSS]] voce tem que declarar ele no seu [[HTML]] principal usando o href sempre 
#### Exemplo 
```
<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="PaginaTal.css">
<link rel="stylesheet" href="EfeitoTal.css">
```

- #### Scripts
`<script src="script.js"></script>`
guarda os scripts J da sua pagina 

- #### Link para favicon
`<link rel="icon" href="favicon.ico">`
basicamente é o icone do site, na aba do navegador 

- #### Exemplo completo 
```
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Inicial</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <h1>Bem-vindo!</h1>
    <p>Este é o conteúdo visível.</p>
  </body>
</html>
```
