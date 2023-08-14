Flugzeug Spiel.
Das Ziel des Spiels ist es, mit einem Flugzeug Hindernissen auszuweichen, Punkte zu sammeln und so lange wie möglich zu überleben.

Voraussetzungen
Bevor du das Spiel ausführst, stelle sicher, dass du die Pygame-Bibliothek installiert hast:
pip install pygame
Spielbeschreibung
Das Spiel enthält die folgenden Elemente:

Ein Flugzeug, das von dir gesteuert wird.
Raketen, die vom Bildschirmrand auf das Flugzeug zusteuern.
Boni, die von oben nach unten fallen und bei Berührung Punkte geben.
Ein Hintergrundbild, das sich kontinuierlich horizontal bewegt.
Spielsteuerung
Pfeiltasten - Steuere das Flugzeug nach oben, unten, links und rechts.
Spiellogik
Das Spiel startet mit 3 Leben und einem Punktestand von 0.
Das Flugzeug kann sich nach oben, unten, links und rechts bewegen.
Raketen kommen von der rechten Seite des Bildschirms und bewegen sich nach links. Wenn das Flugzeug mit einer Rakete kollidiert, verliert es ein Leben, und die Rakete wird neu positioniert.
Boni fallen von oben nach unten. Wenn das Flugzeug einen Bonus berührt, erhöht sich der Punktestand, und der Bonus wird neu positioniert.
Das Hintergrundbild bewegt sich kontinuierlich von rechts nach links, um einen Eindruck von Bewegung zu vermitteln.
Das Spiel endet, wenn alle Leben verloren sind. "Game Over" wird angezeigt, und das Spiel pausiert für 2 Sekunden, bevor es sich beendet.
Spielanpassung
Du kannst die Dateipfade für die Hintergrundbilder, das Flugzeug, die Rakete und den Bonus ändern, indem du die entsprechenden Variablen änderst.
Die Geschwindigkeiten der verschiedenen Elemente können ebenfalls angepasst werden, um das Spiel schwieriger oder einfacher zu gestalten.
Spielstart
Um das Spiel zu starten, führe den Code aus. Stelle sicher, dass die Bilddateien an den richtigen Orten liegen und die Pygame-Bibliothek installiert ist. Verwende die Pfeiltasten, um das Flugzeug zu steuern, weiche den Raketen aus und sammle Boni, um Punkte zu sammeln.

Hinweis: Dieses Spiel ist eine einfache Demonstration der Verwendung von Pygame und kann weiterentwickelt und verbessert werden, um zusätzliche Funktionen, Levels und Grafiken hinzuzufügen.
