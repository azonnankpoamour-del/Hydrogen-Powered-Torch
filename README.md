# 🔥 Conception et réalisation d’un chalumeau à hydrogène alimenté par énergie solaire

![Prototype du chalumeau](prototype-chalumeau-hydrogene.jfif)

## 📌 Présentation du projet

Ce projet porte sur la **conception, le dimensionnement, la réalisation et l’expérimentation d’un chalumeau oxyhydrogène** utilisant un mélange gazeux HHO produit par **électrolyse de l’eau**.

Le système a été développé comme une alternative aux chalumeaux conventionnels utilisant des combustibles fossiles tels que l’acétylène.

L’objectif était de réaliser un prototype capable de produire son combustible à la demande et pouvant être utilisé pour des opérations de **chauffage, brasage, soudage et découpe de tôles fines**, tout en étant alimenté par une **source d’énergie solaire**.

Ce projet a été réalisé dans le cadre de mon projet de fin de formation en **Licence professionnelle – Équipements Motorisés** à l’ENSGEP / UNSTIM.

---

## 🎯 Objectifs

- Concevoir un système de chalumeau fonctionnant avec de l’hydrogène produit par électrolyse.
- Dimensionner le débit de gaz nécessaire au fonctionnement du chalumeau.
- Concevoir et intégrer un **générateur HHO de type Drycell**.
- Dimensionner l’alimentation électrique du système.
- Intégrer une alimentation photovoltaïque permettant d’améliorer l’autonomie énergétique du prototype.
- Concevoir mécaniquement l’ensemble du dispositif sous **SolidWorks**.
- Comparer différentes solutions électrolytiques.
- Réaliser et assembler le prototype.
- Effectuer des essais expérimentaux de production de gaz et de fonctionnement du chalumeau.
- Intégrer les dispositifs nécessaires à la sécurité du système.

---

## ⚙️ Principe de fonctionnement

Le fonctionnement du dispositif repose sur l’**électrolyse de l’eau**.

Sous l’action d’un courant électrique et en présence d’un électrolyte, l’eau est dissociée afin de produire du dihydrogène et du dioxygène :

**2 H₂O (l) → 2 H₂ (g) + O₂ (g)**

Le mélange gazeux produit par le générateur HHO est ensuite acheminé vers le chalumeau.

Le système comporte notamment un réservoir de solution électrolytique, une pompe de circulation, un générateur HHO-Drycell, un séparateur eau-gaz, les éléments de sécurité et le bec du chalumeau.

L’énergie nécessaire au fonctionnement du système est fournie par une batterie alimentée par un panneau photovoltaïque.

---

## 🧩 Architecture du système

Les principaux composants utilisés sont :

| Composant | Fonction |
|---|---|
| Générateur HHO – Drycell | Production du mélange gazeux HHO par électrolyse |
| Réservoir | Stockage de la solution électrolytique |
| Pompe de circulation | Circulation de la solution dans le système |
| Séparateur eau-gaz | Séparation du gaz produit et de la solution |
| Cartouche filtrante | Filtration de l’eau |
| Batterie LiFePO₄ 24 V – 10 Ah | Stockage de l’énergie électrique |
| Panneau photovoltaïque 355–375 W | Production d’énergie électrique |
| Régulateur solaire 40 A | Gestion de la charge de la batterie |
| Bec de chalumeau | Contrôle et orientation de la flamme |
| Tuyauterie et raccords | Circulation du gaz et de la solution |
| Dispositif anti-retour de flamme | Protection du circuit HHO |

---

## ☀️ Alimentation solaire

![Schéma alimentation solaire](schema-alimentation-solaire.jfif)

Le prototype a été conçu pour fonctionner avec une alimentation photovoltaïque.

### Caractéristiques principales

- **Panneau photovoltaïque : 355–375 W**
- **Batterie : LiFePO₄ 24 V – 10 Ah**
- **Énergie stockée : 240 Wh**
- **Régulateur de charge : 40 A**
- **Consommation théorique du Drycell : ≈ 120 W**
- **Autonomie théorique sur batterie : ≈ 2 h**

Cette architecture permet de réduire la dépendance à une alimentation électrique conventionnelle et apporte une autonomie énergétique au dispositif.

