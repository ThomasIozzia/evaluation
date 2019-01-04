# Évaluation individuelle

## Programmation - Coaching

```Français
Nom : Iozzia	
Prénom : Thomas
URL de votre compte Github : https://github.com/ThomasIozzia
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
Le coté client permet de créer le code en html/css/js et c'est ce que l'utilisateur verra directement sur le site. Le coté serveur permet de créer tout ce qui sera derrière les fonctionnalités du coté client comme l'utilisation des formulaires, bases de données. le coté serveur permet donc de créer des requêtes tandis que le coté client permet de les afficher pour l'utilisateur. 
```



 ### 2. HTML est un langage côté... 	

```
Client
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html lang=fr>
    <head>
        <meta charset="utf-8">
        <link href="si il y a">
        <link rel ="si il y aussi">
        
        <title> C'est la base </title>
    </head>
	<body>
        .
        .
        .
    </body>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en vert en utilisant du CSS.

```html
<div>
   <p class="text1"> J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
.text1{
 color: green;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
C'est un site permettant d'avoir des feuilles de styles pré-établies afin de faciliter l'utilisation de certaines fonctionnalité. Cela permet d'avoir des bouts de codes plus rapidement pour mettre en forme son site.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html lang=fr>
    <head>
        <meta charset="utf-8">
        <link href="si il y a">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
        
        <title> C'est la base </title>
    </head>
	<body>
        .
        .
        .
    </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="container">
  <div class="row">
    <div class="col-sm-4">
      Google 
    </div>
    <div class="col-sm-4">
      Microsoft
    </div>
    <div class="col-sm-4">
      Apple
    </div>
  </div>
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <img src="https://www.usine-digitale.fr/mediatheque/5/0/0/000305005_homePageUne/logo-google-g.jpg">
    </div>
    <div class="col-sm-4">
      <img src="https://o.aolcdn.com/images/dims3/GLOB/legacy_thumbnail/630x315/format/jpg/quality/85/http%3A%2F%2Fi.huffpost.com%2Fgen%2F742825%2Fimages%2Fs-05370036PHOTOLOGOMICROSOFT2012-large640.jpg">
    </div>
    <div class="col-sm-4">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/Logo_Apple.inc.gif/220px-Logo_Apple.inc.gif">
    </div>
  </div>
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div class="container">
  <div class="row">
    <div class="col-sm-4">
      <a href="https://www.google.fr/">
       <img src="https://www.usine-digitale.fr/mediatheque/5/0/0/000305005_homePageUne/logo-google-g.jpg">
       </a>
    </div>
    <div class="col-sm-4">
      <a href="https://www.microsoft.com/fr-fr">
       <img src="https://o.aolcdn.com/images/dims3/GLOB/legacy_thumbnail/630x315/format/jpg/quality/85/http%3A%2F%2Fi.huffpost.com%2Fgen%2F742825%2Fimages%2Fs-05370036PHOTOLOGOMICROSOFT2012-large640.jpg">
       </a>
    </div>
    <div class="col-sm-4">
      <a href="https://www.apple.com/fr/"> 
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/Logo_Apple.inc.gif/220px-Logo_Apple.inc.gif">
       </a>
    </div>
  </div>
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Serveur
```



### 11. Listez-moi tous les types de données que vous connaissez en donnant le nom et la syntaxe.

```
my_string = "bonjour" # Ceci est une chaine de caractères
my_num =  25 # ceci est un integer
my_boolean = true # ceci est un booléen
my_floats = 12.3 # ceci est une decimale
Itération = rechercher dans un tableau array 
Array = Tableau
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
My_firstname = "Thomas"
puts My_firstname
My_lastname = "Iozzia"
puts My_lastname
My_github = "https://github.com/ThomasIozzia"
puts My_github
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby
a=674 
b=311
c = a%b
puts c
# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Une gem est un genre de base de données un peu comme bootstrap pour ruby qui permet d'initier des commande directement sur la gem que l'on utilise ex:twitter, tout sera affilié directement à twitter et cela permettra d'exécuté le code pour ce site.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
une API est une interface de programmation.
Le plus ouvent représenter sous forme de clés, elles permettent d'utiliser des programmes afin d'automatiser des commandes. 
Pour nous y connecter, il nous faut donc la clé du programme en question que l'on peut retrouver sur internet.
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
My_name = "Thomas"
hour = 15
# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom
if hour<=12
    puts "Bonjour" + ' ' + My_name
# sinon
	# j'écris mon code permettant de dire Bonsoir prénom
    else 
    puts "Bonsoir" + ' ' + My_name
end
```



### 17. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]

require 'bundler/inline'

gemfile true do
 source 'http://rubygems.org'
 gem 'twitter'
end

client = Twitter::REST::Client.new do |config|
  config.consumer_key        = "blablablablabla"
  config.consumer_secret     = "blablablablabla"
  config.access_token        = "blablablablabla-blablablablabla"
  config.access_token_secret = "blablablablabla"
end

client.follow("@richardbranson")
client.follow("@jeffweiner")
client.follow("@LinkedInQueen")
client.follow("@ericschmidt")
client.follow("@elonmusk")
client.follow("@petecashmore")
client.follow("@SteveForbesCE")
client.follow("@mtbarra")
```



### 18. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

