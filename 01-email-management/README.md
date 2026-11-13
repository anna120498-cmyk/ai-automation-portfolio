# Assistente di gestione email e richieste

Progetto applicativo realizzato durante il Master in AI Automation
presso ProfessionAI.

## Obiettivo
Supportare la gestione di una casella condivisa, classificando
le richieste, assegnando priorità e segnalando i casi
che richiedono attenzione.

## Soluzione
Workflow sviluppato in n8n per:
- Leggere e classificare le email.
- Registrare gli eventi su Google Sheets.
- Inviare notifiche ai responsabili.
- Richiedere revisione umana nei casi incerti.
- Registrare gli esiti delle verifiche manuali.

Una parte significativa del workflow è stata ricostruita in Make.

## Strumenti
n8n, Make, Gmail, Google Sheets, Anthropic e Slack tramite MCP.

## Materiali
- 00_Riepilogo_progetto.docx: panoramica e guida ai materiali.
- 09_Documentazione_flusso.docx: funzionamento dei workflow.
- Assistente_Gestione_mail.json: workflow principale n8n.
- Chiusura_verifiche_umane.json: gestione degli esiti manuali.
- Assistente_Gestione_mail_Make.json: versione Make.
- dataset_email.xlsx: 40 email sintetiche con risultati attesi.
- Registro_email.xlsx: eventi registrati durante le prove.

Gli altri documenti approfondiscono progettazione, configurazione,
casi limite e confronto tra piattaforme.

## Controlli e limiti
Sono previsti gestione degli errori, controllo dei duplicati
e revisione umana. Il sistema non risponde automaticamente
ai clienti e non analizza il contenuto degli allegati.

La documentazione identifica verifiche tecniche ancora necessarie.
Accuratezza, capacità e risparmio di tempo richiedono
ulteriori misurazioni prima dell’uso operativo.
