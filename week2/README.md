# Leçon 5

### Speech sur l'invention

Alors la le prof se penche sur les mystères de l'inventivité humaine et c'est mystérieux. On ne comprend pas bien grâce à quelle mécanique les gens inventent, ni pourquoi certaines mettent pour certaines civilisations, c'est plus long que pour d'autres. Il y aurait semble-t-il une part de hasard dedans. *Necessity is the mother of invention*. Platon

### Le succès de la ville de New York et la responsabilité limité

La résponsabilité limitée. Jusqu'à une certaine époque tout les investisseurs d"une entreprise étaient responsable des éventuelles malversations de l'entreprise. Si l'entreprise faisait faillite, les investisseurs devaient éponger les dettes. A une certaine époque, l'état de New York invente la responsabilité limitée. Les investisseurs ne sont responsables qu'à la hauteur de leur investissement. Cette invention a permis à New York d'exploser économiquement et de devenir la plus grande ville des USA. 50 ans après tout les états américains avaient emboité le pas.

### Index debt

Un des problèmes majeurs lorsqu'on contracte une dette c'est l'inflation de la monnaie dans laquelle la dette est contractée. Pour remédier à ça les japonais ont inventé les rice bonds. La dette était contractée en volume de riz. Mais là aussi, la valeur du riz peut évoluer. C'est en 1786, lors de la revolutionary war que l'armée soucieuse du bien être de ses soldats invente l'inflation index debt. Néanmoins, l'idée ne séduit pas suffisamment, et il faut attendre 1997, pour voir arriver les indexed bonds. Visiblement la population n'était pas particulièrement intéressé jugeant à tort l'inflation de toute manière trop faible. Or 4% d'inflation par an, signifie la perte de la moitié d'un capital.


### Unidad de Fomento

Dans les années 60, le Chili voit son inflation exploser. +1000% en un an. Pour adresser ce problème, les autorités inventent une unité de mesure la UF constamment ajusté à l'inflation de la monnaie le Peso. Aujourd'hui, 1 UF = $ 26,000. L'inflation existe même pour les pays plus stables comme les USA, où le prix d'un verre de coca-cola a été multiplié par 22 en 100 ans.

### Risques dans l'immobilier

Il existe un risque dans l'immobilier qui n'est pas encore assuré. C'est le risque de la dévaluation de son bien immobilier. Par exemple, on emprunte 500,000 dollars pour l'achat d'un bien. Et ce bien perd 50,000 dollars en un an. On va donc payer 50,000 dollars en plus. Aucune sécurité n'existe contre ça. Le prof dit que pour adresser le problème, on pourrait *shorter* le marché de l'immobilier. Car ce risque serait corrélé négativement avec le risque de la dévaluation de son bien. Ca me parait pas super évident :
 * Si le marché baisse, ok tu gagneras de l'argent et ça compensera donc la dévaluation
 * Si le marché monte, tu perdras de l'argent mais elle sera compensé par la valorisation supérieur de ton bien
 * Si le marché est le même, alors tu ne perds ni ne gagnes


# Leçon 6

### Modélisation du marché, AR(1) et Random Walk

Quelle loi suit l'indice représentant le marché, (par exemple le S&P 500). Selon le professeur, cela devrait suivre un mix entre la Random Walk et le modèle AR(1) qui sont de tte manière très proches (selon certains cas particuliers)
 * **Random Walk** : X(t) = X(t-1) + epsilon
 * **AR (1)** selon le cours : X(t) = M + ro(X(t-1)-M) + epsilon
   * habituellement : -1 < ro < 1

### Hypothèse du marché efficient

