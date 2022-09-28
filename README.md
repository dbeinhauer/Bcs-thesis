# About
This repository contains the LaTeX sources for my bachelor thesis.

* Implementation portion available in 
[bcs-source repository](https://github.com/dbeinhauer/bcs-source).

Repository content.
* For download **thesis** as 
[.pdf here](https://raw.githubusercontent.com/dbeinhauer/bcs-thesis/main/text/tex_thesis/thesis.pdf) 
or online 
[through github](https://github.com/dbeinhauer/bcs-thesis/blob/main/text/tex_thesis/thesis.pdf).
* For download **errata** as 
[.pdf here](https://raw.githubusercontent.com/dbeinhauer/bcs-thesis/main/text/tex_errata/thesis.pdf)
or online 
[through github](https://github.com/dbeinhauer/bcs-thesis/blob/main/text/tex_errata/thesis.pdf)
* For download **poster** as 
[.pdf here](https://raw.githubusercontent.com/dbeinhauer/bcs-thesis/main/poster/drawing.pdf)
or online 
[through github](https://github.com/dbeinhauer/bcs-thesis/blob/main/poster/drawing.pdf)

Note that all the text in this repository is written in Czech.

# Abstract (EN)
As the number of electric vehicles grows, so does the need to create a suitable
network of charging stations. A solution of this problem can be significantly
improved by the usage of suitable optimization techniques.
We implement a simplified traffic simulator serving as a suitable tool for 
their analysis.
We also analyze optimization techniques using the so-called greedy algorithm,
genetic algorithm and k-means algorithm. Based on the experiments, the optimizations 
using the genetic algorithm and the greedy algorithm showed noticeably better results.
The k-means method did not show signs of results better than a
random approach.


# Abstract (CZ)
S rostoucím počtem elektrických vozidel roste i potřeba vytvořit vhodnou 
infrastrukturu pro jejich nabíjení. K řešení tohoto problému může výrazně 
napomoci použití vhodných optimalizačních metod. V práci jsme implementovali 
zjednodušený simulátor dopravy sloužící jako vhodný nástroj pro jejich analýzu.
Analyzovali jsme také optimalizační metody tzv. hladovým algoritmem, 
genetickým algoritmem a algoritmem k-means. Na základě experimentů 
vykazovala prokazatelně lepší výsledky optimalizace za využití 
genetického algoritmu a hladová optimalizace. K-means optimalizace 
nevykazovala známky lepších výsledků oproti náhodnému přístupu.


# Prerequisities
* LaTeX (`texlive-full` or equivalent)

# Building
* Makefile for **thesis** is located 
[in](https://github.com/dbeinhauer/bcs-thesis/blob/main/text/tex_thesis/Makefile) 
`text/tex_thesis/Makefile`
* Makefile for **errata** is located
[in](https://github.com/dbeinhauer/bcs-thesis/blob/main/text/tex_errata/Makefile)
`text/tex_errata/Makefile`

# Original template
LaTeX templates are based on the (un)official MFF CUNI template for typesetting bachelor 
thesis available [here](https://github.com/mff-cuni-cz/better-thesis).