# 19-Abgabe02-Schuele-Urlacher

## Aufgabenstellung
  ### Maven
   - [x] Builden Sie das Projekt mit Maven und erzeugen Sie somit eine Jar Datei.
   - [X] Welche Schritte werden beim erzeugen einer Jar Datei durchlaufen?

   ### Manuelle JAR Datei erzeugen
   - [x] Führen Sie die einzelnen Schritte manuell durch.
   - [x] Notieren Sie sich die einzelnen Schritte
   - [X] Wie sieht dabei der Aufwand bei der manuellen Durchführung aus?
    
   ### ANT
   - [x] Nachdem Sie manuell eine Jar Datei erzeugt haben, erstellen Sie eine build.xml Datei im Root Verzeichnis Ihres Projekts.
   - [x] Adaptieren Sie die Maven Projektstruktur auf eine Ant-Projektstruktur. Achten Sie dabei auf die unterschiedliche Ordnerstruktur dieser Projekstrukturen.
   - [x] Versionieren Sie initial das adaptierte Projekt.
   - [x] Versionieren Sie nach jedem erstellten Target.
   - [x] Erzeugen Sie ein Target nach dem anderen und testen Sie das erstellte Target mittels ant <target-name>
   - [x] Erweitern Sie den Output der Java Klasse um Ihre Namen.
 
  ### Schritt für Schritt zum ersten build.xml
   - [x] Erstellen Sie ein leeres build.xml im root Verzeichnis Ihres neuen Projekts
   - [x] Erstellen Sie die folgenden Targets mit den beschriebenen Funktionen und Abhängigkeiten
   
     **init**
       erzeugt Verzeichnisstruktur
       
     **clean**
       löscht die mit init erstellten Verzeichnisse
       
     **compile**
       kompeliert die Java Klassen
       
     **jar**
       erzeugt Jar Datei, die ausführbar ist
       
     **install**
       kopiert Ihre Jar Datei in ein vordefiniertes Verzeichnis
 
       
   **Abhängigkeit**
     
     init -> compile -> jar -> install -> clean
       
   - [x] Testen Sie Ihr Skript ob die Ausführung funktioniert
   - [x] Versionieren Sie die letzten Änderungen.

