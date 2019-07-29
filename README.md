## - Project Snake

Udemy course <br>

Contient un Snake en JavaScript et un peu de documentation

### 1 - Gros plan sur les scopes

- Context d'éxécution :
  A chaque fois qu'une fx est éxécuté on créé un contexte d'éxécution pour le code à l'interieur de cette fx <br>
  Le contexte d'éxécution global est tout le code en dehors des fx <br>
  Le contexte d'éxécution est composé de 3 choses :
  1 - Objet des variables (toutes les variables et fx définies dans ce contexte / bout de code)
  2 - La chaine des scopes (toutes les variables auquel notre bout code aura accès)
  3 - Le `this` (l'objet qui est associé à notre bout de code)

  - Objet des variables :
    Il contient les arguments de la fonction, les déclarations de fonctions (avec le hoisting), les déclarations de variables (avec le hoisting)

- Chaînes des Scopes :
  le code à l'intérieur d'une fonction est le scope local <br>
  Une fonction "enfant" peut accéder au scope de sa fonction "parent" = une fonction déclarée dans une fonction peut accéder au scope de celle-ci
