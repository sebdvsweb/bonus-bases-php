Exercices de Programmation en PHP
Exercice 1: Boucles et Conditions
Écrire un script PHP qui affiche tous les nombres de 1 à 50. Si le nombre est divisible par 3, affichez "Fizz" à la place. Si le nombre est divisible par 5, affichez "Buzz". Si le nombre est à la fois divisible par 3 et par 5, affichez "FizzBuzz".

Exercice 2: Tableaux et Boucles
Créer un tableau associatif représentant une liste d'étudiants avec leur note (sur 20). Ensuite, affichez la moyenne de la classe.

Exercice 3: Boucles et Conditions
Écrire un script PHP qui génère un tableau de 10 nombres aléatoires entre 1 et 100. Ensuite, affichez le plus grand nombre du tableau et son index.

Exercice 4: Tableaux et Boucles
Créez un tableau associatif représentant une équipe de Pokémon. Chaque Pokémon a un nom, un type (Feu, Eau, Plante, etc.) et un niveau (entre 1 et 100). Affichez tous les Pokémon de l'équipe avec leur niveau. Ensuite, ajoutez 10 niveaux à chaque Pokémon et réaffichez l'équipe.

Exemple :
php
Copy code
"Pikachu" => array("type" => "Électrique", "niveau" => 45)
Exercice 5: Conditions et Fonctions
Créez une fonction en PHP qui prend en paramètre le nombre de points marqués par une équipe dans un match de football. Affichez "Victoire" si l'équipe a marqué plus de 2 buts, "Match nul" s'ils ont marqué exactement 2 buts, sinon affichez "Défaite".

Exercice 6: Boucles et Conditions
Écrire un script PHP qui génère la table de multiplication de 7 jusqu'à 10. Affichez le résultat sous la forme "7 x 1 = 7", "7 x 2 = 14", etc.

Exercice 7: Tableaux et Boucles
Créer un tableau de noms d'animaux. Affichez tous les animaux dont le nom commence par la lettre "C". Utilisez une boucle et une condition.

Exercice 8: Boucles et Conditions
Écrire un script PHP qui calcule la somme des carrés des nombres de 1 à 10. Affichez le résultat.

Bonus: Gestion d'inventaire
Imaginez que vous gérez l'inventaire d'une boutique de jeux vidéo. Vous avez une liste de jeux avec leur nom, leur genre, leur prix et leur quantité en stock. Vous souhaitez créer une fonction qui permet de mettre à jour l'inventaire en fonction des ventes.

Utilisez un tableau associatif :
php
Copy code
array("nom" => "The Legend of Zelda: Breath of the Wild", "genre" => "Action-Adventure", "prix" => 59.99, "quantite" => 20)
Créez une fonction qui prend en paramètre l'inventaire, le nom du jeu à vendre et la quantité vendue. Elle parcourt l'inventaire pour trouver le jeu correspondant. Si le jeu est trouvé et si la quantité vendue est inférieure ou égale à la quantité en stock, la fonction met à jour la quantité en stock et affiche un message de succès. Sinon, elle affiche un message d'erreur en cas de stock insuffisant ou si le jeu n'est pas trouvé.
