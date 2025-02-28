# SmartNotes  
**E-Business Idee: SmartNotes**  

Studenten:
- Le Chau Anh Do  
- Quang Anh Nguyen  

---

## Aufbau unserer Website  

Unsere Website besteht insgesamt aus 7 Abschnitten:  
- Start  
- Unsere App
- Funktionen 
- Unsere Partner 
- Feedback
- Unsere Preise 
- Kontakt
- (Abschluss)

Die Website soll den Nutzern unsere App vorstellen. Wir übernehmen viele Inhalte aus unserer Präsentation und dem Lean Canvas, ergänzen aber auch noch weitere Inhalte, die uns sinnvoll erscheinen.  

---

## Aufbau der einzelnen Abschnitte  

### Start  
- Hier wird der Nutzer mit unserem Logo begrüßt.  
- Außerdem zeigen wir hier unsere Channels (iOS, Android, Windows, macOS), damit direkt ersichtlich ist, wo unsere App verfügbar ist.  

### Unsere App  
- Hier gibt es eine kurze Beschreibung der App.  
- Zusätzlich haben wir unsere Mockups, die wir mit Figma erstellt haben, damit sich Nutzer direkt ein Bild davon machen können.  

### Funktionen  
- Hier werden unsere Features und Vorteile erklärt.  
- Unsere Unique Value Proposition wird hier nochmal extra hervorgehoben.  

### Unsere Partner  
- Uns war es wichtig zu zeigen, dass wir mit Bildungseinrichtungen zusammenarbeiten.  
- Außerdem haben wir noch weitere realistische Partner ergänzt, die gut zu unserer App passen würden.  

### Feedback  
- Wir wollten hier unsere Persona "Tom Schmidt" einbauen, um die App aus Nutzersicht zu präsentieren.  
- Anstatt noch eine weitere Persona zu erstellen, haben wir uns entschieden, ein ausgedachtes Zitat vom Handelsblatt zu nutzen.  

### Unsere Preise  
- Hier zeigen wir unsere Preisstruktur bzw. Revenue Streams.

### Kontakt  
- Hier kann der Nutzer Kontakt mit uns aufnehmen, falls er Fragen hat oder Feedback geben möchte.  

### Abschluss 
- Wir haben hier noch einen Abschlussabschnitt eingefügt, um die Seite schön abzurunden.  
- Außerdem gibt es eine untere Leiste mit Impressum, AGB und Datenschutz.  

---
## Website lokal starten

### Installationen
1. Python installieren (https://www.python.org/downloads/)
2. VS Code installieren (https://code.visualstudio.com/)
3. Projekt abrufen:
   - Option 1: Ordner `smartnotes` abspeichern und in VS Code öffnen
   - Option 2: Repo von GitHub klonen (Git erforderlich: https://git-scm.com/downloads)

### Projekt in VS Code starten
1. Projektordner `smartnotes` in VS Code öffnen
2. Terminal öffnen: `Strg + Shift + P` → `Terminal: Create New Terminal`
3. Virtuelle Umgebung erstellen:
   ```sh
   python -m venv venv
   ```
   → Es sollte ein Ordner `/venv` erscheinen
4. Virtuelle Umgebung aktivieren:
     ```sh
     venv\Scripts\activate
     ```
   → Das Terminal sollte nun mit `(venv)` beginnen. Falls nicht, kann man die Seite nicht starten.
5. Python-Interpreter auswählen (optional, falls nötig):
   `Strg + Shift + P` → `Python: Select Interpreter` → `/venv` auswählen
6. Abhängigkeiten installieren:
   ```sh
   pip install -r requirements.txt
   ```
7. Flask-App  starten:
   - Danach die Anwendung starten:
     ```sh
     flask run
     ```
   → Die Website ist unter http://127.0.0.1:5000 erreichbar

Falls irgendwas nicht klappen sollte, können Sie uns einfach direkt kontaktieren oder unter: https://hwrberlin.github.io/fswd/python-vscode.html (Prof. Dr. Alexander Eck 2024) eine detailierte Anleitung für das VSC Setup finden.

---
## Quellen

Alle Quellen wurden zuletzt abgerufen am 28.02.2025

### Coding
- Die Website wurde mit Flask in Visual Studio Code erstellt.
  - Prof. Dr. Alexander Eck (2024): Wi-Inf-M09-F02 Full-Stack Web Development. <br>
    https://hwrberlin.github.io/fswd/
    
- Die HTML basiert hauptsächlich auf Bootstrap. Bootstrap bietet viele Vorlagen und Elemente, die wir verwenden konnten (z.B. NavBar, Carousel, Pricing Structure etc.)
  - GetBootstrap (2025): https://getbootstrap.com/
  - Web Dev Simplified (2022): Bootstrap 5 Crash Course. <br>
    https://www.youtube.com/watch?v=Jyvffr3aCp0&ab_channel=WebDevSimplified 
  - W3School (2025): https://www.w3schools.com/css/ 

### Bilder
- Alles Mockups wurden mit Figma erstellt.
  - Figma (2025): https://www.figma.com/ 

- Das Logo wurde AI generiert.
  - Iconik AI (2025): https://www.iconikai.com/

- Icons
   - Flaticon (2025): https://www.flaticon.com/ 

- Restliche Bilder
  - HWR Logo: https://www.facebook.com/officialHWRBerlin/
  - HTW Logo: https://www.kununu.com/de/hochschule-fuer-technik-und-wirtschaft-berlin
  - SimpleClub Logo: https://play.google.com/store/apps/details?id=com.simpleclub.android&hl=de
  - Coursera Logo: https://www.langoly.com/coursera-review/
  - Open Ai Logo: https://www.vecteezy.com/png/22227364-openai-chatgpt-logo-icon
  - Tom Schmidt: https://www.motortrend.com/features/celebrity-drive-justin-reiter-snowboarder/
  - Handelblatt Logo: https://www.facebook.com/handelsblatt/photos/a.445462238232/10157577862603233/?type=3

- Texte und Slogans wurden teilweise mit Hilfe von ChatGPT erstellt
 

  


