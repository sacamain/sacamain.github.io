---
layout: post
title: Essai de syntaxe MarkDown avec Jekyll
tags: jekyll essai markdown
published: true
---

## Comment insérer une image

![alt text]({{ site.url }}/images/sacamain.png 'mon avatar'), issu de OpenClipart.
Il s'agit d'un sac à main.

## Lien externe

Un lien vers [Jekyll Now](http://github.com/barryclark/jekyll-now/).<br>
Un lien vers [Markdown](https://raw.githubusercontent.com/barryclark/www.jekyllnow.com/gh-pages/_posts/2014-6-19-Markdown-Style-Guide.md).

Pour faire des liens avec des références : par exemple [la doc de Markdown] [markdown] est ici.

[markdown]: http://daringfireball.net/projects/markdown/syntax#html "Markdown: Syntax"


## Comment faire un lien interne 

Un lien sur [about](/about/).

## Comment insérer du code

```python
def toto:
    print "blah"

```

On peut aussi utiliser 4 espaces ou 1 tab:

   print "ca marche aussi"


## Comment faire des itérations

Pour faire des items, il ne faut pas oublier une ligne d'espace :

* un
* deux
* trois

Ou 

1. un
2. deux
3. trois

Ou 

- un
- deux
- trois

Pour mettre du code dans une itération :

- Il faut mettre 8 espaces ou 2 tabs:

     printf('%d',c);


## Lignes

Une ligne horizontale, on peut faire ça de deux façons différentes.

----
****

## Effets

_italique_

**bold**

`un peu de code()`

> Je cite
>> Je cite à l'intérieur

## Insertion d'un tableau

<table>
 <tr><td>Ca marche</td><td>Aussi</td><td>Avec la syntaxe HTML</td></tr>
</table>

Une autre façon de faire les titres H2
--------------------------------------

On peut mettre juste une ligne et ça marche.
