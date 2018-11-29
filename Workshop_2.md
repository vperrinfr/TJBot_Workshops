# Entraînement du robot a reconnaître des produits aka Watson Visual Recognition

Après le sens de la parole, passons à la vue.
Dans ce workshop, je vous propose de faire reconnaitre au TJBot vos produits. Vous avez quelques boites à votre disposition sur les tables.

Pour cet exercice, vous allez entrainer le TJBot gràce à des photos de vos produits (environ une quinzaine pour chacun). Il va alors apprendre à reconnaitre les éléments caractérisiques que chacun d'entre eux et ensuie les déttecter.

## Entrainement du service
Pour gagner du temps sur le lab, les photos son déjà été chargé dans le service de reconnaissance visuelle.
Vous pouvez voir ces photos [ici](https://photos.app.goo.gl/jn3SD1k8noLtp5UL9). Un minimum de 15 photos sont nécessaire pour chaque objet que l'on souhaite lui faire apprendre.

Le mécanisme d'apprentissage est le suivant:

![vr](https://user-images.githubusercontent.com/9534938/49222073-2b05fc00-f3db-11e8-92cd-6b42b4b7d61e.png)

Le service Visual Recognition peut être utilisé par diverses applications et industries, comme :
    - Production : utilisez les images d'un paramètre de production pour vous assurer que les produits sont positionnés correctement sur une chaîne d'assemblage
    - Contrôle visuel : recherchez une conformité visuelle ou une détérioration dans une flotte de camions, d'avions ou d'éoliennes sur le terrain, entraînez des modèles personnalisés à comprendre à quoi ressemblent les défauts
    - Assurance : traitez rapidement les déclarations de sinistres en utilisant des images pour les classer en différentes catégories
    - Ecoute sur les réseaux sociaux : utilisez des images de votre ligne de produits ou de votre logo pour écouter sur les médias sociaux ce qui se dit sur votre entreprise
    - Commerce sur les réseaux sociaux : utilisez l'image d'un plat du jour pour trouver le restaurant qui le sert, trouver des commentaires, servez-vous d'une photo de voyage pour trouver des suggestions de vacances reposant sur des expériences similaires
    - Distribution : prenez une photo d'une de vos tenues favorites pour trouver les magasins où elle est vendue ou soldée, servez-vous d'une photo de voyage pour trouver des suggestions de magasins dans cette région.

Maintenant à vous d'essayer...

## Test de l'entrainement
1. Connecter vous via un navigateur Internet à l'URL suivant : `https://[IP de votre TJBot]:1880/visualtj`
2. Cliquer sur `Prendre Photo`
3. Cliquer ensuite si la photo vous convient sur `Analyse`
4. Le TJBot doit avoir reconnu un de vos produits et vous l'avoir dit à l'oral avec quelques informations additionnelles.

Bravo. Vous avez mérité un petit jeu. 


