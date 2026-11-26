# Datenschutzerklärung: Mondkalender

**Gültig ab:** 26. November 2026

Sprachen: [English](privacy.html) · [Български](privacy.bg.html) · **Deutsch** · [Español](privacy.es.html)

Diese Erklärung beschreibt, welche Informationen die Android-App **Mondkalender** (bulgarisch: „Лунен календар“, Paket `com.stoyanov.dev.android.moon`, ab Version 4.0; frühere Versionen erschienen als „Moon Phases & Sky Events“) verarbeitet. Die App wird von Zdravko Stoyanov, einem unabhängigen Entwickler („wir“), entwickelt, der für die App verantwortlich ist.

Bei Abweichungen zwischen den Sprachfassungen gilt die [englische Fassung](privacy.html).

## Kurzfassung

- Die App hat **keine Konten, keine Anmeldung, keine Analyse, keine Absturzberichte und keine eigenen Server**. Wir erhalten keine personenbezogenen Daten von Ihnen.
- Alle Berechnungen zu Mond, Sonne und Himmel laufen **offline auf Ihrem Gerät**.
- Ihr Ort (Stadt oder Koordinaten) und Ihre Einstellungen werden **nur auf Ihrem Gerät** gespeichert und sind von der Android-Cloud-Sicherung ausgeschlossen.
- Der Standortzugriff ist **freiwillig und ungefähr** und wird einmalig genutzt, wenn Sie auf „Meinen Standort verwenden“ tippen. Ihr Standort wird nicht an uns gesendet und nicht an die Werbung weitergegeben.
- Benachrichtigungen werden **lokal auf dem Gerät** geplant; es gibt keinen Push-Server.
- Die App zeigt **native Anzeigen von Google AdMob** mit der Kennzeichnung „Anzeige“. Google kann Gerätedaten (z. B. Werbe-ID und IP-Adresse) erheben, um Anzeigen auszuliefern und zu messen. Wo erforderlich (z. B. im EWR, im Vereinigten Königreich und in der Schweiz), holen wir zuerst Ihre Einwilligung über das Einwilligungstool von Google ein.
- Wir verkaufen keine Daten.

## 1. Auf dem Gerät gespeicherte Informationen

Die App speichert ihre Einstellungen im privaten App-Speicher auf Ihrem Gerät:

- Ihren Ort: eine Stadt aus der integrierten Liste oder Koordinaten (auf 0,01° gerundet, etwa 1 km) und eine Zeitzone;
- Ihre Vorlieben: Sprache, Design, Mondbild, welche Himmelsereignisse und traditionellen Hinweise angezeigt werden;
- Ihre Auswahl für Benachrichtigungen (welche, zu welcher Uhrzeit) und die Liste der auf dem Gerät geplanten Benachrichtigungen;
- ob Sie die Einführung abgeschlossen haben.

Diese Einstellungen sind **von der Android-Cloud-Sicherung und von der Übertragung auf ein neues Gerät ausgeschlossen** und bleiben nur auf diesem Gerät. Die App sendet sie nirgendwohin, und wir können sie nicht lesen.

## 2. Von uns erhobene Informationen

**Keine.** Die App sendet uns keine Daten. Sie fragt nicht nach Name, E-Mail, Kontakten, Fotos oder anderen persönlichen Informationen. Die integrierte Städteliste und alle astronomischen Daten sind Teil der App; die Städtesuche nutzt daher kein Internet.

### Standort (freiwillig)

Sie können Ihren Ort auf drei Arten festlegen: eine Stadt aus der integrierten Liste wählen, Koordinaten von Hand eingeben oder auf **„Meinen Standort verwenden“** tippen. Nur im letzten Fall fragt die App Android nach dem **ungefähren Standort** (`ACCESS_COARSE_LOCATION`). Sie fragt weder nach dem genauen Standort noch nach dem Standort im Hintergrund.

