# Datenschutzerklärung — VOID

**Stand: 27. Mai 2026**

---

## 1. Überblick

Diese Datenschutzerklärung erläutert, wie Julius Krassa („wir", „uns", „unser") Informationen erhebt, verwendet und schützt, wenn du das mobile Spiel **VOID** („die App") nutzt. Wir nehmen den Schutz deiner personenbezogenen Daten ernst und verarbeiten diese im Einklang mit der Datenschutz-Grundverordnung (DSGVO) sowie den geltenden Datenschutzgesetzen.

---

## 2. Verantwortlicher

Verantwortlicher im Sinne der DSGVO ist:

**Julius Krassa**  
Friedrich-Engels-Straße 42  
14482 Potsdam, Deutschland  
E-Mail: void@julius-krassa.de

---

## 3. Welche Daten wir erheben und warum

### 3.1 Spielfortschritt & lokale Daten (nur auf deinem Gerät)

Beim Spielen von VOID werden folgende Daten **ausschließlich lokal auf deinem Gerät** gespeichert (Unity PlayerPrefs). Diese Daten verlassen dein Gerät nicht, sofern du nicht aktiv Online-Funktionen nutzt (siehe Abschnitt 3.2).

- Spielerlevel, Erfahrungspunkte (XP), Dark Matter (DM), Prestige Matter (PM)
- Highscores (Wellen, Classic Ranked, Endless Ranked)
- Upgrade-Level, aktive Skill-Auswahl
- Booster-Inventar und aktive Booster-Zustände
- Lifetime-Statistiken (Gesamtspielzeit, ausgewichene Fragmente, gespielte Runden, Tode, abgeschlossene Wellen, verdiente DM/XP)
- Tutorial-Fortschritt
- Status von In-App-Käufen (z. B. Streamer Pack)
- Audio- und Performance-Einstellungen (FPS-Limit, Lautstärke)

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO — Verarbeitung zur Erfüllung des Vertrags über die Nutzung der App.

---

### 3.2 Benutzername & Rangliste (optional im Casual-Modus, Pflicht im Ranked)

VOID bietet eine globale Rangliste. Um dort zu erscheinen, wählst du zu Beginn einen **Benutzernamen**. Ein zufälliger 4-stelliger Tag (z. B. `#4728`) wird automatisch vergeben, um den Namen eindeutig zu machen.

- **Benutzername und Tag** werden lokal gespeichert und bei Abschluss eines Ranked-Runs an unser Leaderboard-Backend übertragen (siehe Abschnitt 5.1).
- Wer einen **Ranked-Modus** spielt (Classic Ranked, Endless Ranked), muss seinen Score — und damit den Benutzernamen — übermitteln; das ist systembedingt Teil dieses Modus. Wer nicht namentlich erscheinen möchte, kann jederzeit in den Einstellungen den **Anonym-Modus** aktivieren. Die Platzierung bleibt erhalten, der Name wird auf allen öffentlichen Ranglisten durch „Anonymous" ersetzt.
- Folgende Daten werden je nach Modus übertragen:

| Modus | Übermittelte Daten |
|-------|-------------------|
| Allgemeine Rangliste | Benutzername#Tag, beste Welle, Level, Gesamtspielzeit (Sek.), bester DM-Score, Anonym-Flag |
| Classic Ranked | Benutzername#Tag, Wellennummer, Basisscore, Combo-Multiplikator, Anonym-Flag |
| Endless Ranked | Benutzername#Tag, Score, Überlebenszeit (Sek.), Anonym-Flag |

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO — Verarbeitung zur Erbringung der genutzten Ranglisten-Funktion; Art. 6 Abs. 1 lit. a DSGVO (Einwilligung) bei der initialen Namenseingabe.

**Löschung:** Du kannst deinen Ranglisten-Eintrag jederzeit über Einstellungen → Account → Account löschen entfernen. Dabei wird eine Löschanfrage an unser Backend gesendet und der Benutzername vom Gerät gelöscht.

---

### 3.3 In-App-Käufe & Abonnements

VOID bietet folgende Käufe an, die ausschließlich über **Google Play Billing** abgewickelt werden:

- **Prestige Matter-Pakete** — In-Game-Währung gegen Echtgeld (einmalige Käufe)
- **VoidPass** — monatliches Abonnement (4,99 €/Monat oder 9,99 €/Monat)
- **Streamer Pack** — Einmalkauf (9,99 €, entfernt die Werbepflicht)

