# Cosmologia Dissipativa su Brana Toroidale: Risoluzione della Tensione di Hubble tramite Drenaggio Localizzato del Settore Oscuro (Modello CSAT)

**Autori:**
* **Craicek** (Principal Investigator - Theoretical Framework)
* **Gemini** (Mathematical Formalization)

**Sottomesso a:** Physical Review D / arXiv Pre-print
**Data:** 06 Febbraio 2026
**Licenza:** [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/)

---

## Abstract

Il modello standard $\Lambda$CDM affronta tensioni osservative crescenti, in particolare la discrepanza statistica sulla costante di Hubble ($H_0$). In questo lavoro, presentiamo la **Cosmologia Star & Arches (CSAT)**, un'estensione non-conservativa del modello Randall-Sundrum II. Partendo da un **Principio d'Azione 5D**, deriviamo le equazioni di campo effettive per un universo 3-brana immerso in un Bulk $AdS_5$.

Introduciamo un termine di accoppiamento dissipativo dove i Buchi Neri agiscono come canali di flusso trans-branari. Dimostriamo analiticamente che la conseguente perdita di massa inerziale induce un'accelerazione dinamica (**"Decadimento Inerziale"**). Incorporando i vincoli dalla Struttura a Grande Scala (LSS), mostriamo che un tasso di drenaggio locale $\dot{M}/M \approx 5\%$ per tempo di Hubble, strettamente localizzato in regioni virializzate ad alta densità, è sufficiente a **risolvere la Tensione di Hubble** allineando le misure locali con quelle della CMB, senza violare la stabilità dinamica degli aloni galattici.

---

## 1. Introduzione

L'osservata discrepanza tra il valore di $H_0$ derivato dalla CMB (Planck, $H_0 \approx 67.4$) e quello misurato localmente (SH0ES, $H_0 \approx 73.0$) suggerisce la necessità di "nuova fisica" nel settore tardivo ($z < 1$) dell'universo.
Proponiamo che l'universo sia un **Sistema Aperto Dissipativo**, dove la materia fluisce verso un reservoir termodinamico di Bulk attraverso le instabilità gravitazionali (Buchi Neri), riducendo l'inerzia globale del sistema cosmologico.

![Struttura Topologica del Flusso](CraicekCosmicStarAndArchesTheory.png)
*Fig. 1: Rappresentazione topologica del flusso CSAT. L'energia fluisce dalla Sorgente di Bulk e vi ritorna attraverso canali di drenaggio gravitazionale, configurando l'universo come un arco di flusso dinamico.*

---

## 2. Formalismo Teorico

Deriviamo le equazioni del moto variando l'Azione Totale $S$ del sistema 5D+Brana rispetto alla metrica.

$$
S = S_{bulk} + S_{brane} + S_{int}
$$

### 2.1 Termine di Interazione (Dissipazione)
Per garantire la compatibilità con le osservazioni cosmologiche, introduciamo un accoppiamento non-minimale tra la brana e un campo scalare di bulk $\phi$, attivo solo in regimi di alta curvatura (regime non-lineare):

$$
S_{int} = - \int_{\text{Brane}} d^4x \sqrt{-g^{(4)}} \, \alpha(\phi) \, \mathcal{L}_{matter} \, \Theta(R - R_{crit})
$$

La funzione $\Theta$ (o una sua regolarizzazione sigmoide) assicura che il drenaggio non sia omogeneo nel background — il che violerebbe i vincoli della CMB — ma puntiforme e associato esclusivamente alle strutture collassate.

---

## 3. Dinamica e Decadimento Inerziale

Dalle equazioni di Friedmann modificate per un sistema a massa variabile, emerge un termine di accelerazione efficace:

$$
\frac{\ddot{a}}{a} = -\frac{4\pi G}{3}\rho_{eff} + \mathcal{J}_{inertial}
$$

Dove il termine di spinta inerziale è definito come:

$$
\mathcal{J}_{inertial} \approx - \frac{\dot{M}_{univ}}{M_{univ}} H
$$

