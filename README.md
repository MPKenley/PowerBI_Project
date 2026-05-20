# 📊 Dashboard MEAL Interactif

Ce projet utilise des données entièrement fictives à des
fins de démonstration. Il a été conçu pour illustrer la
 conception d'un système de suivi-évaluation (MEAL) sous
Power BI dans un contexte humanitaire haïtien.

## 📌 Presentation du projet

Ce projet est un dashboard MEAL (Monitoring, Évaluation, Redevabilité et Apprentissage) interactif développé sous Power
BI, conçu pour suivre la performance d'un programme fictif
d'assistance cash & alimentaire en Haïti.
Le dashboard couvre 2 000 ménages bénéficiaires répartis dans trois départements (Artibonite, Ouest, Sud) sur 3 cycles de distribution en 2025. Il intègre quatre sources de données, enregistrement des bénéficiaires, distribution de l'assistance,
suivi post-distribution (PDM) et plaintes/feedback, dans un
modèle de données unifié en étoile.

**Caractéristiques techniques clés** :

- 4 tables de données nettoyées et enrichies dans Power Query
- Modèle relationnel en étoile avec une table de dimension Calendrier.
- 19 mesures DAX couvrant les KPIs de couverture, distribution,
sécurité alimentaire et redevabilité
- 5 pages de rapport interactives avec slicers à filtrage
croisé et navigation entre pages
- Développé entièrement dans Power BI Desktop selon les
standards humanitaires (seuils FCS/CSI du PAM)

## 📊 Présentation Globale des Résultats

Le programme(fictif) a atteint les résultats suivants sur
 l'ensemble des 3 cycles de distribution :

| Indicateur | Résultat |

|---|---|
| Ménages bénéficiaires enregistrés | 2 000 |
| Personnes touchées (membres de ménages) | 10 078 |
| Montant total distribué | 539 640 USD |
| Montant moyen par bénéficiaire | 270 USD |
| Pourcentage de femmes bénéficiaires | 50,65 % |
| Score de vulnérabilité moyen | 50 / 100 |
| Nombre total de distributions | 5 411 |
| Répartition cash / alimentaire | 50 % / 50 % |
| FCS moyen (sécurité alimentaire) | 41 (catégorie Limite) |
| CSI moyen (stratégies de survie) | 17 (catégorie Modéré) |
| Pourcentage de bénéficiaires satisfaits | 41 % |
| Taux de résolution des plaintes | 69 % |
| Délai moyen de résolution | 16 jours |

**Lecture globale :** Le programme a atteint sa cible de couverture de 2 000 ménages. Cependant, plusieurs signaux d'alerte méritent notre attention, notamment le FCS moyen de 41 indique que de nombreux ménages restent en situation de sécurité alimentaire limite, le taux de satisfaction de 41 % est en dessous des standards acceptables et le délai moyen de résolution des plaintes de 16 jours dépasse le seuil recommandé
de 14 jours.

---

## 🏠 Vue d'ensemble

La page Vue d'ensemble offre une vision synthétique et immédiate de la performance globale du programme à destination
de toutes personnes voulant avoir une idee globale du projet
(coordinateurs, bailleurs, etc...)

**Ce qu'elle contient :**

- **4 cartes KPI**(en haut de page) présentant les indicateurs les plus critiques : nombre de ménages touchés, nombre total de
personnes couvertes, pourcentage de femmes bénéficiaires, montant total distribué.
- **Un graphique en barres** montrant la répartition des bénéficiaires par département (Artibonite : 648, Ouest : 643,
Sud : 709), permettant d'identifier les zones d'intervention
prioritaires.
- **Un graphique en barres** comparant le montant distribué par cycle (Cycle 1 : 178 520 USD, Cycle 2 : 179 770 USD, Cycle 3 : 181 350 USD), révélant une progression légère du budget alloué
entre les cycles.
- **Un slicer département** permettant de filtrer l'ensemble
des indicateurs par zone géographique en un seul clic.

