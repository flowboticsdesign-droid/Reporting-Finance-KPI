# Reporting Finance KPI – Power BI Dashboard

> Comprehensive financial reporting platform for Fondasol tracking PNE 
> (Produit Net d'Exploitation) and MOP (Marge Opérationnelle) — comparing 
> actuals vs budget across 14+ regions and 30+ agencies, with ERP ledger 
> drill-through, activity phase analysis, and monthly variance tracking.

---

## 📊 Pages

### 1. Chiffres Clés – Budget vs Réalisé
![KPI Reel VS Budget](Screenshot/KPI%20Reel%20VS%20Budget.png)

> Executive KPI summary for 2025: PBE 66,123K€ budget vs 17,253K€ réel, 
> PNE 68,397K€ vs 16,077K€ (-52,320K€ variation), MOP 22,944K€ vs 5,061K€ 
> (-17,883K€), EBITDA 6,201K€ vs 942K€. Includes detailed MOP breakdown 
> by cost category (Personnel, Véhicules, Équipement Forage, Sous-traitance).

---

### 2. Reporting Détaillé – Réalisé vs Budget
![Reporting details VS budget](Screenshot/Reporting%20details%20VS%20budget.png)

> Full P&L matrix comparing Budget vs Réel across all cost categories: 
> PNE, Dépenses Opérationnelles, Dépenses Indirectes, Dépenses Exceptionnelles, 
> EBITDA — with variance column per line. MOP/PNE ratio: 33.6% budget vs 
> 31.6% réel. Filterable by region and agency grouping code.

---

### 3. Histogramme – Variation Mensuelle Réel vs Budget
![Histogram Mensuel variation Actual vs Budget](Screenshot/Histogram%20Mensuel%20variation%20Actual%20vs%20Budget.png)

> Waterfall charts tracking monthly PNE and MOP variance (Réel vs Budget) 
> with cumulative trend line. Highlights month-by-month drift: 
> PNE Jan +175K€ → Feb -114K€ → Mar -244K€ cumul. 
> MOP Jan +325K€ → Feb -282K€ → Mar -73K€ cumul.

---

### 4. Histogramme Mensuel – PNE / MOP
![Histogram PNEvs MOP](Screenshot/Histogram%20PNEvs%20MOP.png)

> Monthly bar + cumulative line chart for PNE (Jan 5,073K → Mar 5,745K, 
> cumul 16,077K) and MOP (Jan 1,493K → Mar 2,211K, cumul 5,061K). 
> Enables trend monitoring and seasonal pattern detection per region and agency.

---

### 5. Bridges – Variation MOP par Agence
![Bridges details MOP variation by agence](Screenshot/Bridges%20details%20MOP%20variation%20by%20agence.png)

> Waterfall bridge charts decomposing PNE and MOP variance vs Budget and 
> vs N-1 (2024) at agency level. Four views: Var PNE vs Budget, 
> Var MOP vs Budget, Var PNE vs 2024, Var MOP vs 2024 — 
> identifying top contributors to over/under performance by agency code.

---

### 6. Analyse Phases A & B – Par Région
![Analyse activity pahse A and Phase B by region](Screenshot/Analyse%20activity%20pahse%20A%20and%20Phase%20B%20by%20region.png)

> Regional productivity analysis decomposing PNE variance into: 
> Effet ETP (headcount effect) and Effet Activité/Productivité across 
> Phase A (engineering) and Phase B (production units). 
> Covers CEDR, DTNM, Fondasol, GIDR, GSDR, WEDR with ETP réel vs budget, 
> PVJI variance, and production day delta.

---

### 7. Analyse Phases A & B – Ingénieurs vs Machines
![Analyses acctivity phase (A)engineer VS (B)Machines](Screenshot/Analyses%20acctivity%20phase%20(A)engineer%20VS%20(B)Machines.png)

> Agency-level drill-down of Phase A (engineer productivity) vs Phase B 
> (machine/equipment units) — comparing ETP réel vs budget, PVJI variance, 
> production days, and PVJE across all agency grouping codes with 
> dual waterfall charts for effet activité and effet UP.

---

### 8. Statistiques – Budget vs Réalisé
![Details stats](Screenshot/Details%20stats.png)

> HR and production statistics matrix: headcount analysis (Effectif bureau, 
> chantier, ingénieur, intérimaire) Budget vs Réel with variation. 
> Production stats: équipes affectées, jours de production ST externe/interne. 
> Ratio I/B Budget 4.2 vs Réel 4.0. Filterable by agency and region.

---

### 9. Indicateurs FI – Filiale
![Indicator Filiale by region](Screenshot/Indicator%20Filiale%20by%20region.png)

> Subsidiary-level financial indicators: daily cost per production day 
> (Budget 1,285€ vs Réel 1,489€), Coûts/PNE ratio (Budget 25.2% vs Réel 26.6%). 
> Full P&L breakdown Budget vs Réel + Variation: PNE, Dépenses Opérationnelles, 
> Dépenses Indirectes, EBITDA — filterable by Filière (CEFI, GSFI, GIFI, WEFI).

---

### 10. Détail des Écritures Navision
![Deatils ledger entry ERP](Screenshot/Deatils%20ledger%20entry%20ERP.png)

> ERP ledger drill-through from Navision/Business Central — detailed 
> accounting entries by category: PNE (20.7M€), Dépenses Opérationnelles 
> (-11.3M€), Dépenses Indirectes (-4.9M€), Dépenses Exceptionnelles (-537K€). 
> KPI cards: % MOP 31.6% and % PNE R/B 30%. Filterable by month, region, 
> and agency grouping code.

---

## 🔍 Key Features

- 10-page financial reporting platform covering full P&L from PNE to EBITDA
- Budget vs Réel vs N-1 comparison at region, filiale, and agency level
- Waterfall bridge charts for MOP and PNE variance decomposition
- Phase A/B productivity analysis (ETP effect vs activity/productivity effect)
- Direct ERP ledger drill-through from Navision/Business Central
- Dynamic filters: Month range slider, Région, Regroupement Code, Filière
- Weighted staffing ratios and daily cost per production day tracking
