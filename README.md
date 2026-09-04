# La Pension

Un jeu de poche : on élève des Pokémon dans une pension, on les envoie
nettoyer des donjons, on revient plus fort.

**Jouer : https://goboue0837-star.github.io/la-pension/**

Ce dépôt ne contient que le **résultat publié** — la page assemblée et les
ressources qu'elle charge. Le code source vit à côté, rangé ainsi :

```
src/donnees/   des faits, aucune logique
src/moteur/    les règles, indépendantes du contenu
src/jeu/       les écrans et la partie
media/         ce que le jeu charge
outils/        la tuyauterie (assemblage, sprites, serveur de dev)
```

```
index.html     la page entière, assemblée par outils/page.py
assets/
├── sprites/   les Pokémon, animations utiles seulement, + leurs brillants
├── tuiles/    les décors de donjon (DTEF)
├── vfx/       les planches d'effets d'attaque
└── objets/    le décor posable
```

Sprites et effets viennent de [PMD Sprite Collab](https://github.com/PMDCollab/SpriteCollab).
