# Progetto-ML-De-Lellis-Foresi


# Abstract
Nell'ultimo ventennio le tecniche di Machine Learning hanno preso piede nella risoluzione di
molti task che precedentemente venivano risolti manualmente o tramite algoritmi verbosi e
spesso fallaci poichè richiedevano continui aggiornamenti. In questo progetto è stato scelto
di risolvere uno dei task sociali più gettonati nella vita di tutti i giorni, ovvero quello di
identificare il genere e l'età di un individuo attraverso delle immagini contenti volti. L'età e
il genere hanno un ruolo fondamentale nelle interazioni sociali, infatti il linguaggio utilizzato
da una persona spesso ci aiuta ad identificare il genere ma sopratutto l'età di quest'ultima.
La vera sfida infatti risiede nella risoluzione di questo task tramite l'utilizzo di un dataset
contenente immagini di volti. In questa relazione sono presentati i due modelli differenti
per la risoluzione dei task sopra elencati, i risultati ottenuti rispettivamente da entrambi i
modelli e infine il loro comportamento in modalità di inferenza. Abbiamo scelto di utilizzare
due modelli distinti poichè abbiamo notato come un unico modello non riuscisse a riportare
buoni risultati per entrambi i task.




Requisiti
------------

Questo progetto richiede alcuni requisiti :

- Un account Gmail per l'esecuzione del notebook o ambiente con Python installato.

- Una telecamera per pc per testare il sistema in fase di produzione(Inference Mode).

- Il file mmod_human_face_detector.dat per l'inizializzazione dei Pesi della CNN per riconoscere i volti.



Come utilizzare
------------
Per utilizzarlo bisogna aprire i file il notebook Data_preprocessing.ipynb, collegare il notebook al proprio drive personale e eseguire tutte le celle. 
Una volta eseguito tutto il codice avremo il nostro dataset nel drive e possiamo procedere con la fase di addestramento.
Successivamente possiamo scegliere di utilizzare uno tra i due sistemi a disposizione:

- Per Gender Detection è necessario aprire il notebook GenderDetectionProgettoML.ipynb
- Per Age Detection è necessario aprire il notebook AgeDetectionProgettoML.ipynb






Examples 
------------
A seguire sono riportati alcuni screen del nostro sistema in fase di produzione.


![Piervy_output_gender](https://user-images.githubusercontent.com/51997286/134568054-9462d1ab-06e0-49ae-8fa9-bf3f35ab81e7.png)
![Gradilone_output_gender](https://user-images.githubusercontent.com/51997286/134568058-c183dfe3-9999-4fe5-8ee8-d8e58fa1a802.png)
![donna_output_gender](https://user-images.githubusercontent.com/51997286/134568059-c92605df-6de9-4b4b-99a3-cbd3c074bf44.png)
![Francesco_output_gender](https://user-images.githubusercontent.com/51997286/134568062-20b6d48b-a1f2-4ffd-a75b-b43820470391.png)





Maintainers
------------
- Pier Vincenzo De Lellis
- Francesco Foresi