---

## 📐 Dimensionnement du débit d’hydrogène

Le dimensionnement a été réalisé pour permettre le travail sur une **tôle d’environ 0,8 mm d’épaisseur**.

En prenant comme référence un chalumeau oxyacétylénique :

- débit d’acétylène retenu : **250 mL/min**
- débit équivalent théorique d’hydrogène : **≈ 625 mL/min**
- plage de fonctionnement estimée : **600 à 750 mL/min de H₂**

Le dimensionnement théorique a donc retenu un débit cible d’environ :

**Q(H₂) = 625 mL/min**

---

## ⚡ Dimensionnement électrique

La production d’hydrogène a été dimensionnée à partir de la loi de Faraday.

Pour un débit cible de **625 mL/min**, le dimensionnement théorique conduit à un courant d’environ :

**I ≈ 60 A**

Avec une tension de cellule de l’ordre de **2 V**, la puissance théorique absorbée par le générateur est d’environ :

**P ≈ 120 W**

---

## 🧪 Étude expérimentale des électrolytes

Plusieurs solutions électrolytiques ont été étudiées expérimentalement afin d’analyser leur influence sur la production de gaz.

### Solutions testées

- Eau + bicarbonate de sodium (**NaHCO₃**)
- Eau de mer
- Eau + hydroxyde de potassium (**KOH**)

Le débit de gaz a été évalué expérimentalement par la **méthode du déplacement d’eau**.

### Résultats

| Solution | Débit expérimental |
|---|---:|
| NaHCO₃ | ≈ 1,0 L/min |
| Eau de mer | ≈ 0,7 L/min |
| KOH | ≈ 1,4 à 1,6 L/min |

Les essais ont montré que le **KOH présentait les meilleures performances** parmi les solutions étudiées.

L'étude de l'influence de la concentration a également montré un optimum expérimental autour de **6 %**, avec un débit pouvant atteindre environ **1,6 L/min avec le KOH**.

---

## 🖥️ Conception mécanique – CAO

### Générateur HHO

![CAO générateur HHO](conception-cao-generateur-hydrogene.jfif)

Le générateur HHO de type **Drycell** constitue l’un des éléments centraux du dispositif.

La conception mécanique a permis de définir l’organisation et l’intégration des différents composants nécessaires à la production et à la circulation du gaz.

### Assemblage du système

![CAO système complet](conception-cao-systeme-complet.jfif)

L’ensemble du système a été modélisé sous **SolidWorks** afin d’étudier l’intégration des différents composants avant la réalisation du prototype.

Cette étape a notamment permis de travailler sur :

- la conception des pièces ;
- l’assemblage mécanique ;
- le positionnement des composants ;
- l’encombrement du système ;
- l’intégration du Drycell ;
- le passage des tuyauteries et connexions.

---

## 🔧 Réalisation du prototype

![Prototype du chalumeau](prototype-chalumeau-hydrogene.jfif)

Après la phase de conception et de dimensionnement, les différents composants ont été assemblés afin d'obtenir un prototype fonctionnel.

Le système comprend la chaîne :

**Énergie solaire → Batterie → Générateur HHO → Production HHO → Séparation / sécurité → Chalumeau → Flamme**

Le gaz est ainsi produit au fur et à mesure des besoins du système.

---

## 🔥 Essais et résultats

Les essais réalisés ont permis de valider le principe de fonctionnement du prototype.

### Principaux résultats

- Production effective de gaz HHO par électrolyse.
- Obtention d’une flamme stable au niveau du chalumeau.
- Débit expérimental supérieur au besoin théorique de **600–750 mL/min** avec certaines solutions électrolytiques.
- Meilleure performance obtenue avec le **KOH**.
- Débit maximal expérimental de l’ordre de **1,4 à 1,6 L/min** avec le KOH.
- Utilisation prévue pour le chauffage, le brasage, le soudage et le travail sur des tôles fines jusqu’à environ **0,8 mm**.
- Fonctionnement avec une alimentation photovoltaïque.

La littérature et le dimensionnement du projet situent la température d’une flamme oxyhydrogène à des valeurs pouvant approcher **2800 à 3300 °C** selon les conditions de fonctionnement.

