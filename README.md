# Installation des Projekts
## clonen eines Repositorys


1. Navigieren Sie auf GitHub zur Hauptseite des Repositorys.

2. Klicke oberhalb der Liste der Dateien auf

3. Kopiere die URL für das Repository.
    
    Um ein Repository über HTTPS zu klonen, klicke unter „HTTPS“. Wenn du das Repository mithilfe eines SSH-Schlüssels klonen möchtest, einschließlich eines Zertifikats, das von der SSH-Zertifizierungsstelle deiner Organisation ausgestellt wurde, wähle SSH und dann
    Um ein Repository über die GitHub CLI zu klonen, klicke auf GitHub CLI und dann auf

4. Öffne Git Bash.

5. Ändere das aktuelle Arbeitsverzeichnis zum Speicherort, in dem Du das geklonte Verzeichnis haben willst.

6. Gib git clone ein, und füge dann die zuvor kopierte URL ein.

    git clone 'https://github.com/YOUR-USERNAME/YOUR-REPOSITORY'

    Drücke die EINGABETASTE, um den lokalen Klon zu erstellen.
>quelle: github.com
## Notwendiges packet package.json

Ohne dieses Package funktioniert die ToDo liste nicht
- **`scripts`**:
  - **`prettify`**: Formatiert alle `.js`-Dateien im Projekt.
  - **`test`**: Führt Tests im Projekt mit Jest aus.
  - **`dev`**: Startet den Server im Entwicklungsmodus mit automatischem Neustart und Debugging.

- **`dependencies`**:
  - **`express`**: Framework für die Erstellung von Webanwendungen und APIs.
  - **`pg`**: PostgreSQL-Client zur Kommunikation mit einer PostgreSQL-Datenbank.
  - **`sqlite3`**: SQLite-Datenbank-Modul für eine eingebettete Datenbank.
  - **`uuid`**: Generiert eindeutige IDs.
  - **`wait-port`**: Wartet, bis ein bestimmter Port verfügbar ist (z. B. nützlich beim Start von Diensten).

- **`resolutions`**:
  - **`ansi-regex`**: Erzwingt die Nutzung einer bestimmten Version von `ansi-regex` (5.0.1), um potenzielle Sicherheitsprobleme oder Kompatibilitätsprobleme zu vermeiden.

- **`prettier`**:
  - **`trailingComma`**: Fügt bei Listen ein Komma am Ende hinzu.
  - **`tabWidth`**: Setzt die Tab-Breite auf 4 Leerzeichen.
  - **`useTabs`**: Verwendet Leerzeichen statt Tabs.
  - **`semi`**: Fügt Semikolons am Ende jeder Anweisung hinzu.
  - **`singleQuote`**: Verwendet einfache Anführungszeichen für Zeichenketten.

- **`devDependencies`**:
  - **`jest`**: Test-Framework für automatisierte Tests.
  - **`nodemon`**: Entwicklertool, das den Server automatisch neu startet bei Dateiänderungen.
  - **`prettier`**: Code-Formatter für einheitliche Formatierung.
  >Quelle: Chatgpt.com
## Docker-Konfiguration und -Installation
Die installation von Docker ist Ziemlich selbsterklärenden.
Man wählt auf dieser [Website](https://www.docker.com/get-started/) die Version aus die man herunterladen möchte und ladet die Setup datei herunter nach.
## Starten einer applikation in einem Dockercontainer
1. Den Dockercontainer starten und den Port überprüfen
2. Im browser auf localhost:3000 gehen und los kanns gehen

jetzt sollte die ToDo Liste erscheinen.