# Kubernetes

## 16. Quali sono le principali figate di kubernetes? - parti da un caso d'uso

Kubernetes è super utile per la gestione di microservizi e applicazioni containerizzate. Le features principali sono:


- Automatizza vari processi manuali: ad esempio controllare quale server ospiterà il container, come verrà avviato ecc.
- Interagisce con più gruppi di container: è in grado di gestire contemporaneamente più cluster
- Fornisce servizi aggiuntivi: oltre a gestire i container, Kubernetes offre servizi di networking, storage e security
- Self-monitoring: controlla costantemente lo stato dei nodi e dei container (auto-monitoraggio)
- Autoscaling orizzontale: permette una scalabilità delle risorse non solo verticalmente ma anche orizzontalmente, in modo semplice ed immediato
- Orchestrazione storage: monta e aggiunge il sistema di storage selezionato per eseguire le applicazioni
- Automatizza rollout e rollback: se in seguito all’esecuzione di modifiche qualcosa non dovesse funzionare, ritorna automaticamente alle versioni precedenti
- Bilanciamento dei container: sa sempre dove inserire i container, calcolando qual è il “posto ideale”
- Eseguibile dappertutto: è uno strumento open source che ti dà la libertà di sfruttare indistintamente infrastrutture on-premise, cloud pubblico o ibrido, lasciandoti spostare i carichi di lavoro dove vuoi

## 17. Quali sono i pro e i contro di kubernetes?
Vantaggi:

- Controllare e automatizzare i deployment e gli aggiornamenti
- Risparmiare ottimizzando le risorse infrastrutturali grazie all’utilizzo dell’hardware in modo più efficiente
- Orchestrare container su host multipli
- Risolvere problemi comuni dovuti alla proliferazione dei container organizzandoli in “pod” 
- Scalare in tempo reale risorse e applicazioni
- Testare e correggere automaticamente le applicazioni
- Varietà di opzioni di archiviazione, comprese SAN locali e cloud pubblici.


Svantaggi:

- Migrazioni più complesse.
- Complesso processo di installazione e configurazione.
- Incompatibile con gli strumenti Docker esistenti.
- L'implementazione di un cluster manuale è complicata.




  ----
FONTI:
- https://www.criticalcase.com/it/blog/kubernetes-feature-e-vantaggi.html
- https://blog.desdelinux.net/it/Docker-contro-Kubernetes/
