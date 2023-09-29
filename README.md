# Tesina-Change-Detection
Autore: Marco Giangreco, mat. 1938091

**Link utili**
- Dataset: https://rcdaudt.github.io/oscd/
- Descrizione del dataset: https://ieee-dataport.org/open-access/oscd-onera-satellite-change-detection
    
**OSCD - Dataset**  
Nella cartella 'data' del mio progetto, sono disponibili le curve di apprendimento relative a tre importanti metriche: 'loss,' 'accuracy,' e 'f1-score.' Queste curve sono il risultato dell'addestramento di una rete U-Net utilizzando gli indici spettrali NDVI, NDWI e NDBI. Il dataset utilizzato è stato suddiviso in un set di addestramento (train set) e un set di test. Il set di test è ulteriormente suddiviso in 5 aree per la 'validation' e 5 per il test finale (test set). Le diverse configurazioni sono state addestrate e validate sul set di 'validation' e successivamente testate sul set di 'test.' Oltre alle metriche, nella stessa cartella 'data' sono presenti anche le immagini predette, che rappresentano i risultati ottenuti dal modello.
