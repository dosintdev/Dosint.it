WHAT DOES DOSINT DO?

DOSINT is an OSINT (Open Source Intelligence) aggregation and automation platform. Instead of forcing you to look up data across dozens of different websites manually, DOSINT centralizes the workflow: you enter a single starting point (called an "indicator"), and the platform instantly prepares all the necessary links and analyses.

SPECIFICALLY, DOSINT DOES THE FOLLOWING:

1. DOMAIN RECON & IP INTELLIGENCE
- Gathers domain registration details (WHOIS/RDAP) and historical website archives (Wayback Machine).
- Discovers associated subdomains by parsing public Certificate Transparency logs.
- Checks the reputation and exposure of an IP address or domain through third-party platforms like Shodan and VirusTotal (without ever directly scanning or probing the target).

2. DISCORD ACCOUNT TRACKING & ANALYSIS
- Queries the official public Discord API using a 17-20 digit User ID.
- Displays current public profile fields (username, display name, avatar, banner, badges, creation date).
- Automatically saves historical "snapshots": if the user changes their name or avatar over time, DOSINT accumulates this history so you can track identity changes.
- Resolves server invite links to extract creation dates, member counts, and online user metrics without joining the server.

3. IMAGE ANALYSIS & METADATA FORENSICS
- Provides one-click reverse image searching across Google Lens, Yandex, TinEye, and Bing.
- Reads hidden metadata (EXIF) from local images entirely within your browser, revealing camera models, software, and GPS location coordinates.
- Runs Error-Level Analysis (ELA), a visual tool that highlights differences in compression levels to spot edited or manipulated areas in a photo.

4. USERNAME, EMAIL, AND PHONE LOOKUPS
- Checks if a specific username exists across various public network profiles (GitHub, Reddit, Telegram, YouTube, etc.).
- Normalizes and analyzes phone numbers (E.164 format) and prepares public search engine queries for them.
- Verifies if an email address is linked to a public Gravatar profile, revealing associated avatars and connected accounts safely by hashing the email address locally first.

5. ANALYST UTILITIES
- Indicator Extractor: Automatically pulls and categorizes URLs, domains, IPs, emails, and cryptographic hashes from raw, unformatted text.
- URL Expander: Follows shortened or suspicious links hop-by-hop, exposing the final destination and redirect chains safely without executing code in your browser.
- Email Header Analyzer: Parses raw email source code locally to trace server routing and verify potential phishing or spoofing attempts.
- Chronolocation (Sun position): Calculates solar positioning and shadow angles for any given coordinate and UTC time, helping verify if a photo matches its claimed timeframe.

WHAT DOSINT **DOES NOT** DO:
- It DOES NOT hack private accounts or bypass access controls/passwords.
- It DOES NOT query private or illegal databases.
- It DOES NOT scan, probe, or attack targets; it exclusively queries public resources and open APIs that have already cataloged the data.

-----------------

COSA FA DOSINT?

DOSINT è una piattaforma di aggregazione e automazione per l'OSINT (Open Source Intelligence). Invece di costringerti a cercare manualmente un dato su decine di siti web differenti, DOSINT centralizza il lavoro: inserisci un singolo dato di partenza (chiamato "indicatore") e la piattaforma prepara all'istante i collegamenti e le analisi necessarie.

CONCRETAMENTE, DOSINT FA LE SEGUENTI COSE:

1. INVESTIGAZIONE SU DOMINI E INDIRIZZI IP (Domain Recon & IP Intelligence)
- Raccoglie i dati di registrazione dei siti web (WHOIS/RDAP) e la cronologia storica (Wayback Machine).
- Trova i sottodomini associati tramite i registri dei certificati di sicurezza (Certificate Transparency).
- Verifica la reputazione e i rischi di sicurezza di un IP o dominio consultando database come Shodan e VirusTotal (senza mai scansionare direttamente il bersaglio).

2. TRACCIAMENTO E ANALISI DI ACCOUNT DISCORD
- Interroga l'API ufficiale pubblica di Discord tramite un ID utente (composto da 17-20 cifre).
- Mostra il profilo pubblico aggiornato (nome, avatar, banner, badge, data di creazione).
- Memorizza automaticamente degli "snapshot" (istantanee): se l'utente cambia nome o avatar nel tempo, DOSINT accumula la cronologia dei passati cambi di identità.
- Analizza i link di invito dei server per scoprirne la data di creazione, il numero di membri e i canali senza dover entrare nel server.

3. ANALISI DI IMMAGINI E METADATI (Forensics Leggera)
- Permette di avviare con un click la ricerca inversa di un'immagine su Google Lens, Yandex, TinEye e Bing.
- Legge i dati nascosti (EXIF) delle foto caricate nel browser, mostrando dettagli sulla fotocamera, il software usato e le coordinate GPS di dove è stata scattata.
- Esegue la Error-Level Analysis (ELA), uno strumento visivo che evidenzia se parti di un'immagine sono state modificate o ritoccate con programmi di grafica.

4. RICERCA DI UTENTI, TELEFONI ED E-MAIL
- Controlla se un nome utente (username) è registrato su decine di piattaforme diverse (GitHub, Reddit, Telegram, YouTube, ecc.).
- Analizza la struttura e il prefisso dei numeri di telefono (formato E.164) e genera link per cercarli sul web.
- Verifica se un'e-mail possiede un profilo Gravatar associato, mostrando l'avatar o altri account collegati senza rivelare l'e-mail ai servizi esterni (utilizza un sistema di hashing sicuro).

5. STRUMENTI TECNICI PER ANALISTI
- Estrattore di indicatori: Estrae automaticamente e separa indirizzi IP, e-mail, domini e hash da un blocco di testo grezzo.
- Espansore di URL: Segue i link accorciati o sospetti passo dopo passo, mostrando la destinazione finale e la catena di reindirizzamenti in sicurezza, senza aprire il sito nel tuo browser.
- Analizzatore di intestazioni e-mail (Email Headers): Analizza il codice sorgente di un'e-mail per tracciare il percorso dei server e scoprire se è contraffatta.
- Cronolocalizzazione (Sun position): Calcola la posizione del sole e la direzione delle ombre inserendo una coordinata e un orario UTC, per capire se una foto è stata scattata nel momento dichiarato.

COSA **NON** FA DOSINT (LIMITI IMPORTANTI):
- NON buca profili privati e non viola sistemi informatici o password.
- NON accede a database privati o illegali.
- NON effettua attacchi informatici o scansioni invasive contro i bersagli; interroga solo fonti e archivi che hanno già indicizzato quel dato pubblicamente.


https://dosint.it ! Official
