# Ecco qui! alcune istruzioni per utilizzare l'applicazione e tutte le cose necessarie.

## Tools richiesti per il progetto
- Per utilizzare questa applicazione è necessario avere Java JDK 11 oppure anche le versioni successive. Di seguito c'è il link del sito dal quale si può scaricare questa versione: https://www.oracle.com/java/technologies/downloads/#java11;
- Eclipse IDE che serve per implementare il progetto. Di seguito c'è il link del sito dal quale si può scaricare: https://www.eclipse.org/downloads/;
- Infine, abbiamo bisogno di MySql Server and Mysql workbench. NOTA: cambiare la password da "root" ad una nuova password a proria scelta. La password va cambiata anche su Util.java che si trova nella cartella util.

### Tomcat WebServer setup
- Un passaggio fondamentale è Tomcat WebServer setup, che ci serve per utilizzare la nostra applicazione. Di seguito ci sono tutti i passaggi per completare l'installazione.
1. Open Eclipse
2. Go to Window -> Preferences -> Server -> Runtime Environments -> Add... -> Apache -> Apache Tomcat v10.0 -> Click 'Create new a local server' -> Next
3. Click 'Download and install...', that should install the latest stable version (currently 10.0.13) -> Choose your favourite folder for Tomcat installation
4. Since now you can see your installed web servers in the Eclipse 'Server' tab, if it is not displayed by default, you can enable it by going to Window -> Show view -> Server

#### MySQL
- Scaricare MySQL Workbench;
- codice di accesso: #Progetto10

##### L'ultimo passaggio
- Aprire ecplisce e eseguire questi ultimi passaggi:
- File --> import --> Git -> Projects from Git --> Clone URI --> inserire il link di seguito!
- Link GitHub: https://github.com/Borhanmohammed/SecurityProject.git.