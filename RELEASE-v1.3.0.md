# Release v1.3.0

Terminal-Fenster, die Verbinden, Trennen oder Aufräumen öffnen, **schließen sich nach
erfolgreichem Ende selbst**. Bei einem Fehler bleiben sie offen, damit die Meldung lesbar ist.

## Änderungen

- 🪟 Das Fenster schließt sich nach sauberem Trennen, nach dem Trennen per Touch ID und nach dem
  Aufräumen (dort mit drei Sekunden Verzögerung). Von Hand gestartete Skripte und Fenster mit
  mehreren Tabs bleiben offen.
- ⚠️ Scheitert das Trennen per Touch ID, meldet das Fenster das, statt „Fertig" anzuzeigen.
- 🧹 Das Aufräumen nennt fehlgeschlagene Schritte, im Terminal ebenso wie in der Mitteilung nach
  dem Admin-Dialog.

## Installation

- Neuer Helfer `thmvpn-closewindow.sh`. Bestehende Installationen erhalten ihn durch erneutes
  Ausführen von `install.sh`. Wer manuell installiert, muss ihn mitkopieren (siehe README).

---

*Getestet auf macOS 26 (Apple Silicon) mit openconnect 9.21 und SwiftBar 2.1.*
