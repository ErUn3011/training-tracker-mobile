TRAINING TRACKER – MOBILER PROTOTYP

Enthalten:
- spontane Trainingseinheiten ohne festen Trainingsplan
- Beispiel-Übungsbibliothek und eigene Übungen
- Sätze, Gewicht (kg), Wiederholungen
- Vorschlag letzter Satzwerte je Übung
- Trainingshistorie
- lokale IndexedDB-Datenbank
- JSON-Sicherung exportieren/importieren
- PWA-Service-Worker für Offline-App-Oberfläche
- kein Server, kein Konto, keine Synchronisierung

WICHTIG: Die Daten liegen ausschließlich im Browser/App-Speicher dieses Handys. Regelmäßig über „Daten exportieren“ sichern. Browserdaten nicht löschen und nicht im Inkognito-Modus verwenden.

TEST AM PC:
1. ZIP entpacken.
2. Im Ordner eine CMD öffnen und ausführen: python -m http.server 8000
3. Im Browser http://localhost:8000 öffnen.
4. PWA-/Offline-Verhalten funktioniert bei localhost als Entwicklungsumgebung.

INSTALLATION AUF ANDROID:
Für die Installation als PWA muss die App über eine HTTPS-Adresse bereitgestellt werden. Das Hosting liefert nur statische Dateien aus; Trainingsdaten werden nicht an den Host übertragen. Adresse mit Chrome oder Samsung Internet öffnen, App einmal laden und dann „Zum Startbildschirm hinzufügen“/„App installieren“ wählen. Anschließend Offline-Modus testen.

Das ist ein erster Prototyp. Vor regelmäßigem Einsatz im Studio auf dem konkreten Handy das Speichern, Offline-Starten und Importieren/Exportieren testen.
