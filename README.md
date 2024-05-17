SISTEMA DI RICONOSCIMENTO ELETTRODOMESTICO 

Questo progetto è il risultato di una competizione tra gli studenti dell'Università Campus Bio-Medico di Roma (UCBM), Istituto di Ingegneria dei Sistemi Informatici (ISI), in collaborazione con Engineering Ingegneria Informatica S.p.A. L'obiettivo della competizione era sviluppare un sistema in grado di riconoscere, attraverso l'analisi dei dati relativi al consumo energetico come wattaggio, armoniche, potenza attiva e reattiva, tre tipologie di elettrodomestici: forno, lavastoviglie e lavatrice.

Metodologia
Il progetto segue un approccio strutturato per affrontare questa sfida:

Pre-elaborazione dei Dati: I dati grezzi vengono puliti e normalizzati per garantire l'uniformità necessaria per le analisi successive.
Selezione delle Caratteristiche tramite PCA: Utilizziamo l'Analisi delle Componenti Principali (PCA) per ridurre la dimensionalità dei dati e selezionare le caratteristiche più significative che influenzano l'identificazione degli elettrodomestici.
Sviluppo del Modello SVM: La macchina a vettori di supporto (SVM) è stata scelta per classificare gli elettrodomestici in base alle caratteristiche selezionate. La SVM è stata addestrata e testata con un set di dati che comprende varie metriche di consumo energetico.
Risultati
I risultati ottenuti sono stati eccellenti, dimostrando l'efficacia del sistema nel riconoscere con precisione i tre elettrodomestici basati sui loro profili di consumo energetico. La combinazione di PCA per la selezione delle caratteristiche e SVM per la classificazione ha dimostrato di essere una strategia robusta per questo tipo di analisi.

Conclusione
Il successo di questo progetto evidenzia il potenziale delle tecniche di machine learning applicate al settore dell'energia elettrica e apre la strada a future ricerche e sviluppi in questo campo emergente.
















README

Questo pacchetto consente di utilizzare una macchina a vettori di supporto (SVM) per riconoscere gli elettrodomestici attraverso l'analisi dei dati. Segui queste istruzioni per installare e testare il pacchetto sul tuo sistema.
Prerequisiti
Assicurati di avere Python installato sul tuo sistema. Puoi scaricarlo da qui. Dovrai anche installare i seguenti pacchetti Python:
•	numpy
•	scikit-learn
•	matplotlib
Installazione
1.	Scarica il pacchetto:
bash
Copia codice
git clone https://github.com/OrlandoMae/Home_EnergIA
2.	Naviga nella directory del progetto:
bash
Copia codice
cd nome-repository 
3.	Installa i requisiti necessari:
bash
Copia codice
pip install -r requirements.txt 
Uso
Per avviare il test e vedere le discriminazioni effettuate dalla SVM:
1.	Decomprimi il file ZIP contenente i dati:
bash
Copia codice
unzip Test.zip 
2.	Esegui lo script di test:
bash
Copia codice
python test_code.py 
Lo script test_code.py elaborerà i dati utilizzando la SVM per riconoscere i vari elettrodomestici e visualizzerà i risultati delle discriminazioni effettuate.
Supporto
Per domande o supporto, apri un'issue su questo repository GitHub o contatta il mantainer tramite e-mail all'indirizzo ing_orlando_mae@proton.me
Licenza
Questo progetto è rilasciato sotto la Licenza MIT. Consulta il file LICENSE per maggiori dettagli.
