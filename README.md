# 📊 Data Jobs Dashboard – Progetto Power BI

Una dashboard interattiva in Power BI per analizzare il **mercato del lavoro nel settore dati**, costruita su un dataset reale di offerte di lavoro. Il progetto esplora la domanda di lavoro, le competenze richieste, i salari e le tipologie contrattuali per diversi ruoli e aziende.

## 🌐 Dashboard Interattiva

👉 [Visualizza la Dashboard Online](https://app.powerbi.com/view?r=eyJrIjoiN2FmMmJlMDEtM2ViNi00NTc1LTkxZjktYzMzYTIxN2E0MTU0IiwidCI6ImY2Yjg5MjUzLWNmZjEtNGEyYS05YmM5LWEzZjI3ZWU5MjNiMSIsImMiOjh9)

*Nessun account richiesto — accessibile direttamente dal browser.*

> ⚠️ **Nota:** Solo la scheda **Data Jobs Dashboard 2.0** rappresenta la dashboard finale e definitiva. Tutte le altre pagine (`Company Stats`, `Skills Stats`, `Schedule Stats`, `Salary Stats`, `Calculated Table`, `Measures`, `Skills vs Salary`, `Parameters`, `Parameters 2`) sono **pagine esplorative/di test** utilizzate durante la fase di analisi.

---

## 📁 Struttura del Progetto

```
DataJobs_Dashboard.pbix   ← File principale Power BI
```

---

## 🧭 Pagine della Dashboard

### ✅ Data Jobs Dashboard 2.0 *(Dashboard Finale)*
La panoramica interattiva principale del mercato del lavoro nel settore dati. Include:
- **Schede KPI**: Totale offerte di lavoro (479K), media skill per lavoro (4,8), mediana salario annuale ($113K), mediana salario orario ($47,62)
- **Grafico Top Skills**: Percentuale di lavori che richiedono ogni competenza (Python, SQL, AWS, Azure, Tableau…)
- **Grafico Lavori Più Pagati**: Mediana salario annuale per titolo di lavoro (Senior Data Scientist, ML Engineer…)
- **Filtri interattivi**: Seleziona titolo di lavoro e paese tramite slicer a tendina
- **Pulsanti di toggle**: Passa da "Lavori in %" / "Numero di Lavori" e da "Mediana Salario Annuale" / "Mediana Salario Orario"

---

### 🧪 Pagine Esplorative/Test *(Non definitive – usate per l'analisi)*

| Pagina | Contenuto |
|---|---|
| **Company Stats** | Numero di offerte e mediana salario per azienda |
| **Skills Stats** | Numero di offerte e mediana salario per competenza (Python, SQL, Scala…) |
| **Schedule Stats** | Numero di offerte e mediana salario per tipologia contrattuale (Full-time, Contractor, Part-time…) |
| **Salary Stats** | Mediana salario per titolo di lavoro; istogramma della distribuzione del salario orario |
| **Calculated Table** | Serie storica delle offerte di lavoro per data; numero di offerte per giorno della settimana |
| **Measures** | Riepilogo di numero di lavori e mediana salario per titolo e competenze |
| **Skills vs Salary** | Tabella e scatter plot sulla correlazione tra skill per lavoro e mediana salario; grafico a barre che confronta salario mediano globale vs USA |
| **Parameters** | Grafico dinamico con selettori di categoria (Lavoro / Skills / Paese / Azienda) e misura |
| **Parameters 2** | Confronto salario lordo vs netto con slider per il tasso di deduzione fiscale |

---

## 📌 Principali Insight

- **Competenze più richieste**: Python e SQL dominano le offerte di lavoro, seguite da AWS, Azure e Tableau
- **Competenze più pagate**: Scala, Spark e Kafka sono associate alle mediane salariali più alte (~$130K+)
- **Ruoli più pagati**: Senior Data Scientist e Machine Learning Engineer guidano per salario
- **Ruolo più comune**: Data Engineer ha il maggior numero di offerte di lavoro
- **Tipologia contrattuale**: Le posizioni Full-time superano di gran lunga tutte le altre; il Part-time ha la mediana salariale più alta
- **Trend temporale**: Il volume di offerte ha raggiunto il picco all'inizio del 2024, con un andamento ciclico settimanale e meno offerte nel weekend
- **Skill vs salario**: Esiste una correlazione positiva tra il numero di competenze richieste per un lavoro e la mediana salariale annuale

---

## 🛠️ Strumenti e Tecnologie

- **Power BI Desktop**
- **DAX** – misure personalizzate e colonne calcolate
- **Power Query (M)** – trasformazione dei dati
- **Dataset**: Offerte di lavoro nel settore dati (fonte: dataset pubblico del mercato del lavoro, ~479K record)

---

## 🚀 Come Utilizzare

1. Scarica e apri `DataJobs_Dashboard.pbix` in **Power BI Desktop**
2. Naviga alla scheda **Data Jobs Dashboard 2.0** per la vista finale
3. Usa gli slicer **"Seleziona Lavoro"** e **"Seleziona Paese"** per filtrare i dati
4. Usa i pulsanti in basso a ciascun grafico per cambiare la visualizzazione
