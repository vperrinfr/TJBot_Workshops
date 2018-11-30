# Entraînement du robot a comprendre l’humain aka Watson Assistant

Dans ce workshop vous allez converser avec le TJBot, il peut de base répondre à des questions sur l'intelligence artificielle.
Vous aurez également la possibilité de lui apprendre de nouveaux concepts. Vous allez lui apprendre à vous comprendre lorsque vous lui demandez de bouger le bras.
Pour cela, nous utilisons le service IBM Watson™ Assistant qui vous permet de créer une solution qui comprend les entrées en langage naturel et utilise l'apprentissage automatique pour répondre aux clients en simulant une conversion entre des humains.

 Les données d'apprentissage comprennent les artefacts suivants :

- Intentions : objectifs que vous prévoyez pour vos utilisateurs lorsqu'ils interagiront avec le service.  Par exemple, vous pouvez définir une intention nommée `store_hours` qui répond aux questions relatives aux heures d'ouverture d'un magasin. Pour chaque intention, vous ajoutez des énoncés qui reflètent l'entrée que les clients sont susceptibles d'utiliser pour demander les informations dont ils ont besoin, par exemple, `What time do you open?`

- Entités : une entité représente un terme ou un objet qui fournit le contexte d'une intention. Par exemple, une entité peut être un nom de ville qui permet à votre dialogue de distinguer le magasin pour lequel l'utilisateur souhaite obtenir les horaires d'ouverture.

## Exemples de questions
1. Connecter vous via un navigateur Internet à l'URL suivant : `https://[IP de votre TJBot]:1880/ui`
2. Voici quelques questions que vous pouvez poser au TJBot. 
- Liste de questions:
    - Bonjour TJBot
    - Quel temps à Paris ? (ou Lille, Bordeaux, Marseille...)
    - Qu'est ce que [nom de votre entreprise] ?
    - Raconte moi une blague 
3. Le TJBot vous donne à l'oral la réponse.

P.S: Le TJBot peut également comprendre la demande à la voix, mais à cause d'un bruit de fond trop important, nous avons désactivé cette fonctionnalité 

## Mouvement du Bras

1. Nous allons maintenant apprendre au TJBot à vous comprendre.
2. Pour que le TJBot puisse comprendre que vous lui demandez de bouger, il faut lui fournir quelques phrases d'exemples.
3. Entrez plusieurs phrases d'exemple comme par exemple: 
    - Bouge ton bras
    - Lève la main
    - Met la main en haut
    - Agite ton bras
    - ...
4. Le système va prendre quelques instants pour ingérer ces données et apprendre de celles-ci.
5. Ensuite, vous pouvez saisir une phrase proche, mais pas forcément identique à l'une de celles fournies.
6. Grâce à cet entrainement, le bras du TJBot a dû bouger et il a dû vous dire un message.

Bravo, passons à un autre apprentissage.
