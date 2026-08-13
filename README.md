# 👥 HR Analytics Dashboard – Analyse de l'attrition des employés

## 📌 Contexte du projet

Ce projet propose un **dashboard interactif RH** permettant d'analyser les données du personnel d'une entreprise, avec un focus particulier sur **l'attrition (le turnover)**. L'objectif est d'identifier les profils, départements et facteurs les plus associés au départ des employés, afin de fournir des pistes concrètes d'amélioration de la rétention.

Ce projet s'inscrit dans une démarche de **People Analytics**, appliquant les principes de la data visualization à la gestion des ressources humaines.

![Aperçu du dashboard](images/hr_dashboard_preview.png)

---

## 📊 Indicateurs clés (KPIs)

| Indicateur | Valeur |
|---|---|
| **Total Employees** | 1 417 |
| **Active Employees** | 1 186 |
| **Attrition Count** | 231 |
| **Attrition Rate** | 16,3 % |
| **Âge moyen** | 36,9 ans |
| **Expérience moyenne** | 7,04 ans |

---

## 🔍 Insights clés

### 1. Un taux d'attrition global à surveiller de près
- Avec **16,3 % d'attrition**, soit près d'**1 employé sur 6** ayant quitté l'entreprise, ce taux se situe à un niveau qui mérite une attention particulière, notamment lorsqu'on le rapproche des standards du secteur (généralement entre 10 % et 15 % pour une attrition "saine").

### 2. Une attrition très concentrée sur certains postes
- Les postes de **Laboratory Technician (59 départs)** et **Sales Executive (56 départs)** représentent à eux seuls près de **50 % de l'ensemble des départs** (115 sur 231), alors qu'ils ne concentrent pas nécessairement la majorité des effectifs.
- Ces deux fonctions constituent clairement les **points chauds prioritaires** à traiter pour réduire le turnover global.

### 3. La satisfaction au travail n'explique pas tout
- Contrairement à l'intuition, le niveau de satisfaction **3** (sur une échelle de 1 à 4) concentre le plus grand nombre de départs (**72 sur 231**), davantage que le niveau **1** correspondant à la satisfaction la plus faible (**64 départs**).
- Cela suggère que **la satisfaction déclarée seule ne suffit pas à prédire l'attrition** : d'autres facteurs (rémunération, perspectives d'évolution, relation managériale, charge de travail) entrent probablement en jeu.

### 4. Les jeunes salariés en début de carrière quittent le plus vite
- La tendance d'attrition par expérience montre un **pic très marqué chez les employés ayant 0 à 2 ans d'ancienneté**, avant de décroître progressivement.
- Ce constat pointe vers un **problème d'intégration ou d'onboarding**, plus que vers un désengagement progressif des employés expérimentés.

### 5. Une attrition plus élevée chez les hommes
- Les hommes représentent **63 % des départs (146)**, contre **37 % pour les femmes (85)**.
- Ce chiffre mérite d'être **croisé avec la répartition hommes/femmes globale des effectifs** afin de déterminer si cet écart traduit un taux d'attrition réellement plus élevé chez les hommes, ou simplement leur poids plus important dans l'effectif total.

### 6. Des écarts d'attrition importants selon les tranches salariales
- La tranche **6-10 LPA** concentre le plus grand nombre de départs (**73**), suivie par la tranche **0-3 LPA** (61 départs). Les tranches les plus élevées (10+ LPA) affichent en comparaison une attrition plus faible (48 départs).
- Cela suggère que **le milieu de la grille salariale est une zone de vulnérabilité**, potentiellement liée à un sentiment de plafonnement de carrière ou de rémunération jugée insuffisante par rapport au marché.

---

## ✅ Recommandations

### 1. Renforcer l'accompagnement des nouveaux employés (0-2 ans d'ancienneté)
Le pic d'attrition en tout début de carrière appelle à **revoir le parcours d'onboarding et de suivi des 6-24 premiers mois** (mentorat, points réguliers avec le manager, clarté sur les perspectives d'évolution) pour sécuriser cette période critique.

### 2. Cibler en priorité les postes de Laboratory Technician et Sales Executive
Ces deux fonctions concentrant près de la moitié des départs, il est recommandé de mener des **entretiens de départ approfondis (exit interviews)** et une **enquête qualitative ciblée** sur ces rôles afin d'identifier précisément les causes (charge de travail, rémunération, management, conditions de travail spécifiques).

### 3. Revoir la politique salariale sur la tranche 6-10 LPA
Cette tranche concentrant le plus de départs, une **analyse comparative avec le marché (benchmark salarial)** permettrait de vérifier si un ajustement de la grille de rémunération pourrait limiter l'attrition à ce niveau.

### 4. Ne pas se fier uniquement aux enquêtes de satisfaction pour anticiper les départs
Puisque le niveau de satisfaction 3 concentre le plus de départs, il est recommandé de **croiser les données de satisfaction avec d'autres indicateurs** (performance, charge de travail, historique de promotions, relation managériale) pour construire un modèle prédictif d'attrition plus fiable.

### 5. Approfondir l'analyse de l'écart hommes/femmes dans l'attrition
Avant de tirer des conclusions, il est recommandé de **comparer le taux d'attrition par genre à la répartition hommes/femmes des effectifs actifs**, afin de déterminer s'il existe un véritable déséquilibre à corriger ou si l'écart observé est simplement proportionnel à la composition de l'effectif.

### 6. Prioriser les actions de rétention par taux d'attrition plutôt que par volume brut
Au-delà du nombre brut de départs par département, il serait pertinent de **calculer le taux d'attrition rapporté à l'effectif de chaque département** afin d'identifier les équipes les plus fragiles proportionnellement, et non uniquement celles avec le plus grand nombre absolu de départs.

---

## 🛠️ Outils utilisés
- **Power BI** : conception du dashboard et des visualisations
- **Power Query** : nettoyage et préparation des données
- **DAX** : calcul des indicateurs (KPIs, mesures)

---

📫 N'hésitez pas à me contacter pour toute question ou collaboration.
