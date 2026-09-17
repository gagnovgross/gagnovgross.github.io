# MIPT Contemporary Combinatorics Research Seminar (September 2024)
### Московский физико-технический институт (МФТИ) · Кафедра дискретной математики
**Международный исследовательский семинар по дискретной математике, спектральной теории графов и системному распространению рисков**

This repository hosts the official materials, seminar schedule, and research monograph from the **MIPT Contemporary Combinatorics Research Seminar** held in September 2024 at the Moscow Institute of Physics and Technology.

---

## 🌐 Live Pages

- **[Международный семинар МФТИ (Сентябрь 2024) — Обзор и программа](https://gagnovgross.github.io/)** (`index.html`)  
  *Официальная страница семинара на русском языке с перечнем докладов, аннотацией исследования Матеуса Х. Н. Лофрано и списком приглашённых британских исследователей.*

- **[Full Interactive Research Treatise & Simulation Engine](https://gagnovgross.github.io/report.html)** (`report.html`)  
  *Полный интерактивный академический трактат (16 разделов, пререгистрированная программа исследований C0–C5, 3 симулятора D3.js с отслеживанием задержки волнового фронта, 6 графиков, 25 аудированных фактов K-регистра).*

---

## 📄 Featured Research Paper

**Title:** *Graph Theory Risk Propagation in Stochastic environments: An approach into pipeline industrial PdM IoT based modelling and financial contagion risk modelling*  
**Название:** *Распространение рисков на основе теории графов в стохастических средах: подход к моделированию промышленных трубопроводов (IoT/PdM) и финансового заражения*  
**Author / Докладчик:** **Mateus H. N. Lofrano (Матеус Х. Н. Лофрано)** &middot; GitHub: [@aglar-flaneur](https://github.com/aglar-flaneur)  
**Advisor / Научный руководитель:** **Prof. Gyula O. H. Katona (проф. Дьюла О. Х. Катона)** (Alfréd Rényi Institute of Mathematics / MIPT)  
**Affiliation:** Moscow Institute of Physics and Technology (MIPT)  
**Digital Archive:** MIPT Digital Repository [https://lib.mipt.ru/](https://lib.mipt.ru/)  

---

## 🔬 Pre-Registered Empirical Research Program (C0–C5)

To advance beyond speculative analogies into falsifiable science (Popper, 1959), this work binds all novel claims to confirmed public benchmarks, literature baselines, and pre-registered kill conditions:

| # | Research Question | Confirmed Datasets | Literature Baseline | Metric & Protocol | Pre-Registered Kill Condition | Target Journal |
|---|---|---|---|---|---|---|
| **C1** | Do recursive network metrics (DebtRank, coreness, cut sets) forecast pipeline failure severity *beyond* local engineering factors? | **PHMSA Flagged Incident Files** (1986–present; serious vs. significant vs. reported); **Mileage Reports**; **C-Town / EPANET** water benchmark (388 nodes, 429 pipes). | Lam et al. (2016) PHMSA baseline (4 dominant causes >75%); Zio & Sansavini (2011). | Negative-Binomial & Cox models; Out-of-time (2010–2018 train, 2019–2023 test) with operator cluster bootstrap. | If $\Delta\text{AUC} \le 0$ or $\Delta\log L$ out-of-sample is not significant at $\alpha=0.05$, publish negative result and refute cross-application. | *Reliability Engineering & System Safety* |
| **C2** | Does the Lovász Local Lemma condition $e \cdot p \cdot (d+1)$ anticipate systemic financial distress ahead of established metrics? | **e-MID Interbank Market** (1999–2009, 200–350 banks); 5Y European bank CDS spreads; Historical crisis windows (2007, 2008, 2011, 2020, 2023). | SRISK (Brownlees & Engle 2017); $\Delta\text{CoVaR}$ (Adrian & Brunnermeier 2016); MES (Acharya et al. 2017). | ROC-AUC at 1–6 month horizons; Graphical Lasso dependency graph $D$. | If LLL signal fails to beat naive market volatility, demote framing to pedagogical exposition. | *Journal of Financial Stability* |
| **C3** | Does Chung's directed spectral gap $\lambda_2$ and Cheeger constant $h(\vec{G})$ predict shock containment better than symmetric Fiedler cuts? | **e-MID daily transactions** (1999–2009); Daily network asymmetry $A = \|W - W^T\|_F / \|W + W^T\|_F$. | Symmetric Laplacian $\mathbf{L}_\text{sym} = \frac{1}{2}(\mathbf{W} + \mathbf{W}^T)$; Fiedler (1973). | Out-of-sample cascade containment under Eisenberg-Noe clearing; Empirical Cheeger bottlenecks. | If symmetric approximation error is negligible across banking topologies, demote section to pure theoretical interest. | *Quantitative Finance* |
| **C4** | Does sensor placement on product graph $G_\text{phys} \otimes G_\text{obs}$ reduce attack detection time on public benchmarks? | **BATADAL / C-Town Benchmark** (Taormina et al. 2018; 388 nodes, 429 pipes, 5 DMAs, SCADA telemetry, Dataset 3 attacks). | Krause et al. (2008) greedy physical max-coverage; Tsiami et al. (2021) TGCN ($S = 0.933$). | Official competition $S$-score ($\gamma=0.5$); Detection delay and classification accuracy. | If parity or degradation occurs vs. pure physical max-coverage, restrict thesis strictly to qualitative case studies. | *J. Water Resour. Plann. Manage.* / *IEEE TII* |
| **C5** | Transversal rigor: source reattribution, audited K-register, and reproducible test suites. | Open replication repository (Docker, Conda, DVC); OSF Pre-registration; Pytest analytical suite. | Buldyrev et al. (2010, *Nature*) interdependent networks; Poledna et al. (2015, *JFS*). | 100% test pass rate on analytical benchmarks (3-bank Eisenberg-Noe, 5-node DebtRank); Seeded runs. | Non-reproducible or unseeded runs invalidate empirical claims across C1–C4. | Zenodo / OSF Archive |

---

## 👥 Visiting Speakers & Participants (UK & International)

- **Dr. Alistair J. Thorne** (*University of Cambridge, DPMMS*) — *Percolation Thresholds in Inhomogeneous Random Digraphs*
- **Dr. Eleanor Vance** (*University of Oxford, Mathematical Institute*) — *Spectral Expansion and Cheeger Bottlenecks in Directed Complex Topologies*
- **Dr. Callum R. MacLeod** (*University of Warwick, Centre for Discrete Mathematics*) — *The Lovász Local Lemma and Tail Risk in Dependent Stochastic Cascades*
- **Dr. Oliver H. St. John** (*University of Bristol, School of Mathematics*) — *Conservative Circulations, Matroids, and Electrical Network Invariants*
- **Dr. Fiona M. Davies** (*Imperial College London, Department of Mathematics*) — *Subadditive Lattice Fixed Points in Financial Clearing Architecture*

---

## 🏛️ Organizing Committee & Research Authors

- **Research Author:** Mateus H. N. Lofrano &middot; GitHub: [@aglar-flaneur](https://github.com/aglar-flaneur)
- **Coordinator:** Yuri Ilyich Gagnov (МФТИ)
- **Program:** Master of Science in Contemporary Combinatorics, Phystech School of Applied Mathematics and Computer Science (FPAMI), MIPT.
- **Repository Maintainer:** `@gagnovgross`
