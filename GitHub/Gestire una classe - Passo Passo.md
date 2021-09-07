# Gestire una classe - Passo Passo
## Schema generale
1. Una **organization** raccoglie una serie di **classrooms**, contiene i **repository** pubblici da condividere con gli studenti (*starter code*, *tutorial*, ecc.). NB conterrà anche tutti i **repository** individuali degli studenti provenienti dall'accettazione degli **assignements**
2. Una **classroom** raccoglie una serie di **assignements** e il **rooster** degli allievi
3. Ogni **assignment** genera un **repository** per allievo nella **organization**
4. Le **pull requests** consentono al docente di revisionare il codice e inviare feedback puntuali all'allievo

## Come lavora lo studente
1. Crea il proprio account GitHub
2. Ogni volta che deve iniziare un nuovo **assignement** riceve un link dall'insegnante (da Moodle, via mail, ecc.). Il link di avvio dell'**assignement** è lo stesso per tutta la classe.
3. Quando visita li link, accede al proprio account GitHub e accetta l'**assignement**. Viene creato un **repository** specifico per l'allievo
4. L'allievo trova nel proprio **repository** l'eventuale codice di partenza e può modificare o aggiungere file a piacere
5. Da questo momento l'allievo può: clonare il codice per lavorarci in locale, eseguire l'accesso a GitHub, eseguire commit e push per salvare le modifiche nel **repository**. L'insegnante che ha accesso alla **organization** vede tutte le modifiche dell'allievo e le può commentare con le **pull requests**
Si può lavorare sul codice direttamente da Visual Studio (tutorial https://youtu.be/GCZ9x3yqkyc), Visual Studio Code oppure da un client Git qualsiasi (per esempio GitHub Desktop)

## Come organizzare una classe
1. Creare una **organization** per ogni materia di una determinata classe di un determinato anno, utilizzando i prefissi per tenere tutto ordinato, per esempio ItisMajo-2021-3DINFO-Informatica oppure ItisMajo-2021-3DINFO-TPSIT
2. Creare una **classroom** per ogni argomento della materia da agganciare alla **organization** anche qui usando un criterio di suddivisione basata sui prefissi, per esempio info-console-io oppure tele-web-html-basilare
3. Inserire un elenco di identificativi (cognome.nome oppure email) nel **rooster** della **classroom** per distinguere gli allievi
4. Aggiungere alla **organization** i **repository** template da usare come base per gli **assignements**

## Aggiungere uno studente al **rooster** (con il primo assignment)
1. L'insegnante crea un **assignment** e ne condivide il link con lo studente (mail o Moodle)
2. L'allievo visita il link ed accetta l'**assignment** dando il consenso all'accesso con il proprio **account GitHub**. Gli viene chiesto di sceglere il proprio identificativo nella **classroom**
3. Viene creato un **repository**, specifico per quell'allievo, nella **organization** collegata alla **classroom**
4. 

## Revisionare i lavori consegnati
Se la revisione non riguarda codice, la revisione puà essere fatta tutta nel browser su github.com. Altrimenti si hanno varie scelte:
1. Usare l'applicazione Classroom Assistant per scaricare tutti i **repository** di un **assignement** (https://github.com/education/classroom-assistant/releases)
2. Usare l'applicazione GitHub Desktop, per navigare nel proprio account GitHub e selezionare il **repository** da una lista (https://desktop.github.com/)
3. Usare Visual Studio o Visual Studio Code, clonare un **repository** alla volta, compilare (se serve) e correggere
