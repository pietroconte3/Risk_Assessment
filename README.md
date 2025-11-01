# Crypto Agility Risk Assessment Framework (CARAF)


## Descrizione del Progetto

Il progetto presenta **CARAF** (*Crypto Agility Risk Assessment Framework*), un modello a cinque fasi per la **valutazione e mitigazione dei rischi** legati alla **mancanza di crypto-agility** nelle organizzazioni.

L’obiettivo è fornire un approccio **proattivo** alla sicurezza crittografica, aiutando le aziende a **prepararsi all’arrivo del quantum computing** e a gestire in modo strutturato la transizione verso soluzioni *quantum-safe (PQC)*.

---

## Obiettivi

- Analizzare i rischi derivanti dalla mancanza di crypto-agility  
- Valutare l’impatto delle minacce *post-quantum*  
- Proporre strategie di mitigazione e piani di adattamento  
- Offrire una metodologia replicabile per la sicurezza crittografica  

---

## Componenti del Framework

- **CARAF (Crypto Agility Risk Assessment Framework)** → modello operativo in 5 fasi  
- **Threat Modeling Operativo** → identificazione di attori, vettori e vulnerabilità  
- **Modello MOSCA (XYZ)** → metrica per stimare rischio e tempistica  
- **Post-Quantum Cryptography (PQC)** → soluzioni di mitigazione e aggiornamento  

---

## Le 5 Fasi di CARAF

1. **Identificazione della minaccia**  
   Analisi dei vettori di minaccia e delle vulnerabilità crittografiche.  
   *Esempio:* rischio derivante dai computer quantistici in grado di rompere RSA/ECC.

2. **Inventario degli asset**  
   Creazione di un inventario dettagliato degli asset crittografici coinvolti.  
   - **Ambito:** protocolli (es. TLS, IoT)  
   - **Sensibilità:** dati o dispositivi critici  
   - **Crittografia:** algoritmi utilizzati  
   - **Ciclo di vita:** politiche di aggiornamento  

3. **Stima del rischio**  
   Calcolo del rischio secondo il modello MOSCA:
   dove:
- **X** = vita utile dell’asset  
- **Y** = tempo per la mitigazione  
- **Z** = tempo prima che la minaccia si concretizzi  

Se `X + Y > Z` → rischio **critico**.

4. **Strategie di mitigazione**  
Decisioni basate su rischio e costo:
- 🔹 Aggiornamento a PQC o soluzioni ibride  
- 🔹 Accettazione del rischio (se basso)  
- 🔹 Sostituzione graduale degli asset vulnerabili  

5. **Roadmap organizzativa**  
Definizione di un piano operativo:
- Aggiornamento delle policy crittografiche  
- Pianificazione del *change management*  
- Revisione contratti e fornitori  
- Automazione nella gestione delle chiavi  

---

## Caso di Studio: Quantum Threat su IoT

**Scenario:**  
Dispositivi IoT che utilizzano TLS basato su RSA/ECC possono essere compromessi da futuri computer quantistici.

**Applicazione del framework:**  
1. Identificazione → minaccia quantistica su TLS  
2. Inventario → dispositivi IoT critici  
3. Stima → X+Y > Z ⇒ rischio alto  
4. Mitigazione → migrazione a algoritmi *quantum-safe (PQC)*  
5. Roadmap → aggiornamento graduale e automazione policy  

---

## Tecnologie e Strumenti

- **Standard di riferimento:** NIST SP 800-30, ISO/IEC 27005  
- **Algoritmi quantistici:** Shor, Grover  
- **Metriche operative:** MOSCA model (XYZ)  
- **Ambiti applicativi:** Infrastrutture crittografiche, TLS, IoT  

---

## Conclusioni

Il framework **CARAF** propone un approccio **proattivo e strutturato** alla sicurezza crittografica, anticipando le vulnerabilità e supportando la transizione verso la **crittografia post-quantum**.  
Questo metodo integra analisi del rischio, governance e strategia operativa, diventando uno strumento essenziale per la **cyber-resilienza aziendale**.

---

**Corso:** Risk Assessment 
**Autore:** Pietro Conte  
**Professoressa:** Alessandra De Benedictis  
**Università:** Federico II – A.A. 2025–2026 