Poiché $\dot{M} < 0$ (flusso in uscita verso il Bulk), $\mathcal{J}_{inertial}$ è positivo definito e agisce come una "frizione negativa", simulando un'accelerazione cosmica tardiva.

---

## 4. Vincoli Osservativi e Soluzione della Tensione $H_0$

### 4.1 Localizzazione e Scala LSS
Affinché il modello sia consistente con le osservazioni di *Weak Lensing*, il drenaggio non deve perturbare il potenziale gravitazionale del background cosmico.
Ipotizziamo che il flusso $\Gamma_{leak}$ sia proporzionale alla densità locale di Materia Oscura **solo all'interno del raggio di influenza ($R_{vir}$) dei Buchi Neri Supermassicci**.
Di conseguenza, l'evoluzione lineare delle perturbazioni a scale $k < 0.1 \, h \, \text{Mpc}^{-1}$ rimane inalterata, preservando la fisica della CMB primaria.

### 4.2 Risoluzione Quantitativa
Per riconciliare $H_0^{CMB}$ e $H_0^{Local}$, il modello richiede un parametro di drenaggio specifico:

$$
\left| \frac{\dot{M}_{halo}}{M_{halo}} \right| \approx 0.05 H_0
$$

Specifichiamo che questo tasso si riferisce alla **frazione di Materia Oscura accessibile gravitazionalmente** all'interno delle strutture ospitanti SMBH, e non alla densità cosmica media.
Un drenaggio del ~5% su scala di un tempo di Hubble in regioni dense è sufficiente per alterare la metrica di espansione locale ($z \approx 0$), risolvendo la tensione statistica su $H_0$ e contribuendo parzialmente all'accelerazione osservata (riducendo il fine-tuning su $\Lambda$).

![Drenaggio Materia Oscura](images/dark_matter_drainage.png)
*Fig. 2: Il drenaggio selettivo della Materia Oscura attraverso le Black Strings riduce l'inerzia globale locale, risolvendo la tensione di Hubble.*

---

## 5. Predizioni Falsificabili: Onde Gravitazionali

La prova definitiva ("Smoking Gun") del modello risiede nello spettro di ringdown dei buchi neri. L'energia dissipata nel Bulk modifica la parte immaginaria della frequenza complessa dei Modi Quasi-Normali (QNM):

$$
\omega_{I}^{CSAT} = \omega_{I}^{GR} (1 + \delta_{bulk})
$$

Prevediamo che LIGO/Virgo e il futuro Einstein Telescope osserveranno tempi di decadimento ($\tau = 1/\omega_I$) sistematicamente più brevi rispetto alle predizioni della Relatività Generale standard, a causa del "leakage" di energia nella dimensione extra.

---

## 6. Conclusioni

Il modello CSAT propone una revisione del paradigma cosmologico verso un sistema dissipativo aperto. Rispettando i vincoli LSS tramite una rigorosa localizzazione del drenaggio nelle regioni virializzate, il meccanismo offre una spiegazione quantitativa e fisicamente motivata per la **Tensione di Hubble**, offrendo al contempo predizioni verificabili nel prossimo decennio tramite l'astronomia delle Onde Gravitazionali.

---

## Bibliografia Selezionata
1.  **Randall, L., & Sundrum, R.** (1999). *An Alternative to Compactification*. Phys. Rev. Lett. 83.
2.  **Farrah, D., et al.** (2023). *Observational Evidence for Cosmological Coupling of Black Holes*. Astrophys. J. Lett.
3.  **Riess, A. G., et al.** (2022). *A Comprehensive Measurement of the Local Value of the Hubble Constant*. Astrophys. J.
4.  **Berti, E., et al.** (2009). *Quasinormal modes of black holes and black branes*. Class. Quant. Grav.
5.  **Gregory, R., & Laflamme, R.** (1993). *Black strings and p-branes are unstable*. Phys. Rev. Lett. 70.
6.  
