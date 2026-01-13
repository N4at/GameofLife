# 🧬 Conway's Game of Life
Bienvenue dans cette simulation d'automate cellulaire imaginée par le mathématicien John Conway. Ce n'est pas un "jeu" au sens traditionnel : c'est un système qui évolue de manière autonome à partir d'une configuration initiale, révélant des comportements d'une complexité fascinante à partir de règles ultra-simples.

# 🎬 Actions
Bien que ce projet soit basé sur une interface terminal (CLI), l'évolution des cellules crée une véritable danse visuelle. On peut y observer :

1. Les Structures Stables : Des formes qui ne changent jamais.
2. Les Oscillateurs : Des motifs qui se répètent en boucle.
3. La Croissance et le Chaos : Des configurations qui s'étendent indéfiniment ou s'effondrent de manière imprévisible.

# ✨ Technologies
Ce projet est construit pour être léger, rapide et exécutable directement dans votre console :

Node.js : Pour l'environnement d'exécution.

Readline API : Pour gérer les interactions utilisateur en ligne de commande.

JavaScript : Pour la logique algorithmique des générations.

# 📍 Le Process
Le moteur du jeu suit quatre règles fondamentales appliquées simultanément à chaque cellule :

- Naissance : Une cellule morte avec exactement 3 voisines vivantes devient vivante.

- Survie : Une cellule vivante avec 2 ou 3 voisines vivantes reste en vie.

- Solitude : Une cellule vivante avec moins de 2 voisines meurt.

- Surpopulation : Une cellule vivante avec plus de 3 voisines meurt.

# 🚦 Run le Projet :
Pour lancer la simulation sur votre machine, suivez ces étapes simples :

1. Cloner le repository : `git clone https://github.com/N4at/GameofLife.git`
2. Accéder au dossier : `cd GameofLife`
3. Installer les dépendances : `npm install`
4. Lancer le jeu : `node index.js`

Une fois lancé, suivez les instructions dans votre terminal pour configurer votre grille et regarder la vie s'épanouir..... ou mourir !
