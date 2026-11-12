<p align="center">
  <img src="assets/bildtitel-icon.png" width="104" height="104" alt="Bildtitel Icon">
</p>

<h1 align="center">Bildtitel</h1>
<p align="center"><strong>Bilder. Gut benannt.</strong><br>Eine native Mac-App, die aus Screenshot-Inhalten verständliche Dateinamen macht.</p>

<p align="center">
  <a href="https://github.com/Nature0ne/Bildtitel/releases/download/v1.3.0/Bildtitel-1.3.0-macOS-AppleSilicon.dmg"><strong>↓ Bildtitel 1.3.0 herunterladen</strong></a> ·
  <a href="https://github.com/Nature0ne/Bildtitel/releases/download/v1.3.0/Bildtitel-1.3.0-macOS-AppleSilicon.zip">ZIP</a> ·
  <a href="#installation">Installation</a> ·
  <a href="README.en.md">English</a> ·
  <a href="README.nl.md">Nederlands</a>
</p>

<p align="center">macOS 26+ · Apple Silicon · Deutsch · English · Nederlands · Kostenloser Download</p>

![Bildtitel im Dunkelmodus mit einer Namensvorschau](assets/bildtitel-dark.png)

## Aus „Screenshot …“ wird ein Name, der etwas sagt

Screenshots sammeln sich schnell. Bildtitel erkennt ihren Inhalt und schlägt einen passenden Namen vor. Du prüfst ihn, passt ihn bei Bedarf an und benennst die Datei mit einem Klick. Für neue Screenshots kann Bildtitel das auch automatisch im Hintergrund übernehmen.

Version 1.3.0 ergänzt Englisch und Niederländisch sowie mehr Übersicht für deinen täglichen Ablauf: Vorschläge nach Neustarts wiederfinden, Namensprofile wechseln und genau die Bilder gemeinsam benennen, die du ausgewählt hast.

| Funktion | Das bringt sie dir |
|---|---|
| **Lokale KI** | Apple Intelligence formuliert Titel auf deinem Mac; ohne verfügbare KI hilft lokale Texterkennung. |
| **Vorschau vor dem Benennen** | Bild, ursprünglicher Name, bearbeitbarer Titel und fertiger Dateiname stehen zusammen. |
| **Eingang bleibt erhalten** | Offene Vorschläge und bearbeitete Titel werden lokal gespeichert und beim nächsten Start wiederhergestellt. |
| **Namensprofile** | Länge, Schreibweise, Datum und KI-Einstellung für unterschiedliche Aufgaben speichern und wieder anwenden. |
| **Gezielte Stapelverarbeitung** | Sichtbare Bilder oder eine Auswahl prüfen, Namen in der Stapelvorschau bearbeiten und das Ergebnis danach nachvollziehen. |
| **Ordnerüberwachung mit Status** | Aktiv, Vorbereitung, Pause und Fehler unterscheiden; letzte Prüfung sehen, erneut prüfen und automatische Wiederholungsversuche nutzen. |
| **Verlauf durchsuchen** | Nach ursprünglichem oder neuem Namen suchen und nach Zeitraum, Methode oder Status filtern. |
| **Bilder aus der Zwischenablage** | Kopierte Bilder als neue PNG-Datei speichern und direkt einen Namensvorschlag erhalten. |
| **Duplikate erkennen** | Bilder mit identischem Dateiinhalt zu anderen Bildern im Eingang oder bekannten Dateien markieren; nichts wird automatisch gelöscht. |
| **Dein Datumsformat** | Datum davor oder dahinter, zum Beispiel `yy-MM-dd` → `26-11-12`. |
| **Hell, Dunkel oder System** | Darstellung nach Wunsch, mit besser lesbaren Hinweisen und einem Layout für längere Texte. |
| **Nur in der Menüleiste** | Dock-Symbol ausblenden und Bildtitel über das Statussymbol erreichen. |
| **Updates direkt in der App** | Neue Versionen suchen oder auf Wunsch automatisch laden und beim Beenden installieren. |

<details>
<summary><strong>Auch im hellen Design ansehen</strong></summary>

![Bildtitel im hellen Design](assets/bildtitel-light.png)

</details>

## Installation

