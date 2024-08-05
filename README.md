Sito ivotek.it
==============

## Struttura

Il progetto è diviso in sezioni ("categorie" nel linguaggio Jekyll). Ogni sezione ha una directory dedicata con le
pagine corrispondenti.

* `robotics-projects`: /robotica/progetti/_posts
* `robotics-tutorial`: /robotica/tutorial/_posts
* `electronics-manuals`: /elettronica/manuali/_posts
* `electronics-projects`: /elettronica/progetti/_posts
* `programming-basic`: /programmazione/basic/_posts
* `programs-electronics`: /programmi/elettronica/_posts
* `programs-robotics`: /programmi/robotica/_posts
* `courses`: /corsi/_posts

La struttura delle pagine dentro le relative cartelle "_posts" segue le stesse regole
di [MignoloLab](https://github.com/mignololab/website/). Aggiungendo una pagina in una categoria sarà aggiunta
automaticamente una voce nella pagina indice di tale categoria.

La categoria deve essere menzionata nel _front matter_ della pagina del progetto/articolo/ecc.:

```yaml
---
layout: project
title: "Domestica V1"
summary: "Robot aspirapolvere, semplice ed economico."
category: robotics-project
poster: domestica_v1/images/domestica_v1_robot.jpg
permalink: /robotica/progetti/:title/
---
```

## Pagine statiche

Le seguenti pagine sono statiche (nel senso che non hanno pagine figlie):

* /elettronica/datasheet
* /programmi/elettronica
* /programmi/robotica
* /corsi
* /contatti