Certains économistes ont avancé la thèse selon laquelle les prix des actions réflètent toute l'information disponible. Une des conséquences de cette thèse est l'impossibilité de *battre le marché* puisqu'il serait théoriquement impossible de prédire une hausse ou la baisse d'une action étant donné que le prix de l'action contient déjà toute l'information disponible. On ne pourrait donc anticiper quoi que ce soit puisque chacun se base sur tout ou une partie des informations qui existent. Il y aurait un lien éventuel entre le modèle de random walk et l'hypothèse d'efficience des marchés que je n'ai pas saisi. L'économiste Fama distingue trois types d'efficience : 
 * La forme faible : le prix des actions prend en compte les informations passées
 * La forme semi forte : le prix des actions prend en compte les informations publiques
 * La forme forte : le prix des actions prend en compte la totalité des informations (les entreprises ne peuvent tenir de secrets)

Le top 2 des ressources en ligne pour comprendre en détails l'hypothèse du marché efficient :
 * [video1](https://www.youtube.com/watch?v=eNxk5-EJFrY&ab_channel=CrashCourse)
 * [video2](https://www.youtube.com/watch?v=yco0sC7AJ2U&ab_channel=BenFelix)


### L'avis du prix nobel sur l'hypothèse

Le foufou pense que l'hypothèse est à moitié vraie. Selon lui, elle est vraie la plupart du temps mais parfois certaines anomalies surgissent. Le prof met ça sur le compte de la psychologie ou bien la finance comportementale. Il réfute la dénomination du concept pour lui préférer *market efficiency half truth*. Par exemple, investir sur des actions dont le **price earning ratio** est bas, donne en général de bons résultats. Informations sur le PER (noté parfois P/E):
 * **definition** : How much investors are willing to pay per unit of a company’s earnings
 * [wikipedia](https://fr.wikipedia.org/wiki/Price-earnings_ratio)
 * [v1](https://www.youtube.com/watch?v=21STUhQ-iP0&ab_channel=ThePlainBagel)
 * [v2](https://www.youtube.com/watch?v=PqnK0254J_0&ab_channel=DividendInvestor%21)
 * [v3](https://www.youtube.com/watch?v=YjuqNXvWhEw&ab_channel=SovereignFinancials)
 * [v4](https://www.youtube.com/watch?v=4KkTGx2bK_4&ab_channel=TDAmeritrade)


### Valeur théorique d'une action

En théorie (sous l'hypothèse des marchés efficients, hmmm je ne suis même pas sûr de ça) le prix d'une action est censé être égal au 
 * Present Discounted Value (PDV) of Expected Dividend
 * PDV = Earnings * coefficient
   * coefficient = discount rate(ou le interest rate, je ne sais pas si c'est synonyme) - growth rate of earnings. J'ai franchement rien compris à cetter partie. Apparemment, certaines action sont anormalement élevées par rapport à leur earnings. D'après le growth model, si une action est pricée haut relativement aux earnings de la boîte, c'est possiblement pour deux raisons : 1) peu de risque (voir le beta) ou 2) car les gens estiment que le growth rate est élevé


### En vrac, à creuser
 * **Dividende**
   * [youtube](https://www.youtube.com/watch?v=wTCJfPtFvNM&ab_channel=TDAmeritrade)
   * [wikipedia](https://fr.wikipedia.org/wiki/Dividende)
 * **Present Discounted Value**
   * [random youtuvbe](https://www.youtube.com/watch?v=xhiDTnTDEIY&ab_channel=jodiecongirl)
   * [khan 1](https://www.youtube.com/watch?v=ks33lMoxst0&ab_channel=KhanAcademy)
   * [khan 2](https://www.youtube.com/watch?v=4LSktB7Pk_c&ab_channel=KhanAcademy)
   * [khan 3](https://www.youtube.com/watch?v=3SgVUlEcOBU&ab_channel=KhanAcademy)
   * [khan 4]https://www.youtube.com/watch?v=6WCfVjUTTEY&ab_channel=KhanAcademy)
 * **Earnings**
   * [investopedia](https://www.investopedia.com/terms/e/earnings.asp#:~:text=Earnings%20refer%20to%20a%20company's,used%20in%20many%20common%20ratios.)