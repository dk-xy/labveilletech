---
title: "Framing, un coup d'oeil"
date: 2022-12-12T15:22:29+01:00

---
### **Let websites framebust out of native apps** 
| Adrian Holovaty
[Liens de l'article](https://www.holovaty.com/writing/framebust-native-apps/?ref=sidebar)

## Pourquoi cet article ?
Le framing, une pratique particulièrement agaçante. Mais qu’est-ce que c’est en quelques mots?

Mais qu’est-ce que ce mot étrange ? Il provient de la balise HTML < frame > permettant d’afficher du contenu indépendant de la page ou elle est située. Un des exemples notables serait les vidéos youtubes pouvant être intégré à des sites à l’aide de < iframe >

## Qu’est-ce que tu as appris?

### Historiquement dans le web…

Premièrement, l’article nous raconte un historique assez détaillé sur le cas de TotalNews, un site reprenant les grandes publications journalistiques telles que le New York Times ou le Washington Post, pour les réunir au sein d’une même page. En 1997, TotalNews se fait poursuivre par The Washignton Post, et la décision de justice en résulte que TotalNews est interdit d’incorporer les articles the TWP.

On apprend aussi que la pratique du clickjacking fut créée grâce à cette balise, ou l’on fait croire à un utilisateur qu’il clique quelque part, mais une frame invisible est placée au-dessus pour changer les actions du click. Mais cela reste dans le passé, car des headers HTTP spéciaux permettent d’empêcher ce genre de pratiques, ce qu’on appelle le framebusting (https://en.wikipedia.org/wiki/Framekiller)


### ...et aujourd’hui

Les bonnes pratiques du W3C proscrivent à ce jour l’utilisation des frames dans le développement web. Aujourd’hui, le framing est encore utilisé par des applications natives, tels que Reddit et Facebook, afin de donner l’illusion qu’une page est ouverte sur un navigateur.  Cela permet notamment aux applications de garder le contrôle sur les données de leurs utilisateurs et de voir le parcours qu’ils suivent hors de celle-ci.

Cela impacte négativement l'expérience utilisateur pour plusieurs raisons, la principale étant qu’il perd les outils principaux de son navigateur (tels que les extensions de blocage de publicités…)
 
## Que vas-tu faire de cet article?

Il m’a permis de mieux identifier les raisons de l’utilisation d’un tag frame. Il m’apporte des connaissances du côté technique pour mieux prototyper ce genre de projets. Ce qui était fait anciennement fait par framing à été remplacé par les multiples API. Toutefois, nous ne sommes pas à l'abri d’une évolution de l’utilisation du web, et savoir utiliser correctement les frames pourrait s’avérer utile un jour. Pour l’instant, j’en tire principalement les mauvaises pratiques liées à ceux-ci