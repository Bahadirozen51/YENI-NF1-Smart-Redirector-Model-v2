# 🧪 LAB_PROTOCOLS: Wet-Lab & Encapsulation Framework (Phase 2)

This document delineates the Standart Operating Procedures (SOP) formulated for **TRL-4 (Laboratory Validation)** of the **NF1-Smart-Redirector-Model v2**, locked under deterministic constraints via **Seed: 185615162**.

---

## 🇹🇷 1. Oligonükleotid Kimyasal Modifikasyonu (Moleküler Zırh)
Sentetik 21-nt RNA kargosunun hücresel nükleazlardan (RNase) korunması ve in vivo yarı ömrünün uzatılması amacıyla kimyasal sentez aşamasında şu modifikasyon matrisi uygulanacaktır:
- **Riboz Şeker Modifikasyonları:** Tüm pirimidin bazlarında $2'$-O-Methyl ($2'\text{-OMe}$) ve $2'$-Fluoro ($2'\text{-F}$) sübstitüsyonu ile enzimatik direnç maksimuma çıkarılacaktır.
- **Fosfodiester Omurgası:** Ekzopeptidaz aktivitesini tamamen bloke etmek için terminal uçlara (hem $5'$ hem $3'$ yönünde) ardışık 3'er adet fosforotiyoat (PS) bağı entegre edilecektir.

## 🇬🇧 1. Oligonucleotide Chemical Modification (Molecular Armor)
To prevent enzymatic degradation of the synthetic 21-nt RNA payload by cellular RNases and extend its in vivo half-life, the following chemical modification matrix shall be implemented during solid-phase synthesis:
- **Ribose Sugar Modifications:** $2'$-O-Methyl ($2'\text{-OMe}$) and $2'$-Fluoro ($2'\text{-F}$) substitutions on all pyrimidine bases to maximize enzymatic metabolic resistance.
- **Phosphodiester Backbone:** Integration of 3 consecutive phosphorothioate (PS) linkages at both $5'$ and $3'$ terminal ends to systematically block exopeptidase truncation.

---

## 🇹🇷 2. Lipid Nanoparçacık (LNP) Kapsülleme Protokolü

### A. Bileşenlerin Hazırlanması (Molar Oran Regülasyonu)
Toplam lipid konsantrasyonu $10\text{ mM}$ olacak şekilde aşağıdaki 4'lü matris formüle edilir:
- **İyonize Lipid (ALC-0315 / MC3):** $\%45.0$ Molar Oran (Asidik endozomda pozitif yüklenerek endozomal kaçışı sağlar).
- **Helper Lipid (DSPC / DOPE):** $\%10.0$ Molar Oran (Çift katmanlı lipid membran bütünlüğü).
- **Sterol (Kolesterol):** $\%43.5$ Molar Oran (LNP membran akışkanlığının regülasyonu).
- **PEG-Lipid (DMG-PEG2000):** $\%1.5$ Molar Oran (Sistemik dolaşımda agregasyonu engelleme).

### B. Mikroakışkan Sentez Operasyonu (SOP)
1. **Organik Faz:** Hazırlanan 4'lü lipid matriksi susuz saf etanol içerisinde tamamen çözülür.
2. **Aköz Faz:** Modifiye edilmiş 21-nt RNA kargosu, $50\text{ mM}$ Sodyum Asetat tampon çözeltisinde ($\text{pH } 4.0$) çözülür.
3. **Cihaz Parametreleri:** Mikroakışkan çip üzerinde Akış Hızı Oranı (FRR) $\text{Aköz} : \text{Organik} = 3:1$ olarak kilitlenir. Toplam Akış Hızı (TFR) $> 12\text{ mL/dak}$ olarak set edilir.
4. **Purifikasyon:** Sentezlenen LNP'ler derhal Teğetsel Akış Filtrasyonu (TFF) sistemiyle etanollerinden arındırılır ve PBS ($\text{pH } 7.4$) tamponuna diyaliz edilir.

## 🇬🇧 2. Lipid Nanoparticle (LNP) Encapsulation Protocol

