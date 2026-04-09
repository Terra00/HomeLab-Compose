# HomeLab-Compose

Questa repository contiene i file di configurazione per i servizi del mio homelab personale. L'intera infrastruttura è basata su container.

## Contenuto

All'interno del progetto sono presenti diverse directory. Ognuna di esse isola le configurazioni necessarie per il deployment di un servizio specifico o di un gruppo di servizi correlati.

## Prerequisiti

Per poter utilizzare i file presenti in questa repository, la macchina host deve disporre di:

- Docker
- Docker Compose

## Deploy

Per avviare uno dei servizi, è sufficiente posizionarsi nella cartella corrispondente ed eseguire il comando di avvio standard di Docker Compose:

```bash
cd nome-cartella
docker compose up -d
```

## Configurazione

Le configurazioni fornite sono pensate per le mie esigenze. Prima del deployment, potrebbe essere necessario creare file .env dedicati per le variabili d'ambiente o adattare i percorsi dei volumi in base alla struttura del proprio server.
