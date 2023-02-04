Leçon HTML : Les DIV

Qu’est ce qu’une div ?

	Une div est un « container » donc, littéralement un endroit dans lequel placer son code. Elle se forme avec une balise spécifique.

```html
<div>Bonjour !<div/>
```

Utilisation de la div :

    Les divs s'utilisent généralement en leurs **attribuant des class et ID spécifiques** pour pouvoir structurer son code. 
    Ex 
    
```html
<div class="hello" id="helloDiv">Bonjour</div>
```

    Vous pouvez évidemment mettre **des balises html dans une div** : là est tout l'intêret des divs
    
```html
<div class="home">
<img src="./home.png" alt="The image of the home">
<h1>Hello There !</h1>
</div>
``

Attention !

    Attention ! Si au premier coup d'œil, les divs ont l'air génial, il faut savoir qu'elles ne sont pas majoritairement utilisées car d'aures balises sont présentes pour ségmenter le code qui sont plus explicites. Par example, la balise <footer> ou <header> ou encore <section> pour délimiter une section dans votre site etc... etc...
   Par example, il est plus compréhensible d'avoir ceci :
   
```html 
<html>
 <head>
 </head>
  <body>
    <header>Message du début</header>
      <section class="middle">Message du milieu</section>
    <footer>Message de fin</footer>
  </body>
</html> 
```
Que ceci :
```html
<html>
 <head>
 </head>
  <body>
    <div class="header">Message du début</div>
     <div class="middle">Message du milieu</div>
    <div class="footer">Message de fin</div>
  </body>
</html> 
```

Donc n'oubliez pas ! Les divs sont des balises à contenu générique mais si vous souhaitez avoir un site plus propre où vous pourrez mieux vous retrouvez dans le code utilisez les balises spécifiques.
