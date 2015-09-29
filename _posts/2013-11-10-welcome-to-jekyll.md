---
title:  "Créer un site static avec Jekill!"
date:   2015-10-01 10:00:00
description: Thriller Comedy Horror
---

Nous recherchons toujours les solutions les plus efficaces pour nos clients afin de
répondre à leurs problématiques. Mais un cordonnier est toujours le plus mal chaussé
et nous trainons bien sans mal notre blog (Eoko)[http://eoko.fr] depuis trop longtemps.

À l'origine, notre vision du blog n'était pas sans ambition, nous voulions échanger et
partager notre savoir. Mais nous ne conaissions pas encore cette univers.

# Vous avez dit Blogger?

Pour nous, être bloggeur ou tout du moins blogguer ne doit se résumer qu'à 4 éléméents :

  + penser
  + structurer
  + écrire
  + et publier.

Notre propre expérience nous a enseigné que blogguer c'était plutôt :

- Mettre à jour Wordpress
- Trouver des plugins
- Lire la documention
- Configurer
- Se protéger des attaques
- Se battre contre l'éditeur
- Désactiver l'éditeur... pour le réactiver
- Mettre en place des captchas
- Supprimer les commentaires inadéquates
- Nettoyer les spams
- ...

Tout ces petits soucis ce sont accumuler et pour être franc : avoir un Wordpress
c'est une plaie.

Cela fait maitenant un bon mois que l'idée de faire sortir Wordpress est ancré dans
nos pensées avec un seul objectif : trouver la meilleurs solution pour notre Blog.

# Mais qu'est ce que la meilleur solution pour nous?

Finalement,
Notre métier, trouver la solution la plus efficace
aux problèmes de nos clients.



Alors voilà, après avoir officiné quelques années sur Wordpress, on a pas pu
s'empêcher : Go To Hell!




Les premières lignes écritent sur un blog sont souvent
You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

Jekyll also offers powerful support for code snippets:

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```


```php
<?php

echo "test";

```

Result	Markdown
**text**
*text*
~~text~~
[title](http://eoko.fr)
`code`
![alt](http://eoko.fr)

* item
* item

> quote
# Heading
## Heading
### Heading



{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
