<!-- !Les frameworks JavaScript -->

Un framework (ou infrastructure logicielle en français ) désigne en programmation informatique un ensemble d'outils et de composants logiciels à la base d'un logiciel ou d'une application. C'est le framework, encore appelé structure logicielle, canevas ou socle d'applications en français, qui établit les fondations d'un logiciel ou son squelette applicatif. Tous les développeurs qui l'utilisent peuvent l'enrichir pour en améliorer l'utilisation.

L'objectif du framework est de simplifier et d'uniformiser le travail des développeurs. Il fonctionne comme un cadre ou un patron, mais son maniement suppose d'avoir déjà un profil expérimenté. En général, une infrastructure logicielle est associée spécifiquement à un language de script ou de programmation. Par exemple, Hibernate est un framework pour JavaScript et Django pour Python.

<!-- !En resumé :  -->

Un framework est un cadre de travail qui permetde créer des application web et mobiles, un framework propose une bibliothèque de fonctionnalités dans laquelle les developpeurs vont pouvoir piocher en fonction des besoins, l'utilisation de framework permet de gagner du temps et aujourd'hui il s'agit d'un standard dans la construition d'un projet web. C'est pour cette raison qu'on a pour habitude de les comparer a une boite a outils.

<!-- ! LES FRAMEWORK FRONT END  -->

Ces frameworks servent a definir ce que va voir le visiteur lorsque qu'il va arrive sur la site. En exemple de frameworks front end on peut retrouver Vue.js, react, angular et bien d'autre

<!-- ! CHOISIR UN FRAMEWORK JAVASCRIPT -->

À noter que la performance entre les différents frameworks ne diffère pas réellement et est inhérente à l’utilisation qui en est faite. Ce n’est donc pas un critère de différenciation.

<!-- * PolymerJs -->

Polymer.js est une bibliothèque JAvaScript open source pou la creation d'application web a l'aide de composant web.
Cette bibliothèque est developpée par des developpeurs Google et a des colaborteurs GitHub. Contrairement a toute autre frame work JavaScript, Polymer est concu pour tirer partie des fonctionnalité presente sur la plateforme web pour permettre au developpeurs de créer des composant. c'etait la toute premiere bibliothèque a permettre des application de construction interactive des composants.
C’est la meilleure bibliothèque pour introduire une structuration interactive des applications en compilant des composants.
Elle est utilisé par les services de Google et de nombreuse autres plateforme comme youtube, Netflix, Mc Donalds, IBM...
La popularité de Polymer.JS sur le marché peut etre attribué a ses procédures de conception structuré à savoir les composants. la raison meme pour laquelle ils ont renforcé le support de composant web et disposent de modules hors ligne execptionnels par rapport a React.

PolymerJS dispose deplusieurs caracteristique comme :

- une consception avec les meilleur API des normes Web, ce qui permet de creer des elements HTML personalisé.
- Une possibilité de créer vos porpes modules reutilisable et personnalisable en utilisant les specificatyions des
  composants Web Polyfills<!--! * -->
- Une fonction de propriete calculées, qui permet 'afficher les mises a jour automatique lorsqu'une valeur calculé change.
- Unefonction de mise en page des applications, qui permettent de créer des conceptions réactives
- Il fournit une liaison de données unidirectionnelle et bidirectionnelle pour garantir un liaison unidirectionnelle <!--! ** -->
- Il encapsule les CSS, JavaScript et les modeles pour quele code de vos composants Web reste modulaire et séparé du reste du DOM a l'aide du Sahdow DOM <!--! *** -->
  Il est aussi possible de prendre en charge du developpement rapide et facile d'application hybrides ainsi que de créer des évenements gestuels

<!-- ?Quelque avantage de PolymerJS :  -->

Il vous permet de créer des composants qui faciliteront la compréhension du fonctionnement d’un même composant. Cela vous préparera à écrire des plugins en JavaScript.
Il vous donne la liberté de créer ce que les gens désirent.
Tout sera stocké dans des éléments et les codes sans importance seront éliminés automatiquement.
Réduit l’écart entre le développeur et le concepteur.
Il assure un équilibre de travail entre le designer qui travaille sur l’UX de la page Web et les développeurs qui sont plus concernés par la fonctionnalité de la page Web. Grâce aux éléments polymères (thèmes et designs), les développeurs n’ont pas à modifier le code source de pages Web complexes pour qu’il corresponde aux spécifications du concepteur.
Il est trois fois plus rapide sur Chrome et quatre fois plus rapide lorsqu’il est utilisé avec Safari. On estime qu’il est plus pratique et plus facile pour les développeurs de créer des applications et des sites Web riches en fonctionnalités.

<!-- ? Mais assi des inconvenients :  -->

La création de composants pour chaque navigateur prend beaucoup de temps. Vous devrez savoir comment les différents navigateurs fonctionnent avec le DOM caché.
Les performances seront relativement lentes lorsque vous utiliserez des appareils mobiles, car ces derniers ne disposent pas d’un moteur JS aussi puissant que celui du Web.
Il n’y a pas de clarté sur la façon dont vous pouvez organiser des applications plus grandes en utilisant Polymer JS.
Nécessite le téléchargement de la bibliothèque entière et des Polyfills.

<!-- ! * : Un polyfill est un bout de code (généralement en JavaScript sur le web) utilisé pour fournir des fonctionnalités récentes sur d'anciens navigateurs qui ne les supportent pas nativement. -->

<!-- ! ** Une relation décrit la dépendance ou la connectivité entre les éléments de configuration. Une relation peut être unidirectionnelle ou bidirectionnelle. Les résultats d'une recherche sont affectés lorsque les relations sont bidirectionnelles ou unidirectionnelles. -->

<!-- ! *** Le Shadow DOM est une technologie du navigateur conçue principalement pour limiter la portée des variables et du CSS dans les Web Components. Le DOM virtuel est un concept implémenté par les bibliothèques en JavaScript en plus des API des navigateurs. -->

En conclusion : Sur papier, PolymerJS offre une perspective attirante mais est en avance sur son temps.
Il requiert des fonctionnalités de composants avancées de navigateur qui sont encore en phase de normalisation par le W3C et qui n'ont pas encore été implémentées dans les navigateurs.
Exemples incluent shadow dom, modèle éléments, éléments personnalisés, importations HTML, observeurs de mutation, modèle orienté vues, événements de pointeur, et animations web. Bien que ce soient de bonnes technologies, elles ne sont pas actuellement disponibles sur les navigateurs modernes.
Polymer se base sur une stratégie pour que les développeurs front-end utilisent ces technologies qui seront bientôt normalisées par le W3C dès leur disponibilité sur les navigateurs.
Mais pour combler cette lacune, Polymer suggère l’utilisation de polyfills (code JavaScript téléchargeable qui fournit des fonctionnalités qui ne sont pas encore intégrées aux navigateurs) ou encore X-Tag (Mozilla).
Ces polyfills sont conçus de telle sorte qu’ils peuvent être facilement remplacés lorsque les navigateurs natifs introduisent ces technologies.

Erreurs de dépendance et versions
Vous rencontrerez des erreurs de dépendance qui indiquent des dépendances de versions différentes même dans les mêmes éléments, même si vous téléchargez les éléments Polymer.js comme recommandé. Il a déjà été établi que Ploymer.js est actuellement en cours de développement en ce qui concerne les problèmes de l’élément, mais il peut rendre le développement difficile, ce qui pourrait décourager les développeurs de travailler avec lui.
