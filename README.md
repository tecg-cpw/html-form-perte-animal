# Les formulaires
Créer le document index.html avec le formulaire suivant :

![Rendu de la page avec CSS](./img/rendu.webp "rendu avec CSS de la solution" )

---

## Consignes
- l’identifiant du formulaire est "disparition"
- le script qui reçoit les données se trouve à l’URL (sur serveur interne) **/form.php**
- le texte « * pour les champs obligatoires » est dans un paragraphe identifié "required-field-symbol"
- chaque ligne est dans une `div` de la classe `row`
- chaque label est lié à son champ
- le premier champ obtient automatiquement le focus
- les noms des champs sont dans l’ordre : *email*, *vemail*, *tel*, *country*; *animal-type*, *animal-name*, *chip*, *gender*, *age*, *race*, *tatoo*, *tatoo-code*, *description*, *animal-photo*; *disparition-date*, *disparition-time*, *postal-code* et *disparition-country*
- s'il est envoyé avec la méthode GET, la query string est : https://tecg-cpw.github.io/form.php?email=dominique.vilain%40hepl.be&vemail=dominique.vilain%40hepl.be&tel=04+279+76+16&country=be&animal-type=dog&animal-name=Rex&chip=12345678&gender=male&age=2&race=poodle&tatoo=left-ear&tatoo-code=B999AA&description=IL+est+beau&animal-photo=&disparition-date=2024-12-12&disparition-time=12%3A30&postal-code=4000&disparition-country=be (notez que le fichier n’y est pas puisque la méthode GET ne permet pas d’envoyer un fichier)
- veillez à bien respecter le caractère obligatoire des champs marqués d’une astérisque (*)
- veillez à bien respecter tous les *placeholders*
- veillez à utiliser pour chaque champ un attribut title adéquat (info-bulle explicite qui renseigne l’Internaute sur l’information à entrer)
- les adresse e-mail sont limitées à 60 caractères maximum et ont une taille apparente de 40 caractères
- le numéro de téléphone est limité à 20 caractères maximum et possède une taille apparente de 20 caractères
- les options pour le pays (des coordonnées) sont *Belgique*, *France* et *Luxembourg* et les valeurs envoyées au serveur sont respectivement *be*, *fr* et *lu*
- les options pour le type d’animal sont *Chien* et *Chat* et les valeurs envoyées au serveur sont respectivement *dog* et *cat*
- le nom de l’animal est un texte limité à 40 caractères maximum et possède une taille apparente de 40 caractères
- la puce de l’animal est un texte limité à 15 caractères maximum et possède une taille apparente de 15 caractères
- les boutons radio pour le genre de l’animal sont dans un *div* de la classe "radio-set" en plus de "row" avec
	- le texte « Sexe »
	- le label « Femelle », suivi d’un bouton radio de valeur ’female’
	- le label « Mâle », suivi d’un bouton radio de valeur ’male’
- l’âge de l’animal est un nombre entre 0 et 150, il est suivi d’un span dans la classe "info"
- la race de l’animal est un texte limité à 40 caractères maximum et possède une taille apparente de 40 caractères et celui-ci possède une **datalist** associée avec différentes races de chiens dont : *Basset*, *Beagle*, *Bichon*, *Caniche (poodle)*, *Épagneul (spaniel)*, ...    
- les options pour l’endroit de tatouage sont *Oreille gauche*, *Oreille droite*, *Cuisse gauche* et *Cuisse droite*, et les valeurs envoyées au serveur sont respectivement *left-ear*, *right-ear*, *left-tigh* et *right-tigh*
- le tatouage de l’animal est un texte limité à 6 caractères maximum et possède une taille apparente de 6 caractères
- la zone de texte pour la description s’étend sur 50 colonnes et possède une taille apparente de 4 lignes
- la photo de l’animal n’accèpte que les fichiers de type *image/gif*, *image/jpg* ou *image/png*
- la date de disparition est suivie d’un span dans la classe "info"
- l’heure de disparition est suivie d’un span dans la classe "info"
- le code postal est un texte limité à 5 caractères maximum et possède une taille apparente de 5 caractères
- les options pour le pays (de la perte) sont *Belgique*, *France* et *Luxembourg* et les valeurs envoyées au serveur sont respectivement *be*, *fr* et *lu*
