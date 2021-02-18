# DecisionTree
A Java program using "ID3" and "C4.5" algorithms to build a decision tree. Once trained, the tree is then used to classify some data.

Le programme utilise l'algorithme Id3 et C4.5 pour créer un arbre de décision à partir de données d'apprentissage.
L'arbre est ensuite parcouru pour prédire la classe des données d'un ensemble de test.
Les résultats et performances sont données sous forme de matrices de confusion :

![](https://github.com/SimonGuilbert/DecisionTree/blob/main/Code/Data/Matrices.PNG)

### Mode d'emploi du programme sur l'arbre de décision
* 1ère méthode : avec un terminal
  * Télécharger ce dépôt
  * Ouvrir un terminal
  * Avec la commande cd, se déplacer à l'emplacement du dossier DecisionTree
  * Entrer la commande cd Code
  * Écrire javac Main.java
  * Écrire java Main
  * Si ça ne fonctionne pas, regarder ceci : https://fr.wikihow.com/compiler-et-ex%C3%A9cuter-un-programme-Java-en-ligne-de-commande
  
* 2ème méthode : avec Eclipse
  * Télécharger ce dépôt
  * Télecharger Eclipse gratuitement : https://www.eclipse.org/downloads/
  * Ouvrir Eclipse
  * File > new > Java Project
  * Décocher Use Default Location
  * Dans la zone de texte Location: écrire le chemin amenant au dossier Code (sous-dossier de DecisionTree)
  * Finish
  * A gauche, dans l'onglet Package Explorer, clic droit sur Code
  * Run As > Java Application
