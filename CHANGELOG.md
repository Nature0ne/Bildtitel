# Versionshinweise

## 1.3.0 · 12. November 2026

- Oberfläche vollständig auf Deutsch, Englisch und Niederländisch; automatische Auswahl nach macOS-Sprachpräferenz. Dynamische Meldungen, native Dateidialoge, Menüleiste und Einstellungen sind übersetzt. KI-Anfragen berücksichtigen die Appsprache, niederländische OCR und Screenshot-Namen werden unterstützt. Eigene Titel und Profilnamen bleiben unverändert.
- Ordnerüberwachung mit tatsächlichem Aktiv-/Vorbereitungs-/Pause-/Fehlerstatus, letzter erfolgreicher Prüfung und „Jetzt prüfen“. Vorübergehende Zugriffsfehler lösen erneute Versuche aus; einzelne nicht lesbare Dateien stoppen nicht die gesamte Prüfung.
- Eingang mit offenen und bearbeiteten Vorschlägen lokal speichern und beim Neustart wiederherstellen. Wiederhergestellte Vorschläge werden nicht automatisch umbenannt.
- Namensprofile anlegen, anwenden, aktualisieren und löschen.
- Mehrfachauswahl, auf sichtbare Bilder oder Auswahl begrenzte Stapelvorschau und Ergebnisbericht mit erfolgreichen und fehlgeschlagenen Umbenennungen. Suche, Auswahl und Detailansicht bleiben auf denselben sichtbaren Umfang bezogen.
- Verlauf nach ursprünglichem/neuem Dateinamen, Zeitraum, Methode und Status durchsuchen und filtern.
- Bildimport aus der Zwischenablage über Menü oder ⇧⌘V mit frei gewähltem Speicherort für die neue PNG-Datei; vorhandene Dateien werden nicht überschrieben.
- Identische Bilddateien als Duplikat markieren, auch im Vergleich mit passenden bereits bekannten Dateien. Keine automatische Löschung und keine automatische erneute Benennung markierter Duplikate.
- Besser lesbare Betriebsinformationen, klarere Statusfarben, größere Klickflächen und mehr Platz für längere Übersetzungen. Der leere Eingang lässt sich auch bei kleinen Fenstern scrollen.

67 automatisierte Tests bestanden. Englische und niederländische Oberfläche sowie manuelle und automatische Updates mit bearbeiteten Vorschlägen im Eingang geprüft. App und DMG von Apple notarisiert.

Vor dem Wechsel von 1.1.0/1.2.0 offene Vorschläge abschließen: Diese Versionen speichern den Eingang noch nicht. Vorhandene Einstellungen und Verlauf bleiben erhalten.

Die Ursache des zuvor gemeldeten Überwachungsausfalls auf einem weiteren Mac ist weiterhin nicht durch Diagnosedaten dieses Geräts bestätigt. Die Verbesserungen ersetzen diese ausstehende Überprüfung nicht.

## 1.2.0 · 12. November 2026

- Integrierte Update-Suche über App-Menü, Menüleiste und Einstellungen.
- Automatische Suche sowie optionale Hintergrund-Downloads und Installation beim Beenden mit Sparkle.
- Signierter Update-Feed und signierte Archive über GitHub; kein Systemprofiling und keine Übertragung von Bildern oder Diagnoseprotokollen.

- Datumsformat für Präfix und Suffix selbst einstellen, zum Beispiel `yy-MM-dd` für `26-11-12` oder `dd.MM.yyyy` für `12.11.2026`.
- Sofortige Vorschau und Datum in der lokalen Zeitzone des Macs; bisherige Einstellungen bleiben erhalten.
- Diagnoseexport über Einstellungen und Menüleiste zur Untersuchung von Problemen mit der Ordnerüberwachung.
- Begrenztes lokales Protokoll mit Scan-Anzahlen, Zeitpunkten, technischen Zuständen und Fehlercodes. Keine Bilder, Bildtexte, Dateinamen, Ordnerpfade oder Bookmarkdaten im Export; keine automatische Übertragung.

27 Tests einschließlich echter Apple Intelligence bestanden. Manuelle Updateinstallation mit Neustart sowie Hintergrund-Download mit automatischer Installation beim Beenden in einer getrennten Test-App geprüft. Der gemeldete Überwachungsausfall auf einem weiteren Mac ist noch nicht reproduziert; dieses Update stellt die Diagnose dafür bereit.

## 1.1.0 · 11. November 2026

Erste öffentliche Version von Bildtitel für Apple Silicon.

- Screenshot- und Bildtitel mit lokaler Apple Intelligence.
- Vorschau mit bearbeitbarem Titel sowie Stapelverarbeitung.
- Überwachung neu eintreffender Screenshots mit optionaler automatischer Umbenennung.
- Dateinamensstile, Titellänge und Datum im Dateinamen.
- Dauerhafter Verlauf mit sicherem Rückgängig.
- Hell, Dunkel und automatische Systemdarstellung.
- Optionaler reiner Menüleistenbetrieb ohne Dock-Symbol.
- Anzeige der tatsächlich verwendeten Benennungsmethode.
- Developer-ID-Signatur und Apple-Notarisierung für die Downloads.

Voraussetzungen: Apple Silicon und macOS 26+. Oberfläche auf Deutsch. 21 Tests einschließlich echter Apple Intelligence bestanden.
