Home_EnergIA 
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
