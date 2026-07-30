# 📈 Simulateur de Retraite et Épargne – Régime Général (Salarié du privé, début de carrière)

[![V01 Mode Expert](https://img.shields.io/badge/V01-Mode%20Expert-blue.svg)](https://github.com/J34NMY/simulateur-retraite-et-epargne-regime-general/blob/main/simulateur_retraite_capitalisation_expert.html)
[![Statut : en ligne](https://img.shields.io/badge/statut-en%20ligne-brightgreen.svg)](https://simulateur-citoyen.fr/simulateur-retraite-et-epargne-regime-general/)
[![Licence CC BY-NC-SA 4.0](https://img.shields.io/badge/licence-CC%20BY--NC--SA%204.0-lightgrey.svg)](LICENSE.md)

Outil pédagogique gratuit pour les **salariés du régime général en début de carrière** : projette votre future pension (base CNAV + complémentaire Agirc-Arrco) et compare vos options d'épargne (CTO, PEA, PER) pour la compléter.

> ⚠️ **Outil éducatif non officiel.** Pour votre estimation retraite officielle, consultez [info-retraite.fr](https://www.info-retraite.fr).

> 💡 **Pourquoi ce nom ?** La retraite par répartition n'offre aucun choix individuel — vous cotisez, l'État redistribue. L'épargne par capitalisation (CTO, PEA, PER), elle, vous laisse le choix. Ce simulateur montre les deux, sans jamais laisser penser que la retraite française serait "par capitalisation" — elle reste, et reste obligatoirement, par répartition.

---

## 📂 Périmètre

Ce simulateur couvre les **salariés du régime général** en début de carrière. Il ne couvre **pas** :
- Les **fonctionnaires** → voir [simulateur-retraite-progressive](https://github.com/J34NMY/simulateur-retraite-progressive)
- Les **travailleurs indépendants** (ne cotisent pas à l'Agirc-Arrco, ont leur propre régime RCI/CIPAV)
- Les **professions libérales** (CNAVPL)

---

## ✨ Fonctionnalités

- **Projection de carrière** : 30 à 40 ans, salaire constant ou par paliers, en euros constants (pouvoir d'achat d'aujourd'hui)
- **Pension à la retraite** : base CNAV + complémentaire Agirc-Arrco, même moteur validé que le simulateur régime général classique
- **Comparateur d'épargne** : 100% investi sur chaque enveloppe séparément (CTO, PEA, PER) pour comparer directement le net après fiscalité 2026 (flat tax 31,4%, PEA 18,6%, PER mixte)
- **ETF réels vérifiés** (ISIN, frais, éligibilité PEA) pour 4 indices : MSCI World, S&P 500, MSCI Emerging Markets, MSCI ACWI
- **Réinvestissement de l'économie d'impôt du PER** simulé sur un PEA séparé
- **Mode Expert** : tableau année par année, ETF personnalisé, export PDF (séparé par onglet), comparaison multi-scénarios
- **Épargne de précaution** : rappel systématique avant toute simulation d'épargne
- 100% local : aucune donnée transmise, fonctionne hors ligne une fois la page chargée

---

## ⚡ Utilisation

1. Rendez-vous sur [simulateur-citoyen.fr/simulateur-retraite-et-epargne-regime-general](https://simulateur-citoyen.fr/simulateur-retraite-et-epargne-regime-general/)
2. Choisissez le **Mode Guidé** (première utilisation) ou le **Mode Expert** (fonctionnalités avancées)
3. Consultez le [Mode d'emploi](mode-emploi.html) pour un guide détaillé

---

## 🗺️ Feuille de route

- [x] Moteur de calcul CNAV + Agirc-Arrco (réutilisé et validé)
- [x] Comparateur d'épargne CTO/PEA/PER avec fiscalité 2026
- [x] ETF réels vérifiés individuellement (ISIN, TER)
- [x] Mode Guidé et Mode Expert
- [x] Tableau annuel, export PDF, ETF personnalisé, multi-scénarios (Expert)
- [x] Mise en ligne (GitHub Pages)
- [ ] Simulateur équivalent pour les fonctionnaires (en cours)

---

## 🔗 Liens officiels

- [info-retraite.fr](https://www.info-retraite.fr) — Relevé de carrière, simulateur M@rel
- [agirc-arrco.fr](https://www.agirc-arrco.fr) — Retraite complémentaire

---

*Développé bénévolement par J34NMY avec l'assistance de Claude (Anthropic) · Licence CC BY-NC-SA 4.0 · Juillet 2026*
