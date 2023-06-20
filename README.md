# Tesina-Change-Detection
Autore: Marco Giangreco, 1938091

**Link utili**
- Dataset: https://rcdaudt.github.io/oscd/
- Descrizione del dataset: https://ieee-dataport.org/open-access/oscd-onera-satellite-change-detection
- https://github.com/rcdaudt/fully_convolutional_change_detection

**Svolgimento:**

1. Per prima cosa, è necessario scaricare il dataset OSCD - ONERA SATELLITE CHANGE DETECTION utilizzando i seguenti mirrors:
   - Onera Satellite Change Detection dataset - Images;
   - Onera Satellite Change Detection dataset - Train Labels;
   - Onera Satellite Change Detection dataset - Test Labels.
2. Utilizzare le immagini in imgs_1_rect e imgs_2_rect, che si trovano nella directory "Onera Satellite Change Detection dataset - Images", dove le immagini presenti in "imgs_1_rect" rappresentano l'immagine acquisita prima della modifica, mentre quelle presenti in "imgs_2_rect" rappresentano l'immagine acquisita dopo la modifica.
3. Creare una classe per il tuo dataset utilizzando PyTorch e visualizzare l'output del dataloader per verificare che funzioni correttamente.
4. Utilizzare i codici che ha fornito per calcolare gli indici spettrali.
5. Creare il tuo modello U-Net e addestralo utilizzando il dataset di train.
6. Utilizza precision, recall ed F1-score come metriche per valutare il modello.
7. Per migliorare le prestazioni del modello, puoi provare a bilanciare la loss passando il parametro pos_weight alla BCEWithLogitsLoss, utilizzare data augmentation, utilizzare la Focal Loss e salvare i checkpoint ogni epoca per evitare di perdere i dati in caso di disconnessione.
