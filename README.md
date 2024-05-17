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


-------------------------------------------------------------ENG--------------------------------------------------------------------------------------------


HOME APPLIANCE RECOGNITION SYSTEM

This project is the result of a competition among students from the Campus Bio-Medico University of Rome (UCBM), Institute of Computer Systems Engineering (ISI), in collaboration with Engineering Ingegneria Informatica S.p.A. The goal of the competition was to develop a system capable of recognizing, through the analysis of energy consumption data such as wattage, harmonics, active and reactive power, three types of appliances: ovens, dishwashers, and washing machines.

Methodology
The project follows a structured approach to address this challenge:

Data Preprocessing: Raw data is cleaned and normalized to ensure uniformity necessary for subsequent analysis.
Feature Selection via PCA: We use Principal Component Analysis (PCA) to reduce data dimensionality and select the most significant features that influence the identification of the appliances.
Development of SVM Model: The Support Vector Machine (SVM) was chosen to classify the appliances based on the selected features. The SVM was trained and tested with a dataset that includes various metrics of energy consumption.
Results
The results obtained were excellent, demonstrating the system's effectiveness in accurately recognizing the three appliances based on their energy consumption profiles. The combination of PCA for feature selection and SVM for classification proved to be a robust strategy for this type of analysis.

Conclusion
The success of this project highlights the potential of machine learning techniques applied to the electric power sector and paves the way for future research and developments in this emerging field.

README

This package allows the use of a Support Vector Machine (SVM) to recognize appliances through data analysis. Follow these instructions to install and test the package on your system.

Prerequisites
Ensure you have Python installed on your system. You can download it from here. You will also need to install the following Python packages:

numpy
scikit-learn
matplotlib
Installation

Download the package:
bash
Copia codice
git clone https://github.com/OrlandoMae/Home_EnergIA
Navigate to the project directory:
bash
Copia codice
cd nome-repository
Install the necessary requirements:
bash
Copia codice
pip install -r requirements.txt
Usage
To start testing and see the discrimination made by the SVM:

Unzip the ZIP file containing the data:
bash
Copia codice
unzip Test.zip
Run the test script:
bash
Copia codice
python test_code.py
The test_code.py script will process the data using the SVM to recognize various appliances and will display the results of the discriminations made.

Support
For questions or support, open an issue on this GitHub repository or contact the maintainer by email at ing_orlando_mae@proton.me

License
This project is released under the MIT License. See the LICENSE file for more details.






