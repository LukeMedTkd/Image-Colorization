![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

# Image Colorizarion
<p align="justify">
Il presente progetto esplora la <b>colorazione di immagini</b> attraverso un approccio di deep learning. <br>
La colorazione manuale delle immagini è un'operazione complessa che implica un notevole impegno umano, tempi lunghi e una spiccata sensibilità artistica. Proprio per questo, lo sviluppo di tecniche automatizzate capaci di imitare, almeno in parte, il processo decisionale umano nella scelta dei colori rappresenta una sfida significativa nel campo dell'elaborazione delle immagini. 
<br><br>
A partire dalla domanda: <i>è possibile “ridare vita” a vecchie fotografie in bianco e nero grazie all'apprendimento automatico profondo?</i>, questo progetto si propone di esplorare e confrontare diverse tecniche di <b>deep learning</b> applicate alla colorazione automatica, con l'obiettivo di ottenere risultati visivamente credibili e coerenti per l'occhio umano.
<br><br>
Nello specifico, verranno sviluppati e messi a confronto <b>modelli CNN</b> (Reti Neurali Convoluzionali) con leggere differenze architetturali, affiancati da un <b>modello GAN</b> (Generative Adversarial Network) che rappresenta un approccio distinto e potente per questo tipo di inferenza.

 
# Dataset utilizzato
<p align="justify">È stato utilizzato il dataset <i>"Landscape color and grayscale images"</i>, scaricabile da questo <a href="https://www.kaggle.com/datasets/theblackmamba31/landscape-image-colorization/data">link</a>. Il dataset non è incluso nel repository; le operazioni di scaricamento, upload e gestione dei dati sono gestite in modo autonomo in un notebook dedicato, permettendo il caricamento su Drive e la sua corretta importazione e riutilizzo negli altri notebook del progetto</p>

# Installazione
## **Requisiti:**   
L'unico requisito fondamentale per l'esecuzione del progetto è la disponibilità di un <a href="https://drive.google.com/">Account Google</a> attivo. Questo è indispensabile per poter utilizzare Google Colab ed eseguire i notebook, consentendo l'accesso e la corretta archiviazione su *Google Drive* di tutti gli asset necessari, inclusi:

- Il dataset originale e i relativi split utilizzati per il training dei modelli.

- I risultati intermedi e finali del tuning e dell'addestramento dei modelli.   


# Struttura del progetto
Il progetto è stato organizzato in più notebooks in base ai modelli e alle diverse operazioni necessarie:

<div align="center">

| Nome File | Descrizione |
| :---: | :---: |
| `dataset_managment.ipynb` | Automatizza il download, l'upload su Google Drive e lo split del dataset nelle codifiche RGB e LAB, preparando i dati per l'addestramento dei modelli di colorazione. |
| `AE.ipynb` | Implementazione, analisi e confronto di quattro configurazioni distinte di Autoencoder, addestrate separatamente utilizzando le due diverse codifiche cromatiche adottate nel caso di studio: RGB e LAB. |
| `GAN.ipynb`| Implementazione e addestramento della variante cGAN Pix2Pix (Generative Adversarial Network) utilizzando la codifica colore del caso di studio, per un confronto generativo con gli Autoencoder. |

</div>

# Autori
<a href="https://github.com/LukeMedTkd/Image-Colorization/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=LukeMedTkd/Image-Colorization" />
</a>  
<br></br>

[@LukeMedTkd](https://github.com/LukeMedTkd)  
[@apellegrini4](https://github.com/apellegrini4)

