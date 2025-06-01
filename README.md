# Tecniche-di-rappresentazione-e-modellizzazione-dati-COVID-19
Analisi modellistica dei contagi COVID-19 in Friuli Venezia Giulia tramite modelli di crescita logistica e Gompertz, con visualizzazioni, ottimizzazione e inferenza bayesiana.
# Analisi dei contagi COVID-19 in Friuli Venezia Giulia

Questo progetto contiene un'analisi completa dell'evoluzione dei contagi COVID-19 nella regione Friuli Venezia Giulia, utilizzando modelli di crescita (Logistica e Gompertz) e metodi statistici per la stima dei parametri.

## 📈 Contenuti principali

- Pulizia e visualizzazione dei dati giornalieri e mensili
- Modellazione dei contagi con curve logistiche e di Gompertz
- Studio dell'effetto dei parametri k e t₀
- Stima dei parametri tramite MCMC (`emcee`)
- Previsioni a 35 e 100 giorni con intervalli di confidenza
- Modellazione di una seconda ondata con doppia curva

## 🛠 Requisiti

Installare le dipendenze con:

```bash
pip install -r requirements.txt