Wenn Sie zustimmen, ermittelt die App Ihre ungefähre Position einmalig, während die App geöffnet ist, rundet sie auf 0,01° und speichert sie in den oben beschriebenen Einstellungen. Sie wird nur verwendet, um Mondaufgang, Monduntergang und andere Zeiten für Ihren Ort zu berechnen. Die App **sendet Ihren Standort weder an uns noch an Dritte und gibt ihn nicht an die Werbung weiter.** Sie können die Berechtigung verweigern und die App mit einer Stadt oder Koordinaten nutzen.

### Benachrichtigungen (freiwillig)

Wenn Sie Benachrichtigungen einschalten (Mondphasen, Finsternisse, Planetenkonjunktionen, Meteorströme, günstige Tage), fragt die App nach der Berechtigung, Benachrichtigungen anzuzeigen (`POST_NOTIFICATIONS`, Android 13+). Benachrichtigungen werden **auf dem Gerät** berechnet und geplant; die App nutzt außerdem `RECEIVE_BOOT_COMPLETED`, um sie nach einem Neustart wiederherzustellen. Für Benachrichtigungen werden keine Daten gesendet.

## 3. Werbung: Google AdMob und Einwilligung über Google

Die App enthält Software Development Kits (SDKs) von Google. Diese SDKs senden Daten **direkt an Google, nicht an uns**. Wie Google diese Daten verarbeitet, steht in der [Datenschutzerklärung von Google](https://policies.google.com/privacy?hl=de) und unter [Wie Google Informationen von Websites oder Apps verwendet, die unsere Dienste nutzen](https://policies.google.com/technologies/partner-sites?hl=de).

### Google AdMob (Google Mobile Ads SDK)

Die App zeigt höchstens eine kleine native Anzeige pro Bildschirm, eingebettet in den Inhalt und mit „Anzeige“ gekennzeichnet. Es gibt keine Vollbildanzeigen und keine Anzeigen in der Einführung oder in den Einstellungen. Um Anzeigen auszuliefern, zu begrenzen und zu messen und Betrug zu verhindern, erhebt das SDK laut Googles eigener Angabe:

- die **IP-Adresse** des Geräts, aus der Ihr ungefährer Standort abgeleitet werden kann;
- **Interaktionen mit Anzeigen und der App**, z. B. App-Starts, Tippen und Anzeigenaufrufe;
- **Diagnoseinformationen** zur Leistung von App und SDK;
- **Gerätekennungen**, z. B. die Android-Werbe-ID und die App-Set-ID.

Die App selbst fügt Anzeigenanfragen nur einige feste Stichwörter hinzu (Mond, Kalender, Garten); sie fügt weder Ihren Standort noch andere persönliche Informationen hinzu. Laut Google werden diese Daten bei der Übertragung verschlüsselt. Anzeigen können je nach Ihrer Einwilligung und Ihren Geräteeinstellungen personalisiert oder nicht personalisiert sein. Sie können Ihre Werbe-ID zurücksetzen oder löschen oder personalisierte Werbung abwählen unter Android **Einstellungen > Datenschutz > Werbung** (das genaue Menü hängt vom Gerät ab).

### Google User Messaging Platform (Einwilligung)

Wenn Sie sich im Europäischen Wirtschaftsraum, im Vereinigten Königreich oder in der Schweiz befinden (oder in einer anderen Region, in der Google es verlangt), zeigt die App das Einwilligungsformular von Google, bevor eine Anzeige angefordert wird. Anzeigen werden erst angefordert, wenn das Einwilligungstool es erlaubt. Je nach Ihrer Wahl zeigt Google personalisierte, nicht personalisierte oder eingeschränkte Anzeigen. Ihre Wahl wird vom Google-SDK auf dem Gerät gespeichert. Dazu sendet das SDK einige Geräteinformationen (z. B. IP-Adresse und Geräte-/App-Kennungen) an Google.

Sie können Ihre Wahl jederzeit ändern: Öffnen Sie in der App **Einstellungen** und tippen Sie unter **„Werbung und Datenschutz“** auf **„Datenschutzeinstellungen“**. Dieser Eintrag erscheint, wenn das Einwilligungstool von Google ihn für Ihre Region benötigt.

## 4. Rechtsgrundlage (EWR/Vereinigtes Königreich)

Wir selbst erheben keine personenbezogenen Daten. Die in Abschnitt 3 beschriebene Verarbeitung erfolgt durch Google. Wo personalisierte Werbung eine Einwilligung erfordert, wird diese über das Formular von Google eingeholt; Sie können sie wie oben beschrieben jederzeit widerrufen. Nicht personalisierte Anzeigen können Daten weiterhin für Zwecke wie Frequenzbegrenzung, Betrugsprävention und Messung verwenden, wie von Google beschrieben. Der Standort auf Ihrem Gerät wird nur verwendet, weil Sie es angefordert haben (über „Meinen Standort verwenden“).

## 5. Weitergabe und Verkauf von Daten

Wir verkaufen, vermieten oder teilen keine personenbezogenen Daten von Ihnen – wir haben keine. Die von den Werbe-SDKs von Google erhobenen Daten werden von Google wie in Abschnitt 3 beschrieben erhoben.

## 6. Kinder

Die App ist ein Mondkalender für ein allgemeines Publikum. Sie **richtet sich nicht an Kinder unter 13 Jahren**, und wir erheben nicht wissentlich personenbezogene Daten von Kindern. Wenn Sie glauben, dass ein Kind die App nutzt, kann ein Elternteil oder Erziehungsberechtigter personalisierte Werbung in den Geräteeinstellungen abschalten oder uns kontaktieren (Abschnitt 10).

## 7. Speicherdauer

- Einstellungen und Ihr Ort bleiben auf dem Gerät, bis Sie sie löschen (siehe Abschnitt 8).
- Von Google erhobene Daten werden nach den Richtlinien von Google aufbewahrt; siehe [Wie Google Daten aufbewahrt](https://policies.google.com/technologies/retention?hl=de).

## 8. Ihre Wahlmöglichkeiten und Löschung

- **App-Daten löschen:** Deinstallieren Sie die App oder öffnen Sie in Android **Einstellungen > Apps > Mondkalender > Speicher > Daten löschen**. Dadurch werden Ort, Einstellungen und geplante Benachrichtigungen gelöscht. Da sie nicht gesichert werden, bleibt nichts bei uns oder in Ihrer Google-Sicherung.
- **Standort:** Verweigern oder widerrufen Sie die Standortberechtigung jederzeit in den Android-Einstellungen; nutzen Sie stattdessen eine Stadt oder Koordinaten.
- **Benachrichtigungen:** Schalten Sie sie in den Einstellungen der App oder in den Android-Einstellungen aus.
- **Werbe-Einwilligung:** Ändern Sie sie über **„Datenschutzeinstellungen“** in den Einstellungen der App (siehe Abschnitt 3).
- **Werbe-ID:** Setzen Sie sie in den Android-Einstellungen zurück, löschen Sie sie oder wählen Sie personalisierte Werbung ab.
- **Bei Google gespeicherte Daten:** siehe [Datenschutzeinstellungen von Google](https://myaccount.google.com/data-and-privacy?hl=de).

Nach der DSGVO haben Sie das Recht auf Auskunft, Berichtigung, Löschung und Datenübertragbarkeit, auf Einschränkung der Verarbeitung und Widerspruch, auf Widerruf einer Einwilligung sowie auf Beschwerde bei einer Datenschutzaufsichtsbehörde. Da wir keine personenbezogenen Daten über Sie speichern, können wir auf bei Google gespeicherte Daten nicht zugreifen und sie nicht löschen, helfen Ihnen aber gern, die richtige Stelle zu finden.

## 9. Änderungen dieser Erklärung

Version 4.0 ist eine komplett neue App. Frühere Versionen von „Moon Phases & Sky Events“ nutzten Google Analytics for Firebase; ab Version 4.0 enthält die App keine Analyse mehr. Wenn sich diese Erklärung ändert, aktualisieren wir diese Seite und das Datum oben.

## 10. Kontakt

- Zdravko Stoyanov
- E-Mail: **stoyanov.dev@gmail.com**
- Website: [https://stoyanov.dev](https://stoyanov.dev)
