README

# Projeto Final Ciclo Formativo Pretalab - Módulo HTML e CSS

![gif introdução](https://media.giphy.com/media/968taxwNaAXqZASdcn/giphy.gif)

## Sobre o projeto
Link do projeto no ar:

- [link do projeto final no netlify](https://www.figma.com/file/dykEV9jRKyK7K83CQ74zfP/Portfolio-Ciclo-Formativo-II---M%C3%B3dulo-I?node-id=0%3A1)

O projeto final é um portfólio feito em HTML, CSS e hospedado no netlify.

Ferramentas usadas:
✓		Visual Studio Code como ambiente de desenvolvimento.

✓		Github como ferramenta de versionamento.

✓		Netlify para realizarmos o Deploy da nossa aplicação.

<br>
Link do Protótipo:

- [link do protótipo do projeto final](https://www.figma.com/file/dykEV9jRKyK7K83CQ74zfP/Portfolio-Ciclo-Formativo-II---M%C3%B3dulo-I?node-id=0%3A1)

---
<br>
_Foi ser incrível caminharmos juntas!_
<br>

### Vamos nos conectar!

- [instagram](https://www.instagram.com/simara_conceicao)
- [linkedin](https://www.linkedin.com/in/simaraconceicao)
- [github](https://github.com/simaraconceicao)
- [podcast](https://open.spotify.com/show/59vCz4TY6tPHXW26qJknh3?si=f6562e559cb44560)
- [canal do youtube](https://www.youtube.com/@queroserdev)

<br>


HTML

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="./style.css">
  <title>Projeto Final</title>
</head>
<body>
  <div id="menu">
    <ul>
      <li><a href="#formacao">Formação</a></li>
      <li><a href="#portfolio">Portfólio</a></li>
      <li><a href="#contato">Contato</a></li>
    </ul>      
  </div>
  <div id="perfil">

  </div>
  <div id="formacao">

  </div>
  <div id="portfolio">

  </div>
  <div id="contato">

  </div>
</body>
</html>





CSS

* {
  box-sizing: border-box;
  margin: 0;
}

#menu {
  background-color: #BE89CB;
}

#menu ul {
  display: flex;
  padding: 30px;
  justify-content: right;
  align-items: flex-end;
  gap: 150px;
}

#menu ul li {
  list-style: none;
}

#menu ul li a {
  font-family: 'Open Sans', sans-serif;
  font-weight: 700;
  font-size: 18px;
  color: #FFFFFF;
  text-decoration: none;
}
-------
Tutorial github e git

no github:
cria o repositorio inserindo nome e descrição apenas
escolhe a segunda opção de conexão 

volta no vs code:
roda comando git init  (ele serve para inicializar o git no meu projeto)
pego o link git add remote (link do repositorio) - serve para linkar o projeto que está no meu computador com o link do github
git add . (adicionar todas as mudanças que fiz)
git commit -m "texto com nome da versao que descreve as mudancas que vc fez no código''
git push origin main