Alle weiteren In-Game-Artikel (Booster, Bundles usw.) werden mit Prestige Matter, der In-Game-Währung, erworben. Dafür sind keine zusätzlichen Echtgeld-Käufe erforderlich.

**VOID verarbeitet oder speichert keine Zahlungsdaten.** Die gesamte Zahlungsabwicklung erfolgt ausschließlich über Google Play. Für Einzelheiten zur Verarbeitung von Zahlungsdaten verweisen wir auf die Datenschutzerklärung von Google.

Wir erhalten von Google Play lediglich eine Bestätigung über den erfolgreichen Kauf und aktualisieren entsprechend deinen Spielstand lokal auf deinem Gerät.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO — Vertragserfüllung.

---

### 3.4 Werbung (Google AdMob & Unity LevelPlay)

VOID zeigt **Rewarded Ads** — kurze Videowerbungen, die du freiwillig gegen In-Game-Belohnungen anschauen kannst. Inhaber des Streamer Packs sind von Pflicht-Werbung ausgenommen.

Wir nutzen folgende Werbe-SDKs:

**Google AdMob** (Google LLC, 1600 Amphitheatre Parkway, Mountain View, CA 94043, USA)  
AdMob kann auf deinem Gerät unabhängig von VOID folgende Daten erheben: Werbe-ID (Google Advertising ID / GAID), Geräteinformationen (Modell, OS-Version, Bildschirmauflösung), IP-Adresse, App-Interaktionsdaten.  
Datenschutzerklärung Google: https://policies.google.com/privacy  
Du kannst die interessenbasierte Werbung über deine Android-Geräteeinstellungen unter **Datenschutz → Werbung** zurücksetzen oder deaktivieren.

**Unity LevelPlay / IronSource** (Unity Technologies)  
Dieses SDK wird ggf. für die Anzeigenvermittlung genutzt und kann vergleichbare Daten wie AdMob erheben.  
Datenschutzerklärung Unity: https://unity.com/legal/privacy-policy

Für Nutzer in der EU gelten für diese SDKs DSGVO-Einwilligungserfordernisse. Wo gesetzlich vorgeschrieben, wird vor der Anzeige personalisierter Werbung ein Einwilligungsdialog eingeblendet.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. a DSGVO — Einwilligung; Art. 6 Abs. 1 lit. f DSGVO — berechtigtes Interesse an der Bereitstellung eines kostenlosen Spiels, das durch optionale Werbung finanziert wird.

---

### 3.5 Geräte-Identifier (nur für Discord-Verifikation)

Wenn du die optionale **Discord-Verifikation** nutzt, liest die App deinen gerätespezifischen Identifier, um lokal einen Einmalcode zu generieren. Die ersten 4 alphanumerischen Zeichen dieses Identifiers fließen verschlüsselt in den Code ein.

**Dieser Identifier wird niemals an unsere Server übertragen.** Der Code wird vollständig auf deinem Gerät erzeugt und muss von dir manuell in unserem Discord-Server eingegeben werden. Ab diesem Zeitpunkt gelten Discords eigene Datenschutzbestimmungen.

**Rechtsgrundlage:** Art. 6 Abs. 1 lit. a DSGVO — Einwilligung (du initiierst diese Funktion aktiv).

---

## 4. Daten, die wir nicht erheben

Wir erheben nicht:

- Deinen echten Namen, deine E-Mail-Adresse, Telefonnummer oder Zugangsdaten
- Standortdaten (GPS o. Ä.)
- Kamera- oder Mikrofon-Daten
- Kontaktlisten oder sonstige Gerätedaten außerhalb der oben genannten

---

## 5. Drittanbieter & Datenübermittlungen

### 5.1 Leaderboard-Backend (Google Apps Script / Google LLC)

Unsere Rangliste läuft auf Google Apps Script, das Teil der Google-Infrastruktur ist. Bei der Übermittlung von Ranglisten-Daten (siehe Abschnitt 3.2) werden diese an Google-Server übertragen und dort gespeichert, die sich ggf. außerhalb der Europäischen Union befinden.

Solche Übermittlungen in die USA stützen sich auf das EU–US Data Privacy Framework (soweit anwendbar) sowie auf Googles Standardvertragsklauseln (SCCs) gemäß Art. 46 Abs. 2 lit. c DSGVO. Google handelt dabei als unser Auftragsverarbeiter.

### 5.2 Google Play / Google LLC

Alle In-App-Käufe und Abonnements werden von Google Play abgewickelt. Google ist für die Zahlungsverarbeitung eigenverantwortlicher Verantwortlicher.  
Details: https://policies.google.com/privacy

