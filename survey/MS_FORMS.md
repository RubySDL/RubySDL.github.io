# Microsoft Forms 问卷转换

按下列清单在 [forms.office.com](https://forms.office.com) 逐题创建。

---

## 0. Consentement RGPD — Choice 单选 · 必填 · 启用 Branching

```
Consentement éclairé — Recherche sur les comportements de voyage

Responsable : [姓名] · Contact : [邮箱]
Finalité : Recherche qualitative sur les habitudes de voyage.
Base légale : Article 6(1)(a) RGPD.
Stockage : Microsoft 365 — EU Data Boundary.
Conservation : 12 mois.
Droits : accès, rectification, effacement, retrait via [邮箱].
```

- Oui, j'accepte
- Non, je refuse → **Branching: End of the form**

---

## Section 1 — Informations sur l'entretien

1. Nom de l'enquêteur — Text · 必填
2. Code participant — Text · 必填
3. Date de l'entretien — Date · 必填
4. Lieu / Modalité — Text
5. Notes complémentaires — Long answer

---

## Section 2 — Informations personnelles

### Q1. Âge — Choice 单选 · 必填
- A. 18–24 ans
- B. 25–34 ans
- C. 35–44 ans
- D. 45–54 ans
- E. 55 ans et plus

### Q2. Études — Choice 单选 · 必填
- A. Inférieur Bac
- B. Bac
- C. Bac+2
- D. Bac+3
- E. Bac+5 et plus
- F. Doctorat

### Q3. Situation familiale — Choice 单选 · 必填
- A. Célibataire
- B. Concubinage
- C. Pacsé(e)
- D. Marié(e)
- E. Divorcé(e) / Veuf(ve)

### Q4. Nombre d'enfants — Choice 单选 · 必填
- A. Aucun
- B. 1
- C. 2
- D. 3 et plus

### Q5. Revenu net mensuel du foyer — Choice 单选 · 必填
- A. Moins de 1 500 €
- B. 1 500 – 2 500 €
- C. 2 501 – 4 000 €
- D. 4 001 – 6 000 €
- E. Plus de 6 000 €
- F. Je préfère ne pas répondre

---

## Section 3 — Habitudes de voyage

### Q6. Fréquence annuelle — Choice 单选 · 必填
- A. Jamais
- B. 1 fois
- C. 2–3 fois
- D. 4–5 fois
- E. 6 fois et plus

### Q7. Destinations principales — Choice 多选 · 必填
- A. France
- B. Europe (hors France)
- C. Afrique du Nord / Méditerranée
- D. Amériques
- E. Asie
- F. Autre destination lointaine

### Q8. Budget annuel total — Choice 单选 · 必填
- A. Moins de 500 €
- B. 500 – 1 500 €
- C. 1 501 – 3 000 €
- D. 3 001 – 6 000 €
- E. Plus de 6 000 €

### Q9. Budget moyen par voyage — Choice 单选 · 必填
- A. Moins de 300 €
- B. 300 – 800 €
- C. 801 – 1 500 €
- D. 1 501 – 3 000 €
- E. Plus de 3 000 €

---

## Section 4 — Style de voyage

### Q10. Style(s) de voyage préféré(s) — **Ranking** · 必填
- A. Séjour balnéaire
- B. Camping / plein air
- C. Randonnée / nature
- D. Montagne / ski / sports extrêmes
- E. Culture, histoire & art
- F. Gastronomie & artisanat
- G. Fêtes, événements & traditions locales

---

## Section 5 — Brise-glace (2 min)

**S0Q1** — Long answer
Parlez-moi de votre dernier voyage — où, combien de jours, avec qui, comment, pourquoi cette destination, ce qui vous a attiré(e) ?

---

## Section 6 — Processus de planification (30 min)

> 全部 Long answer，追问写在 Description 字段

**S1Q1 — Motivation**
Pour quelle raison avez-vous décidé de partir ? (besoin interne ou stimulus externe)
- Qu'est-ce qui a déclenché cette décision ?
- Votre propre envie ou inspiré(e) par d'autres / du contenu ?

**S1Q2 — Sources d'information**
Par quels canaux ou plateformes obtenez-vous vos informations de voyage ?
- Pourquoi cette plateforme ? Type d'infos ? Évaluation ?
- Un blogueur (KOC/KOL) vous a-t-il influencé(e) ? Lequel et pourquoi ?
- Quel type d'info vous attire le plus : vidéo / photo+texte / promo / guide ?
- Quelles infos manquez-vous de sources fiables ?

**S1Q3 — Connaissance préalable**
Avant le départ, dans quelle mesure connaissiez-vous votre destination ?
- Trouvez-vous la recherche de voyage épuisante ?

**S1Q4 — Anticipation**
À combien de temps à l'avance planifiez-vous ? Quand réservez-vous ?
- Dans quels scénarios planifiez-vous et réservez-vous à l'avance ?

**S1Q5 — Outils de planification**
Quels outils utilisez-vous pour planifier votre itinéraire ?
- Qu'est-ce qui vous pousse à les utiliser ? Avantages et inconvénients ?

**S1Q6 — IA et planification**
Avez-vous déjà utilisé des outils IA pour planifier un itinéraire ?
- Oui — lequel ? Ressenti ? Dans quelle mesure adoptez-vous ses suggestions ?
- Non — pourquoi pas ?
- Quels problèmes aimeriez-vous qu'un outil IA résolve ? Paieriez-vous ? Combien ?

**S1Q7 — Réservation séparée**
Réservez-vous hébergement, transport et expériences séparément ?
- Que réservez-vous en premier ?
- Est-ce fastidieux ?

**S1Q8 — Forfaits / Packages**
Avez-vous déjà acheté un produit "forfait / package" ?
- Oui : pourquoi ? Quoi ? Prix ? Plateforme ? Comparaison ?
- Si plus cher mais acheté quand même, pourquoi ?
- Non : pourquoi pas ? Envisageable ? Prime acceptable ?

**S1Q9 — Frictions**
Y a-t-il quelque chose de particulièrement ennuyeux lors de la réservation ?
- Une plateforme tout-en-un résoudrait-elle vos points de friction ?

**S1Q10 — Paiement**
Quel mode de paiement utilisez-vous ? (CB / PayPal / Apple Pay / Virement / Chèque) Pourquoi ?
- Le paiement fractionné vous attire-t-il ?
- À quel montant en auriez-vous besoin ?
- Avez-vous abandonné une réservation à cause d'un mode de paiement non supporté ?

---

## Section 7 — Choix de transport (5 min)

**S2Q1**
Quel transport choisissez-vous pour voyager en France ?
- Pourquoi ce choix ?
- Combien de plateformes ? Comparaison ? Plateforme finale ?
- Plateforme la plus utilisée et pourquoi ?

**S2Q2**
Avez-vous une carte de réduction TGV ?
- Oui : détails, fréquence, lignes principales ?
- Les billets à 0 € influencent-ils votre choix de destination ?
- Après un billet 0 €, que réservez-vous d'autre ? Où ?
- Points de friction ?
- Utiliseriez-vous un outil compilant billets 0 € + produits associés ?
- Non : pourquoi pas ?

---

## Section 8 — Préférences d'hébergement (5 min)

**S3Q1**
Quel type d'hébergement choisissez-vous habituellement ? (hôtel / location / auberge / camping / autre)
- Pourquoi ce type ? Essayé d'autres ?
- Selon le contexte (famille / couple / solo) ?

**S3Q2**
Quels facteurs comptent le plus ? (prix / emplacement / équipements / avis / annulation)
- Si prix et emplacement s'opposent, lequel prime ?
- Les avis ont-ils déjà changé votre décision ?

**S3Q3**
Avez-vous abandonné une réservation à cause d'une politique d'annulation trop stricte ?
- Quelle plateforme / quel hôtel ?
- Quelle politique est acceptable ?

---

## Section 9 — Expériences & Activités (5 min)

**S4Q1**
Réservez-vous des activités locales à l'avance ?
- Combien de temps à l'avance ?
- Si vous décidez sur place, comment ?

**S4Q2**
Avez-vous utilisé des plateformes d'activités ? (Viator / Get Your Guide / Airbnb Expériences)
- Oui — quoi, quand, prix, fréquence, satisfaction ?
- Non — pourquoi ? Méthode alternative ?

---

## Section 10 — Guides & Partage (5 min)

**S5Q1**
Êtes-vous prêt(e) à partager vos guides de voyage en ligne ?
- Pourquoi ? Sur quelles plateformes ?
- Combien de temps y consacreriez-vous ?
- Une plateforme qui vous récompenserait quand votre guide est adopté ?

---

## Section 11 — Démo produit & Conclusion (8 min)

**S6Q1** — Long answer
Envisageriez-vous d'acheter ce produit ? Pourquoi ?

**S6Q2** — Long answer
Avez-vous des opinions ou commentaires sur ce produit ?

**S6Q3** — Long answer
Y a-t-il quelque chose d'important que nous n'avons pas abordé ?

---

## Settings 检查

- ☑ Anyone can respond
- ☑ 关闭 Record name
- ☑ 关闭 One response per person
- ☑ Customize thank you message: `Merci ! Vos données sont stockées dans l'UE conformément au RGPD.`
