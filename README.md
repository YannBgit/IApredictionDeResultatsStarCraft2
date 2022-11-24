# IApredictionDeResultatsStarCraft2
Mise en place d'un réseau de neurones permettant de prédire des résultats de parties de StarCraft 2

Réalisé par :
- Yann BARBIER 21800844
- Fanoa RAZAFIMBELO 22105665

Idée générale :
Le réseau de neurones est entraînés sur des milliers de replays parsés à chaque instant.
Elle doit déterminer qui va gagner étant donné un instant donné d'une partie.

Idée de parseur de replays :
https://github.com/ggtracker/sc2reader

Le programme utilise un GPU de google colab pour entraîner le réseau de neurones :
https://colab.research.google.com/