**Apprentissage :** Le département Sud concentre le plus grand
 nombre de bénéficiaires (709) avec un budget légèrement plus
 élevé au Cycle 3, ce qui peut indiquer une expansion de la
 couverture dans cette zone.

 ![Vue d'ensemble](C:\Users\DELL\Documents\Repo_PowerBI)

## 📋 Redevabilité : Gestion des Plaintes

La page Redevabilité est dédiée au **suivi du Mécanisme de Retour d'Information (MRA)** du programme. Elle répond aux exigences de transparence et de redevabilité envers les bénéficiaires, les partenaires et les bailleurs.

**Ce qu'elle contient :**

- **4 cartes KPI** : nombre total de plaintes, nombre de
plaintes résolues, taux de résolution et délai moyen de
résolution (16 jours).
- **Un graphique en barres** présentant les plaintes par type:
Corruption (57),Retard (53), Exclusion (51), Comportement du
personnel (39). La corruption et les retards concentrent la
majorité des signalements.
- **Un graphique en anneau** illustrant la répartition entre
plaintes résolues (69 %) et plaintes encore ouvertes (31 %),
offrant une lecture immédiate de l'efficacité du mécanisme.
- **Un graphique en barres** comparant le délai moyen de résolution par canal de signalement : Relais communautaire (17,1 jours), Boîte à plainte (16,2 jours), Appel (15,8 jours). Le
canal Appel est légèrement plus efficace.
- **Un slicer par type de plainte** permettant d'isoler chaque
catégorie pour une analyse approfondie.

**Apprentissage :** Avec 63 plaintes encore ouvertes et un délai moyen de 16 jours dépassant le seuil standard de 14 jours, le mécanisme de redevabilité nécessite un renforcement, notamment sur le traitement des cas via relais communautaire,
canal le moins efficace en termes de délai.
![Redevabilite](C:\Users\DELL\Documents\Repo_PowerBI)

## 👥 Profil des Bénéficiaires

La page Profil des Bénéficiaires offre une **analyse
démographique et socio-économique** des ménages enregistrés
dans le programme. Elle est essentielle pour documenter le
ciblage et justifier l'allocation des ressources.

**Ce qu'elle contient :**

- **3 cartes KPI** : nombre de ménages touchés (2 000), nombre total de personnes touchées (10 078) et score de vulnérabilité
moyen (50%).
- **Un graphique en barres** montrant la répartition des bénéficiaires par tranche d'âge, les 30-44 ans constituent le groupe le plus important (673 personnes), tandis que les 0-4 ans sont les moins représentés (91). Cela indique que le programme cible principalement des ménages avec des adultes en
âge de travailler.
- **Un graphique en anneau** illustrant la répartition par
genre : 51 % d'hommes (1 013) et 49 % de femmes (987),
confirmant une parité quasi-totale dans le ciblage.
- **Un graphique en barres** présentant le score de vulnérabilité moyen par commune. Les scores varient de 48 à 51
sur 100, indiquant une vulnérabilité modérée à élevée
relativement homogène entre les zones.
- **Un graphique en barres** sur la catégorie de ménage : Grand
(899), Moyen (670), Petit (431), montrant que le programme
touche majoritairement des grands ménages de 6 personnes et plus.
- **Un slicer département** pour filtrer tous les visuels par zone géographique.

**Apprentissage :** La prédominance des grands ménages (45 % du total) combinée à un score de vulnérabilité moyen de 50 % suggère que le programme cible bien les familles nombreuses en situation de vulnérabilité modérée à élevée, profil cohérent
avec les critères d'un programme cash & food humanitaire.
![Profil](C:\Users\DELL\Documents\Repo_PowerBI)

## 🌍 Explication Non-Technique du MEAL

Le **MEAL** (Monitoring, Evaluation, Accountability and Learning) est le système de suivi-évaluation utilisé par les organisations humanitaires pour s'assurer que leurs programmes atteignent vraiment les personnes dans le besoin, de la façon
prevue.

Voici ce que chaque lettre signifie concrètement sur le terrain :

**M : Monitoring (Suivi)**
C'est le suivi continu des activités du programme. On pose des questions simples : est-ce que les distributions se passent comme prévu ? Est-ce que tous les bénéficiaires ont bien reçu
leur aide à chaque cycle ? Dans ce dashboard, le suivi est
assuré par les pages *Vue d'ensemble* et *Distributions*.

**E : Evaluation (Évaluation)**
C'est l'analyse approfondie des résultats du programme :Est-ce que l'aide a vraiment amélioré la situation des bénéficiaires ? Les indicateurs FCS et CSI de la page *PDM* permettent de répondre à cette question en mesurant la sécurité alimentaire
avant et après les distributions.

**A : Accountability (Redevabilité)**
C'est la responsabilité de l'organisation envers les bénéficiaires. Les bénéficiaires ont le droit de signaler un problème et d'obtenir une réponse. La page *Redevabilité* suit le mécanisme de gestion des plaintes, combien ont été reçues,
traitées et dans quel délai.

**L : Learning (Apprentissage)**
C'est la capacité de l'organisation à tirer des leçons de ses expériences pour améliorer ses futurs programmes. Les données de ce dashboard: satisfaction, délais, types de plaintes, FCS par département, alimentent cet apprentissage institutionnel.

Enfin,le MEAL garantit que l'aide humanitaire va aux bonnes personnes, au bon moment, de la bonne façon et que si quelque
chose ne va pas, on le sait et on le corrige.

## ⚠️ Limitations

Ce projet présente plusieurs limitations importantes à prendre
 en compte lors de l'interprétation des résultats :

**1. Données entièrement fictives**
Toutes les données utilisées dans ce dashboard ont été générées par intelligence artificielle. Elles ne représentent aucune organisation, aucun bénéficiaire réel, ni aucune intervention
 humanitaire existante en Haïti. Les résultats ne peuvent pas
 être utilisés à des fins d'analyse ou de prise de décision.

**2. Absence de données longitudinales**
Le dashboard couvre une seule période (2025) sans données de référence (baseline) ni de comparaison avant/après intervention. Il est donc impossible de mesurer l'impact réel
du programme sur la sécurité alimentaire des bénéficiaires.

**3. Table des plaintes sans dimension temporelle**
La table `fact_plaintes` ne contient pas de colonne date. Il est donc impossible de suivre l'évolution des plaintes dans le
temps ni de les relier à la table Calendrier. Dans un projet
réel, la date d'enregistrement de chaque plainte est
indispensable.

**4. FCS et CSI sans données de référence**
Les scores FCS (41) et CSI (17) sont interprétés selon les seuils standards du PAM, mais sans données collectées avant les
 distributions, il est impossible de savoir si le programme a
amélioré, maintenu ou détérioré la situation alimentaire des
ménages.

**5. Un seul cycle PDM**
Les visites post-distribution couvrent l'ensemble des 2 000 bénéficiaires mais sur un seul passage. Dans la réalité, le PDM
est répété à chaque cycle pour mesurer l'évolution dans le
temps.

## 📝 Résumé de l'Analyse

Ce dashboard MEAL fictif met en lumière plusieurs enseignements
clés qui, dans un programme réel, guideraient les décisions
opérationnelles :

**✅ Points forts du programme**
Le programme a atteint sa cible de couverture avec 2 000
ménages enregistrés représentant plus de 10 000 personnes.
La répartition quasi-égale entre aide cash (50 %) et aide
alimentaire (50 %) reflète une approche mixte adaptée aux
besoins diversifiés des ménages. La parité de genre est bien
respectée avec 49 % de femmes bénéficiaires.

**⚠️ Points d'alerte**
Le FCS moyen de 41 place la majorité des ménages visités en
catégorie *Limite*, juste au-dessus du seuil d'insécurité
alimentaire. Avec 18 % des ménages en catégorie *Pauvre*
(FCS < 28), une part significative des bénéficiaires reste en
situation critique malgré l'aide reçue.

Le taux de satisfaction de 41 % est préoccupant, moins d'un bénéficiaire sur deux se déclare satisfait du programme. Ce chiffre, croisé avec les 57 plaintes pour corruption et les 53 pour retard, suggère des dysfonctionnements dans la chaîne de
distribution.

**🔧 Recommandations**
Sur la base de cette analyse, trois recommandations prioritaires se dégagent :
1- renforcer le mécanisme de redevabilité pour réduire le délai de résolution des plaintes sous les 14 jours et viser un taux
de résolution plus elevé
2- investiguer les causes de la faible satisfaction, particulièrement dans les zones où la corruption est la plainte
dominante
3- envisager un ciblage complémentaire des ménages dont le FCS
reste inférieur à 28 après les distributions pour un soutien
additionnel.

## 📁 Structure du Projet

📦 meal-dashboard-haiti-2025
 ┣ 📂 data
 ┃ ┣ 📄 beneficiaries.csv
 ┃ ┣ 📄 assistance_distribution.csv
 ┃ ┣ 📄 post_distribution_monitoring.csv
 ┃ ┗ 📄 complaints_feedback.csv
 ┣ 📄 MEAL_Dashboard_Haiti_2025.pbix
 ┗ 📄 README.md

## 👤 Auteur

Projet réalisé Par **Pierre Kenley MERVIL** dans le cadre d'un
apprentissage autonome en Data Analysis appliqué au secteur humanitaire.

**Compétences démontrées :** Power BI, Power Query, DAX,
 Modélisation de données, Analyse MEAL, Contexte humanitaire
 haïtien
