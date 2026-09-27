# TryHackMe: File and Hash Threat Intel

Questo repository contiene gli appunti, le procedure e la documentazione tecnica relativa al completamento della room **File and Hash Threat Intel** su TryHackMe. Il laboratorio si concentra sulle procedure di base di Malware Analysis e sull'uso della Threat Intelligence in ambito Blue Team / SOC.

## 🎯 Obiettivi del Progetto
- Identificazione e calcolo degli Hash crittografici (MD5, SHA256) di file sospetti.
- Analisi degli Indicatori di Compromissione (IoC) in scenari simulati di Incident Response.
- Interrogazione di database di Threat Intelligence (es. VirusTotal) per l'analisi di minacce informatiche.
- Triage iniziale per la categorizzazione di malware e artefatti malevoli.

## 🛠️ Strumenti e Piattaforme Utilizzate
- Terminale Linux (per l'estrazione degli hash)
- Piattaforme di Threat Intelligence e OSINT
- TryHackMe Lab Environment

## 📋 Note Tecniche e Procedure
1. **Identificazione della minaccia:** Isolamento dell'artefatto malevolo all'interno dell'ambiente sicuro.
2. **Generazione Hash:** Estrazione dell'impronta del file per evitare l'esecuzione accidentale durante l'analisi.
3. **Analisi e Reportistica:** Verifica della firma contro i database globali per identificare pattern di attacco e metodologie utilizzate dagli attaccanti.
