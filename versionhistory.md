
# Version History

## 1.5.3 - Code-Review #1

- Fixes
  - Ein benutzerdefinierter Prefix kann jetzt länger als ein Zeichen sein.
- Neue Funktion
  - Der nervtötenste Befehl wurde hinzugefügt: 'spam'.
  - Er ist endlich da, wir alle haben ihn erwartet: Der 'weather' Befehl òwó
- Entfernt
  - Das Plugin 'app-heroku.js' wurde entfernt.
- Änderung
  - Kleine Änderungen in dem 'about'-Befehl
    - Der Avatar wird automatisch geladen.
    - Der Titel des Programms wird jetzt aus dem Benutzernamen geladen.
    - Die Informationen und Kontaktdaten sind jetzt in einzelnen Zeilen eingeteilt.
    - Kontakt E-Mail hinzugefügt.
    - Projekt URL geändert.
  - Die Dateinamen der Tier-Befehle wurden geändert:
    - bird.js => animal-bird.js
    - cat.js => animal-cat.js
    - dog.js => animal-dog.js
    - fox.js => animal-fox.js
    - koala.js => animal-koala.js
    - panda.js => animal-panda.js
    - red_panda.js => animal-red_panda.js
  - Die Formatierung des 'sendall'-Befehls wurde geändert:
    - Thumbnail wurde entfernt.
    - Das Author-Icon wurde zum Server-Icon geändert.
    - Der Titel 'Message from {{guildname}}' wurde in '{{guildname}}' geändert.
  - Die Dateinamen der Plugins wurden geändert:
    - raccoon-colors.js => wolf-colors.js
    - raccoon-joinrole.js => wolf-joinrole.js
    - raccoon-music.js => wolf-music.js
    - raccoon-new-guild.js => wolf-new-guild.js
  - Das Ascii-Art Logo in der Konsole wurde geändert.
- Anmerkung
  - Nicht mehr gültige Todo- und Hack-Tags wurden entfernt.

## 1.5.2 - Wolf Bot

- Fixes
  - Nichts
- Neue Funktion
  - Procfile hinzugefügt.
- Entfernt
  - Nichts
- Änderung
  - Name geändert: Der Bot heißt jetzt "Wolf Bot"
  - Avatar geändert.
  - Fullview-Avatar geändert.
  - Urls durch CyberFen.eu Adressen ersetzt.
- Anmerkung
  - Nichts

## 1.5.1 - Hotfix

- Fixes
  - Nichts
- Neue Funktion
  - Procfile hinzugefügt.
- Entfernt
  - Nichts
- Änderung
  - Nichts
- Anmerkung
  - Nichts

## 1.5.0 - Die namenlose Version

- Fixes
  - Nichts
- Neue Funktion
  - Tolle neue Funktion! Dank Heroku kann man jetzt Plugins deaktivieren!
  - Der 'bird'-Befehl wurde hinzugefügt ^.^
  - Der 'cat'-Befehl wurde hinzugefügt ^.^
  - Der 'dog'-Befehl wurde hinzugefügt ^.^
  - Der 'fox'-Befehl wurde hinzugefügt ^.^
  - Der 'koala'-Befehl wurde hinzugefügt ^.^
  - Der 'panda'-Befehl wurde hinzugefügt ^.^
  - Der 'pikachu'-Befehl wurde hinzugefügt ^.^
  - Der 'red_panda'-Befehl wurde hinzugefügt ^.^
  - Der 'tfdne'-Befehl wurde hinzugefügt unterstützt durch This Fursona Does Not Exist (versteckter Befehl).
- Entfernt
  - Heroku ist jetzt erstmal deaktiviert aufrgund von inkompetenz.
- Änderung
  - Nichts
- Anmerkung
  - Nichts

## 1.4.3.2 - Hotfix

- Fixes
  - Hört das eigentlich auch mal auf?
- Neue Funktion
  - Nichts
- Entfernt
  - Nichts
- Änderung
  - Nichts
- Anmerkung
  - Nichts

## 1.4.3.1 - Hotfix

- Fixes
  - Korrigierte einen Fehler der Heroku daran gehindert hat die Anwendung zu starten. Mal wieder.
- Neue Funktion
  - Nichts
- Entfernt
  - Nichts
- Änderung
  - Nichts
- Anmerkung
  - Nichts

## 1.4.3 - Hotfix

- Fixes
  - Korrigierte einen Fehler der Heroku daran gehindert hat die Anwendung zu starten.
- Neue Funktion
  - Nichts
- Entfernt
  - Nichts
- Änderung
  - Nichts
- Anmerkung
  - Nichts

## 1.4.2 - Disco-Coon

- Fixes
  - Der Versionsname wird jetzt unter dem Raccoon Bot Logo zentriert.
  - Ich habe ein paar Module entfernt die nicht verwendet wurden.
- Neue Funktion
  - Wenn ein Benutzer  jetzt einen ungültigen Befehl eingibt, erscheint eine "Unknown command"-Nachricht
  - Befehle können jetzt spezifisch für Alpha Tester, Beta Tester und Entwickler gesondert aktiviert werden.
  - Befehle können jetzt deaktiviert werden.
  - Ein neues Alias-System wurde hinzugefügt.
    - Aliasse werden gesondert gespeichert.
    - Doppelte Aliasse werden ignoriert.
  - Sollte kein Bot Token in der .env-Datei angegeben worden sein, fordert das Programm den Nutzer auf einen Token einzugeben und speichert diesen.
  - Wenn ein ungültiger Bot Token angegeben wurde, fordert das Programm ein auf einen neuen einzugeben und startet neu.
- Entfernt
  - Nichts
- Änderung
  - Alpha Tester können jetzt die maximale Lautstärke von 100% überseteigen.
  - Der Help-Befehl wurde überarbeitet
    - Eine Unterstützung für Aliase wurde hinzugefügt.
    - Aliasse werden den Befehlen untergeordnen im Help-Befehl angezeigt.
  - Das Befehls-System wurde überarbeitet.
    - Doppelte Befehle werden nicht registriert (+Aliasse werden nicht hinzugefügt);
- Anmerkung
  - Erlauben der erstellung von eigennen Aliasen (eventuell).
  - Hinzufügen von globalen Werten für die Farben der Rich Embed Antworten.

## 1.4.1 - Disco-Coon

- Fixes
  - Nichts
- Neue Funktion
  - 'back' Befehl hinzugefügt.
- Entfernt
  - Nichts
- Änderung
  - Nichts
- Anmerkung
  - Der 'back' Befehl nutzt aktuell einen Workaround (Hack) um den nullten Eintrag der Queue anzugeben.
    In Zukunft könnte dies für Fehler sorgen.

## 1.4.0 - Disco-Coon

- Fixes
  - 'stop' Befehl löscht Playlist nicht.
  - 'lyrics' Befehl funktioniert jetzt wieder.
  - Ein Haufen interner Dinge an die ich mich nicht mehr erinnern kann.
  - Der 'avatar' Befehl funktioniert jetzt auch auf mobilem geräten.
- Neue Funktionen
  - 'volume' Befehl hinzugefügt
- Entfernt
  - Nichts
- Änderung
  - Nichts
- Anmerkung
  - Nichts
