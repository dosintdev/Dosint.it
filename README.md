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
