# 19-Abgabe02-Schuelle-Urlacher
 19-Abgabe02-Schuelle-Urlacher

## Aufgabenstellung
  ### Maven
   - [ ] Builden Sie das Projekt mit Maven und erzeugen Sie somit eine Jar Datei.
   - [ ] Welche Schritte werden beim erzeugen einer Jar Datei durchlaufen?

   ### Manuelle JAR Datei erzeugen
   - [ ] Führen Sie die einzelnen Schritte manuell durch.
   - [ ] Notieren Sie sich die einzelnen Schritte
   - [ ] Wie sieht dabei der Aufwand bei der manuellen Durchführung aus?
    
   ### ANT
   - [ ] Nachdem Sie manuell eine Jar Datei erzeugt haben, erstellen Sie eine build.xml Datei im Root Verzeichnis Ihres Projekts.
   - [ ] Adaptieren Sie die Maven Projektstruktur auf eine Ant-Projektstruktur. Achten Sie dabei auf die unterschiedliche Ordnerstruktur dieser Projekstrukturen.
   - [ ] Versionieren Sie initial das adaptierte Projekt.
   - [ ] Versionieren Sie nach jedem erstellten Target.
   - [ ] Erzeugen Sie ein Target nach dem anderen und testen Sie das erstellte Target mittels ant <target-name>
   - [ ] Erweitern Sie den Output der Java Klasse um Ihre Namen.
 
  ### Schritt für Schritt zum ersten build.xml
   - [ ] Erstellen Sie ein leeres build.xml im root Verzeichnis Ihres neuen Projekts
   - [ ] Erstellen Sie die folgenden Targets mit den beschriebenen Funktionen und Abhängigkeiten
   
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
       
     - [ ] Testen Sie Ihr Skript ob die Ausführung funktioniert
     - [ ] Versionieren Sie die letzten Änderungen.

