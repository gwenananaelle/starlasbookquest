---
layout: default
title: "Bienvenue"
lang: "fr"
---
## Bienvenue!
Starla a besoin de votre aide pour mettre en lumière une sélection de livres en l'honneur des Utopiales!<br>
Au lieu de chercher dans une pièce, vous allez chercher dans ce blog : « Space Queen Starla's bookquest » afin de trouver 5 livres à mettre en avant dans son post spécial pour les Utopiales.<br>
Une fois les 5 livres trouvés, il vous suffira d'un code à 3 chiffres pour lancer la publication du post et terminer votre mission.<br>
Vous avez toutes les informations dès le début, ce qui peut s'avérer très compliqué, surtout si vous n'êtes pas sûr de ce que vous cherchez. N'hésitez pas à consulter les indices [to be added] pour vous aider au fur et à mesure de votre progression.<br>
En cas de problème technique ou si vous êtes vraiment bloqué, vous pouvez toujours « contacter un humain » [to be added] et obtenir de l'aide.<br>

{% assign filtered_puzzle_lang = site.puzzles | where: 'lang', page.lang %}
<ul>
  {% for puzzle in filtered_puzzle_lang %}
    <li>
      <h5><a href="{{ puzzle.url | absolute_url}}">{{ puzzle.title }}</a></h5>
    </li>
  {% endfor %}
</ul>