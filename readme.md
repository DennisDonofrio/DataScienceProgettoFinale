# Analisi Spotify Tracks Dataset

Questo repository contiene un'analisi del **Spotify Tracks Dataset**, un dataset che raccoglie migliaia di brani Spotify con relative caratteristiche audio e metadati.  
Il dataset include informazioni estratte tramite le API di Spotify ed è particolarmente adatto per progetti di:

- Data Analysis
- Data Visualization
- Machine Learning
- Music Recommendation Systems

## Dataset

Link al dataset Kaggle:  
https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset

## Informazioni sul Dataset

Il dataset contiene:

- Migliaia di tracce musicali
- Oltre 125 generi musicali
- Caratteristiche audio numeriche dei brani
- Informazioni su artisti e popolarità

Formato del dataset: **CSV**

## Colonne Interessanti

Alcune delle colonne principali presenti nel dataset:

| Colonna            | Descrizione                              |
| ------------------ | ---------------------------------------- |
| `track_name`       | Nome del brano                           |
| `artists`          | Artista/i del brano                      |
| `track_genre`      | Genere musicale                          |
| `popularity`       | Popolarità del brano (0-100)             |
| `danceability`     | Quanto il brano è adatto al ballo        |
| `energy`           | Livello di energia/intensità             |
| `valence`          | Positività percepita del brano           |
| `tempo`            | BPM del brano                            |
| `acousticness`     | Probabilità che il brano sia acustico    |
| `instrumentalness` | Probabilità che il brano sia strumentale |

## Analisi Previste

L'obiettivo del progetto è analizzare le relazioni tra le caratteristiche audio dei brani e la loro popolarità.

Alcune analisi previste:

- Relazione tra `danceability` e `popularity`
- Confronto delle caratteristiche audio tra diversi generi musicali
- Distribuzione della popolarità dei brani
- Clustering dei brani in base alle caratteristiche audio
- Visualizzazioni tramite grafici e heatmap

## Tecnologie Utilizzate

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Possibili Grafici

Esempi di grafici che verranno realizzati:

- Istogramma della popolarità
- Scatter plot tra danceability e popularity
- Boxplot dei generi musicali
- Heatmap delle correlazioni tra feature audio

## Licenza

Il dataset è disponibile pubblicamente su Kaggle per scopi educativi e di ricerca.  
Fare riferimento alla pagina originale del dataset per ulteriori dettagli sulla licenza.