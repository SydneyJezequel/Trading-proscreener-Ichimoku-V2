Le code contenu dans ce repository est le code de 2 proscreeners basés sur l'indicateur Ichimoku.


Le premier proscreener (Ichimoku-bullish-screener) identifie les actifs haussiers.
Il détecte les actifs qui répondent aux conditions suivantes :
* Le nuage future est haussier (SpanA > SpanB).
* Le prix de l'actif est supérieur au nuage.
* La Kijun est supérieure au nuage.
* Le prix de l'actif est supérieur ou égal à la Kijun et à la Tenkan.
* Le prix de l'actif croise à la hausse la Kijun où se situe à x% au-dessus de la Kijun.
* La Chikou Span est libérée (supérieure aux clôtures 24/25 et 26 périodes en arrière, SpanA, SpanB, Kijun).


Le second proscreener (Ichimoku-bearish-screener) identifie les actifs baissiers.
Il détecte les actifs qui répondent aux conditions suivantes :
* Le nuage future est baissier (SpanA < SpanB).
* Le prix de l'actif est inférieur au nuage.
* La Kijun est inférieure au nuage.
* Le prix de l'actif est inférieur ou égal à la Kijun et à la Tenkan.
* Le prix de l'actif croise à la baisse la Kijun où se situe à x% sous la Kijun.
* La Chikou Span est libérée (inférieure aux clôtures 24/25 et 26 périodes en arrière, SpanA, SpanB, Kijun).


Le langage utilisé est ProRealcode, un langage propre à la plateforme de Trading Prorealtime. Ci-dessous des exemples d'actions détectées par le screener.