### A. Formulation Formulation Matrix (Molar Ratio Regulation)
The 4-component lipid matrix is formulated to achieve a final total lipid concentration of $10\text{ mM}$:
- **Ionizable Lipid (ALC-0315 / MC3):** $45.0\%$ Molar Ratio (Triggers positive charge in acidic endosomes for endosomal escape).
- **Helper Lipid (DSPC / DOPE):** $10.0\%$ Molar Ratio (Maintains structural lipid bilayer integrity).
- **Sterol (Cholesterol):** $43.5\%$ Molar Ratio (Regulates LNP membrane fluidity and endocytosis).
- **PEG-Lipid (DMG-PEG2000):** $1.5\%$ Molar Ratio (Prevents systemic aggregation and opsonization).

### B. Microfluidic Hydrodynamic Focusing (SOP)
1. **Organic Phase:** The 4-component lipid formulation is dissolved completely in anhydrous absolute ethanol.
2. **Aqueous Phase:** Modified 21-nt RNA payload is dissolved in $50\text{ mM}$ Sodium Acetate buffer ($\text{pH } 4.0$) to enable electrostatic entrapment.
3. **Instrument Configuration:** Flow Rate Ratio (FRR) is locked at $\text{Aqueous} : \text{Organic} = 3:1$ on the microfluidic chip. Total Flow Rate (TFR) is set at $> 12\text{ mL/min}$ to secure sub-100 nm diameters.
4. **Purification:** Synthesized LNPs are systematically purified via Tangential Flow Filtration (TFF) for ethanol removal and buffer-exchanged into PBS ($\text{pH } 7.4$).

---

## 🇹🇷 3. In Vitro Kalite Kontrol ve Biyolojik Doğrulama Testleri

### A. Fizikokimyasal Karakterizasyon
- **DLS (Dinamik Işık Saçılması):** Üretilen yapay kapsüllerin hidrodinamik çap spektrumu ölçülür. Başarı kriteri: Boyut $70-90\text{ nm}$ aralığında, Polidispersite İndeksi ($\text{PDI}$) $< 0.18$ olmalıdır.
- **Zeta Potansiyeli:** Parçacıkların yüzey yükü nötr pH'ta ($\text{pH } 7.4$) ölçülerek nötre yakın veya hafif negatif (hücresel toksisiteyi önlemek adına) olduğu tescillenmelidir.

### B. Hücre Canlılık ve Fonksiyonel Blokaj Testleri
- **MTT / WST-1 Analizi:** Mutant onkoprotein eksprese eden kanser hücre hatlarında (örn. MIA PaCa-2, A549) LNP-RNA kompleksinin hücre ölüm hızı ve hücre toksisitesi kinetiği ölçülür. Hedef: $\text{IC}_{50} \leq 0.45\text{ nM}$.
- **Western Blot (Sinyal Yolağı Takibi):** Hücre içi allosterik engellemenin doğrulanması amacıyla, hücreler doza bağlı olarak LNP ile muamele edildikten sonra aşağı akış (downstream) efektörlerin fosforilasyon protein seviyeleri (p-ERK1/2 ve p-MEK1/2) nicel olarak analiz edilecektir.

## 🇬🇧 3. In Vitro Quality Control & Biological Assays

### A. Physicochemical Characterization
- **DLS (Dynamic Light Scattering):** Hydrodynamic diameter spectrum of the formulated capsules is verified. Success criteria: Particle size between $70-90\text{ nm}$, with a Polydispersity Index ($\text{PDI}$) $< 0.18$.
- **Zeta Potential:** Surface charge profile is monitored at physiological pH ($\text{pH } 7.4$) to confirm near-neutral or slightly negative surface values to eliminate localized cytotoxicity.

### B. Cell Viability & Functional Cascade Blockade Assays
- **MTT / WST-1 Assay:** Cytotoxicity kinetics and anti-proliferative efficiency of the LNP-RNA complex are quantified in mutant oncoprotein-expressing cell lines (e.g., MIA PaCa-2, A549). Target threshold: $\text{IC}_{50} \leq 0.45\text{ nM}$.
- **Western Blotting (Signal Cascade Tracking):** To validate intracellular allosterik interception, cells will be treated with escalating doses of LNPs, followed by quantitative immunoblotting of downstream phosphorylation markers (p-ERK1/2 and p-MEK1/2).
