# Exercice 4 : Création d'un champ de recherche avec un label caché

Votre tâche consiste à créer un champ de recherche avec un label caché pour améliorer son accessibilité.

Commencez par créer un formulaire avec un rôle de "search". Dans ce formulaire, vous aurez besoin de créer un label et un champ de saisie de texte. Le label doit être associé au champ de saisie via l'attribut for, qui doit correspondre à l'attribut id du champ de saisie.

Ajoutez un texte explicatif dans le label, par exemple "Rechercher par mot clé", mais assurez-vous qu'il n'est pas visible à l'écran en ajoutant la classe CSS "sr-only" (pour Screen Readers Only).

Ensuite, créez votre champ de saisie de texte. Ajoutez un attribut placeholder à ce champ avec une indication courte de ce que l'utilisateur doit entrer, par exemple "Rechercher".

Voici le code CSS à utiliser :
```css
.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0,0,0,0);
    border: 0;
}
```