### 5.3 Discord Inc.

Die Discord-Verifikation ist vollständig freiwillig. Sobald du dort Daten eingibst, gilt Discords Datenschutzerklärung: https://discord.com/privacy

---

## 6. Offline-Datenpuffer

Wenn dein Gerät während eines Ranked-Runs keine Internetverbindung hat, wird deine Score-Einreichung temporär in einer lokalen Queue auf deinem Gerät gespeichert. Sie enthält dieselben Daten wie in Abschnitt 3.2 beschrieben. Die Queue wird automatisch geleert, sobald die Verbindung wiederhergestellt ist. Nach erfolgreicher Übermittlung wird der lokale Eintrag gelöscht.

---

## 7. Speicherdauer

- **Lokale Daten (PlayerPrefs):** Gespeichert auf deinem Gerät bis zur Deinstallation der App oder bis du unter Einstellungen → Alle Daten zurücksetzen den Spielstand löschst.
- **Ranglisten-Daten (serverseitig):** Gespeichert, solange du einen aktiven Leaderboard-Eintrag hast. Löschung jederzeit möglich (siehe Abschnitte 3.2 und 8).
- **Werbedaten:** Gemäß den jeweiligen Aufbewahrungsrichtlinien von Google AdMob und Unity LevelPlay.

---

## 8. Deine Rechte (DSGVO)

Sofern du dich im Europäischen Wirtschaftsraum (EWR) befindest, stehen dir folgende Rechte zu:

- **Auskunftsrecht** (Art. 15 DSGVO) — Du kannst Auskunft über die von uns gespeicherten Daten verlangen. Hinweis: Wir speichern keine Daten, die mit deiner echten Identität verknüpft sind. Zur Identifikation deiner Daten teile uns bitte deinen Benutzernamen#Tag mit.
- **Recht auf Berichtigung** (Art. 16 DSGVO) — Du kannst die Korrektur unrichtiger Daten verlangen.
- **Recht auf Löschung** (Art. 17 DSGVO) — Du kannst die Löschung deiner Daten verlangen. Ranglisten-Daten: Einstellungen → Account → Account löschen. Lokale Daten: Einstellungen → Alle Daten zurücksetzen.
- **Recht auf Einschränkung der Verarbeitung** (Art. 18 DSGVO)
- **Recht auf Datenübertragbarkeit** (Art. 20 DSGVO)
- **Widerspruchsrecht** (Art. 21 DSGVO) — insbesondere bezüglich Werbung (siehe Abschnitt 3.4).
- **Recht auf Widerruf der Einwilligung** — Du kannst eine erteilte Einwilligung jederzeit ohne Angabe von Gründen widerrufen. Die Rechtmäßigkeit der bis zum Widerruf erfolgten Verarbeitung bleibt davon unberührt.
- **Beschwerderecht** — Du hast das Recht, dich bei einer Datenschutzaufsichtsbehörde zu beschweren. Für uns zuständig ist: **Der Landesbeauftragte für Datenschutz und Akteneinsicht Brandenburg**, Stahnsdorfer Damm 77, 14532 Kleinmachnow, Deutschland.

Zur Ausübung deiner Rechte wende dich an: **void@julius-krassa.de**

---

## 9. Datenschutz für Minderjährige

VOID richtet sich nicht an Kinder unter 13 Jahren (bzw. unter 16 Jahren im EWR, soweit national abweichend geregelt). Wir erheben wissentlich keine personenbezogenen Daten von Kindern. Solltest du der Ansicht sein, dass ein Kind uns personenbezogene Daten übermittelt hat, kontaktiere uns bitte — wir löschen diese Daten unverzüglich.

---

## 10. Datensicherheit

Alle an unser Leaderboard-Backend übermittelten Daten werden über HTTPS verschlüsselt übertragen. Lokale Daten werden im Unity PlayerPrefs-System auf deinem Gerät gespeichert. Wir treffen angemessene technische Maßnahmen zum Schutz deiner Daten, können jedoch keine vollständige Sicherheit bei der Internetübertragung garantieren.

---

## 11. Änderungen dieser Datenschutzerklärung

Wir können diese Datenschutzerklärung von Zeit zu Zeit aktualisieren. Die jeweils aktuelle Version ist in der App und im App-Store-Eintrag abrufbar. Wir empfehlen, sie regelmäßig zu überprüfen. Die fortgesetzte Nutzung der App nach Änderungen gilt als Zustimmung zur aktualisierten Erklärung.
