# Palindrom

Ein Palindrom ist ein Wort oder ein Satz, dass rückwärts gelesen genau dasselbe Wort oder den gleichen Satz ergeben. Groß-/Kleinschreibung oder Satzzeichen sind ggf. zu ändern (siehe auch <https://de.wikipedia.org/wiki/Palindrom>).

Bekannte Palindrom-Worte sind:
- Reittier
- Lagerregal
- Reliefpfeiler
- Anna
- Rentner

Bekannte Palindrom-Sätze sind:
- Die Liebe ist Sieger; stets rege ist sie bei Leid.
- Erika feuert nur untreue Fakire.
- O Genie, der Herr ehre dein Ego!

## Aufgaben

1. Schreiben Sie eine Klasse mit einer Instanz-Methode, die prüft, ob es sich beim übergebenen String um ein Palindrom-Wort handelt. Die Methode soll dazu einen `boolean` zurückgeben, d. h. `true`, wenn es sich beim übergebenen String um ein Palindrom-Wort handelt oder `false`, wenn es kein Palindrom-Wort ist. Es gilt: Ein leerer String, ein String mit nur einem Buchstaben oder `null` sind keine Palindrome.
2. Schreiben Sie mind. zwei Unit-Tests für Ihre Methode.
3. Schreiben Sie eine zusätzliche Methode, die nicht nur ein Wort als Parameter entgegennimmt, sondern eine Liste von Wörtern. Die Methode soll für die Wörter in der Liste eine Palindrom-Prüfung durchführen und das Ergebnis dieser Prüfung in einer `Map<String, Boolean>` zurückgeben.

   **Beispiel**
    - Methode wird aufgerufen mit `["Rentner", "Otto", "Hans"]`
    - Die Rückgabe ist wie folgt:
      ```json
      "map": {
        "Rentner": true, 
        "Otto": true, 
        "Hans": false 
      }
      ```

4. Schreiben Sie auch für diese Methode einen Unit-Test.
5. Erweitern Sie Ihre Implementierung so, dass auch Palindrom-Sätze korrekt erkannt werden.
