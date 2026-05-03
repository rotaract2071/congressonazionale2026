# Context
L'app tableau servirà agli invitati dell'evento Congresso Nazionale Siena 2026 ad individuare il proprio tavolo.
User story:
- l'invitato inquadra col telefono un QR code, che rimanda all'app
- l'app si apre e chiede all'utente di inserire nome e cognome in una barra di ricerca
- mentre l'utente scrive, l'app filtra in realtime i commensali, fino a restare con quello desiderato
- il record filtrato deve riportare
  - nome e cognome della persona
  - nome del tavolo (che dev'essere cliccabile)
- al click sul nome del tavolo, l'utente può vedere tutti gli altri commensali seduti con lui

# Implementation notes
- La webapp si deve connettere a un Google Spreadsheet che contiene tutte le informazioni (è il nostro DB/backend)
- Il look 'n' feel dev'essere moderno, sobrio ed elegante.
- L'app sarà interamente implementats in tableau/index.html
- Usa tag HTML semantici quando opportuno
