# Edukometrija: Formulių konspektai ir atsiskaitymų medžiaga

Šioje saugykloje pateikta Vilniaus universiteto Matematikos ir informatikos fakulteto (VU MIF) **Edukometrijos** kurso (prof. V. Čekanavičius) atsiskaitymams skirta medžiaga, formulių konspektai ir paruoštukės.

---

## 📄 Pagrindiniai formulių konspektai

### 1. SEM ir Kelių analizė rankomis (S1 atsiskaitymas)
* **[`eduko.pdf`](eduko.pdf)** — **Sukompiliuotas 4 puslapių PDF failas**, paruoštas spausdinimui:
  * Užima lygiai **2 A4 lapus** (spausdinant dvipusiu būdu / *duplex*).
  * 2 stulpelių tankus formatas, 1.1 cm paraštės, aiškios dėžutės ir TikZ brėžiniai.
* **[`sem_rankomis_formules.tex`](sem_rankomis_formules.tex)** — LaTeX šaltinio failas:
  * **Wright'o kelių sekimo taisyklės** (*Tracing rules*) ir leistinų kelių reikalavimai.
  * **Poveikių išskaidymas**: tiesioginis ($\text{DE}$), netiesioginis ($\text{IE}$), bendrasis ($\text{TE}$), neanalizuojamas ir iškraipytas.
  * **Modelio identifikavimas**: duomenų taškai ($p^*$), laisvės laipsniai ($df$), $t$-taisyklė, rekursyvumo taisyklė.
  * **Greitoji 2x2 lygčių sistemos Kramerio formulė** ryšių koeficientams rasti.
  * **Liekamųjų paklaidų dispersijos** $\text{Var}(e)$ ir determinacijos koeficientas $R^2$.
  * **Vadovėlio 3.3.9 pav. Klasikinio SEM modelio TikZ diagrama** ir jos LISREL matricos ($B, \Gamma, \Lambda_x, \Lambda_y, \Phi, \Psi, \Theta_\delta, \Theta_\epsilon$).
  * **Vadovėlio 3.3.7 pav. Mokinio savybių modeliai**: MTMM, CTCU ir CT modelių struktūros ir interpretavimas.
  * **Pilnai išspręsti uždavinių pavyzdžiai**:
    1. *1 Pavyzdys (Žalia lenta)*: 4 kintamųjų $A, B, C, D$ ryšių radimas pagal koreliacijų matricą.
    2. *2 Pavyzdys (Baltas ekranas)*: hierarchinis modelis $* \to A, B, C \to D, E$, visų koreliacijų išvedimas ir dėstytojo taisyklė dėl galutinių kintamųjų $D$ ir $E$.
    3. *3 Pavyzdys (Vadovėlio p. 167)*: trikampė kelių analizės schema su pilna dekompozicija.
  * **Modelio tinkamumo rodikliai**: $\chi^2, NC = \chi^2/df$, RMSEA, CFI, TLI, SRMR.
  * **Dažniausi kontroliniai klausimai**: *collider* savybės, Heywood atvejai, $\chi^2$ jautrumas imties dydžiui $N$.

### 2. Klasterinė analizė (K1/K2 atsiskaitymas)
* **[`klasterine_analize_formules.tex`](klasterine_analize_formules.tex)** — Hierarchinės ir $k$-vidurkių klasterizacijos atstumų metrikos, jungimo metodai (Single, Complete, Average, Ward) ir kokybės indeksai (Silueto, Davies-Bouldin, Dunn, Calinski-Harabasz).

---

## 🖨️ Spausdinimo rekomendacijos (`eduko.pdf`)
* **Formatas**: A4
* **Režimas**: Dvipusis spausdinimas (*Duplex / Flip on long edge*)
* **Mastelis**: 100% (*Actual size*)
* **Apimtis**: Lygiai 2 fiziniai A4 lapai.
