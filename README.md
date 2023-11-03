# P2_Booki : Transformez une maquette en site web avec HTML & CSS
> Intégration de Maquette - Parcours Openclassrooms Développeur Web

Vous avez trouvé votre premier stage en tant que développeur web chez Booki, une petite entreprise proposant un outil de planification de vacances ! Son site permet aux usagers de trouver des hébergements et des activités dans la ville de leur choix. Les hébergements peuvent également être filtrés par thématique, par exemple leur budget ou leur ambiance.

Un nouveau design basé sur les principes du Material Design vient d’être réalisé par Loïc, designer UI.

![Maquette Desktop](https://github.com/thealamenthed/p2/assets/90263288/fdb0214d-ba06-494a-9d99-72cbebde80ff)


Avant de valider définitivement le design, l’entreprise a décidé de réaliser un prototype. Vous êtes chargé de créer ce prototype en intégrant la maquette en HTML et CSS.

Voici l’ensemble des points techniques et fonctionnels à prendre en compte pour le développement du nouveau site Booki. L’ensemble de ces éléments ont été validés par l’équipe Produit, il est donc important de les respecter.

## Spécifications fonctionnelles

Les usagers pourront rechercher des hébergements dans la ville de
leur choix. Le champ de recherche est un champ de saisie, le texte
doit donc pouvoir être édité par l’utilisateur. Il faut englober ce
champ dans un formulaire pour que ce dernier soit valide auprès du
W3C. La partie recherche ne doit pas être fonctionnelle.
* Chaque carte d’hébergement ou d’activité devra être cliquable dans
son intégralité (pas uniquement le titre). Pour l’instant, les liens sont
vides. On peut utiliser un attribut href=”#” pour simuler la
présence d’un lien.
* Les filtres doivent changer d’apparence au survol. Je te laisse décider
de l’effet approprié, je n’ai pas encore eu le temps de me pencher
dessus. Par contre, ils ne doivent pas être fonctionnels.
* Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont
des liens. Ils doivent mener respectivement vers la section
“Hébergements à Marseille” et “Activités à Marseille”.

## Spécifications techniques

* Trois maquettes ont été réalisées : desktop, tablette et mobile.
* Breakpoints : Nous avons convenu avec le designer UI d’utiliser 1024 px et 768 px : >1024 px pour les écrans d’ordinateurs ; >=768 px pour les tablettes ; et tout ce qui est en dessous de 768 pour les téléphones portables.
Largeur min - max
Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer
une largeur maximum de 1440 px. Au-delà, une marge blanche doit apparaître sur les
côtés et le contenu doit se limiter à 1440 px de large.
La largeur minimum est fixée à 320 px, en-deçà de cette largeur, le comportement n’est
pas garanti.
* Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first),
puis les tablettes et enfin les téléphones. L’utilisation des Media Queries nous permettra
de réaliser l’intégration pour les différents supports.
* Les icônes proviennent de la bibliothèque Font Awesome.
* Les couleurs de la charte sont le bleu (#0065FC), le bleu clair (#DEEBFF) et le gris pour le
fond (#F2F2F2).
* La police du site est Raleway. Nous pouvons passer par Google Fonts pour importer
facilement cette police dans le code : https://fonts.google.com/specimen/Raleway
Mise en page Il est recommandé d'utiliser Flexbox.
* Il est important d’utiliser des balises sémantiques, au minimum “header”, “nav”, “h1-h2-h3”, “main”, “section”, “article” et “footer”.


Aucun IDE ou éditeur de code particulier n’est imposé pour le développement.
Le code doit être valide aux validateurs W3C HTML et CSS.
Le code HTML ne doit pas contenir de propriété CSS.
Lors du passage du desktop au mobile et à la tablette, ne pas dupliquer le code
HTML (exception faite dans le formulaire avec le mot “Rechercher” et l’icône de la
loupe).

Privilégier l’utilisation des classes CSS pour cibler un élément, plutôt que d’utiliser
le nom de l’élément lui-même.
Ne pas dupliquer des classes CSS inutilement. Exemple : si 4 éléments sont
identiques du point de vue de la mise en forme, alors utiliser une seule et même
classe CSS, et non pas 4.

* Compatibilité navigateurs : La maquette doit être compatible avec les dernières versions de Google Chrome et de
Mozilla Firefox. Il faudra tester la page web sur ces deux navigateurs.
* Restrictions : Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass
ou Less) ne doit être utilisé.
Aucun autre langage ne doit être utilisé (comme JavaScript, par exemple).