1. Lade die **[DMG für Apple Silicon](https://github.com/Nature0ne/Bildtitel/releases/download/v1.3.0/Bildtitel-1.3.0-macOS-AppleSilicon.dmg)** herunter.
2. Öffne sie und ziehe **Bildtitel.app** nach **Programme**.
3. Starte Bildtitel aus Programme.

Alternativ gibt es eine **[ZIP-Datei](https://github.com/Nature0ne/Bildtitel/releases/download/v1.3.0/Bildtitel-1.3.0-macOS-AppleSilicon.zip)**. Die fertigen Downloads sind mit Developer ID signiert und von Apple notarisiert. Prüfsummen stehen als `SHA256SUMS.txt` im [Release](https://github.com/Nature0ne/Bildtitel/releases/tag/v1.3.0) bereit.

**Schon eine ältere Version installiert?** Ab 1.2.0 kannst du **Nach Updates suchen …** verwenden. Version 1.1.0 bitte einmal manuell ersetzen. Schließe offene Vorschläge in diesen älteren Versionen vor dem Wechsel ab: Sie speichern den Eingang noch nicht. Vorhandene Einstellungen und der Umbenennungsverlauf bleiben erhalten; ab 1.3.0 wird auch der Eingang gespeichert.

## Schnell loslegen

### Bilder und eine Auswahl benennen

Zieh Dateien ins Fenster oder klicke **Bilder hinzufügen**. Prüfe den Vorschlag, bearbeite den Titel und klicke **Benennen**. Im **Verlauf** kannst du die Umbenennung rückgängig machen; vorhandene Dateien werden nicht überschrieben.

Für mehrere Bilder wählst du Einträge im Eingang aus und öffnest **Auswahl prüfen**. Ohne Auswahl kannst du die **sichtbaren Bilder prüfen**. Suchfilter und Auswahl begrenzen diesen Umfang. Die Stapelvorschau zeigt die vorgesehenen Namen vor dem Start; anschließend zeigt der Ergebnisbericht erfolgreiche und fehlgeschlagene Umbenennungen. Fehlgeschlagene Vorschläge bleiben im Eingang.

### Neue Screenshots automatisch vorbereiten

Wähle unter **Einstellungen → Screenshot-Ordner** den Ordner, in dem macOS deine Screenshots ablegt. Aktiviere **Neue Screenshots sofort benennen**, wenn neue Aufnahmen direkt umbenannt werden sollen. Bestehende Dateien werden beim Start der Überwachung ausgelassen; für ältere Bilder gibt es **Ordner vorbereiten**.

Der Status unterscheidet Vorbereitung, aktive Überwachung, Pause und Fehler. Du siehst die letzte erfolgreiche Prüfung und kannst **Jetzt prüfen** wählen. Bei vorübergehenden Zugriffsfehlern versucht Bildtitel die Prüfung erneut. Nicht lesbare einzelne Dateien werden ausgelassen und als Hinweis gezählt.

### Vorschläge behalten und Profile verwenden

Der Eingang wird samt bearbeiteten Vorschlägen lokal gespeichert. Nach einem Neustart kannst du dort weiterarbeiten. Wiederhergestellte Vorschläge werden nicht automatisch umbenannt.

Unter **Einstellungen → Namensprofile** kannst du beispielsweise Profile für Arbeit, Privat oder Belege anlegen. Gespeicherte Profile lassen sich anwenden, aktualisieren und löschen. Eigene Profilnamen und bearbeitete Titel werden beim Wechsel der Appsprache nicht übersetzt.

Unter **Namen** wählst du **Datum davor** oder **Datum dahinter**. `yy-MM-dd` ergibt **26-11-12**, `dd.MM.yyyy` ergibt **12.11.2026**. Die Vorschau aktualisiert sich sofort; das Datum folgt der lokalen Zeitzone deines Macs.

### Zwischenablage und Duplikate

Mit **Bild aus Zwischenablage hinzufügen** oder **⇧⌘V** übernimmst du ein kopiertes Bild. Du wählst, wo die neue PNG-Datei gespeichert wird. Bestehende Dateien werden dabei nicht überschrieben.

Dateien mit identischem Inhalt werden als Duplikat markiert. Du kannst das Original im Finder zeigen oder das Bild mit **Trotzdem prüfen** bewusst erneut analysieren. Es wird nichts automatisch gelöscht; markierte Duplikate werden nicht automatisch erneut analysiert oder benannt.

### Verlauf, Sprache und Darstellung

Im Verlauf kannst du nach alten und neuen Dateinamen suchen sowie nach Zeitraum, KI/Texterkennung und Bearbeitungsstatus filtern.

Die App folgt automatisch deiner macOS-Sprachpräferenz und unterstützt **Deutsch, Englisch und Niederländisch**. Bei Bedarf kannst du in macOS unter **Systemeinstellungen → Allgemein → Sprache & Region → Apps** eine Sprache für Bildtitel festlegen. Auch die Anfrage für KI-Titel berücksichtigt die Appsprache; eigene Titel und Dateinamen bleiben erhalten.

Unter **Erscheinungsbild** wählst du **System**, **Hell** oder **Dunkel**. Schalte **Im Dock anzeigen** aus, wenn Bildtitel nur als Statussymbol erscheinen soll. Das Fenster öffnest du über das Menüleistensymbol wieder; beim Schließen des Fensters läuft die App weiter.

### Updates

**Nach Updates suchen …** findest du im App-Menü, über das Menüleistensymbol und in den Einstellungen. Die automatische Suche ist standardmäßig aktiv. **Einstellungen → Updates → Updates automatisch installieren** lädt neue Versionen im Hintergrund und installiert sie beim Beenden. Ein Neustart wird nicht erzwungen.

Bildtitel verwendet [Sparkle](https://sparkle-project.org/) und prüft die Signaturen des Update-Feeds und der Downloads. Update-Anfragen verbinden sich mit GitHub; Bilder, erkannte Bildtexte und Diagnoseprotokolle werden dabei nicht übertragen. Systemprofiling ist ausgeschaltet.

## Apple Intelligence und Datenschutz

Für KI-Titel muss Apple Intelligence auf deinem Mac aktiviert und das Modell verfügbar sein. Unter macOS 27 und neuer wird auch der Bildinhalt direkt an das lokale Modell übergeben; unter macOS 26 basiert die Benennung auf erkanntem Text und Bildmerkmalen.

Ist die KI nicht verfügbar oder kann sie ein Bild nicht benennen, verwendet Bildtitel lokale Texterkennung. **Welche Methode tatsächlich verwendet wurde, steht in der Vorschau und im Verlauf.** Ein KI-Fehler wird als Rückfall auf Texterkennung kenntlich gemacht.

Kein Konto bei Bildtitel. Kein API-Schlüssel. Kein Abo. Bildtitel lädt deine Bilder nicht zu einem externen KI-Dienst hoch. Einstellungen, Namensprofile, Eingang mit Vorschlägen und erkanntem Text, Verlauf und ein begrenztes technisches Diagnoseprotokoll werden lokal auf dem Mac gespeichert.

## Voraussetzungen

- **Apple Silicon** – M1 oder neuer. Dieser Download enthält keine Intel-Version.
- **macOS 26 oder neuer**.
- Für KI-Titel: **Apple Intelligence aktiviert und verfügbar**.
- Oberfläche: **Deutsch, Englisch und Niederländisch**, automatisch nach macOS-Sprachpräferenz.

67 automatisierte Tests bestanden. Die englische und niederländische Oberfläche sowie manuelle und automatische Updates mit bearbeiteten Vorschlägen im Eingang wurden unter macOS 27.2.1 geprüft. Ein separater Praxistest unter macOS 26 steht noch aus.

## Fragen oder einen Fehler gefunden?

Erstelle ein [Issue](https://github.com/Nature0ne/Bildtitel/issues) mit deiner macOS-Version und einer kurzen Beschreibung. Ideen für Verbesserungen sind ebenfalls willkommen.

Falls neue Screenshots nicht im Eingang erscheinen: Lass Bildtitel geöffnet, erstelle einen neuen Screenshot und wähle **Einstellungen → Diagnose → Diagnose exportieren …**. Den Export findest du auch im Menüleistenmenü. Die JSON-Datei enthält technische Zustände, Zeitpunkte, Dateianzahlen und Fehlercodes – keine Bilder, erkannten Bildtexte, Dateinamen, Ordnerpfade oder gespeicherten Zugriffsrechte. Es wird nichts automatisch hochgeladen.

Version 1.3.0 verbessert die Überwachung und ihre Rückmeldungen. Die Ursache des zuvor gemeldeten Ausfalls auf einem weiteren Mac ist weiterhin nicht durch eine Diagnose des betroffenen Geräts bestätigt.

Dieses Repository enthält die fertigen Downloads, Produktvorschauen, Versionshinweise und den signierten Update-Feed.

---

Entwickelt von [Nature0ne](https://github.com/Nature0ne).
