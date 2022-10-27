### Inizializzazione come rete IBFT 2.0
1. Copiare il Network Setup, il file ibft2Config.json ed il file configuration.toml nella cartella
2. Eseguire lo script di Network Setup insieme al numero di nodi da creare
3. copiare il genesis.json dalla directory NetworkFiles alla directory dove si trovano i nodi
4. ATTENZIONE! Aprire il genesis file e copiare nella sezione alloc il codice necessario ad aggiungere i contratti di permissioning
5. Andare in ognuno dei nodi e lanciare l'esegubile ConfigNode{n}.sh per ognuno di essi
6. Assicurarsi che i nodi si vedano effettivamente trovandosi come peers
6. Inizializzare la web-app del permissioning tramite aggiungendo i nodi alla liste degli allowed.


### Migrazione a Permissioned Network
1. Stoppa tutti i nodi che sono in esecuzione
2. Esegui lo script PermissioningSetup.sh
3. Esegui nuovamente i nodi per ottenere la rete permissioned