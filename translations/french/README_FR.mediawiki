<pre>
  DEF: 1
  Title: The Social Smart Contract
  Author: @DemocracyEarth.
  Comments-Summary: No comments yet.
  Status: Active
  Type: Paper
  Created: 2017-07-14
  License: MIT
  Replaces: 0
</pre>

=Le contrat social intelligent.=
Une offre initiale de droits par la [http://democracy.earth Fondation Democracy Earth].

==i. Résumé.==

Dans un monde qui a réussi à globaliser les actifs financiers mais où les droits politiques restent foncièrement attachés à la notion de territoire, nous devons construire de nouveaux modèles de gouvernance démocratique qui permettent à l'humanité de collaborer et de résoudre les problèmes mondiaux urgents. La fondation Democracy Earth s'est fixé pour objectif de créer des logiciels libres et open source pour organiser des prises de décision (votations) qui ne soient pas sujettes à la corruption en s'appuyant sur la technologie blockchain, dans des organisations de toute taille, du plus local avec simplement deux personnes, au plus global en impliquant chacun d'entre nous. La répartition inégale des opportunités dans le monde, qui résulte de la confrontation perpétuelle entre les gouvernements nationaux, a conduit à l'accélération du changement climatique, à la croissance des inégalités, au terrorisme et aux migrations forcées. La fondation Democracy Earth considère que la technologie derrière le Bitcoin, qui permet la circulation de monnaie programmable sans passer par les banques centrales, et Ethereum qui supporte des contrats intelligents sans avoir besoin de tribunaux judiciaires, nécessite une nouvelle couche qui permet des votations incorruptibles au-delà des limites territoriales fixées par les États-nations. Ce réseau transnational agira conformément à la souveraineté personnelle de ses membres et protégera leurs droits fondamentaux grâce à des méthodes de cryptage des données. Dans notre ''offre initiale de droits'' (Initial Right Offering), nous offrons un ''token'' nommé «vote» qui accordera des droits de participation à chaque être humain avec pour principale fonction la prise de décision. Notre proposition introduit l'égalité induite par la cryptographie : tant qu'une personne est capable de valider son identité souveraine, elle recevra une part correspondante de ''votes'' égale à la part de chaque participant actif dans le réseau. Nous définissons un processus de ''preuve d'identité'' (Proof of Idendity) qui permet d'éviter l'intervention d'une autorité centrale en introduisant le concept de ''minage d'attention'' qui incite les participants à renforcer la confiance des  ''votes'' en effectuant des tests simples visant à détecter les ''replicants'' (doublons). Finalement, les ''votes'' sont distribués aux participants valides selon un mécanisme de revenu de base universel dans le but de trouver un équilibre adéquat dans la tension historique entre l'argent et la politique. Nous ne voulons rien de moins qu'une véritable gouvernance démocratique pour l'ère d'Internet, que nous considérons comme l'un des éléments fondamentaux pour parvenir à une paix et à une prospérité globales, rendues possible par les vagues d'innovations technologiques qui changeront ce que cela signifie d'être humain sur Terre.

==ii. Contenus.==

Ce texte est structuré en trois parties, chacune visant à satisfaire un type de lecteur différent (tous les types pouvant se retrouver dans le même profil).

* [[#Manifesto|Manifeste]]: Pour les idéalistes. Fait le diagnostic du contexte politique mondial et plaide pour un changement de paradigme.

* [[#Paper|Article]]: Pour les bâtisseurs. Décrit les fondations d'un système qui peut être mis en œuvre par n'importe qui, n'importe où.

* [[#Execution|Exécution]]: Pour les pragmatiques. Explique comment mettre en oeuvre ces idées pour avoir de l'impact.

Notre intention est que ce texte évolue. Il est publié sous une licence open source et nous accueillons toutes les contributions dans la mesure où notre objectif est que ce document constitue une feuille de route vivante pour une gouvernance mondiale. La démocratie comme capacité à se faire mutuellement confiance dans la mesure du possible est un facteur clé qui façonne la trajectoire de l'histoire. Notre mission résonne instamment de par le monde, englobant ainsi toute l'humanité: la nécessité de faire de notre Maison un lieu de coexistence pacifique. La [http://democracy.earth Fondation Democracy Earth] a mené des [[#Background|recherches approfondies]] sur les systèmes électoraux, la cyberpolitique et les réseaux blockchain ; nous nous tenons ainsi à l'avant-garde d'une conversation publique concernant l'idée de considérer l'internet comme une nouvelle juridiction planétaire.

En suivant [https://twitter.com/lsukernik/status/892101885771034628 l'exemple de Satoshi Nakamoto], nous avons d'abord entrepris d'écrire du code informatique avant de partager nos idées sous forme écrite, afin de comprendre au mieux ce qui peut être fait. À cette fin, plus de [https://github.com/DemocracyEarth/sovereign 30 000 lignes de code ont été écrites depuis octobre 2015], lesquelles ont à leur tour guidé nos recherches, cas d'utilisation, et les idées présentées ici. Ceci constitue notre proposition.

<div id="Eléments de contexte"></div>
==iii. Eléments de contexte.==

En créant les plus importants logiciels de démocratie open source [https://github.com/search?utf8=%E2%9C%93&q=topic%3Ademocracy&type=Repositories (considérés comme tels par la Communauté de GitHub)] nous avons été les pionniers de la démocratie numérique. Nous sommes notamment à l'origine de la conception originale de [https://www.youtube.com/watch?v=qNCgfd7dNb0 DemocracyOS], un projet de démocratie directe simple que nous avons créé en 2012. Nous avons fondé le premier parti politique numérique du continent Américain, le [http://partidodelared.org Partido de la Red] (Parti du Réseau) qui s'est présenté aux suffrages pour la première fois à [http://www.wired.co.uk/article/e-voting Buenos Aires] en 2013. En 2014, nous avons partagé notre expérience avec 1,2 millions de téléspectateurs grâce à la plateforme [https://www.ted.com/talks/pia_mancini_how_to_upgrade_democracy_for_the_internet_era TED]. En 2015 et 2016,  [http://ycombinator.com Y Combinator] et [http://ffwd.org Fast Forward] de la Silicon Valley ont financé nos efforts pour lancer la [http://democracy.earth Democracy Earth Foundation], une organisation à but non lucratif engagée dans la promotion de la gouvernance au-delà des frontières.

Notre expérience, qui conjugue les enjeux politiques et technologiques de la démocratie, nous a amenés à réfléchir aux modalités de conception d'un parti politique en utilisant des contrats intelligents, ou plutôt une forme peu contraignante de gouvernance qui peut être mise en œuvre par n'importe qui et à faible coût. Nous nous sommes donc attelés à la mise au point de [http://sovereign.software Sovereign], une '''''solution de démocratie liquide basée sur les blockchains''''' qui permet d'organiser des votes directs et qui offre également la possibilité de déléguer le vote sur des sujets spécifiques à des pairs grâce à un réseau sécurisé sans autorité centrale. En opérant avec des tokens signalés sur une blockchain, tous les votes deviennent résistants à la censure et des droits d'audit immédiats peuvent être accordés à tous les électeurs sans avoir besoin d'autoriser l'accès aux serveurs ou à des infrastructures privées. Le système est par conséquent ouvert et transparent pour tous. travail repose sur le développement de logiciels open source et nous coopérons avec des projets clés visant à sécuriser l'identité dans des environnements décentralisés, dont [https://blockstack.org/blockstack_usenix16.pdf Blockstack], [http://civic.com Civic] et [https://whitepaper.uport.me/uPort_whitepaper_DRAFT20170221.pdf Consensys] entre autres.

[[File:/images/sovereign.png|Sovereign.]]

[https://github.com/DemocracyEarth/sovereign La base du code de Sovereign] offre aux électeurs et aux organisations une application pour mobile et ordinateur évolutive qui normalise la prise de décision incorruptible dans un système démocratique basé sur les blocs. Notre objectif est de continuer à ouvrir la voie au recours à [https://www.usenix.org/legacy/event/sec08/tech/full_papers/adida/adida.pdf des systèmes de vote cryptographiques audibles par tous] et d'intégrer notre logiciel avec des blockchains capables de garantir les droits souverains des utilisateurs.

----

<div id="Manifesto"></div>

==1. Manifeste.==

<blockquote>
  La démocratie est par définition une oeuvre inachevée. Si elle était une idée absolue, elle ne serait qu'une idéologie totalitaire parmi tant d'autres.
</blockquote>
'''[https://en.wikipedia.org/wiki/Jos%C3%A9_Mujica José Mujica]''', Président de l'Uruguay (2010–2015).

Les systèmes démocratiques actuellement en vigueur dans les sociétés vivant dans les contours des États-nations ont atteint un plateau en termes de participation et évoluent vers une polarisation accrue. Les électeurs sucent le lait de médias faits à leur image qui les confortent dans leurs croyances de groupe et disloquent l'unité sociale en remplaçant le discours et le débat fondé sur des faits par une mentalité de la post-vérité. Ceci résulte de l'essor considérable des canaux de communication qui ont réduit les capacités d'attention à un point tel que l'analyse réfléchie n'a plus sa place. Au XXe siècle, la gestion centralisée de l'information avait créé des récits, des réalités et des identités uniformes.L'Internet les a fracturés. Les instances de participation politique aux démocraties dites «modernes» ne sont pas adaptés à des contextes où l'information abonde. Malheureusement, ces instances n'ont pas évolué depuis leur création.

[[File:/images/bipartisan-votes-us-congress.png|Bipartisan votes in the U.S. House of Representatives since 1981, source: The Rise of Partisanship (2015).]]

Les formes d'engagement traditionnelles ont moins d'écho chez les jeunes générations, [http://www.economist.com/news/essays/21596796-democracy-was-most-successful-political-idea-20th-century-why-has-it-run-trouble-and-what-can-be-do qui s'abstiennent souvent de voter et qui sont peu susceptibles de s'engager dans un parti]. L'implication politique en ligne se développe en parallèle, et les réseaux sociaux sont de plus en plus le théâtre principal des affrontements politiques. Parmi ces réseaux, on retrouve Facebook and Twitter (sur lesquels la diffusion de rumeurs est monnaie courante, avec le recours aux fake news, aux bots et au trolling, notamment) et des caisses de résonance nouvelles comme 4chan.org, où l'anonymat encourage le politiquement incorrect ou encore gab.ai, refuge de l'extrême droite américaine. Cela va sans dire, l'endogamie vient encore renforcer la polarisation, et nos sociétés tribalisées ont tendance à relativiser la vérité, ce qui met en péril la préservation des ressources et la survie des générations futures.

Les processus démocratiques à l'œuvre lors d'élections à haut risque sont menacés par des comportements frauduleux,[https://en.wikipedia.org/wiki/Gerrymandering ''les truquages électoraux''] sont courants et l'on observe un lien étroit [https://www.ineteconomics.org/uploads/papers/WP_48_Ferguson_et_al.pdf entre les dépenses des principaux partis et leurs scores]. Dans les pays en développement, on voit parfois de grands partis aller jusqu'à brûler des urnes électorales pour étouffer les chances des candidats plus modestes. 

Ce document propose une solution aux problèmes à la fois politiques et techniques qui affaiblissent actuellement les perspectives de la démocratie dans le monde. Cette solution prend la forme d'une alternative qui peut être adoptée directement par les citoyens et mise en œuvre par le biais de réseaux peer-to-peer. Alors qu'internet s'affirme comme la force dominante de la politique moderne, nous estimons indispensable de développer des technologies de vote numérique susceptibles d'être déployées de manière sécurisée quel que soit le lieu ou la taille de la population concernée. 

Plus de [http://www.bbc.com/news/technology-32884867 3 milliards de personnes] ont désormais accès à internet (c'est bien davantage que le nombre de fidèles des principales religions ou les populations des grands États-nations). Avec le développement de réseaux cryptés connus sous le nom de blockchains, qui permettent d'opérer des transactions incorruptibles avec des audits sans autorisation, rien n'empêche plus l'humanité de construire des espaces communs au-delà des frontières, et de contribuer ainsi à façonner la procaine grande évolution de la gouvernance démocratique à n'importe quelle échelle. Même dans les régions où la pénétration de l'Internet est inférieure à 50 %, la fracture numérique n'est pas basée sur des facteurs socio-économiques, mais plutôt sur un écart générationnel.
Selon Rick Falkvinge, fondateur du [https://en.wikipedia.org/wiki/Pirate_Party Parti Pirate], « L'évolution politique se fait à des vitesses glaciaires : rien ne semble se produire jusqu'à ce que soudain, un énorme vacarme n'attire l'attention de tous. L'évolution est lente car il faut souvent qu'une génération disparaisse pour que la prochaine prenne le relais. Or nous vivons dans un monde où la génération hors-ligne occupe le pouvoir tandis que la génération en ligne grandit. »

Les nouvelles formes de gouvernance doivent reconnaître les réseaux d'espaces communs qui relient l'humanité et affaiblissent progressivement les traditionnelles frontières nationales incapables par nature d'aborder des problèmes mondiaux pressants tels que le changement climatique, l'inégalité croissante, le terrorisme, l'automatisation et les migrations forcées. Les inégalités dans le monde, causées par la confrontation perpétuelle des gouvernements nationaux, donnent à ces questions une place de plus en plus prépondérante dans les priorités internationales. Nous pensons que la pile technologique qui comprend [http://bitcoin.com/bitcoin.pdf le Bitcoin] comme monnaie programmable indépendante des banques centrales, et [http://ethdocs.org/en/latest/index.html Ethereum ]qui permet de conclure des contrats intelligents sans passer par l'autorité judiciaire exige l'avènement d'une nouvelle strate démocratique permettant un vote incorruptible au-delà des limites des États-nations. Ce réseau transnational agira en fonction de la souveraineté personnelle de ses membres et protégera leurs droits humains grâce au cryptage.


===1.1 Héritage.===

On peut considérer que les élections organisées par les états, les provinces et les municipalités sont des démocraties qui nous réduisent au rôle passif de récipiendaires d'un monologue. Les citoyens sont appelés, à des intervalles relativement longs, à apporter une contribution de base à travers leur vote. Il s'agit essentiellement d'adouber ou de désavouer les représentants d'un même système. C'est la pierre angulaire du système que nous ont légué nos prétendues ''démocraties modernes''. Ces règles du jeu n'accordent qu'à moins d'un pour cent de la population le pouvoir de voter les lois ou d'exécuter les budgets tandis que les autres sont juridiquement contraints d'externaliser leurs droits de citoyenneté complète à une minorité représentative qui cède tôt ou tard aux sirènes de l'auto-perpétuation.

La technologie qui sous-tend les ''démocraties représentatives'' se subdivise en deux ensembles :

* '''Les élections analogiques''': le plus souvent, des bulletins papier et des urnes fournies par des autorités chargées de compter les votes et de signaler les comportements frauduleux. Même si ces systèmes sont stables dans les pays développés, ils souffrent d'une grave carence en termes de participation. Des exigences, telles que l'obligation de s'inscrire pour voter selon une procédure excessivement bureaucratique peuvent finir par bloquer un grand nombre d'électeurs privés de droits. Les autorités découpent également les circonscriptions en prévision des résultats électoraux en exploitant de façon frauduleuse les données d'enquête. Bien que ces systèmes soient plus faciles à contrôler, le corollaire est qu'ils sont également plus faciles à corrompre : dans les pays en développement, les ''élections analogiques'' peuvent être dévoyées par des masses représentant de grands partis qui brûlent ou font disparaître des urnes, menaçant les scrutateurs des plus petits candidats et laissant la violence embraser les circonscriptions clef. Notre expérience avec le [http://partidodelared.org Partido de la Red], lors des élections pour le Congrès de la ville de Buenos Aires en 2013, nous a permis de découvrir qu'aucun effort n'était plus important que de déployer suffisamment de scrutateurs pour couvrir tous les districts de la ville, faute de quoi des votes pouvaient être volés. Plus le territoire concerné par l'élection est vaste, moins le système analogique peut garantir un processus équitable. En outre, les coûts d'organisation élevés finissent par limiter les élections à une poignée de jours par an (et encore), ce qui fait de la démocratie une exception plutôt qu'une norme dans le processus de désignation des décideurs. De plus, les élections traditionnelles analogiques sont semblables à des oléoducs : les votes y transitent des mains de l'électeur jusqu'à un serveur central. Dans cet oléoduc, les voix exprimées lors de chaque scrutin sont résumées manuellement sur un document papier, qui est ensuite scanné et transmis à un bureau central. Là, les feuilles reçues sont chargées manuellement dans un serveur final qui calcule le nombre de voix. Tout le long de ce processus, les votes sont traités par différents acteurs humains qui peuvent les modifier, intentionnellement ou non, et entraîner une fraude. L'élection électronique vise à écourter cet oléoduc afin qu'aucun humain ne soit en mesure de manipuler les votes : les électeurs interagissent avec un dispositif (par exemple, une machine de vote électronique) qui transmet les votes chiffrés à un serveur central ou à un chef partagé (i.e. une blockchain).

[[File:/images/nation-state-voter-turnout.png|Territorial voting.]]

* '''Le vote électronique''': des solutions basées sur les machines de vote électronique qui visent à sécuriser le processus par une interface numérique, mais dans une même logique de rareté des élections. La nouvelle technologie est de fait mise au service des mêmes objectifs que l'ancien système, à savoir la légitimation des professionnels de la politique.
Les machines peuvent contribuer efficacement à éviter le recours à des [https://en.wikipedia.org/wiki/Clientelism techniques clientélistes] pour corrompre une élection, mais elles offrent un nouveau talon d'Achille en exposant les scrutins au risque de piratages ou d'interventions étrangères non détectés. Des experts de ce domaine ([https://www.ndi.org/e-voting-guide/examples/constitutionality-of-electronic-voting-germany dont la Cour Suprême allemande])  recommandent d’utiliser des machines de vote électroniques qui laissent une trace papier [https://www.amazon.com/Voting-Wars-Florida-Election-Meltdown/dp/0300198248 ou tout autre moyen] qui permette la constitution de preuves. Un autre moyen de sécuriser les systèmes de vote et d'en assurer la transparence passe par les tentatives de faire fonctionner les machines à voter en [https://www.nytimes.com/2017/08/03/opinion/open-source-software-hacker-voting.html open source et de les rendre contrôlables par le public.] La technologie peut également être introduite directement par les citoyens à l'aide d'applications pour smartphones qui permettent de réaliser un comptage parallèle des résultats en faisant remonter les résultats partiels des différents bureaux de vote. C'est une méthode qui peut servir de garantie face aux rapports officiels. De par leur nature même, les systèmes informatiques conservent des journaux de données et ne peuvent garantir le secret du vote. Pour cette raison, tout enregistrement d'un système de vote numérique devrait être public par défaut et basé sur la confiance. Le système devrait fonctionner avec un registre partagé qui synchronise les résultats d'un réseau partagé. En bref, une blockchain.

Les élections traditionnelles analogiques et électroniques sont strictement réservées aux démocraties représentatives à long terme avec des périodes électives de 4 à 6 ans. La dynamique sous-jacente de ces systèmes est toutefois que les représentants sont pré-élus par l'élite et présentés aux citoyens qui doivent sanctionner leur légitimité par le vote. L'argument selon lequel les citoyens n'ont ni les connaissances ni les compétences nécessaires pour s'acquitter de la responsabilité politique et que leur vie quotidienne ne leur laisse pas suffisamment de temps pour s'engager dans la vie publique ne tient pas : les élus ont plus souvent qu'à leur tour besoin de consulter des experts dans des domaines spécifiques pour accomplir leur tâche législative. De plus, grâce à Internet, aux téléphones portables, aux réseaux sociaux et aux satellites, nous vivons sans conteste dans un monde fourmillant de citoyens qui s'engagent régulièrement dans le débat politique (bien que leurs chances de peser sur les décisions soit nulles.)

===1.2 Geopolitics.===

A consequence of the US Presidential Election of 2016 is that the [https://www.theguardian.com/us-news/2016/dec/16/qa-russian-hackers-vladimir-putin-donald-trump-us-presidential-election fear of foreign intervention] has become a leading threat to the security of electoral processes. But although voting machines are an extremely vulnerable target, ([https://blog.horner.tj/post/hacking-voting-machines-def-con-25 defcon 25 had a large selection of voting machines, all of them were exploited]) foreign attacks have a simpler method than hijacking voting machines because directly manipulating votes potentially can be traced, is very expensive, and difficult to execute on a scale large enough to satisfy an attacker. A more efficient approach is [https://en.wikipedia.org/wiki/2016_Dyn_cyberattack instilling public fear by collapsing internet infrastructure days prior to an election] in a way that can help push favoritism on a candidate that is perceived stronger than the other one. This kind of cyberattack able to trigger a shift in voter perception is nearly impossible to trace as political subversion and reveals the inherent conflict that a digital commons has with territorial democracies.

[[File:/images/hacked-america.png|Impact of DNS cyberattack (October 21, 2016) & Presidential Election (November 6, 2016).]]

This happened two weeks before the US 2016 election when a botnet coordinated through a large number of Internet of Things (IoT) devices executed a [https://en.wikipedia.org/wiki/Denial-of-service_attack#Distributed_DoS Distributed Denial of Service (DDoS) attack] that affected Domain Name System (DNS) provider Dyn Inc. bringing down major websites in the US including Amazon, Paypal, New York Times and Wall Street Journal among many others.

===1.3 Terre ferme vs. Cloud.===

<blockquote>
Dans un avenir proche, les électrons et la lumière circulent librement, et les réseaux informatiques d'entreprise éclipsent les étoiles. En dépit de grands progrès informatiques, les pays et la race ne sont pas encore obsolètes... 
</blockquote>
[http://www.imdb.com/title/tt0113568/ '''''Ghost in the shell'''''], roman graphique (1995).

Le 21ème est le théâtre d'un conflit croissant entre ''la Terre Ferme'' - des gouvernements qui monopolisent le droit sur des juridictions territoriales en limitant la libre circulation des biens et des personnes ; et ''le Cloud'' - des sociétés internationales qui monopolisent l'accès aux données des utilisateurs afin de pouvoir les suivre et les cibler via une publicité personnalisée. Dans ce monde, la liberté est une illusion. Nos corps appartiennent aux gouvernements, nos esprits aux entreprises. Parmi les grandes batailles de ce conflit on pourrait citer [https://en.wikipedia.org/wiki/FBI%E2%80%93Apple_encryption_dispute ''l'affaire Apple contre le FBI''] portant sur l'accès aux données d'un téléphone chiffré, ou bien l'antagonisme historique entre [https://www.washingtonpost.com/news/the-switch/wp/2017/03/06/trumps-new-travel-ban-raises-the-same-silicon-valley-objections/?utm_term=.0854c54536d6 une Silicon Valley cosmopolite demandeuse de visas souples et Washington, poursuivant une politique nationaliste de multiplication des entraves à la migration]. Dans ce scénario, le cryptage joue un rôle de plus en plus essentiel dans la protection des droits de l'homme des citoyens numériques, car il peut les aider à se délivrer du piège de la ''dichotomie entre cloud et terre ferme.''

[[File:/images/the-land.png|The land: monopolies on force.]]

Les origines de la cryptographie moderne remontent à la Seconde Guerre mondiale avec la mise au point par Alan Turing des premiers proto-ordinateurs servant à décrypter les messages nazis. Depuis lors, les États-Unis ont légiféré sur le cryptage de la même manière que pour les armes traditionnelles : il est inscrit sur la ''Liste des Munitions'' du[https://www.pmddtc.state.gov/regulations_laws/itar.html Règlement relatif au trafic international d'armes], et les logiciels et matériels connexes font face à des restrictions à l’exportation. Et bien que le cryptage soit souvent considéré comme un droit protégé par le Premier Amendement en vertu du fait que « le code est un discours », son caractère défensif le place sous la protection du Deuxième Amendement puisqu'il relève du même raisonnement que le « droit à porter des armes ». En effet, dans un monde où [http://twitter.com/Snowden  les donneurs d'alerte] révèlent de quelle façon le ''Deep State'' espionne les citoyens aux quatre coins du monde, le chiffrement de l'information est la seule garantie réaliste disponible pour se protéger contre les abus du gouvernement (et des sociétés qui les soutiennent).

[[File:/images/the-cloud.png|The cloud: monopolies on data.]]

Le secret est une condition sine qua non pour la tenue d'élections libres et équitables car il s'agit d'un mécanisme qui contribue à éviter que ceux qui détiennent le pouvoir n'exercent des pressions, et qui contrecarre le risque d'achat et de vente de voix. La protection de la vie privée est la meilleure garantie pour qu'un esprit libre et conscient réfléchisse par lui-même. Mais la protection de la vie privée est illusoire sur l'internet d'aujourd'hui lorsque l'on utilise Facebook, Google ou tout autre service basé sur le Web. Bien que les géants d'Internet se targuent d'être les gardiens de la vie privée en ligne, en théorie Facebook peut encore se faire passer pour l'un de ses 2 milliards d'utilisateurs s'il le souhaite. Google et Facebook détiennent les plus grandes bases de données d'identité dans le monde, surpassant les gouvernements de l'Inde et de la Chine, alors que [https://twitter.com/AdrianChen/status/832452637320556544 97% de leurs revenus déclarés proviennent de la publicité], qui conditionne très largement l’expérience des utilisateurs de leur technologie. Il est dans leur intérêt de recueillir autant d'informations que possible pour profiler les utilisateurs et rester compétitifs. Les deux sociétés filtrent les informations fournies aux utilisateurs à l'aide [https://medium.com/@piamancini/future-scenarios-for-algorithmic-accountability-and-governance-17cd436d22a0 d'algorithmes qui ne rendent de comptes] à personne, sauf à leur propre conseil d'administration. Aucun de leurs services n'est vraiment gratuit. En réalité, la souveraineté personnelle est abandonnée grâce à la même illusion que celle présentée aux Indiens d'Amérique dont l'attention, il y a 500 ans, a été détournée par la contemplation de leur ''selfies'' dans de brillants miroirs tandis que les conquistadors Européens balayaient en un clin d'oeil leur mode de vie tout entier. Les débats non censurés, libres et souverains sur l'avenir de l'humanité sont éclipsés par d'inutiles ''likes'' qui ne font que contribuer à perpétuer ces entités. L'exploitation de ''fake news'' (comme lors des élections américaines) ou la diffusion incontrôlée de contenus critiques (comme pendant le ''Printemps Arabe'') atteste que tout effort pour empêcher les influences internationales de peser sur la politique nationale est futile car les sociétés passent la plupart de leur temps en ligne. Internet est incompatible avec les États-nations.

===1.4 Intelligence.===

<blockquote>
  Je ne peux pas te laisser faire ça, Dave.
</blockquote>
'''HAL 9000''' dans ''2001: Odyssée de l’espace'' (1968).

La meilleure technologie civique est la technologie que l'on utilise tous les jours. Facebook, Twitter et d'autres plateformes de médias sociaux sont d'ores et déjà devenues, par procuration, les principales interfaces que les citoyens utilisent pour influencer la politique quotidienne. Mais les conséquences invisibles de la diffusion de données personnelles par des services web centralisés peuvent être nombreuses et ont des répercussions qui intéressent l'avenir de l'humanité. Il est fondamental de comprendre l'architecture de l'information - la façon dont les données personnelles sont stockées, partagées et monétisées - pour comprendre la souveraineté au 21ème siècle.

L'utilisation sans restriction de l'intelligence artificielle (IA) alimentée par le contenu généré par les utilisateurs sans aucun type de supervision publique constitue une menace imminente. Les révélations d'un ancien employé de Blackwater sur la façon dont les données peuvent être transformées en armes en constituent une preuve patente. Il a pu, à partir d'un bureau à Dubaï, piloter et obtenir des informations en direct d'un drone volant au-dessus de la Syrie ou du Pakistan. Étonnamment, la décision d'abattre la cible n'a pas été prise par l'opérateur humain (ou par la hiérarchie), mais par une IA qui a pris les décisions en ligne "au moins 90 % du temps". Cette IA avait été fournie par une société de la Silicon Valley souvent citée pour avoir fourni des services de renseignement à la CIA et avoir localisé Oussama Ben Laden en 2011.

Le fait qu'une intelligence artificielle puisse décider de vies humaines pose des questions éthiques et morales. Même les chercheurs humains ne sont pas véritablement capables de comprendre comment l'intelligence artificielle se comporte, d'où la menace potentielle si elle devient élément clef de la technologie militaire. Selon Yuval Noah Harari, « l'intelligence se détache des organismes vivants et elle ne sera plus longtemps l'apanage d'êtres de chair et de sang ». La nouvelle frontière politique qui se dessine est donc la conscience, qui distingue les machines des humains. En d'autres termes, il s'agit de comprendre si nous utilisons les machines ou si les machines nous utilisent. La façon dont nous structurons les organisations humaines - et administrons le code qui les sous-tend - définit qui est à la manœuvre. À mesure que les capacités de l'intelligence du silicium rattrapent les taux de croissance de la loi de Moore, l'humanité dans son ensemble doit se demander comment elle va assumer cette puissance sans précédent.

===1.5 Décentralisation.===

<blockquote>
  Est souverain celui qui décide de l'exception.
</blockquote>
[https://wikipedia.org/wiki/Carl_Schmitt '''Carl Schmitt'''], théoricien politique (1888-1985).

Le talon d'Achille des géants d'internet insatiables en données et avides d'attention est leur besoin d'une architecture d'information centralisée. Ils se sont affirmés comme des ''superhubs'' dans ce qui était alors la promesse d'un réseau en toile d'araignée, en déployant des solutions efficaces pour répondre aux principales utilisations en ligne. Il en a néanmoins découlé un écosystème privatisé. Le code est verrouillé, les jardins sont fortifiés et la centralisation du pouvoir entre quelques mains a ouvert la voie à l'avènement d'une véritable [https://youtu.be/IrSn3zx2GbM?t=10m34s société de la surveillance] plutôt qu’à ce qui pourrait être un territoire commun sans frontières. Sir Tim Berners-Lee, créateur des protocoles ''world wide web'',  conscient des risques intrinsèques que l'on observe sur Internet aujourd'hui, avait insisté sur la nécessité de rédiger une [https://www.ted.com/talks/tim_berners_lee_a_magna_carta_for_the_web Magna Carta du Web]: "À moins d'avoir un Internet ouvert et neutre sur lequel nous puissions compter sans nous soucier de ce qu'il se passe dans les coulisses, nous ne pourrons pas avoir un gouvernement ouvert, une démocratie saine, des communautés connectées et des cultures diverses. Il n'est pas naïf de croire que nous pouvons atteindre ce but, en revanche il est naïf de penser que nous pouvons nous croiser les bras et l'obtenir. "

La centralisation est le point unique d'échec des élections et est incompatible avec la démocratie. Dans notre expérience de mise en œuvre d'un vote numérique centralisé pour la prise de décisions au sein du Partido de la Red, nous avons constaté que si une élection s'accompagne d'enjeux élevés (la totalité ou la plupart des membres ont des intérêts particuliers à défendre), la probabilité que le système soit corrompu augmente. C'est au niveau de ceux qui sont responsables du contrôle des serveurs et de l'intégrité de la base de données que les risques sont les plus élevés. Lors d'[https://asamblea.partidodelared.org/topic/58eaf4739b96a611009bc3fc élections internes,] au début de 2017, nous avons découvert des divergences entre les informations rapportées par les auditeurs de base de données et les registres tenus par les électeurs dans leurs machines locales : la manipulation des données sur les émissions de vote, la modification arbitraire de la date de clôture du scrutin, les registres effacés et le bannissement soudain de comptes enregistrés ont été prouvés et dénoncés. Cela a entraîné un sentiment largement partagé de fraude dans l'ensemble du processus. Les démocraties numériques centralisées qui ne prennent aucune mesure pour assurer la sécurité cryptographique sont des jouets utiles à des fins ludiques, mais elles peuvent s'avérer dangereuses lorsqu'elles sont mises en place en conditions réelles par des agents malintentionnés.

Les élections traditionnelles recourent, quant à elles, à une technique connue sous le nom de ''comptage contradictoire'' lorsque les résultats sont serrés. Des responsables de toutes les parties concernées participent à un décompte manuel des voix. Mais lorsqu'une élection concerne une population nombreuse, le ''comptage contradictoire'' rend la corruption du scrutin très facile, puisqu'il suffit de soudoyer quelques responsables d'un parti concurrent pour obtenir le résultat souhaité. Tout système reposant sur la confiance des participants risque tôt au tard de voir sa structure s'effondrer si des responsables commettent des fraudes.

[[File:/images/blockchain-permissionless-audit-voting.png|Blockchain democracies enable permissionless audits.]]

La décentralisation est indispensable à des élections démocratiques. Sans elle, la corruption est toujours possible. Les blockchains permettent de mettre en place des systèmes non basés sur la confiance en érodant la nécessité d'une supervision humaine et en renforçant la protection de l'intégrité du vote grâce à une ressource partagée dont la fonction principale est de pointer les voix. Cela permet la conception de systèmes électoraux complètement nouveaux. '''Avec une démocratie basée sur les blockchains, les votes ne sont plus exposés à la censure et chaque électeur peut scruter une élection sans avoir à demander un droit d'accès à l'infrastructure.''' En stockant les données de vote dans une blockchain plutôt que sur des serveurs privés ou dans des urnes, on réduit les coûts d'audit, et le contrôle devient un droit garanti pour chaque participant. Les électeurs ne sont plus seulement des spectateurs, ils sont aussi les gardiens souverains de l'ensemble du processus. Les systèmes électoraux traditionnels, analogiques ou électroniques sont incapables de ce niveau de transparence.

===1.6 Souveraineté.===

Sur Internet d'aujourd'hui, le vote a toujours été l'interaction principale. Chaque fois que les utilisateurs ''likent'', ''font remonter'', ''assignent un cœur'', ''copient un lien'' ou ''retweetent'' du contenu, ils expriment une préférence qui alimente la génération de recommandations adaptées à ce qui les intéresse. Mais ça ne va plus loin. Il s'agit d'un ''ersatz de vote'' sans répercussions institutionnelles. Les ''Likes'' des médias sociaux fonctionnent comme des tokens sans valeur qui peuvent être gonflés par un seul clic même si, en réalité, ils définissent les prix de la publicité. Les effets de réseau ont transformé cette interaction en une mécanique qui met en évidence l'influence d'une idée donnée au sein d'une groupe, un outil souvent utilisé par les détenteurs du pouvoir pour évaluer les besoins de la société. Mais les avantages financiers et politiques de ces transactions sont entièrement conservés par les [https://www.nytimes.com/2016/10/16/technology/peter-thiel-donald-j-trump.html propriétaires des réseaux].

[[File:/images/web-voting.png|Web voting.]]

La technologie Sovereign, qui est capable de fonctionner sur des réseaux peer to peer, de valider l'identité, de préserver l'anonymat, de chiffrer les données et de décentraliser l'infrastructure avec un code source ouvert en accès libre et gratuit a le pouvoir de révolutionner le contexte que nous avons décrit plus haut.

L'Histoire humaine n'a connu que trois types de souveraineté : la ''tribu souveraine'' où la masse obéit à un chef, le ''roi souverain'' qui ne rend de comptes qu'à Dieu, et la ''république souveraine'' dont les territoires sont régis par une loi commune. Les blockchains fonctionnant dans le cyberespace font émerger un quatrième type, ''l'individu en réseau''. Ce n'est pas une possibilité farfelue : la conquête de [https://www.amazon.com/Sovereign-Individual-Mastering-Transition-Information/dp/0684832720 la souveraineté personnelle] est déjà une réalité pour ceux qui gèrent leurs finances avec des bitcoins ou d'autres actifs cryptographiques. Selon les termes de l'investisseur [http://twitter.com/naval Naval Ravikant], “on peut traverser une frontière internationale en transportant un milliard de dollars en bitcoins entièrement dans sa tête". Ce type d'acte souverain est sans précédent, même pour des chefs d'État contemporains.

L'adoption généralisée des blockchains fait émerger un modèle qui a d'abord été créé dans l'ombre des institutions établies mais qui finira par les rendre obsolètes. Les blockchains sont des administrations automatisées qui présentent des avantages financiers importants en termes de coûts de transaction grâce à la suppression du recours aux intermédiaires. Elles rendent possibles des systèmes d'association libre qui contribuent à briser les contraintes politiques et financières imposées par que les gouvernements et les banques en limitant le droit de vote ou l'accès au capital. Une société avancée du point de vue technologique peut prospérer au-delà des territoires nationaux, il suffit d'une connexion à internet et de citoyens numériques qui construisent un nouveau type de diaspora.

----

En nous appuyant sur ces constats, nous proposons dans la [[#Paper|Section 2]] du document une cartographie des éléments de base d'une démocratie liquide décentralisée. Une fois les outils définis, la [[#Execution|Section 3]] envisage une mise en œuvre axée sur la sécurité et l'inclusivité du système.

<div id="Paper"></div>

==2. Paper.==

<blockquote>
  It is the technology that we do not control the one that is used to control us.
</blockquote>
[https://twitter.com/earlkman '''Emiliano Kargieman'''], space hacker (1975).

A foundational principle of democracy is the right to be heard. Today most of the world’s population is not heard: having a voice is an accident of birth. Individual and collective voices are politically and economically silenced by ‘illiquidity’ - the marginalized are given no instruments to broadcast or amplify their voice. Modern democracy is the birthchild of the ''Printing Press Era'': printed constitutional systems dependent on wet ink contracts and the speed of the postal service. Representative democracies are an accident of the information technologies of the 18th century.

[[File:/images/liquid.png|Direct democracy vs. Liquid Democracy.]]

A liquid democracy is based on a dynamic representation model that works with a bottom-up approach: citizens are able to freely elect within their social graph (friends, colleagues, family) who they want to have as representatives on a specific set of topics. It is the most flexible form of democratic governance that can be constructed with digital technology, operating as a hybrid that enables direct or delegated voting at any time. There are few precedents of trustworthy bottom-up environments that led to authoritative content, [https://www.wikipedia.org/ Wikipedia] being a pioneering case. But if history is any guide, the last time civilization faced [https://en.wikipedia.org/wiki/Age_of_Enlightenment a paradigm shift regarding encyclopedic enlightment] it was precisely on the epoch preceding the rise of modern democracies.

L'article qui va suivre déroule la mise en oeuvre d'une démocratie liquide utilisant [http://github.com/DemocracyEarth/sovereign Sovereign], notre application de gouvernance qui opère avec les 



s blockchains à partir d'une série de contrats intelligents. Nous avons misé sur la simplicité du design et de son langage afin de développer des outils authentiques, car aucune technologie ne peut satisfaire les aspirations démocratiques si elle ne s'adresse qu'aux élites. Comme l'explique pertinemment le cryptographe [https://fr.wikipedia.org/wiki/Ralph_Merkle] :

<blockquote>
Nous ne faisons pas appel à des citoyens ordinaires pour procéder à des opértions chirirgicales, piloter des avions, dessiner des ordinateurs ou prendre en charge les myriades de tâches qui font qu'une société fonctionne, pourquoi la gouvernance obéirait-elle à d'autres règles ? Or le problème est clair : si nous la laissons aux “experts”, ils prendront des décisions dans leur propre intérêt, non pas dans celui de nous tous.
</blockquote>

===2.1 Token.===

Un système de vote idéal doit être capable de satisfaire les conditions suivantes :

* '''Discrétion''': l'électeur doit pouvoir voter en secret.

* '''Vérification''': l'électeur doit pouvoir vérifier les scrutins.

* '''Intégrité''': le système doit être capable de corriger le décompte.

De plus, en raison du risque de coercition à travers la violence physique ou de menances dans des contextes politiques instables, une option de protection des électeurs doit être introduite :

* '''Résistance''': l'électeur doit être capable d'annuler son vote si nécessaire.

D'après le travail mené par les chercheurs Hosp & Vora, une [https://pdfs.semanticscholar.org/24d5/5c866a7317dae11d37518b312ee460bc33d3.pdf approche de la théorie de l'information a été utilisée pour modéliser les systèmes de vote], menant ses auteurs à conclure qu'une tension naturelle existe au sein d'un système informatique entre ''l'intégrité parfaite'', ''la discrétion parfaite du scrutin'' et ''la vérification parfaite du décompte''. Les trois éléments ne peuvent pas être satisfaits simultanément si un adversaire n'est pas soumis à la puissance de calcul commune, et capable de forcer un système informatique, dans le cas où il disposerait par exemple d'un temps illimité ou d'un espace de stockage suffisant. Pour ces raisons, nous considérons qu'il est indispensable de mettre en oeuvre des démocraties digitales qui utilisent la blockchain. Avec les effets de réseau déjà en place, la blockchain est capable de vérifier l'intégrité des transactions et de prévenir la dépense multiple d'un même token. Les modèles bitcoins [https://fr.wikipedia.org/wiki/Preuve_de_travail ''preuve de travail''] récompensent une capacité de calcul en vérifiant les blocks de transaction (à travers les ''mines''), générant à des réseaux “300 fois plus puissant que les ressources de Google” selon le mineur pionnier [http://twitter.com/balajis Balaji Srinivasan]. C'est pourquoi notre design est fondé sur des tokens avec des réseau de blockchain qui fonctionnent comme une ''cryptomonnaie politique''.

Ce qui différencie un vote d'une monnaie (ou une ''économie politique'' d'une ''économie financière'') tient du fait que la monnaie politique est pensée pour guarantir le doit à la participation d'après des conditions justes entre tous les membres d'une organisation. Les droits ont pour objectif de satisfaire une gouvernance légitime au sein d'une institution. Tandis que la monnaie est le langage de l'intérêt particulier, le vote exprime l'intérêt partagé d'une communauté. La monnaie politique ne sert pas seulement l'échange, mais aussi le choix social.

{| class="wikitable"
|-
! scope="col"| Feature
! scope="col"| Coins
! scope="col"| Votes
|-
! scope="row"| Utility
| Trade.
| Governance.
|-
! scope="row"| Mining
| Computation (e.g. Proof of Work).
| Attention (e.g. Proof of Identity).
|-
! scope="row"| Liquidity
| Scarce.
| Guaranteed.
|-
! scope="row"| Signal
| Self interest.
| Social choice.
|-
! scope="row"| Value
| Space (material goods).
| Time (information).
|}

====2.1.1 Mise en œuvre.====

Etant donné que [https://en.wikipedia.org/wiki/Dogecoin la capacité de mimétisme peut entraîner une création de valeur], le token Democracy Earth qui donne accès au droit de vote sera marqué du message le plus important qu'une démocratie - quelle qu'elle soit - puisse transmettre : ''vote''.

Le token ''vote'' peut être mis en oeuvre grâce à un code contrat intelligent à travers une variété de blockchains qui supportent des scripts [https://en.wikipedia.org/wiki/Turing_completeness Turing-complet], dont le Bitcoin. Nous avons imaginé un système indépendant de la blockchain car nous sommes conscients que l'informatique en est encore à ses balbutiements et des innovations importantes restent à inventer. Nous travaillons toutefois à l'implémentation du token ''vote'' dans les environnements de contrats intelligents suivants :

* '''Ethereum''': Utilisation d'un ensemble de contrats intelligents [https://github.com/ethereum/solidity Solidity] selon le [https://theethereum.wiki/w/index.php/ERC20_Token_Standard token standard Ethereum ERC20].

** '''Rootstock''': Nous prenons les mesures nécessaires pour rendre le code de Solidity compatible avec [http://www.rsk.co/ l'interprète de contrat intelligent de Rootstock pour la blockchain Bitcoin].

* '''Lightning''': Avec l'activation du [https://en.bitcoin.it/wiki/Segregated_Witness témoin séparé] dans le protocole Bitcoin, qui permet l'acheminement des canaux de paiement par [http://lightning.network le protocole Lightning Network], les délégations dans la démocratie liquide peuvent être cartographiées à l'aide de transactions de niveau satoshi portant un identifiant ''vote'' attaché. Les coûts de règlement des transactions via la blockchain doivent être couverts par l'organisme de mise en oeuvre.

En outre, les implémentations multi-chaînes sont encouragées, dans l'esprit de favoriser davantage d'expérimentation et de collaboration par rapport à ces technologies.

===2.2 Mécanismes de vote.===

Le token de ''vote'' vise à devenir une norme pour la démocratie numérique ; un outil capable d'interagir avec d'autres tokens et établissant un langage commun pour la gouvernance des organisations fondées sur les blockchains. Les démocraties liquides rendent possible une large palette de transactions de ''vote'':

* '''Le vote direct''': Alice, électrice égoïste, est autorisée à utiliser ses tokens pour exprimer directement par le vote son avis sur des sujets précis, comme dans une démocratie directe.

* '''La procuration simple''': Alice peut déléguer ses ''votes'' à Bob. Tant que Bob a accès à ces tokens, il peut les utiliser pour voter au nom d'Alice.

* '''La procuration circonscrite à une étiquette''': Alice peut déléguer sa ''voix'' à Charlie en l'assortissant de la condition qu'il ne peut utiliser les tokens que pour voter sur des problèmes portant une étiquette spécifique. Si la procuration précise que les ''votes''  délégués s'appliquent uniquement aux décisions portant l'étiquette ''#environnement'', then Charlie won't be able to use these anywhere else but on those specialors Charlie ne pourra pas les utiliser pour voter sur d'êtres questions. Cela conduit à un modèle de représentation qui ne dépend pas du territoire, mais de la connaissance.

* '''La procuration transitive''': Si Bob a reçu une ''procuration'' d'Alice, il peut ensuite déléguer à Frank. Cela génère une chaîne de procurations qui habilité des acteurs spécifiques au sein d'une communauté. Si Alice ne souhaite pas que des tiers reçoivent la procuration qu'elle a confiée à Bob, elle peut modifier le cadre transitif du contrat de procuration. Les procurations circulaires (p. Ex. Alice recevant de Frank les tokens qu'elle a envoyés à Bob) sont interdites puisque l'attribution initiale de ''votes'' par une organisation à ses membres les assortit d'une signature indiquant qui est le propriétaire souverain des ''votes''.

* '''Le vote prioritaire''': Si Bob a déjà utilisé la ''procuration'' qu’il a reçue d'Alice, mais qu'elle a une opinion différente sur un problème donné, en tant que propriétaire souveraine de ses ''votes'', Alice conserve le pouvoir d'annuler la décision de Bob. Les votants ont toujours le dernier mot sur les décisions grâce à leurs tokens d'origine.

* '''Le vote public''': Souvent considéré comme la ''règle d’or'' des démocraties liquides, tous les mandants ont le droit de savoir comment leur mandataire a utilisé leurs ''votes''sur un problème donné. De même que les votes des parlementaires des démocraties conventionnelles sont publics, les mandataires concurrents d'une démocratie liquide sont incités à se forger une réputation publique par leur historique de vote afin d'attirer davantage de procurations.

* '''Le vote secret''': Une méthode qui rend les ''transactions de vote'' absolument intraçables pour les électeurs. C'est indispensable dans le contexte d'élections publiques concernant des populations nombreuses où le risque de coercition est élevé. Même dans le cas d'un respect parfait du secret du ''vote'' , il reste possible de remonter jusqu'aux électeurs en exploitant les métadonnées. C'est pourquoi la recherche sur l'intégration avec les blockchains conçues pour les transactions anonymes dotées d'une traçabilité éprouvée est souhaitable. Cela pourrait passer par une taxe sur le minage pour régler la ''transaction de vote''. . Elle pourrait être subventionnée par l'organisme chargé de la mise en oeuvre ou bien directement payée par les électeurs. Nous recommandons la recherche et l'intégration des scrutins secrets avec les blockchains ci-dessous :

** [https://z.cash ZCash]: permet des transactions blindées grâce à des [https://en.wikipedia.org/wiki/Zero-knowledge_proof preuves à divulgation nulle de connaissance]

** [https://getmonero.org Monero]: s'appuie sur [https://en.wikipedia.org/wiki/Ring_signature ur les signatures de cercle avec des adresses "stealth" à usage unique].

===2.3 Expérience utilisateur.===

L'expérience utilisateur (UX) est un aspect essentiel d'une architecture décentralisée et le devient d'autant plus à mesure que le mille-feuilles redondant des architectures centralisées se condense autour de l'utilisateur. Dans une architecture internet centralisée, l'utilisateur n'est propriétaire ni de l'interface ni de l'expérience. Dans une architecture Internet décentralisée au contraire, l'interface utilisateur (IU) doit être axée sur la perspective de l'utilisateur. Les transactions sont opérées selon trois modes distincts :

* '''Individuel (SELF)''': Utilisation d'une identité publique liée à un individu.

* '''Organisation (ORG)''': En représentation d'une organisation qui confère des droits de représentation à des individus (entreprise, club, parti politique, etc.).

* '''Anonyme (ANON)''': Sans lien aucun avec une identité publique.

La prise en compte de cette exigence multiforme ''SELF / ORG / ANON'' a fortement influencé la conception de notre interface et des tokens. Les utilisateurs de Sovereign peuvent à tout moment opter pour l'un ou l'autre de ces modes pour interagir avec les organisations décentralisées.

====2.3.1 Liquidité.====

L'objectif de Sovereign est de rendre le vote liquide immédiat et simple. Il convient d'éviter tout accroc dans le processus. En outre, le widget de procuration doit être visible en permanence sur l'interface de consultation des sujets à débattre ou des profils des membres. Sovereign utilise donc une ''barre liquide'' qui permet d'opérer des ''transactions de vote'' d'un seul geste, aussi bien sur mobile que sur ordinateur.

[[File:/images/liquid-mobile-ux.png|Sovereign mobile interface displaying decision, ballot and liquid voting.]]

La ''barre liquide'' aoffre les fonctionnalités suivantes :

* '''Rappel des ''votes'' disponibles''': Dans une démocratie liquide, un utilisateur peut être dépositaire d'une ou plusieurs procurations, un rappel constant des votes restants l'aide par conséquent à connaître son pouvoir dans le système à un moment T. Si certains ''votes'' ont été délégués dans des conditions strictes (avec une ''procuration circonscrite à une étiquette'' par exemple), cela signifie qu'un utilisateur n'aura pas la même quantité de votes disponibles pour chaque sujet.

* '''Affichage des ''votes'' exprimés''': Affichage d'un pourcentage représentant la quantité de ''votes'' déjà exprimés sur d'autres décisions ou délégués à d'autres membres de la communauté. L'utilisateur peut cliquer à tout moment sur cette valeur pour afficher une liste complète des sujets sur lesquels il a utilisé un ''vote'' et décider de ne pas modifier son choix ou au contraire de procéder à un changement stratégique.

* '''Glisser pour ''voter''''': L'utilisateur peut utiliser son doigt (ou la souris) pour faire glisser la ''barre liquide'' vers la droite. Une demande de confirmation s'affiche alors pour établir s'il souhaite ou non ''voter''.

* '''Cliquer pour ''voter''''': Si l'utilisateur ne souhaite pas allouer plus d’1 vote, il peut simplement appuyer sur la ''barre liquide'' une fois et sera invité à confirmer une transaction de ''vote'' unique.


* '''Retrait de ''votes''''': Tant que le scrutin est ouvert, l'utilisateur peut à n'importe quel moment retirer son ou ses ''votes'' 'une décision. Il lui suffit de faire glisser la ''barre liquide'' vers la gauche pour la remettre dans la position initiale.

Cette interaction nous paraît un progrès par rapport au système de ''likes'' des médias sociaux. Le système des ''likes'' limite le vote à des clics dénués d'intention et pouvant être gonflés à volonté. Dans notre proposition, les votes sont une ressource rare qui ne peut pas être générée à volonté. Les utilisateurs doivent donc faire preuve d'un minimum de réflexion tactique pour peser sur une décision spécifique. Les ''votes'' ont des implications réelles pour l'utilisateur en tant qu'acteur d'une organisation décentralisée alors que les ''likes'' ne profitent qu'aux entreprises qui les contrôlent.

====2.3.2 Procurations.====

La ''barre liquide'' affiche également les procurations qu'un utilisateur a reçues ou données à tout autre membre d'une organisation. Les procurations vont dans les deux sens :

* '''Mandataire (procurations envoyées)''': Un utilisateur doit être en mesure de déléguer n'importe lequel de ses ''votes'' disponibles et de consulter, le cas échéant, le nombre de votes délégués à un moment T.

* '''Mandaté (procurations reçues)''': Un utilisateur doit avoir une vision claire du nombre de ''votes'' confiés par d'autres utilisateurs.

Chaque fois qu'un profil de membre est affiché sur Sovereign, le statut des procurations entre l'utilisateur et le membre en question s'affiche.

[[File:/images/delegation-relation-votes.png|View of vote delegation relation with another member.]]

====2.3.3 Agora.====

Sovereign propose également un outil de discussion qui répond au nom de code ''Agora''. Dans toute démocratie, le débat est probablement aussi important que le vote. Les Agoras affichent les ''fils de discussion'', un modèle abouti dont [http://reddit.com Reddit] et [http://news.ycombinator.com Hacker News]ont été les pionniers. Nous considérons ce modèle d'expérience utilisateur comme la meilleure façon d'engager des conversations réfléchies en ligne car les commentaires les plus appréciés remontent à la surface, ce qui aide à trier l'information en utilisant l'intelligence collective de la communauté.

Contrairement aux applications basées sur le Web, Sovereign ne permet cependant pas d'interactions de témoignage : plutôt que de permettre des ''upvotes'' ou ''downvotes'', à l'infini, si l'utilisateur se retrouve dans le commentaire d'un autre usager de la plateforme, la délégation d'un seul ''vote''est instantanément déclenchée. Les Agoras permettent donc :

* '''Les upvotes''': Envoi d'un seul ''vote'' délégué de l'utilisateur à l'auteur du commentaire.

* '''Les downvotes''': Si un utilisateur n'est pas d'accord avec le commentaire de quelqu'un, un ''downvote'' peut permettre de révoquer une ''procuration'' s'il avait délégué des votes à l'auteur du commentaire. Ou alors, si aucune procuration ne relie ces usagers, un ''downvote'' agira comme une pénalité en renvoyant un ''vote'' de l'intervenant à l'organisation mettant en œuvre le système Sovereign. Les critères de ce type de sanction peuvent être définis dans le ''contrat constitutionnel intelligent'' de l'organisation chargée de la mise en oeuvre.

Ce mécanisme a le mérite d'inciter à déléguer les votes et à rendre les procurations plus fréquentes sur la plateforme. L'impact politique de débats constamment exposés à la sanction du ''vote'' est réel. Ce mécanisme peut aider à récompenser les bons arguments et à punir le trolling sans qu'il soit besoin de mettre en place des instances de modération.

=== 2.4 Projet pilote ===

<blockquote>
La technologie des blockchains pourrait révolutionner le vote, exactement comme cela a été le cas pour la monnaie, et pourrait s'appliquer à n'importe quel gouvernement démocratique.</blockquote>
[https://www.oecd.org/gov/innovative-government/embracing-innovation-in-government-colombia.pdf '''L'Organisation de coopération et de développement économiques'''], Faire place à l'innovation dans le gouvernement : tendances mondiales (2016). 

En octobre 2016, à la suite du choc provoqué par un "Non" inattendu au référendum colombien sur la paix - issue mettant en péril des années de négociations entre le gouvernement et les narcoguérillas marxistes - Democracy Earth a mis la plate-forme de démocratie liquide Sovereign au service d’un [http://plebiscitodigital.co/ plébiscite en ligne], donnant ainsi un accès symbolique au vote à une diaspora d'environ 6 millions de citoyens expatriés. Plutôt que de contraindre les électeurs à un choix binaire, ce projet pilote leur a permis de voter séparément sur sept sous-thèmes du projet de traité et de déléguer leurs votes à des électeurs plus informés. Les résultats ont fait apparaître des nuances importantes dans les préférences des électeurs que le référendum n'avait pas permis de révéler, dont un [https://words.democracy.earth/a-digital-referendum-for-colombias-diaspora-aeef071ec014 point d’achoppement essentiel]: les participants du projet pilote se sont, à une écrasante majorité, prononcés contre une clause spécifique du traité concernant la participation politique des FARC.

[[File:/images/colombia-use-case.png|Colombia use case data..]]

Cette étude pilote a en [https://www.oecd.org/gov/innovative-government/embracing-innovation-in-government-colombia.pdf outre permis] de renforcer le poids médatique et politique de la démocratie liquide décentralisée fondée sur les blockchains en Colombie. On a vu naître depuis un parti politique qui défend l'utilisation des blockchains, le Partido de la Red Colombia («Le Parti du Réseau»), et le Centre pour l'innovation publique numérique (CDPI) du gouvernement colombien a quant à lui lancé des études sur cette technologie.

===2.5 Contrats Intelligents.===

Lorsque Claude Shannon a écrit son [http://math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf article fondateur de 1948 sur la Théorie de l'Information], il a réussi à démontrer comment les circuits peuvent effectuer des fonctions logiques en exprimant un état binaire valant 1 ou 0 (états <code>vrai</code> ou <code>faux</code>). Depuis lors, la technologie numérique a façonné la dynamique de tout type de systèmes d'information. Dans cet esprit, nous nous sommes concentrés sur la création d'une conception efficace d'un appareil de gouvernance capable de fonctionner avec des blockchains et qui maintient ses opérateurs humains en tant que dirigeants souverains au moyen de ''votes''. De la même manière que les bits se déplacent dans les ordinateurs signalant un état <code>vrai</code> ou <code>faux</code>, les ''votes'' signalent une valeur booléenne pour que les décisions institutionnelles soient enregistrées dans le cadre de contrats intelligents.

Les jetons de ''vote'' fonctionnent dans les limites institutionnelles créées par cet ensemble de contrats: <code>Organizations</code> (Organisations), <code>Members</code> (Membres), <code>Issues</code> (Enjeux), <code>Ballots</code> (Bulletins de vote) and <code>Budgets</code> (Budgets). Ce sont les éléments de base qui aident à créer un circuit de gouvernance qui peut monter en échelle pour opérer des démocraties liquides au sein de communautés de toute taille.

[[File:/images/vote-liquid-democracy-smart-contracts.png|VOTE Liquid Democracy smart contracts..]]

====2.5.1 <code>Organizations</code> (Organisation)====

L'entité ou institution implémentant une instance de Sovereign est désignée comme une organisation (<code>Organization</code>). Cette entité agit en tant qu'autorité gouvernante définissant qui sont les membres (<code>Members</code>) autorisés à participer à ses décisions et en leur accordant des jetons de ''vote''. Puisque les organisations (<code>Organizations</code>) peuvent exister dans un réseau décentralisé, les exigences pour rendre une entité capable de fonctionner avec des ''votes'' sont similaires à celles trouvées lors de la mise en place d'un site web:

* Domaine (<code>Domain</code>): Chaque organisation doit avoir son propre nom de domaine (par exemple, ''democratie.earth'' sur le protocole HTTP). Certaines peuvent même avoir un espace de noms fonctionnant comme un domaine de premier niveau ou un TLD (Top Level Domain, par exemple ''.earth''). Ce code de référence pour une organisation au sein d'un réseau ouvert, qu'il s'agisse de l'ancien réseau HTTP ou de nouveaux réseaux émergents pour des domaines décentralisés tels que [https://blockstack.org Blockstack], est crucial pour construire une couche sémantique qui décrit efficacement les problèmes (<code>Issues</code>) sans risquer que les électeurs manipulent les tags dans un système fermé (référé à la section 2.5.4 comme ''squatting''). Les noms de domaine aident à décrire un problème ainsi qu'à restreindre la portée d'un contrat de délégation.

* Constitution (<code>Constitution</code>): Chaque organisation a une constitution qui définit ses règles fondamentales sous la forme d'un contrat intelligent. Le ''contrat intelligent constitutionnel'' décrit comment les membres (<code>Members</code>), les problèmes (<code>Issues</code>) et les ''votes'' se connectent au sein du système.

=====2.5.1.1 <code>Constitution</code>=====

The ''constitutional smart contract'' determines how ''votes'' will be allocated to members among other governance decisions. Allocation conditions are a prerogative of the organization depending on its goals: in some cases it can be aligned with financial rights (e.g. the shareholders of a corporation getting one ''vote'' per share); in other cases can be assigned based on an egalitarian distribution to all members (e.g. tax payers within a jurisdiction each getting a same amount of ''votes'').

The basic settings to be found on a constitution are:

* '''Decentralized ID''' (or URL): An identifier that helps refer to the <code>Organization</code> anywhere on the network and that it is connected to its <code>Domain</code>.

* '''Bio''': A basic description of the organization including its name, website, address, jurisdiction (if applicable).

* '''Funding''': The amount of ''vote'' tokens this organization will manage and how these will be allocated to every member and grant access to <code>Budgets</code>.

* '''Membership''': Requirements to become a valid member within organization. This criteria defines the voter registry that guarantees a fair electoral process of a democracy and can be scrutinized by its members.

** '''Open''': Anyone can freely join an organization.
** '''Voted''': Existing members must vote on applicant members. A percentage criteria must be set for approval.
** '''Fee''': The organization requires a payment for membership approval.

* '''Content''': Defines who is allowed to post <code>Issues</code> on the organization.

** '''Open''': Anyone (whether its a member or not) can post. Only members get the right to vote.
** '''Members''': Only approved members have the right to post.
** '''Special Members''': Members that meet certain criteria (e.g. a minimum of delegated ''votes'' or ''votes'' received under a specific tag) have the right to post.
** '''Anonymous''': Defines whether anonymous content is allowed to be posted.

* '''Moderation''': Describes the rules that help define a code of conduct among members of an organization.

** '''Ban''': An amount of ''downvotes'' required to ban a member from participating in the organization and the penalty attached to it (e.g. a period of time)
** '''Expulsion''': If an organization is based on ''Voted Membership Approval'', a member can receive negative votes from other members signalling that such identity has been corrupted or is no longer part of the organization. This criteria can be established as a minimum percentage required.

* '''Voting''': The allowed <code>Ballots</code> to be used for the decisions to be made by the organization and specific settings such as ''quadratic voting''.

* '''Reform''': The requirements to change any of the rules set on a ''Constitution'' (e.g. a special majority).

Templates defining common practices for specific kinds of organizations are encouraged to simplify organizational setup. This will be aided and abetted through work with the Democracy Earth Foundation partnership with [https://aragon.one/ Aragon], who is working on a digital jurisdiction that will make decentralized organizations efficient. Sovereign will include templates for corporations, political parties, trade unions, clubs and coops among others; whatever form the organization takes, Aragon's decentralized network ensures that a company will always work, even in the face of malicious tampering by hostile third parties or abusive governments.

====2.5.2 <code>Members</code>====

Every Organization has members that get the right to vote on the decisions of the organization. Membership criteria is defined in the ''constitutional smart contract'' and is key for the trust on any democratic environment. Among the most common ways to subvert an election is the manipulation of voter registry. Securing this aspect with cryptographic means as well as an approval protocol is critical. Once a member is approved within an organization, he or she gets a specific amount of ''votes'' to be used for its governance.

All <code>Organizations</code> who take the responsibility to approve or disapprove <code>Members</code>, contribute with this task to the ''Proof of Identity'' process described on Section 3.3.

Compatibility with decentralized identity protocols is encouraged for the purpose of guaranteeing decentralized governance. The [https://opencreds.github.io/did-spec/ specification of DIDs (decentralized identifiers analogous to the web's URIs)], proposed by the [https://www.w3.org/ W3C] enabling self-sovereign verifiable digital identity is recommended.

====2.5.3 <code>Issues</code>====

An organization consists of a collection of ''issues'' each describing a decision to be made by the members. Membership properties described in the ''constitutional smart contract'' define member's voting and posting rights. An issue in its most basic form has these properties:

* <code>Description</code>: Text of the decision to be made.
* <code>Tags</code>: Categories that describe the decision within the organization. This helps members navigate across issues, define areas or teams within an organization and limit the scope of a delegation of ''votes''. If the implementation is done with blockchain environments that are used to manage a fixed taxonomy (like [http://blockstack.org Blockstack]), a common distributed language for tags based on decentralized domains helps making the democratic environment more fair as it avoids members trying to control naming conventions for their own benefit. For this reason, within an open network <code>Tags</code> that describe <code>Issues</code> or are used to constraint delegations, are pointers to other <code>Organizations</code>. This is detailed in the ''Proof of Identity'' process.
* <code>Signatures</code>: Members that are authoring the proposal. It can remain anonymous if an organization's governance rules allows it.
* <code>Ballot</code>: The presented options for voters to participate on this decision.
* <code>Budget</code>: An optional element that may include locked funds in a cryptocurrency address that can trigger an action if a decision is voted in support.
* <code>Timespan</code>: For the final tally, an open poll must also set its scope in time and define the kind of decision being made. There are two types of decisions:
** <code>Tactical</code> (limited in time): These are contracts that receive ''votes'' until a closing date is met, where a given block height within the blockchain implementing the ''vote'' smart contracts can be set as the end line for the electoral process. Once all transactions have been tallied and a final result is recorded, all tokens get returned to the corresponding voters and can be used again on future decisions.
** <code>Strategical</code> (unlimited in time): Never-ending open polls that are perpetually registering the consensus of a decision state. ''votes'' can be retrieved by voters at any given time if they feel the need to discontinue their voice in support or rejection of a decision. But as long as the token is assigned to signal a preference on a contract ballot without closing date, it is part of the strategical decision. A common use for strategical decisions can be the members voting for approval of other members within the community of an organization.

====2.5.4 <code>Ballot</code>====

An issue can be implemented with any possible ballot design according to the specifications defined in the ''constitutional smart contract'' of the organization. The building blocks for a ballot are its <code>Interface</code>, <code>Options</code> and <code>Criteria</code>.

=====2.5.4.1 <code>Interface</code>=====

By default Sovereign provides the most commonly used choice mechanisms for ballot interaction. Further innovation on ballot interfaces is encouraged.

* <code>SingleChoice</code>: One selectable option.
* <code>MultipleChoice</code>: One or more selectable options.
* [https://en.wikipedia.org/wiki/Cardinal_voting <code>Cardinal</code>]: A given score per option with a pre-defined range of value.
* [https://en.wikipedia.org/wiki/Ranked_voting <code>Ranked</code>]: Sortable options as ranked preferences. [https://en.wikipedia.org/wiki/Arrow%27s_impossibility_theorem Arrow's impossibility theorem] must be taken into consideration for any innovation regarding ranked ballots. This theorem states that rank-based electoral systems are not able to satisfy fairness on three key aspects at the same time:
** '''Unrestricted domain''': all preferences of all voters are allowed.
** '''Non-dictatoship''': no single voter possesses the power to always determine social preference.
** '''Pareto Efficiency''': if every voter prefers an option to another, then so must the resulting societal preference order.

=====2.5.4.2 <code>Options</code>=====

In order to enable the information processing of ''votes'', ballots carry boolean values expressed in their options. This lets ''vote'' transactions signal a ''decision state'' that will act as a force modeling the institutional choices for the implementing organization. This makes all decentralized organizations also into programmable institutions. Options can then be:

* <code>True</code>: It will signal a <code>true</code> boolean value if selected (often described with 'Yes' or 'Positive' label strings).
* <code>False</code>: Signals a <code>false</code> state (e.g. can display 'No' or 'Negative' labels).
* <code>Linked</code>: The option is connected to another decision within the organization.
* <code>Candidate</code>: A member or list of <code>Members</code> from the organization. This helps elect authorities within the organization or it can be used for membership approvals.

=====2.5.4.3 <code>Criteria</code>=====

Finally, counting methods for the final or ongoing result of a decision within an organization.

* <code>Plurality</code>: Simple majority wins decision.
* <code>Majority</code> A minimum percentage is required for winning decision.
* [https://en.wikipedia.org/wiki/D%27Hondt_method <code>DHont</code>]: Widely used by Nation-State elections based on member lists.
* [https://en.wikipedia.org/wiki/Schulze_method <code>Schulze</code>]: Commonly used by open source communities and Pirate Parties using ranked choice ballots.
* [http://ilpubs.stanford.edu:8090/422/1/1999-66.pdf <code>PageRank</code>]: Counts votes weighting voter reputation in a graph.

====2.5.5 <code>Budget</code>====

Every <code>Organization</code> can have 1 or more cryptocurrency addresses to fund its efforts. Sovereign permits to fund an <code>Organization</code> with Bitcoin and in its <code>Constitution</code> define a criteria on how these assets get distributed among <code>Members</code>:

* '''Percentage for ''Proof of Identity''''': Applicant <code>Members</code> can submit their ''Proof of Identity'' evidence to get membership approval to an <code>Organization</code>. If ''votes'' approve the new member, it strengthens the reputation of a self-sovereign identity in the open network by rewarding him or her a fixed amount of Bitcoin to permit hashing the ''Proof of Identity'' on a blockchain. Some <code>Organizations</code> may allow a bigger reward than others, effectively creating a Reputation score that can protect the network against ''Sybils'' or false identities. This process is detailed on [[#Executive|Section 3]].

* '''Percentage for <code>Issues</code>''': <code>Members</code> seeking to use resources from the <code>Organization</code> can request them by attaching a <code>Budget</code> to an <code>Issue</code>. A <code>Member</code> can request to used funds from a pool specifically reserved for this. If the final tally of a decision reaches a certain value (<code>true</code> or <code>false</code>), it can then enforce the final decision by unlocking coins or triggering a transaction sending the requested assets to a specific address.

===2.6 Sécurité.===

Avec Sovereign, nous visons à fournir un cadre de gouvernance léger qui permet à toutes les parties prenantes d'une organisation de participer et d'appliquer les décisions grâce à l'utilisation de la cryptographie. Mais il est important de préciser que nous ne visons pas un système démocratique classique basé sur la domination de la populace ou le [https://en.wikipedia.org/wiki/Majoritarianism ''majoritarisme'']. L'histoire offre suffisamment d'exemples de situations où une majorité aveugle finit par faire échouer les aspirations d'une république en mettant souvent des démagogues au pouvoir.

[[File:/images/ideal-democracy.png|Ideal democracy.]]

Notre objectif principal est de fournir un système capable de garantir la plus grande légitimité possible tout en habilitant les voix les plus compétentes dans n'importe quelle communauté. La différence entre un fait et une promesse est simple: alors que l'art de la politique consiste à soutenir la fiction qui nourrit la confiance dans les institutions établies (par exemple des politiciens durant une campagne), la preuve cryptographique des événements fournit une méthode plus fiable pour une bonne gouvernance. La nature incorruptible des transactions blockchain incite les gens à ne pas mentir, ce qui explique que les organisations qui y stockent les votes et les décisions sont guidées par des faits plutôt que par des promesses. La corruption peut être combattue à sa source à mesure que nous développons un nouveau sens de la citoyenneté basé sur les réseaux numériques.

Pourtant, les démocraties liquides peuvent être faussées de différentes manières, avec des résultats dominés par les conséquences inattendues de deux dynamiques qui représentent les extrémités du spectre de la participation:

* '''Un manque de délégation''' menant à un ''polyopole'': fragmentation extrême du pouvoir électoral.
* '''Une abondance de délégations''' conduisant à un ''monopole'': concentration extrême du pouvoir électoral.

Chaque résultante a un impact sur l'un des deux axes qui mesure la qualité de la gouvernance démocratique. Les incitations sur l'économie politique ''vote'' sont conçues pour maintenir un équilibre stable visant à garantir le plus haut niveau de légitimité et de prise de décision factuelle.

Pour créer un environnement de confiance pour une gouvernance décentralisée dans de grandes communautés (villes, nations ou à l'échelle mondiale), Sovereign doit être protégé contre différents types d'attaques: les ''Mobs'', les ''Corporations'', les ''Sybils'', les ''Fakes'' et ''Big Brother''.

====2.6.1 Polyopole.====
<blockquote>
  également connu sous le nom de ''Populace''
</blockquote>

[http://www.tdcommons.org/cgi/viewcontent.cgi?article=1092&context=dpubs_series Google Votes] fait partie des projets de recherche les plus notables dans le domaine. Il s'agissait d'une implémentation interne réalisée pour les employés de Google et menée par l'ingénieur Steve Hardt. Il a ainsi créé un plug-in de démocratie liquide à utiliser sur la version interne de Google+. Le projet produisit les résultats chiffrés ci-après en termes d'impact:

* 15 000 participants.

* 371 décisions.

* '''3,6% de votes délégués''' au total.

Le faible pourcentage de délégations signifie que Google Votes fonctionnait davantage comme une démocratie directe qu'une démocratie liquide. Les délégations se sont principalement produites parmi les utilisateurs qui ont activement fait campagne pour les attirer (par exemple, les végétaliens dans une équipe qui espéraient accumuler du pouvoir pour choisir les collations servies au travail). Le risque associé au faible nombre de délégations est que cela ouvre la démocratie aux risques connus de la domination par la populace. Bien que la légitimité puisse restée élevée, la qualité des décisions prises par une organisation devient davantage politique que factuelle. Les voix bien informées capables d'adresser des problèmes spécifiques au sein d'une communauté perdent ainsi de leur pouvoir.

Pour augmenter la fréquence des délégations, celles-ci se produisent chaque fois que les auto-souverains sont validés. En ce qui concerne le processus de ''preuve d'identité'' (voir la section 3), les utilisateurs sont capables de générer nativement leurs propres ''votes'' aussi longtemps que leur individualité est endossée par d'autres identités. De plus, les délégations n'ont pas forcément besoin de se produire à l'intérieur de l'application Sovereign puisque le token ''vote'' fonctionne dans une blockchain: les applications de messagerie, les tweets et les e-mails peuvent être envoyés avec des adresses de vote ou des codes QR en attachement permettant ainsi au token vote d'être diffusé sur plusieurs réseaux.

====2.6.2 Monopole.====
<blockquote>
  également connu sous le nom de ''Corporations''
</blockquote>

Lorsque le Parti Pirate allemand a mis en place [https://en.wikipedia.org/wiki/LiquidFeedback Liquid Feedback], un logiciel pionnier de démocratie liquide développé en 2009, celui-ci a atteint un niveau de participation d'environ 550 affiliés, ce qui a conduit [http://www.spiegel.de/international/germany/liquid-democracy-web-platform-makes-professor-most-powerful-pirate-a-818683.html un professeur de linguistique à devenir le membre le plus influent du parti]. Martin Haase était chargé de traduire toutes les propositions téléchargées dans le système dans un langage neutre afin d'éviter tout parti pris idéologique, ce qui fait qu'il a pris 167 délégations à d'autres membres.

Les conséquences de ce genre de monopole créé par un leader  dans un environnement de démocratie liquide vont à l'encontre de l'esprit d'un écosystème qui vise à encourager une plus grande participation. Dans les démocraties liquides, ''des célébrités'' peuvent devenir extrêmement influentes et attirer ainsi la plupart des votes délégués. Un agresseur prêt à renverser une élection peut faire la promotion d'une star de télévision arborant un code QR pour créer un afflux soudain de délégations de la part des fans et des téléspectateurs, devenant instantanément une force monopolistique. Les monopoles sont une menace pour les démocraties liquides, car ils peuvent dissuader les électeurs moins chanceux de participer, détournant ainsi la légitimité des décisions prises.

=====2.6.2.1. Vote quadratique.=====

Une caractéristique clé d'un système de démocratie liquide est de permettre un [http://ericposner.com/quadratic-voting/ vote quadratique] pour les délégations. Le coût pour Alice de déléguer des votes à Bob augmente de façon exponentielle à mesure que les votes sont délégués. Avec des délégations quadratiques, Alice ne peut déléguer à Bob que 1, 2, 4, 8, 16 ou même 128 ou 512 ''votes'', mais aucune valeur entre deux. Cela permet à toute délégation de taxer le délégant en réduisant le coût d'opportunité de déléguer à un autre membre. Cette méthode prévient la montée des monopoles dans la dynamique de marché des démocraties liquides, en faisant toujours en sorte que la participation de tous les membres soit pertinente. Si certaines organisations souhaitent une chaîne de commandement plus verticale (par exemple, des corporations), le vote quadratique peut toujours être désactivé dans le ''contrat intelligent constitutionnel'' d'une implémentation Sovereign.

====2.6.3 Attaque Sybil.====
<blockquote>
  également connu sous le nom d' ''usurpation d'identité''
</blockquote>

Quiconque a la capacité de contrôler le registre des électeurs d'une élection donnée peut directement influencer le résultat final. Un exemple classique est l'inscription de membres défunts de la société pour voter à une élection. Sur les réseaux décentralisés, on parle communément d'[https://en.wikipedia.org/wiki/Sybil_attack attaque Sybil] (un terme tiré d'un [https://www.youtube.com/watch?v=8kPIDt3yu1M film du même nom sorti en 1976] basé sur un personnage qui souffre d'un syndrome de personnalité multiple). Les nœuds Sybil sont ceux qui s'identifient comme des acteurs indépendants du réseau alors qu'ils sont tous sous le contrôle d'un seul opérateur. Dans les environnements décentralisés, les attaques Sybil sont la menace la plus commune. Et c'est pour cette raison que nous considérons qu'il est indispensable que les ''votes'' doivent être validés par un protocole (social et algorithmique) qui fonctionne comme ''preuve d'identité'', afin d'être accordés.

====2.6.4 Fausses nouvelles.====
<blockquote>
  également connus sous le nom de ''potins''
</blockquote>

Ce n'est pas une coïncidence si le champ de bataille des démocraties modernes se dispute dans les médias. Les agences de presse et autres organisations qui vendent de l'information disposent d'une capacité sans précédent pour façonner la perception des électeurs. A travers différentes juridictions dans le monde, les gouvernements mènent une guerre interne entre l'État et le plus grand conglomérat de médias locaux. C'est le mode d'emploi utilisé par Donald Trump dans son combat contre le tandem formé par CNN et le New York Times. C'est aussi la raison pour laquelle Vladimir Poutine a investi d'importantes ressources pour créer Russia Today afin de disposer d'une plateforme pour présenter des faits alternatifs. Contrôler le message a plus d'importance que la vérité elle-même. Des médias libres et un journalisme indépendant sont une exigence fondamentale pour des démocraties stables. Mais s'il est difficile de faire la preuve des faits institutionnels, alors la marge de manœuvre pour la manipulation est plus grande que la place mise à disposition pour que la vérité prévale. Les institutions traditionnelles cultivent le secret et manquent de transparence même si elles relèvent de la fonction publique. Les blockchains permettent de stocker des faits institutionnels qui garantissent la transparence dans les organisations. En ce sens, il est possible de lutter contre de ''fausses nouvelles'' grâce à un nouveau modèle institutionnel capable de stocker des ''promesses fermes''.

=====2.6.4.1 Promesses fermes=====

Les corporations et les institutions publiques sont sujettes à la corruption parce que les décisions sont souvent prises en secret derrière des portes closes, tandis que la comptabilité se produit au fur et à mesure. En effet, les organisations ''blanchissent les décisions'' en déconnectant la redevabilité des décisions. Le fait qu'il manque une ligne de temps incorruptible qui stocke les décisions financières et politiques permet une telle absence de redevabilité. L' [https://fr.wikipedia.org/wiki/Léviathan_(Thomas_Hobbes) État ''Léviathan''] est une machine inefficiente: bien qu'il se proclame comme le souverain d'une population donnée par le moyen de la force, quiconque est en charge de gérer sa bureaucratie peut toujours être corrompu, entraînant par là même l'effondrement de tout le château de cartes. Cette distance entre les faits et la comptabilité est la source des potins.

Les éléments constitutifs des institutions consistent en des faits qui définissent des accords. Mais les faits contenus dans les accords sont d'un type très spécifique: les institutions ne sont pas construites sur des faits objectifs qui sont scientifiques, mesurables et indépendants du jugement humain; mais plutôt sur des faits intersubjectifs qui façonnent le monde social au sein d'une communauté qui fixe les rapports de droits et de propriété. Par exemple, la notion selon laquelle chaque canette de soda rouge appartient à la Coca Cola Corporation n'est pas objective mais constitue un fait intersubjectif accepté par tous les membres de la société qui reconnaissent les droits de propriété intellectuelle qu'une entreprise exerce sur son produit. De cette façon, la réalité institutionnelle permet le passage à l'échelle des relations économiques et la réduction des informations nécessaires pour que les organisations puissent réaliser des transactions.

Les bureaucraties qui protègent ces accords reposent sur des promesses, à savoir “tout l'argent qui est gardé dans les banques sera là demain”. Mais comme le dit [https://twitter.com/aantonop/ Andreas Antonopoulos]: “Nous sommes habitués à des systèmes de douces promesses et de transactions réversibles.” Si le gouvernement (ou tout autre type d'autorité centrale) voulait confisquer des fonds privés stockés dans une banque, personne ne pourrait les empêcher de rompre cette promesse. Cela a été l'expérience des citoyens grecs, argentins, vénézuéliens ou portoricains avec leurs propres gouvernements défaillants au cours de la dernière décennie. D'un autre côté, les organisations basées sur la blockchain offrent une alternative basée sur des ''promesses fermes'': des accords stockés dans des contrats intelligents rigoureusement protégés au moyen de la cryptographie qu'aucune tierce partie ne peut corrompre. Plutôt que de réguler le comportement humain a posteriori comme le fait la loi gouvernementale, les blockchains garantissent la transparence par défaut en encourageant un comportement honnête puisque chaque participant est conscient que les événements institutionnels seront ouvertement sujettes à un examen minutieux.

====2.6.5 Squattage.====
<blockquote>
  également connu sous le nom de ''Big brother''
</blockquote>

Une démocratie liquide opère à travers plusieurs domaines. Mettre en place une <code>Organisation</code> au sein d'un réseau de ''votes'' délégables est analogue à la création d'un serveur sur le Web. Le squattage de domaine est la pratique qui consiste à occuper des adresses Web abandonnées ou inutilisées dans l'espoir d'en tirer un bénéfice. Cela a généré un marché d'un milliard de dollars dans lequel les mots les plus couramment utilisés (identifiants) représentent le meilleur type de propriété numérique. [http://sex.com Sex.com] [https://en.wikipedia.org/wiki/Sex.com#Highest_price_paid_for_domain est ainsi le domaine le plus cher].

A grande échelle, le jeu de la démocratie liquide se développe à la longue autour des <code>balises</code> utilisées pour décrire les délégations et les problèmes. Dans un système fermé, les <code>balises</code> les plus utilisées pointent vers un univers réduit d'électeurs pertinents qui mènent les délégations qui leur sont associées. La participation réduite des électeurs augmente la capacité de prédiction d'une démocratie, réduisant ainsi les moments ouverts à la prise de décision collective. La démocratie prospère tant que la participation est encouragée. Pour éviter ce genre d'attaque, les intérêts financiers et politiques doivent être alignés. Le ''squattage de balises'' peut être évité si la taxonomie utilisée pour créer des délégations liquides et des descriptions de problèmes fonctionne dans un réseau ouvert: Les <code>balises</code> désignent des <code>Organisations</code> qui sont enregistrées sous un système décentralisé de nom de domaine, dans la mesure où chaque <code>Organisation</code> a besoin d'un nom de domaine. [Blockstack.org Blockstack's blockchain] se spécialise dans les noms de domaine décentralisés et gère actuellement plus de 70 000 identifiants décentralisés (IDD). Ces identifiants s'obtiennent via un processus ''Proof of Burn'' dans lequel les utilisateurs brûlent des Bitcoin contre des tokens Blockstack qui permettent d'enregistrer un nouveau nom de domaine.

Les mots définissent les idées politiques. La narration sociale développée par l'art de la politique consiste à décider de l'intention sémantique. Le pouvoir définit les empreintes théâtrales qui marquent nos souvenirs chaque fois que nous utilisons les termes ''gauche'', ''droite'', ''libre'' ou ''égal''. Le langage est un code hérité qui permet une collaboration humaine à grande échelle et on ne peut pas nier ses vertus.

----

Toutes ces stratégies sont au coeur de la façon dont une organisation décentralisée s'institutionnalise. En d'autres termes: il s'agit de définir les risques sur la manière dont Democracy Earth attribue les ''votes'' à ses membres sur la blockchain en tant qu'entité décentralisée. Pour cette raison, nous détaillons à la [[#Execution|Section 3]] un plan de déploiement des ''votes'' qui érige des défenses solides contre ce type d'attaques et ouvre la voie à une démocratie globale.

<div id="Execution"></div>

==3. Exécution.==

[[File:/images/humans.png|Population humaine exponentielle au cours du temps.]]

L'augmentation de la population est au cœur des défis économiques et politiques du 21<sup>e</sup> siècle : [https://esa.un.org/unpd/wpp/ Les Nations Unies estiment que d'ici l'an 2100 la population mondiale surpassera les 10 000 000 000 individus]. En d'autres termes, la [https://fr.wikipedia.org/wiki/Capacit%C3%A9_porteuse capacité porteuse] de la planète sera atteinte d'ici la fin du siècle.

On peut trouver des indices sur les conséquences de l'apauvrissement en ressources en étudiant l'histoire des îles. Une île lointaine comme [https://fr.wikipedia.org/wiki/Histoire_de_l%27%C3%AEle_de_P%C3%A2ques l'île de Pâques] a été durant son histoire un système fermé, coupé de tout contact avec l'exterieur, dont la population n'avait pas d'autre moyens de survie que ses propres ressources, faisant sans cesse face aux dangers de famine, d'épidémie, et de guerre civile. Bien que ces menaces semblent lointaines dans une économie mondiale, la hausse soudaine de la population humaine au cours du siècle dernier est en majorité responsable de l'augmentation du niveau de CO<sub>2</sub> dans l'atmosphère et de l'effondrement du système public, incapable de gérer les migrations massives. Les réfugiés fuient des guerres d'annexion de ressources énergétiques pour un futur qui s'approche toujours plus vite, au rythme des innovations technologiques. Bien que certains préparent déjà des échappatoires, notamment le secteur privé avec la colonisation de Mars dans les prochaines décennies (qui n'est pas sans rappeler l'Arche de Noé), l'appel urgent à la sauvegarde de l'humanité toute entière doit être amplifié et répondu.

Une distribution des opportunités et une collaboration mondiale intelligente ne peuvent être obtenues pacifiquement qu'à condition que toutes les voix puissent se faire entendre, sans exception. La gouvernance globale est la prochaine étape logique dans un monde déjà connecté via Internet. Les blockchains creusent les fondations d'une démocratie de pairs et nous guident vers la possibilité d'une gouvernance liquide. La permission des États-Nations en place n'est pas requise : les citoyens du monde peuvent accueillir ce changement par biais de réseaux souverains.

===3.1 Droits vs. Dette.===
<blockquote>
   "Qu'est-ce que la justice ?" demanda le philosophe.
   "Paie tes dettes et ne mens pas" répondit Kefalos (capital), un riche fabricant d'armes.
</blockquote>
'''Platon''', ''La Republique''. Philosophe (428-348 av. J.-C).

Bien que la politique et l'économie soient souvent considérées comme des domaines distincts, l'histoire nous enseigne que l'argent donne du pouvoir, et que le pouvoir donne des votes. Afin de promouvoir la démocratie de façon efficace, il est indispensable de s'occuper des deux.

Les modèles économiques actuels sont toujours enracinés dans une intrication de la dette, de la morale et des guerres. La monnaie a été inventée par les grands empires financiers pour permettre aux soldats d'acheter des provisions dans des contrées lointaines, et les récompenser de leurs victoires. Ils pouvaient ainsi piller l'or et l'argent des cités conquises et l'échanger plus tard aux empereurs qui s'en servaient pour émettre des pièces et développer des marchés. Les empires finirent par réclamer une partie de ces pièces sous forme de taxe, afin de financer l'armée. La morale de l'histoire fut que les citoyens devinrent ''endettés'' auprès de leur empereur pour leur sécurité, pour pouvoir rester en vie. La dette a évolué comme justification des formes de coercition maintenant les hiérarchies de pouvoir en place dans tous les pays. Le manque d'argent est l'entrave à la liberté la plus immédiate et la plus tangible pour la plupart des êtres humains.

Le bulletin de ''vote'' sera distribué comme un '''Droit''' opposant l'association historique de la '''Dette''' et de la morale, générant un terrain fertile pour des transactions libres de coercition. Il a pour but de rendre équivalentes les entités de part et d'autre d'une transaction, ainsi que de rétablir la justice et l'équilibre en tant que standards moraux. La liberté et la souveraineté personnelle sont la mission de Democracy Earth, qui ne peut être remplie que si tous les individus ont la possibilité de dire "non" et de choisir sans contraintes des solutions alternatives. Cela ne pouvant pas être atteint avec la rareté induite qu'on retrouve sur la plupart des cryptomonnaies, il faut garantir un accès équitable aux ''votes'' à tous les membres de la société, transformant le droit de vote en instrument liquide.

Pour cette raison, la [http://democracy.earth Fondation Democracy Earth] génèrera une ''Offre Initiale de Droits'' en bulletins de ''vote'', dans le but de traiter équitablement tout le monde dans un processus qui offrira deux mécanismes : le financement cryptographique pour quiconque souhaite allouer des ressources pour renforcer le développement d'une démocratie globale au moyen du bulletin de ''vote'' ; et un état de droit comme moyen d'obtenir des bulletins de ''vote'', pour quiconque pouvant ''miner'' sa part de ''votes'' au travers d'un processus connu sous le nom de ''Preuve d'Identité'' (PI).

====3.1.1 Offre Initiale de Droits.====

L'identité est fondamentale pour la souveraineté personnelle, et est au cœur de tout système de vote. Les votes (peu importe le système) ne sont valides que si leur auteur peut être vérifié comme appartenant une organisation, aucune démocratie ne peut fonctionner avec des identités corrompues. Les systèmes d'identification actuels sont basés sur des autorités centrales qui collectent les informations personnelles et rendent vulnérables leurs utilisateurs au vol d'identité si les serveurs se font pirater, comme c'est arrivé notamment pour [https://gov.uk le Royaume Uni (gov.uk)] et [https://uidai.gov.in/ l'Inde (aadhaar)], les deux ayant été affligés de nombreuses pratiques de sécurité insuffisantes, menant à des fuites d'information affectant la vie privée de millions de gens.

Pour que les identités puissent être auto-souveraines, elles ne peuvent être détenues ou contrôlées par des gouvernements, organisations ou entreprises qui ont pour but final d'extraire de la valeur de leurs utilisateurs. Notre approche avec [http://sovereign.software Sovereign] est centrées sur une organisation en tant que technologie, mais une organisation peut être décentralisée si son processus de vérification d'identité ne requiert pas d'autorité centrale. Puisque le principe d'identité autonome rend ''Big Brother'' obsolète, tout processus reposant sur une identité décentralisée devient part du domaine public. Donc la clef pour assurer la valeur du bulletin de ''vote'' comme outil démocratique sans frontières est de vérifier les identités au travers d'un processus décentralisé qui peut créer, mettre à jour ou révoquer des clefs. C'est ainsi que la Fondation Democracy Earth offrira un accès aux ''votes'' comme droit fondamental.

[[File:/images/identity-blockchain.png|Identité auto-souveraine.]]

Quiconque capable de démontrer sa propre identité dans le cadre d'un protocole décentralisé appelé ''Preuve d'Identité'' (PI) reçevra une part initiale et équitable de ''votes''. Ce mécanisme déclenche une allocation au fil du temps à l'adresse publique revendiquée de l'identité accessible via un portefeuille auto-hébergé connecté au contenu et aux données utilisées pour la PI. Si assez de ''votes'' valident les éléments de preuve utilisés pour la PI, le porte-monnaie dégèlera une quantité correspondante de ''votes'' suivant les règles d'une dynamique de ''Revenu de Base Universel'' qui alloue des bulletins au fil du temps, et qui utilise la blockchain de Bitcoin comme horloge universelle.

===3.2 Preuve d'Identité.===

Une identité auto-souveraine doit être générée volontairement par un utilisateur qui la revendique. À cette fin, l'utilisateur doit diffuser une preuve de son identité qui satisfait pleinement des critères requérant un jugement humain et capables d'empêcher un robot d'interfèrer avec le processus. Par conséquent, une bonne preuve est dans un format qui nécessite une grande quantité de bande passante cérébrale, comme la vidéo. Une preuve acceptable doit satisfaire à toutes ces propriétés :

* '''Incorruptible''': Le fichier vidéo doit être protégé contre toutes modifications une fois qu'il a été utilisé comme source de preuve.
* '''Singulière''': La preuve doit valider une identité unique sans permettre la duplication de participants sur le réseau (''réplicants'').
* '''Reputée''': Toute <code>Organization</code> validant une PI lui attache sa reputation en lui apposant sa signature.

Même si tout système de gouvernance numérique peut bénéficier de la confiance déjà présente dans les réseaux existants validant les identités (c'est-à-dire les États-nations), un protocole décentralisé pour valider les identités répond à l'objectif politique de la souveraineté personnelle. Les avantages de cet enregistrement public dans un espace partagé sur le réseau peuvent éventuellement être utilisés par des gouvernements ou des organisations privées de différentes façons (par exemple, vérifier l'âge ou la nationalité). Nous proposons ici une nouvelle méthode pour valider les identités sans avoir besoin d'un seul ''Big Brother''.

Une ''Preuve d'identité'' expire après une période donnée afin d'éviter les attaques sibyllines et d'assurer que seuls les utilisateurs vivants participent au réseau. Pour maintenir la validité de la paire de clefs, nous pensons qu'une période de 1 an est suffisante pour requérir la génération d'une nouvelle preuve mettant à jour la précédente. De la même manière que les identités physiques sont vérifiées en comparant l'image à la personne, les utilisateurs devront recréer leur ''Preuve d'identité'' et la diffuser pour vérification afin d'authentifier leur légitimité. Le jour de mise à jour peut être qualifié d' ''anniverchaîne'' d'un individu et, si désiré, célébré chaque année, de la même manière que les nations célèbrent leur journée de l'indépendance. Quand les nouveau-nés seront inscrits sous cette juridiction mondiale, les ''anniverchaînes'' se synchroniseront avec les anniversaires et pourront incorruptiblement attester de l'âge tout en réduisant progressivement le travail des authentificateurs au fil du temps.

====3.2.1 Démo.====

[[File:/images/roma-siri-blockchain-baby.png|Le certificat de naissance de Roma Siri stocké sur la chaîne de blocs.]]

Il existe un précédent qui aide à illustrer la manière dont une ''Preuve d'Identité'' fonctionne. [https://youtu.be/Irc-VMuUs3c?t=55m20s Selon le professeur de NYU David Yermack], la nouvelle-née Roma Siri est devenue le premier bébé à avoir un certificat de naissance valide sur la chaîne de blocs pour le 7 novembre 2015. Le processus, bien que symbolique à l'époque, se composait d'une [https://www.dropbox.com/s/tsi4xo4k6j1jsa6/Blockchain%20Birth%20Certificate%20of%20Roma%20Siri%20-%20Daughter%20of%20Santiago%20Siri%20%28father%29%20and%20Pia%20Mancini%20%28mother%29.MOV?dl=0 vidéo montrant Roma bébé, sa vitalité et des témoins de sa naissance]. Une fois la vidéo filmée, une empreinte numérique du fichier a été générée et encodée dans une transaction Bitcoin. Cela signifie que peu importe où la vidéo est stockée, l'enregistrement permanent de son empreinte sur la chaîne de blocs Bitcoin permet de vérifier que le fichier n'a pas été corrompu et qu'il existait au moment où la preuve a été générée. Avec cette preuve incorruptible, Roma est devenue une citoyenne mondiale certifiée par la chaîne de blocs.

Cette démo sert d'exemple pour les étapes à franchir pour obtenir une ''Preuve d'Identité'' décentralisée :

# '''Preuve audiovisuelle''' obtenue depuis un téléphone ou une caméra.
# '''Preuve par empreinte''' sur une chaîne de blocs pour garantir d'incorruptibilité de la preuve.
# '''Preuve de validation''' au travers d'un processus de vote entre pairs (''Attention Mining'').

====3.2.2 Video Proof.====

A proof can be done with any recording application as long as it satisfies the requirements of the protocol. An extension no longer than 3 minutes is recommended for the video. In it the user must follow a series of scripted steps in order to help validators judge with their attention:

# '''Face''': Under frontal light, film frontal expression (as when taking a ''selfie'') and each side of the head without wearing eyeglasses, hats, makeup or masks of any kind.

# '''Names''': Say out loud the following indicators:
## Full given name (language-based identity).
## Full surname (blood-based identity, additionally it can state information regarding mother and father).
## Nationality (territorial-based identity, it can include place of residence or tax paying jurisdiction).
## Alternatively the user can use a nickname if it is a more common pointer to his self.

# '''Biometrics''' (Optional): Say out loud or demonstrate in a reliable way any of these indicators. This can be useful for specific use cases such as birth certificates.
## Birthday (day, month and year).
## Height (inches or centimeters).
## Weight (pounds or kilograms).
## Gender (male, female, etc).

# '''Witnesses''' (Optional): Previously validated identities can act as witnesses for this identity. They can be physically on location and appear in the video stating their full names and public keys to endorse a new identity.
## The witnesses can get granted the rights to revoke, update or cancel this proof (e.g. in case of loss of private keys or biological death).
## Twins. Those who have a twin brother or sister must specify this to prevent being flagged as a ''replicant'' during the verification process.
## Certifications. Even though this would be falling back to central authority, legacy reputation from state-issued documents can help make a video proof easier to trust. This might include a birth certificate, driver's license or a national ID as long as it doesn't hold any sensitive information (e.g. using a Social Security Number in the US).

# '''Declaration''': To guarantee that the person generating his or her identity proof is aware of the rights he will receive upon having his membership approved on the network and is not being coerced by an unseen attacker, it is mandatory to make a declaration of self-sovereignty that also includes an oath regarding the stated facts: <blockquote>I, (Personal Name), declare that I'm making this video in accordance to my personal sovereignty as a citizen of Earth and all the statements made are true. I will be the sole user of all the ''votes'' allocated on behalf of this proof and I'm acting without any threat or coercion against my free will.</blockquote>

# '''Public Key''': An address where ''votes'' will be allocated if identity is validated. This will be the [https://github.com/WebOfTrustInfo/ID2020DesignWorkshop/blob/master/topics-and-advance-readings/DID-Whitepaper.md Decentralized Identifier (DID)] pointing to this user. If this identity eventually is voted as corrupted or the user (or any listed witness) revoke it, then the allocated ''votes'' will get invalidated for future use.

# '''Timestamp''': Current block height of the blockchain used for hashing this video to prevent any videos unrelated to the moment in time the POI is being generated to be used as proof. A manual timestamp can simply film the screen of a blockchain explorer application displaying the last block number and the hash corresponding to it. Since this might be complex for most users, apps designed to generate this proof can automatically add this content to the video. This information once the proof is hashed with a blockchain transaction will certify the video was not modified in any possible way by a third party after it was broadcasted to the network.

Even though this process can be more complex than the average sign-up form found on most applications, it is important to state that it is also a political act declaring independence from authorities of any kind. This video is the personal manifesto anyone can make to break free from coercion and a step taken towards a borderless democracy.

====3.2.3 Hashing.====

Once the digital file with the self-sovereign proof has been generated, a [https://en.wikipedia.org/wiki/Cryptographic_hash_function cryptographic hash function] applied to it is calculated. Following the steps of the implementation made by Manuel Araoz and Esteban Ordano with [https://proofofexistence.com ProofofExistence.com], a standard [https://en.wikipedia.org/wiki/SHA-2 SHA-256] digest is recommended. Once the hash has been generated, it can be encoded in a Bitcoin transaction using an [https://en.bitcoin.it/wiki/OP_RETURN OP_RETURN] script that also includes a marker that helps track identity-related proofs. We suggest using 'IDPROOF' (0x494450524f4f46) for this particular use case.

Considering that an average bitcoin transaction consists of 226 bytes with a mining fee as of August 2017 at 27,120 satoshis, the cost for hashing a proof directly on the blockchain is at ~$1 per proof. This can be relatively expensive for a majority of people, hence we recommend scaling this process by enabling a [https://github.com/aantonop/chainpoint Chainpoint] implementation able to store up to 10,000 proofs per transaction by putting the hashed data on a [https://en.wikipedia.org/wiki/Merkle_tree Merkle Tree] and encoding the Merkle root in the OP_RETURN script instead. This will also significantly reduce the memory requirements of the Bitcoin blockchain, a public resource that must not be abused. Alternatively, virtualchains that run on top of the Bitcoin blockchain that have a focus on identity and namespaces such as [http://blockstack.org Blockstack] can be used to satisfy this use case and the management of the private-public key pair.

Any proof that goes through this process in a digital context is guaranteed to not be corrupted in any way. The digital files being used as proof can be stored anywhere, copied without restrictions or even kept in secret without sharing it with anyone. As long as there is a transaction in the blockchain that can validate the encoded hash with the data of the digital file, then the evidence is valid. The Bitcoin blockchain offers the strongest resistance to corruption since it has the largest amount of hashing power in the world protecting its infrastructure. With this mechanism in place, the Bitcoin blockchain can operate as a decentralized index of self-sovereign identities. Leveraging this capacity will only make the bureaucracy of a borderless democracy stronger than any other government on Earth.

====3.2.4 Attention Mining.====
<blockquote>
  In the blockchain nobody knows you are an AI.
</blockquote>
'''Satoshi Nakamoto'''.

[[File:/images/proof-of-identity.png|Proof of Identity.]]

In computer-space identities are nothing but pointers: algorithms lack any awareness about the patterns they are trained to recognize. Identities strictly belong to the human realm (i.e. only a person can recognize another person). So rather than harnessing ''distributed computing power'' to verify transactions as it happens with most cryptocurrencies, ''votes'' use ''distributed attention power'' to verify self-generated identity proofs. This attention is brought in by human participants that act as validators.

A well known precedent of attention mining are CAPTCHA tests often found in the login of high-traffic websites. CAPTCHA is an acronym for ''Completetly Automated Public Turing test to tell Computers and Humans Apart''. These consist of simple vision excercises that can be completed by a human more easily than by a computer. A field [https://www.cs.cmu.edu/~biglou/reCAPTCHA_Science.pdf pioneered by researcher Louis Von Ahn], he used this technique to help build datasets able to train machine learning algorithms to read words printed on paper. As a Google engineer Von Ahn created a simple test distributed across all login pages that displayed two words obtained from scanned pictures. A user would write both words in a text input field to prove he is human and not a machine. The system already knew the meaning of the first word (hence validating the user is human) but it got trained with the second input as it uses this information in the dataset for character recognition algorithms. This simple excercise has been extended to train all kinds of pattern recognition systems and it contributed to the security of websites preventing bots (and botnets) from intruding.

Attention can also validate human identities on a decentralized network, analogous to [https://bitcoin.com/bitcoin.pdf Bitcoin's Proof of Work algorithm (POW)] used by mining nodes to timestamp peer to peer transactions. In Bitcoin, each miner generates its own blockchain-compatible proof hash for a new block of transactions and broadcasts it to the network. If 51% of the nodes in the network accept the verified block, it gets chained to the blockchain and the miner starts working on the next transaction block using the accepted block as the previous hash. This technique permits monetary transactions without central banks. In a democracy without central governments instead of verifying encrypted blocks, human attention serves the purpose of voting on self-generated identities in order to grant them ''votes'' which can eventually be used for new verifications.

Most of the research concerning how to prevent sybil attacks (identity forgery on peer to peer networks) revolves around requiring entities to perform a task that a sybil attacker would not be able to perform. Attention mining requires validators to observe certain aspects of ''Proof of Identity'' videos that only a person can recognize. In order to have a mechanism that prevents bots, the system can generate modified videos to induce attackers to error. These distortions can be created through cropping certain sections out of a video, mixing it with others or distorting voices to work as a video version of a CAPTCHA test aimed to securely distinguish between real human validators and botnets.

====3.2.5 Little Brothers.====
<blockquote>
  Who watches the watchmen?
</blockquote>
[https://en.wikipedia.org/wiki/Watchmen '''''Watchmen'''''], graphic novel (1987).

Self-sovereign identities can be valued on two key aspects that help define their right to participate in the network:

* '''Reputation''': A social indicator that a given identity is to be trusted.
* '''Singularity''': An individual indicator that certifies an identity is uniquely tied to a single person.

Anyone on the network can participate to verify new self-sovereigns in order to secure a global democracy against the threat of a ''Big Brother''. This task is effectively performed whenever an <code>Organization</code> decides to approve a new <code>Member</code>. By harnessing distributed attention across multiple <code>Organizations</code> instead of an all-observing central power, validators are in effect an army of [http://groups.csail.mit.edu/mac/classes/6.805/articles/crypto/cypherpunks/little-brother.txt little brothers] who can collaboratively score a self-sovereign identity in the network. ''Little brothers'' can outperform centralized identity providers in terms of accuracy as they are constantly incentivized to maintain legitimacy within the network in order to keep ''votes'' as a valuable asset: the success of the network on detecting ''replicants'' (duplicated identities) determines the scarcity of the ''vote'' token. The legitimacy of any democracy is based on the maintenance of a proper voter registry.

=====3.2.5.1 Reputation.=====

The interest on effectively validating a ''Proof of Identity'' is among <code>Organizations</code> that must deal with applicant identities willing to become <code>Members</code> able to use their ''votes'' for the decisions related to the entity. Those who within an <code>Organizantion</code> have the rights to approve new memberships end up contributing with the reputation an <code>Organization</code> has to the applicant identity if approved.

The allocation of reputation from an <code>Organization</code> to an approved <code>Member</code> that applied with its POI is done by simply signing the approved POI to certify that an identity is a valid <code>Member</code>. The memberships connected to an identity in the network can be interpreted by future validators on other <code>Organizations</code> in any desired way. <code>Organizations</code> in the network can be as small as a family or as large as a multi-national corporation, but ultimately they are <code>domains</code> in a network that can resemble <code>Tags</code> describing the attributes of an identity. Some <code>Organizations</code> may exist for very specific verifications, e.g. an <code>Organization</code> under a ''legal.age'' domain that only verifies if a POI belongs to someone older than 18 years making any approved <code>Member</code> of such entity carry a valid ''legal.age'' signature on its POI.

The reputation of an <code>Organization</code> can be measured on how often they end up allowing [https://en.wikipedia.org/wiki/Replicant ''replicants''] as <code>Members</code>. In other words: <code>Organizations</code> that fail on the ''Singularity score'' used to value the individuality of participants in the network, end up being less trustworthy than those able to effectively include sovereign individuals.

=====3.2.5.2 Replicants.=====

While governments need to verify the family tree of a potential new citizen and traditional corporations need to rely on [https://en.wikipedia.org/wiki/Know_your_customer ''Know Your Customer''] practices (KYC) to draw a line between their clients and the rest of the world; a global democracy has no such concern for establishing a difference between ''us and them''. The goal of Democracy Earth Foundation is to scale the right to use ''votes'' to every single human: we are all ''us'' (or ''them''). Hence, the overall challenge for a successful decentralized ''Proof of Identity'' dynamic is to simply focus on using the available attention in the network to check for ''replicants'' that are requesting a share of ''votes''.

''Replicants'' are identities that get ''voted'' as duplicates, illegitimately claiming more ''votes'' than they deserve. Fake POIs are likely to happen using modern techniques of 3D rendering aiming to trick the human eye (e.g. beating the [https://en.wikipedia.org/wiki/Uncanny_valley uncanny valley] of perception), but it is a safe assumption to consider that [http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Taigman_DeepFace_Closing_the_2014_CVPR_paper.pdf humans are able to recognize faces with 98% of accuracy] while [http://www.washington.edu/news/2016/06/23/how-well-do-facial-recognition-algorithms-cope-with-a-million-strangers/ the capacity of algorithmical systems decrease when scaled]. Considering that the frontier being drawn is between humans and artificial intelligences is that we use the term ''replicant'' which was coined for the 1982 film ''Blade Runner'' referring to androids capable of simulating being real people.

=====3.2.5.3 Singularity Score.=====

To certify an identity is valid, verifiers are exposed to two simultaneous POI videos that can be chosen at random from all the indexed and hashed videos found on the blockchain. A face-matching algorithm that seeks similarities among facial expressions can be used to optimize the test. Validators must use ''votes'' to agree whether these POI videos belong to a same person or not, being the ongoing result of this decision a ''Singularity score'' for the identity.

The validation process is the same as in every Sovereign voting dynamic: Validators can approve by casting a ''vote'' that includes a <code>Ballot</code> with a <code>true</code> checked <code>Option</code> on it. Otherwise they must cast a ''vote'' in rejection with a <code>false</code> checked <code>Option</code>. All POI related decisions are <code>Strategical</code>: without a closing date where allocated ''votes'' impact in real time. At any time a validator can override the ''vote'' value if it has found evidence that modifies previous judgement. Also ''votes'' validating a POI can be removed if the identity already has input from sufficient validators which makes allocation of additional ''votes'' redundant. As with any Sovereign decision, the end result of a POI related vote will end up on either a <code>true</code> or <code>false</code> value. Anyone who ends up being voted as a ''replicant'' will see his or her granted ''votes'' useless.

The <code>Criteria</code> used for the ''Singularity score'' is also subject for voting by every validated POI participating in the network. Democracies are always a work in progress, perpetually self-correcting with a feedback loop that defines how the observers get observed. The threshold that establishes the sovereign right to ''vote'' must constantly adapt to the exponential growth of computing capacity that can risk subverting the network. By being backed with a decentralized identity index using an incorruptible blockchain that gets maintained with distributed attention (i.e. an open face book), the ''vote'' token becomes a trusted device for a digital democracy to emerge anywhere. Allocating attention to secure the network not only brings consciousness to a system otherwise blind to artificial Intelligence, but also allows participants to own their identities without being coerced by a centralized power that could monetize from it without consent. Conscious attention must always be put in the service of strengthening a global democracy because it is only in the realm of human consciousness that we can define what it means to be human.

===3.3 Universal Basic Income.===
<blockquote>
  Now is the time to make real the promise of democracy.
</blockquote>
'''Martin Luther King Jr.''', Minister and activist (1929-1968).

The ability to develop a reliable self-sovereign identity validation process not only guarantees the legitimate value for ''votes'' to express social choice but also establishes the bedrock for the infrastructure required to make a ''Universal Basic Income'' (UBI) mechanism that can reach everyone on Earth. The symbiotic relationship of UBI and democracy has been well substantiated. According to research presented at Basic Income Earth Network (Munich September 2012), the implementation of basic income [http://basicincome.org/bien/pdf/munich2012/Choi.pdf can greatly contribute to realizing the principles of democracy as well as the establishment of its substantial foundation]. Therefore in order to consolidate the political and financial logic able to establish a borderless democracy, once a ''Proof of Identity'' is validated by peers the distribution mechanism triggered for ''votes'' will be based on time as a UBI.

Time is a valuable and limited asset, therefore tradable. One cannot buy, rent or hire more time: it has an inelastic supply no matter how high the demand. [https://books.google.com/books?id=sjlVAAAAcAAJ&pg=PA5&lpg=PA5&dq=what+is+money+man%27s+birthright+time&source=bl&ots=uxfZPDT94J&sig=gWf_LpHeEA-g6ukveZ1-mQI3FE4&hl=es&sa=X&ved=0ahUKEwjgyuHR2ejVAhUK7iYKHUX0AzgQ6AEILjAB#v=onepage&q=what%20is%20money%20man's%20birthright%20time&f=false Time is the only standard of value by which to test all the labour, either manual or mental, done by men and women]. And by tokenizing time and using it as the basis for allocating ''votes'', it liquidates a possession that every member of a global democracy possesses on equal terms. Liquidity is a requirement for any democracy that aims to avoid coercion: voices must be able to be heard in order to count and by granting ''votes'' as a UBI we are tapping on delivering a human right that can effectively empower individuals that will have to face the coming challenges of automation. ''Votes'' granted throughout time as a right avoids the [https://en.wikipedia.org/wiki/Tragedy_of_the_commons ''tragedy of the commons''] while it sets the foundations for a governance model that goes beyond debt and Nation-States.

A self-sovereign then, is able to obtain ''votes'' in three different ways:

* '''Delegation''': Any <code>Member</code> within an <code>Organization</code> operating as a liquid democracy can get delegated ''votes''.
* '''Grant''': <code>Organizations</code> may grant ''votes'' to new participants on its own terms. Participants can create or fund <code>Organizations</code> using their own ''votes''.
* '''Drip''': Once a ''Proof of Identity'' becomes valid, ''votes'' begin to drip on the user's wallet throughout time.

====3.3.1 Dripping.====

The rate at which 1 ''vote'' gets dripped to a verified identity is syncronized with the Bitcoin blockchain. By using Bitcoin's synchronization mechanism as a clock, an incorruptible consensus sets the rythm for the whole network. Bitcoin chains a new block to the blockchain every 10 minutes, which means,

  1 hour = 6 blocks

Assuming that earnable time across the globe is based on 8 hour work days,

  8 hours per day x 5 days per week x 52 weeks per year = 2,080 hours per year

Or in block time,

  2,080 hours = 12,480 blocks

And considering that established consensus on [https://medium.com/economicsecproj/how-to-reform-welfare-and-taxes-to-provide-every-american-citizen-with-a-basic-income-bc67d3f4c2b8 an ideal basic income rate averages around 10% of an individual's earnings] we can define that,

  10% earnings Annual Basic Income = 208 hours per year = 1,248 blocks

Which means that of the ~52,560 blocks that register a full year of activity on Bitcoin's blockchain, a total of 1,248 blocks should be accounted for rewarding a UBI per year. To sync ''vote'' dripping with Bitcoin as a UBI mechanism based on 10% earnings for every working hour, 1 full unit of a ''vote'' token should then drip every ~42 hours (or ~252 blocks). For the purpose of guaranteeing a feasible divisibility of the ''vote'' token so it can be dripped every few seconds (while it also becomes easier for human and machine interpretation), we set the dripping rate at,

  1 vote = 250 blocks

So every valid POI gets granted a total of:

  210 votes per year

[[File:/images/proof-of-identity-dripping.png|Dripping mechanism for mined votes.]]

Therefore by taking into account the following variables:

* T = Present block height (i.e. current Time).
* r = A constant for ''vote'' allocation rate, set at 1 vote every 250 blocks in time.
* Pᵢ = The ''Proof of Identity'' block containing its corresponding hash for a given identity (i).
* Sᵢ = ''Singularity score'' expressed as a <code>true</code> or <code>false</code> state for a given identity (i).
* Vᵢ = Total quantity of ''votes'' for a given identity (i).

Then the ''votes'' a self-sovereign identity is allowed to use in the system can be calculated on any node running a smart contract with the formula:

[[File:/images/ubi-vote-formula.png|Vᵢ = ((T - Pᵢ) / r) * Sᵢ]]

As long as the ''Proof of Identity'' has been validated by the community and a smart contract is synced with an active blockchain node, then the value of Vᵢ will either be a number that defines the total amount of ''votes'' a self-sovereign has as a right to use on a hosted wallet or, if the POI is rejected (i.e. Sᵢ = <code>false</code>), then the participant's available votes becomes zero.

====3.3.2 Equality====

The described dripping dynamic ends up benefitting early-adopters as it is often the case with financial-oriented cryptocurrencies. Bitcoin for instance is often described as ''cryptographically induced scarcity'' as it is an instrument able to measure wealth in terms of economical resources due to the fixed scarcity of its token. But with the ''vote'' token we are building a network of a different nature that aims to be complementary to financial cryptocurrencies by having governance as a goal. By issuing ''votes'' as a right that can be granted to anyone as long as his or her singular identity is proven, the ''vote'' operates as political clout. So in essence, our approach is about ''cryptographically induced equality'': such is the basis for any real democracy. For this reason we introduce another variable to its ''Universal Basic Income'' dynamic,

* E = Amount of ''votes'' allocated to the ''Genesis Identity'' at present block height (T).

We refer to the ''Genesis Identity'' as the very first ''Proof of Identity'' that gets approved by the network. With this information the next validated identity won't begin in disadvantage: it will have a wallet with the same amount of ''votes'' than the first participant in the network currently has. Since this rule applies to every participant it will guarantee ''Equality'' in terms of participation letting everyone have the same amount of Sovereign ''votes'' than everyone else, extending the UBI formula as follows:

[[File:/images/ubi-equality-formula.png|Vᵢ = (E + ((T - Pᵢ) / r)) * Sᵢ]]

With the ''Equality'' variable, if a second participant Bob got validated 1500 blocks after a first one Alice, he won't begin with 0 ''votes'' but rather get an initial amount matching Alice's current balance at that moment (i.e. at a rate of 1 ''vote'' per 250 blocks, it is a total of 6 ''votes''). Bob will continue to get ''votes'' dripped on equal terms with Alice block after block after that. If a third participant Charlie generates a valid ''Proof of Identity'' 1000 blocks later, he will begin with the equivalent amount of ''votes'' that Alice and Bob each currently have by then as well (i.e. a total of 10 ''votes'' each). With this inflation process that rewards every new participant (diluting all pre-existing ones), everyone is guaranteed an ''equal'' share in the overall participating rights of the network. As long as ''replicants'' get successfully banned, the ''vote'' network is a genuinely democratic global commons.

[[File:/images/chart-votes-coins-time.png|Vote emission and inflation rate.]]

Even though the inflation rate might initially seem too aggressive, the total supply of ''votes'' is still fixed to a maximum cap based on the quantity of participants in the network. As more participants engage, the overall inflation will tend to limit 0% since new ''votes'' have a reduced influence in the economy as a whole. When compared to uncapped ''likes'' and ''retweets'' in other social applications, it must be noted that from the subjectivity of each individual the allocation of ''votes'' is still a decision based on a limited resource that implies opportunity costs, forcing a more rational behaviour rather than impulsive liking (i.e. trolling).

====3.3.3 Nakamoto Coefficient====

Significant efforts on quantifying decentralization are being made, including Balaji Srinivasan's work on establishing a [https://news.21.co/quantifying-decentralization-e39db233c28e ''Nakamoto Coefficient''] defined as:

<blockquote>
  The minimum number of entities in a given subsystem required to get to 51% of the total capacity.
</blockquote>

The importance of measuring decentralization relies on finding a metric able to certify the ability of a network to be censorship resistant, being this a fundamental property for self-sovereign currencies such as Bitcoin. But ultimately the question of who is in control of the entities running a networked system must be addressed as well. By establishing a reference network that guarantees an egalitarian distribution of its token based on a ''Proof of Identity'' mechanism designed to prevent ''replicants'', this brings in a new perspective that can help increase the resolution of the Nakamoto Coefficient by means of discernible equal access.

By guaranteeing an equal starting point for every participant regardless of the time they decide to join the network, the ''vote'' network operates as a genuine meritocracy. The proposed ''Equality'' variable is simply a rule for establishing a starting point and by no means a permanent imposition: at any time, any self-sovereign is allowed to either delegate ''votes'' to someone else or use them to start an <code>Organization</code> in the network. In this way, the ''vote'' token can work as a device fit to foster a wave of entrepreneurship even among today's disenfranchised individuals left out by the legacy financial and political systems. But as this happens on the individual level, the overall statistics of the network itself works as a reference framework in which to effectively measure decentralization down to each human across the globe and identify opportunities where its needed as it grows.

The value of the network does not reside on the simulated scarcity but on its ability to register uncoerced decisions among self-sovereigns on the basis of equality. Initially the ''vote'' token might be able to compete with pollsters and any other rudimentary simulations that aim to predict elections, but eventually it can become a sovereign system on its own right as citizenship migrates online. ''Votes'' operate as a signal able to register events recorded on an incorruptible blockchain that stores political history that cannot be erased or modified in any way. Future generations get exposed to their past without intermediaries.

===3.4 Value===

We take three approaches to define the value of the ''vote'' token:

* '''Status-Quo''': Social media offers a clear reference on how ''likes'' get valued online.
* '''Work & Time''': A ''Universal Basic Income'' perspective offers useful insights on how labour time is being valued.
* '''Nation-Sates''': Traditional elections offer useful insights on how votes are valued today.

With those references, we then discuss the divisibility of the ''vote'' token and its implementation to govern a Democracy Support Fund.

====3.4.1 Status-Quo====

A comparative benchmark for the value of the ''vote'' token can be found on the Facebook network currently valuing 2 billion users with a market capitalization of ~$500 billion averaging an estimate of '''$250 per user'''. Democracy Earth Foundation regards Facebook's ''like'' function analogous to using ''votes'' in an open network. It is hard to estimate the quantity of ''likes'' made on this platform since it's private information and raw estimates project ''likes'' happening in the amount of trillions on a daily basis.

Marketers that operate the Facebook advertising machine price ''likes'' in a range that can go from '''$0.10 to as high as $25''' based on the reputation and popularity of the account being used to capture user attention. In this sense, we believe this price reference is relevant for end-users in order to empower them with a token that can be competitive with leading social media platforms. But it must be noted that unlike ''likes'', ''votes'' directly empower holders with the right to participate in any financial benefit that can be connected to their use without intermediation. With ''votes'', profiting from user data will no longer be the exclusive domain of the Facebook middleman but instead will be enabled by a native token generation mechanism that is based on the principles established by the [http://www.un.org/en/universal-declaration-human-rights/ Universal Declaration of Human Rights]:

<blockquote>
  Everyone has the right to freedom of opinion and expression; this right includes freedom to hold opinions without interference and to seek, receive and impart information and ideas through any media and regardless of frontiers. Everyone has the right to freedom of peaceful assembly and association. Everyone has the right to take part in the government of his country, directly or through freely chosen representatives.
</blockquote>

With the creation of Sovereign as an interface for blockchain-based democracies operating with ''vote'' tokens, Democracy Earth Foundation's aim is to deliver a ''Linux moment'' to Facebook: analogous to the rise of open source operating systems in the early 1990's, Linux became an alternative to the monopolizing force of Microsoft's Windows that dominated the market of personal computers and internet servers. A free and open Internet must pursue the creation of a social network where no single entity can excercise algorithmic control of the shared ideas in exchange for the private information of its users. And while Facebook mines user attention for profit, the Democracy Earth network will use the same resource to strengthen the trust of the ''vote'' token with its ''Proof of Identity'' process. As we acknowledge the growing political influence social media already has in the world, the urgency of laying out an open social network that is uncensorable, sovereign and free becomes pressing.

====3.4.2 Work & Time====

Coming from a ''Universal Basic Income'' perspective, a useful reference that values time and labour is the proposed [https://en.wikipedia.org/wiki/Minimum_wage_in_the_United_States minimum wage in the US] based on federal, state and local laws across the country. As of July 2016 it has been set at '''$7.25 per hour'''.

[[File:/images/minimum-wage-us.png|Minimum wage in the US.]]

For the ''vote'' token to effectively become a useful network able to index UBI on a global scale, an expectation regarding its pricing dynamic must be set at 1 ''vote'' unit as equivalent to 1 hour of work. Hence this anchors the initial price of the token at:

  1 vote = $ 7.25

As long as the network successfully bans ''replicants'' and rewards validated self-sovereign identities indexed on the Bitcoin blockchain, then any UBI initiative can trust the present data to allocate resources without the risk of abuse.

====3.4.3 Nation-States====

From a Nation-State perspective, a useful reference can be found in the cost for implementing national elections. The 2016 Presidential Race in the United States had a total cost as high as [https://www.opensecrets.org/overview/cost.php $ 2,386,733,696]. Even though it had the lowest voter turnout in 20 years, an estimated total of [https://en.wikipedia.org/wiki/Voter_turnout_in_the_United_States_presidential_elections ~138,847,000 voters] participated. Hence, a simple calculation can price the vote token issued by the US government for this electoral process at '''$ 17.18 per vote'''. On the other end of the spectrum, developing nations like Argentina offer a similar reference: their 2017 legislative election had an estimated cost of [http://www.lanacion.com.ar/2034493-las-paso-costaran-2800-millones-pero-casi-no-definiran-candidatos $ 164,705,882] with a total of [http://www.elintransigente.com/politica/2017/8/13/cuantos-argentinos-votaron-paso-449552.html ~24,500,000 voters], setting the price at '''$ 6.70 per vote'''. It is within that range of value that Nation-States invest resources to guarantee voting rights to all its citizens.

[[File:/images/cost-of-us-elections.png|Cost of US Elections.]]

According to Facebook's seed investor Peter Thiel, a rule of thumb for technological innovation is that in order to beat a precedent paradigm, an innovation must outperform the task of the previous way of doing things [http://zerotoonebook.com/ by at least a factor of 10] in terms of cost and utility. For example: the digital word processor became successful because it does what a typewriter did in a way that can be considered at least ten times better and ten times cheaper. The same applies to fax in contrast to the postal service; and e-mail in contrast to fax. Hence the transition from traditional voting to a new standard of blockchain based voting should work on the same basis.

A simple comparison shows the strict limitations electoral votes have in comparison with the ''vote'' token proposed on this paper:

* '''Expensive Security''': Nation-State's ''Proof of Identity'' demands several resources to identify citizens during many stages of their life. Birth certificates, passports, driver's license, national ID cards, social security, wedding certificates, death certificates are all aimed at keeping the public record of citizens up to date. This is the leading function of the State and it can lead to persecutory behaviour.
* '''Limited Utility''': Once a citizen casts a vote during an election, it cannot be modified until 4 to 6 years later when the elected positions get renovated. Only those among the elected positions (i.e. senators and congressmen) get the right to spend more votes than the rest of the citizens.
* '''Reduced Bandwidth''': Citizens get to choose from a handful of options only once every 2 or 4 years. If we consider each option as a bit on the system then traditional elections can be regarded as ''8 bit democracies'', such is the current bandwidth for participation under most governments.

In order to maintain the reference price set at the minimum wage in the US while being able to be at least ~10X more efficient than any traditional election, ''vote'' utility must be extended by making the token divisible.

====3.4.4 Divisibility====

The waiting period of 250 blocks for every new dripped ''vote'' limits the perceived gratification delivered by the system to every ~42 hours. This constraint is set in order to tie the economic logic of the ''vote'' token to its capacity of indexing all the successful ''Proof of Identities'' to a ''Universal Basic Income'' dripping dynamic. But the ability to begin interacting with the system itself shouldn't require a long waiting period: by introducing decimal positions, the network can offer instant gratification by adapting the dripping dynamic down to a minimum fraction of human attention.

Considering that,

  1 vote = 250 blocks = 2,500 minutes = 150,000 seconds

To keep the shortest possible decimal extension while adapting the dripping rate to the minimum span of human attention, the ''vote'' network should perform a revolution every 15 seconds:

  15 seconds = 0.0001 votes

In the same way the minimum fraction of a Bitcoin is branded as 1 satoshi (i.e. 100,000,000 satoshis = 1 bitcoin), we consider it is suitable to brand the minimum fraction of a ''vote'' as a ''revolution'' since this concept helps to express the speed at which the network grants political rights,

  1 vote = 10,000 revolutions

Which can also be expressed as,

  1 revolution = 0.0001 votes

By allowing 4 decimal positions in the token, a ''revolution'' gets dripped to a valid ''Proof of Identity'' in the network every 15 seconds. ''Revolutions'' bring almost instant access to political rights while keeping the same utility capacity as ''votes'' with a cost that is comparatively 10,000X more efficient than Nation-State elections:

  1 revolution = 0.0001 votes = $ 0.000725

For the identification of the token in third party applications, we suggest the ''VOTE'' and ''VOT'' tickers.

===3.5 End Game.===

<blockquote>
  “What happened to the governments?” I inquired. 
  “It is said that they gradually fell into disuse. Elections were called, wars were declared, taxes were levied, fortunes were confiscated, arrests were ordered, and attempts were made at imposing censorship — but no one on the planet paid any attention. The press stopped publishing pieces by those it called its ‘contributors,’ and also publishing their obituaries. Politicians had to find honest work; some became comedians, some witch doctors — some excelled at those occupations…”
</blockquote>
'''Jorge Luis Borges''', ''Utopia of a Tired Man''. Writer (1899–1986).

To those who argue about electronic voting online scoring their arguments with Facebook ''likes'': [https://en.wikipedia.org/wiki/The_medium_is_the_message ''the medium is the message'']. The need to establish trusted relations in digital environments is mandatory as human cooperation scales to the whole globe. But the generational opportunity to collaboratively build this possibility must be able to learn from the great lessons of History. The origins of computing goes back to [https://en.wikipedia.org/wiki/History_of_IBM#1880s.E2.80.931924:_The_origin_of_IBM the first tabulating machine built by IBM for the 1890 US census] and the tallying of national elections after that. The very first proto-computers built by Alan Turing where made as a war effort able to beat nazi encryption ultimately demonstrating how intelligence can beat violence. The transition from analog to digital communications began with the [https://wheatoncollege.edu/provost/2016/03/21/claude-shannon-and-the-magna-carta-of-the-information-age/ Magna Carta of the Information Age] published by Claude Shannon in 1948 laying out the foundations for digital code and vast networks for the transmission of intelligence, a vision made real by Sir Tim Berners-Lee's creation of the ''world wide web'' protocols. When Satoshi Nakamoto published the Bitcoin paper he inaugurated the era that is giving rise to the transition from analog to digital ''institutions''. An inevitable leap from maturing our shared understanding of the properties of information security. Blockchains are giving our world a new canvas in which to lay foundations that shall govern us all to the point of being worthy of not needing governance anymore. After all [https://en.wikiquote.org/wiki/Alfred_North_Whitehead civilization advances by extending the number of important operations which we can perform without thinking about them]. Digital technology has proven to possess a greater capacity in the reach and quality of its messaging abilities and as new generations grow connected under a global commons, information architectures will regulate our political and financial relations without the physical restrictions of the past. The undeniable success of the Bitcoin experiment consistently beating even the most radical forecasts throughout a decade speaks greatly about the unleashed potential humanity has found. The status-quo will always speak from a skeptical position since halting progress can only come from a position of comfort. But just as the Internet didn't wait for the adaptation of age-old empires, blockchains won't care for political promises: a technologically advanced society can enter agreements of mutual cooperation without falling back to the means of coercion and violence. Such is the remarkable consequence of disintermediation of trust without boundaries, a reality that won't emerge in a single isolated part of a country or region of the globe, but will be distributed across the entire planet. The ''next Silicon Valley'' is not in a far away land or on any land at all, but a new frontier of the internet itself rising as the one true open, free and sovereign network of peers.

----

==4. À Propos.==

La Fondation Democracy Earth ne peut exister que grâce à ses collaborateurs, donateurs et partenaires en tous genres. Nous sommes une organisation californienne à but non lucratif 501©3, présente à New York, Paris, Buenos Aires et San Fransisco.

===4.1 Équipe & Collaborateurs.===

Santiago Siri, Virgile Deville, Paula Berman, Eduardo Medina, Herb Stephens, Sandra Miller, Dwight Wilson, Mair Williams, Louis Margot-Duclot, Felipe Alvarez, Cyprien Grau, Peter Schurman, Andrew James Benson, Gonzalo Stupenengo, Lucas Isasmendi.

===4.2 Conseil.===

Pia Mancini, Alexis Ohanian, Matias Mosse, Ariel Kogan, Ernesto Dal Bó, Kate Courteau, Giorgio Jackson, Julio Coco, Dan Swislow.

===4.3 Donateurs.===

Ricardo Gorodisch, Matias Mosse, Krishna Bahrat, Wenceslao Casares, Dwight Wilson, Marcos Galperin, Alejandro Estrada, Chris & Hedy Eyre, Kevin	Barenblat, Clinton Yara, Tom Preston-Werner, Lloyd Nimetz, Eduardo Medina, Jim D'Amico, Erik Walter, Vivek Krishnappa, Kevin Berk, Micah Rosenbloom, Karén Gyulbudaghyan, Satoshi Nakamoto, Paul Wehrley, Josh Jacobson, Allison Sparks, Ahin Thomas, Ron Hirson, Ken Ettinger, Sharon Goldstein, Shreenath Regunathan, Matt Price, Josh Zaretsky, Heejae Lim, Allison Koblick.

===4.4 Remerciements.===

Quelques-uns des esprits ayant inspiré des idées exprimées dans ce document.

Nick Szabo, Nubis Bruno (Bitex.la), Cesar Hidalgo (MIT), Balajis Srinivasan (21.co & Anderssen Horowitz), Andrea Antonopoulos (Bitcoin Evangelist), Peter Asaro (Stanford), Naval Ravikant (Angel List), Guillermo Rauch (Zeit), Andrew DeSantis (E8), Greg Slepak (Open Turtles), Demian Brener (Zeppelin), Manuel Araoz (Zeppelin), Ralph Merkle, Satoshi Nakamoto (Bitcoin), Vitalik Buterin (Ethereum), Vlad Zamfir (Ethereum), Joseph Lubin (Consensys), Ryan Shea (Blockstack), Muneeb Ali (Blockstack), Luis Cuende (Aragon), Vinny Lingham (Civic), Luke Duncan, David Graeber (London School of Economics), Peter Schurman (One Global Democracy), Jim D'Amico, Federico Ast, Harry Halpin, Guy Standing (University of London), Sebastian Serrano.

===4.5 Partenaires.===

Ces organisations nous ont apporté leur support par le biais de financements, partenariats, et reconnaissance de nos travaux de recherche et de développement.

[[File:/images/grants-awards-support-organizations.png|Financements, médailles et support de la part de ces organisations.]]