> **Remarque :** la température exacte de la flamme du prototype n’a pas été mesurée expérimentalement, faute d’instrumentation adaptée. Elle ne doit donc pas être interprétée comme une température directement mesurée sur le prototype.

---

## 🛡️ Sécurité

La manipulation de l’hydrogène nécessite une attention particulière.

Plusieurs dispositions ont été prises en compte dans le projet :

- production du gaz en fonction des besoins ;
- limitation du stockage de gaz ;
- utilisation d’un dispositif anti-retour de flamme ;
- contrôle de l’étanchéité des raccords et tuyauteries ;
- vérification régulière de la cellule électrolytique ;
- éloignement des sources d’étincelles pendant les opérations de maintenance ;
- utilisation obligatoire des équipements de protection individuelle.

**EPI recommandés :**
- lunettes de protection ;
- gants de protection ;
- vêtements et équipements adaptés aux opérations de soudage.

---

## 💰 Étude économique

Le coût total estimé pour la fabrication du prototype est de :

### **637 000 XOF**

Ce montant comprend notamment :

- le générateur HHO ;
- les accessoires de circulation d’eau et de gaz ;
- le câblage ;
- le panneau photovoltaïque ;
- le régulateur solaire ;
- la batterie LiFePO₄ ;
- le bec du chalumeau ;
- le transport et les accessoires nécessaires au montage.

L’utilisation de l’énergie solaire permet par ailleurs de réduire le coût électrique associé au fonctionnement du système.

---

## 🚀 Perspectives d’amélioration

Plusieurs améliorations ont été identifiées :

- optimisation du rendement du générateur HHO ;
- optimisation de la concentration de l’électrolyte ;
- amélioration de la conception des électrodes ;
- instrumentation du système pour mesurer précisément température, pression et débit ;
- intégration de capteurs de température et de gaz ;
- automatisation de la régulation avec un microcontrôleur ou un automate ;
- mise en place d’une protection contre la surchauffe et les surtensions ;
- poursuite des recherches sur l’utilisation de l’eau de mer dans un contexte maritime ;
- amélioration de la compacité et de la portabilité du dispositif.

---

## 🧠 Compétences mobilisées

Ce projet m’a permis de mettre en œuvre des compétences multidisciplinaires en :

**Conception mécanique**
- CAO sous SolidWorks
- conception de pièces et assemblages
- intégration mécanique
- prototypage

**Dimensionnement**
- calcul énergétique
- dimensionnement électrique
- dimensionnement d’un générateur HHO
- dimensionnement d’une alimentation photovoltaïque

**Expérimentation**
- électrolyse de l’eau
- étude comparative d’électrolytes
- mesure de débit par déplacement d’eau
- analyse et interprétation de résultats expérimentaux

**Énergie**
- hydrogène
- énergie solaire photovoltaïque
- batterie LiFePO₄
- gestion énergétique

**Gestion de projet**
- étude du besoin
- conception
- dimensionnement
- réalisation
- essais
- analyse économique
- amélioration continue

---

## 📄 Documentation

La documentation détaillée du projet comprend :

- **Rapport de fin de formation – Réalisation d’un chalumeau utilisant l’hydrogène comme combustible**
- **Manuel d’utilisation du chalumeau à hydrogène vert**

Ces documents présentent le dimensionnement, la conception, les résultats expérimentaux, les procédures d’utilisation ainsi que les recommandations de sécurité.

---

## 👤 Auteur

**Amour Tamègnon AZONNANKPO**

Projet de fin de formation – Licence professionnelle  
**Génie Mécanique-Équipements Motorisés**

École Nationale Supérieure de Génie Énergétique et Procédés (**ENSGEP**)  
Université Nationale des Sciences, Technologies, Ingénierie et Mathématiques (**UNSTIM**)

Année académique : **2024–2025**

---

## ⚠️ Avertissement

Ce dépôt présente un projet académique et expérimental.

L’hydrogène et les mélanges hydrogène/oxygène présentent des risques importants d’incendie et d’explosion. Les informations contenues dans ce dépôt sont fournies à des fins de présentation technique et pédagogique et ne constituent pas des instructions permettant de reproduire le dispositif sans équipements, procédures de sécurité et encadrement appropriés.
