# Exercice 5 : Relier plusieurs informations - Format et message d'erreur

Votre tâche est de créer un champ de formulaire pour une adresse email et de le relier à une indication de format et à un message d'erreur.

Commencez par créer un label pour un champ de formulaire destiné à recueillir une adresse email. Ensuite, créez un élément div qui fournit une indication du format attendu pour l'adresse email (par exemple, "jean.dupont@exemple.com").

Créez un autre élément div qui contient un message d'erreur (par exemple, "Veuillez saisir un email valide."). Assurez-vous d'attribuer à chaque div un identifiant unique.

Lorsque vous créez votre champ de saisie de texte pour l'adresse email, utilisez l'attribut aria-describedby pour le lier aux div contenant l'indication de format et le message d'erreur. Assurez-vous d'inclure les identifiants de ces div dans l'attribut aria-describedby dans l'ordre dans lequel ils doivent être lus par les lecteurs d'écran. Dans cet exemple, le message d'erreur doit être lu en premier, suivi de l'indication de format.
