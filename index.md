---
layout: default
title: "Bienvenue"
---

## Bienvenue!
Starla a besoin de votre aide pour mettre en lumière une sélection de livres en l'honneur des Utopiales, et elle a besoin de votre aide pour y parvenir!
Au lieu de chercher dans une pièce, tu vas chercher dans ce blog : « Space Queen Starla's bookquest » afin de trouver 5 livres à mettre en avant dans son post spécial pour les Utopiales.
Une fois les 5 livres trouvés, il vous suffira d'un code à 3 chiffres pour lancer la publication du post et terminer votre mission.
Vous avez toutes les informations dès le début, ce qui peut s'avérer très compliqué, surtout si vous n'êtes pas sûr de ce que vous cherchez. N'hésitez pas à consulter les indices pour vous aider au fur et à mesure de votre progression.
En cas de problème technique ou si vous êtes vraiment bloqué, vous pouvez toujours « contacter un humain » et obtenir de l'aide.

<ul>
  {% for puzzle in site.puzzles %}
    <li>
      <h2><a href="{{ puzzle.url }}">{{ puzzle.title }}</a></h2>
    </li>
  {% endfor %}
</ul>