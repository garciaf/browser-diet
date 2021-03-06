---
order: 12
title: Toujours utiliser la dernière version de jQuery
---

L'équipe en charge du noyau de jQuery cherche constamment à améliorer la performance de la librairie, en utilisant du code plus lisible, de nouvelles fonctionnalitées et en optimisant les algorithmes existants.

<div class="img-right">
  <img id="geek-36" class="icos-geek" src="http://browserdiet.com/img/36.png" alt="Geek #36" width="144" height="275" />
</div>

Pour cette raison, utilisez toujours la dernière version de jQuery, elle est toujours disponible ici, si vous voulez la copier localement:

```html
http://code.jquery.com/jquery-latest.js
```

Mais ne déclarez _jamais_ cet URL dans une balise `<script>`, cela vous posera des problèmes dans le future car la dernière version se retrouvera sur votre site dès qu'elle sortira, avant même que vous ayez put la tester. A la place mettez un lien à la dernière version spécifique de jQuery que vous souhaitez. 

```html
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
```

Comme le sage [Barney Stinson](/img/new-is-always-better.gif) dit, *"Le nouveau est toujours mieux"* :P

*> [References](https://github.com/zenorocha/browser-diet/wiki/References#always-use-the-latest-version-of-jquery)*