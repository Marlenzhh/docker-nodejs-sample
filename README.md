# Aufgabe 2. README.md


### **Aufgabenstellung:**

1. **Repository clonen:**
   - Zuerst muss man den Speicherort wählen. In meinem Fall währe es der Ordner **Projects**. Im Terminal schreibt man dann 
   **cd ~/projects** um den Speicherort anzuwählen.
   - Danach muss man das Repository mit **git clone** *URL von Repository* auf den Computer clonen. 

2. **Installation der notwendigen Pakete:**
   - Pakete werden automatisch in Docfilen installiert. 
   - man braucht folgendes:
     - Docker Engine
     - Docker CLI 
     - Docker Compose
     - WSL2 Integration
   - sichergehen ob alles stimmt:
      - docker --version
      - docker compose version
      - java -version
      - mvn -v
      - git --version


3. **Docker-Konfiguration und -Installation:**
   - Docker herunterladen
   - PC neustarten
   -Docker testen mit Terminal [docker run hello-world]


4. **Starten der Applikation in einem Docker-Container:**
   - Docker auf Desktop öffnen.
   - Warten bis wann es grün (aktiviert) ist.
   - Prüfen ob Docerfile vorhanden ist. 
   - Docker image in Terminal öffnen
   - Container starten
   - Container stoppen und evtl. löschen