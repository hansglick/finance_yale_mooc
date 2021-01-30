
# Leçon 1

La finance n'est pas seulement faire de l'argent mais faire en sorte que les gens créatifs puissent créer. Le marché a besoin d'être régulé car la tendande des hommes c'est de le manipuler. Bon soit disant, les gros business men finissent philantropistes ... OK, on s'en fout. D'après lui, les Financial markets sont essentiels au succès économique d'un pays

# Leçon 2

### VaR et Stress Tests

 * VaR : Value at Risk. Défini en 1987, mesure le risque d'un portfolio
   * 1% 1 year VaR of 10 millions signifie que le portfolio a une probabilité de 1% de perdre 10 millions
 * VAR : Variance. Mesure la variabilité d'un portfolio
 * Stress Test (test d'efforts) : ensemble de mesures conduites pour évaluer la robustesse d'une entreprise face à une hypothétique crise financière. Alors apparemment, les insitutions financières américaines sont soumis à des stress tests tout les ans par une instance appelée la OFHEO. Le stress test repose sur trois scénarios différents (par exemple : le dollar qui baisse, plus de liquidité, etc.). Le stress test a une valeur évidente pour le patron d'une entreprise mais celui-ci n'a aucun intérêt à rendre ce genre de résultat publique si celui-ci lui est défavorable. Raison en partie pour laquelle certaines doutent de la pertinence des résultats des stress tests opérés jusqu'ici car ils sont globalement toujours positifs. Les raisons seraient que :
   * Les responsables des tests seraient incompétents
   * Les entreprises financières feraient une sorte de rétention d'informations aux instances responsables, de sorte qu'il serait difficile d'évaluer correctement les choses

### S&P 500

Le [S&P 500](https://fr.wikipedia.org/wiki/S%26P_500) est un indice boursier de 500 grandes entreprises américaines. Il est *détenu* par [Standars And Poor's](https://fr.wikipedia.org/wiki/Standard_%26_Poor%27s). C'est une société qui publie des analyses financières, i.e. qui donne des bons ou des mauvais points aux grandes entreprises. Le S&P 500 subit beaucoup de fluctuations ce qui fait dire au profs que les actions des boîtes dépendent les uns des autres, car s'ils étaient indépendants, le cours du S&P 500 serait moins volatile. (Comprend pas pourquoi??)

### Beta

Si je comprends bien le S&P 500 est une mesure de la santé du marché (global). En traçant les monthly return de Apple versus S&P 500, on peut s'apercevoir de deux choses : 
 1. Il existe une corrélation. Quand le marché monte, Apple monte.
 2. Cette corrélation est à l'avantage de Apple. Quand le marché monte, Apple monte encore plus (1.45>1)
 3. Le **beta** d'une action est la valeur de cette corrélation

<img src="img/overreact.PNG" width="612">

### Le risque d'une action

Le risque d'une action = **risque du marché** + **risque idiosyncratic**
 * risque du marché = Beta² * Variance(market return)
 * risque idiosyncratic = Variance(résidus)


### Régression linéaire dans la finance

 * Y = mx + b (trouvé m et b tel que Yi-(mxi+b)² soit minimum)
 * Y : Stock Monthly Return
 * m : Beta
 * x : Market Return
 * b : Alpha 


### Distribution de Cauchy

En finance, les objets qu'on manipule ont tendance à suivre des lois de Cauchy plutot que des lois normales. Quelques rappels :

 * Theoreme central limite : la moyenne de x variables aléatoires et indépendantes suit une loi normale. Ceci n'est pas vrai si les lois de distributions possèdent des fat tails.
 * Loi de cauchy : pareil que la loi normale mais possède des fat tails. Les événements extraordinaires sont en quelque sorte beaucoup plus probables

<img src="img/cauchyvsnormal.PNG" width="339">


### Risque et covariance

#### **Idée sous jacente**

**C'est LE point le plus important du cours jusqu'ici**. Admettons qu'on souhaite miser sur deux actions. Si la covariance des deux titres est nulle alors ça signifie que les probabilités de *réussite* des deux titres sont indépendantes l'une de l'autre. Si la covariance est positive, cela signifie que leur probabiliité de réussite sont corrélés positivement, autrement dit si l'une réussit, l'autre également mais si l'une se crash alors l'autre aussi. Lors de la construction d'un portfolio, on veut s'assurer que la covariance n'est PAS positive car c'est trop risqué. **LE RISQUE EST DETERMINE PAR LA COVARIANCE**. Dans le cas où ma covariance est négative, cela peut également nous intéressé car cela signifie que l'un des deux titres explosera quand l'autre se crashera, ce qui peut être à notre avantage s'il explose pour de bons. Les grands investisseurs sont donc ceux qui arrivent à estimer cette covariance de manière correcte ce qui fait appel à une forme d'intuition ou d'intelligence

#### **Rappel mathématique**


<img src="img/covarianceformula.JPG" width="485">
<img src="img/covarianceillus.GIF" width="485">


#### **Beta et covariance**

Le Beta vu plus haut, est la covariance entre le titre et le marché normalisée entre 0 et 1. Le Beta d'une entreprise vaut en moyenne 1 car la variance du titre sera en moyenne égale à celle du marché, la covariance d'une variable avec elle même étant égale à la variance, le Beta moyen vaut 1



# Questions et vocabulaire

 * **Mortgage** : apparemment ce serait une sorte de prêt de la banque si tu leur accord le droit de saisir la propriété que tu tentes d'acheter avec le prêt
 * **Second mortgage** : ce serait un autre prêt auquel on aurait le droit sous certaines conditions
 * **Monthly Stock Return** : ce serait la croissance mensuel d'un investissement. Apparemment, ce serait une mesure qui souffrirait d'une grande variabilité. Très difficile d'estimer la santé financière de deux companies en comparant uniquement leurs courbes de monthly stock return

# Anglais

 * to be thrilled to be : être excité/avoir l'honneur
 * chalk talk : lit. discous à la craie, en gros un cours avec la possibilité de faire des illustrations
 * self indulgent : qui ne fait que jouir

