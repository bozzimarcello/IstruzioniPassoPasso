# Gestire una classe - Passo Passo
## Schema generale
1. Una **organization** raccoglie una serie di **classrooms**, contiene i **repository** pubblici da condividere con gli studenti (*starter code*, *tutorial*, ecc.). NB conterrà tutti i **repository** individuali degli studenti provenienti dall'accettazione degli **assignements**
2. Una **classroom** raccoglie una serie di **assignements** e il **rooster** degli allievi
3. Ogni **assignment** genera un **repository** per allievo nella **organization**
4. Le **pull requests** consentono al docente di revisionare il codice e inviare feedback puntuali all'allievo

## Come organizzare una classe
1. Creare una **organization** per ogni materia di una determinata classe di un determinato anno, utilizzando i prefissi per tenere tutto ordinato, per esempio ItisMajo-2021-3DINFO-Informatica oppure ItisMajo-2021-3DINFO-TPSIT
2. Creare una **classroom** per ogni argomento della materia da agganciare alla **organization** anche qui usando un criterio di suddivisione basata sui prefissi, per esempio info-console-io oppure tele-web-html-basilare
3. Inserire un elenco di identificativi (cognome.nome oppure email) nel **rooster** della **classroom** per distinguere gli allievi
4. Aggiungere alla **organization** i **repository** template da usare come base per gli **assignements**

## Aggiungere uno studente al **rooster** (con il primo assignment)
1. L'insegnante crea un **assignment** e ne condivide il link con lo studente (mail o Moodle)
2. L'allievo visita il link ed accetta l'**assignment** dando il consenso all'accesso con il proprio **account GitHub**. Gli viene chiesto di sceglere il proprio identificativo nella **classroom**
3. Viene creato un **repository**, specifico per quell'allievo, nella **organization** collegata alla **classroom**
4. L'allievo trova nel **repository** l'eventuale codice di partenza e può modificare o aggiungere file a piacere
5. Clonare il codice per lavorarci in locale, eseguire commit e push per salvare le modifiche nel **repository**

## Revisionare i lavori consegnati
Se la revisione non riguarda codice, la revisione puà essere fatta tutta nel browser su github.com. Altrimenti si hanno varie scelte:
1. Usare l'applicazione Classroom Assistant per scaricare tutti i **repository** di un **assignement** (https://github.com/education/classroom-assistant/releases)
2. Usare Visual Studio o Visual Studio Code, clonare un **repository** alla volta e correggere
