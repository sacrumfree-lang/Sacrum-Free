# Sacrum
Sacrum - I Tesori d'Italia
## SACRUM MVP Complete
- App mobile Expo per catalogare luoghi sacri italiani (fede, arte, storia, cultura, cammini) con palette editoriale (pergamena/bordeaux/oro/blu notte)
- Backend FastAPI + MongoDB: `/api/places` (con filtri q, regione), `/api/regions`, `/api/reports`, `/api/newsletter`, `/api/stats`, `/api/alerts`, `/api/export/{table}`; 2 luoghi seed (Abbazia di Farfa, Eremo delle Carceri)
- Frontend expo-router con 4 tab (Home, Preferiti, Segnala, Admin) + schermata dettaglio luogo con cover immersiva; preferiti/visitati persistenti via AsyncStorage
- Area Admin con dashboard statistiche, avvisi scadenza editoriale, toggle sostenibilità (disattivi di default) ed export OpenData JSON
- PayPal: NON implementato (richiesta ritirata dall'utente prima di ricevere le credenziali)
- Testing agent: 13/13 test backend pass, tutti i flussi frontend verificati

Note:
- Stai lavorando in un ambiente di dev/preview.
- Quando sei soddisfatto puoi pubblicare l'app in produzione e generare build iOS/Android: Click su Publish (in alto a destra) → Deploy your app → Generate iOS and Android builds.
- L'anteprima nel browser impiega 20-30 secondi per aggiornarsi.
- Per testare sul telefono, scansiona il QR code accanto al pannello di anteprima con l'app Expo Go.
- Funzioni native (notifiche, audio, camera) si testano solo dopo aver generato una build reale.

Next Action Items: (opzionale) aggiungere altri luoghi seed regionali, caricare font custom Playfair Display/Satoshi con expo-font, integrare mappa geografica dei luoghi, riattivare PayPal quando avrai le credenziali sandbox.
Action: finish
Observation: ## SACRUM MVP Complete
- App mobile Expo per catalogare luoghi sacri italiani (fede, arte, storia, cultura, cammini) con palette editoriale (pergamena/bordeaux/oro/blu notte)
- Backend FastAPI + MongoDB: `/api/places` (con filtri q, regione), `/api/regions`, `/api/reports`, `/api/newsletter`, `/api/stats`, `/api/alerts`, `/api/export/{table}`; 2 luoghi seed (Abbazia di Farfa, Eremo delle Carceri)
- Frontend expo-router con 4 tab (Home, Preferiti, Segnala, Admin) + schermata dettaglio luogo con cover immersiva; preferiti/visitati persistenti via AsyncStorage
- Area Admin con dashboard statistiche, avvisi scadenza editoriale, toggle sostenibilità (disattivi di default) ed export OpenData JSON
- PayPal: NON implementato (richiesta ritirata dall'utente prima di ricevere le credenziali)
- Testing agent: 13/13 test backend pass, tutti i flussi frontend verificati

Note:
- Stai lavorando in un ambiente di dev/preview.
- Quando sei soddisfatto puoi pubblicare l'app in produzione e generare build iOS/Android: Click su Publish (in alto a destra) → Deploy your app → Generate iOS and Android builds.
- L'anteprima nel browser impiega 20-30 secondi per aggiornarsi.
- Per testare sul telefono, scansiona il QR code accanto al pannello di anteprima con l'app Expo Go.
- Funzioni native (notifiche, audio, camera) si testano solo dopo aver generato una build reale.

Next Action Items: (opzionale) aggiungere altri luoghi seed regionali, caricare font custom Playfair Display/Satoshi con expo-font, integrare mappa geografica dei luoghi, riattivare PayPal quando avrai le credenziali sandbox.
