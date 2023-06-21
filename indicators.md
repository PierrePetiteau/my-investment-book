# Indicators

## Realized Profit/Loss Ratio

Le RPP (Ratio Perte/Profit) est un indicateur permettant d’observer si les bitcoins se déplaçant sur le réseau sont en perte ou en profit.

```javascript
T1 et T2 correspondent respectivement au dernier achat et à la dernière ventes

T1 = 100$
T2 = 200$

RPP = T2 / T1
RPP = 200 / 100
RPP = 2

```

## NUPL - Net Unrealized Profit/Loss

Le RPPp (Ratio Perte/Profit potentiel) est un indicateur qui répond à la question :
si tous les bitcoins étaient vendus aujourd’hui, combien les investisseurs pourraient-ils gagner ou perdre?
Le RPPp calcule la différence entre toutes les pertes et tous les profits potentiels pour évaluer si le marché, de manière globale, est plutôt dans le vert ou dans le rouge. Pour information, cette différence est ensuite divisée par la capitalisation totale du marché pour standardiser la valeur à travers le temps.

## LTHM - Long-Term Holder Movement

D’abord, définissons ce que nous entendons par “Long term Hodler”. Il s’agit des adresses sur le réseau bitcoin n’ayant pas bougé depuis au minmum 155 jours. Les investisseurs détenant ces adresses sont statistiquement moins susceptibles de vendre leurs bitcoins. Ces ‘Hodlers’ ont souvent des convictions relativement fortes à propos de Bitcoin, et ne sont pas là pour trader. Ils ont plutôt une vision moyen-long terme de leur portefeuille.
L’indicateur “Mouvement des ‘Long Term Holder’” permet de voir si ces adresses sont en train d’augmenter ou de diminuer leurs avoirs en Bitcoin.

## Mouvement sur les plateformes d’échange

Avec cet indicateur, nous pouvons observer le mouvement des bitcoins rentrant ou sortant des plateformes d’échange (comme par exemple Coinbase, Kraken, Binance, etc.).
Selon moi, cet indicateur est l’un des plus importants et des plus pertinents de l’analyse “on-chain”. Historiquement, les périodes où les exchanges se sont fortement vidés de leurs bitcoins ont précédé de forte hausse du cours (ce que l’on appelle parfois un “supply shock”). Au contraire, l’arrivée massive de jetons sur les exchanges appelle à la prudence...

## Liquidité de l’offre

 Les adresses possédant des bitcoins peuvent être divisées en 3 catégories en fonction de leur ratio entrée/ sortie (que l’on appelle le ratio L) pour “liquidity”.

 si je n’ai fait qu’accumuler des bitcoins sur ma clé Ledger pendant ces 3 dernières années, sans jamais les vendre, j’aurais un L = 0.
 Au contraire si j’ai régulièrement revendu mes bitcoins, disons 50%, j’aurais un L = 0,5.

A partir de là, nous pouvons distinguer 3 catégories d’adresses:

- ‘Non Liquide’ si L < 0.25
- ‘Liquide’ si 0.25 < L < 0.75
- ‘Très liquide’ L > 0.75
