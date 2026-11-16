# vps kaufen: Was ein VPS wirklich kostet, welcher Tarif reicht – und für wen sich Vultr lohnt (Tarifvergleich, Laufzeiten, $300-Credit)

Ein VPS für ein kleines Projekt kostet in Deutschland zwischen 2 und 10 Euro im Monat. Sobald 4 GB RAM und etwas Reserve für Datenbank und Container dazukommen, liegt man bei 15 bis 20 Euro. Bei Vultr beginnt der Cloud-Compute-Einstieg bei $2,48 im Monat, der Tarif mit 2 vCPU und 4 GB RAM kostet $20,00, abgerechnet wird stündlich und ohne Mindestlaufzeit.

Ob ein Angebot günstig bleibt, entscheiden drei Dinge, die selten auf dem Plakat stehen: die Vertragslaufzeit, die Frage netto oder brutto und die Funktionsdecke des Einstiegstarifs. Alle drei lassen sich mit den aktuellen Preislisten von IONOS, netcup und OVHcloud belegen, und alle drei gelten unabhängig davon, bei wem man am Ende bestellt.

> **Auf einen Blick**
> - **Test, Blog, ein einzelner Container:** der 1-GB-Tarif für **$5,00/Monat** mit 1 vCPU, 25 GB SSD und 1 TB Traffic.
> - **n8n, Docker, kleine Datenbank, WordPress mit Plugins:** 2 vCPU, 4 GB RAM, 80 GB Local SSD für **$20,00/Monat**, 3 TB Traffic inklusive.
> - Stundengenaue Abrechnung, keine Mindestlaufzeit, Monatsdeckel bei 672 Stunden. Kein Vertrag, aber auch keine Rückerstattung.
> - 👉 [Alle Tarife und Konfigurationen auf der Vultr-Preisseite ansehen](https://bit.ly/VuLtr)

## Die Vultr-Tarife im Überblick

Vultr fährt ein anderes Preismodell als die klassischen deutschen VPS-Anbieter: keine Vertragslaufzeit, keine Einrichtungsgebühr, Abrechnung pro angefangener Stunde. Der Monatspreis ist eine Hochrechnung, die bei 672 abrechenbaren Stunden gedeckelt wird. Wer den Server nach zwei Tagen wieder löscht, zahlt auch nur zwei Tage.

| Tarif | vCPU | RAM | Speicher | Preis | Bestellen |
| --- | --- | --- | --- | --- | --- |
| Cloud Compute Einstieg (vc2, 0,5 GB) | 1 | 0,5 GB | – | $2,48/Monat ($0,0034/Std.) | [Einstiegstarif ansehen](https://bit.ly/VuLtr) |
| Cloud Compute 1 GB (vc2) | 1 | 1 GB | 25 GB SSD | $5,00/Monat ($0,007/Std.), 1 TB Traffic | [1-GB-Tarif ansehen](https://bit.ly/VuLtr) |
| Cloud Compute 2 vCPU / 4 GB | 2 | 4 GB | 80 GB Local SSD | $20,00/Monat, 3 TB Traffic inklusive | [4-GB-Tarif ansehen](https://bit.ly/VuLtr) |
| GPU-Instanz (vx1, 96 vCPU) | 96 | 384 GB | – | $2.102,40/Monat | [GPU-Klasse ansehen](https://bit.ly/VuLtr) |

Vultr listet derzeit über 100 Konfigurationen in elf Instanzfamilien und betreibt nach eigenen Angaben 30 Standorte auf sechs Kontinenten. Die Tabelle zeigt die Stufen, zwischen denen die meisten Projekte liegen. Für alles darüber entscheidet die Frage, ob die Last CPU-, RAM- oder Speicher-getrieben ist, und dafür gibt es bei Vultr eigene Familien.

Neben dem On-Demand-Preis gibt es zwei weitere Abrechnungswege:

| Modell | Abrechnung | Konditionen |
| --- | --- | --- |
| On-Demand | stündlich | keine Mindestlaufzeit, Monatsdeckel 672 Stunden |
| Reserved | 1 bis 3 Jahre | typischerweise 30–40 % Rabatt bei einem Jahr, 55–70 % bei drei Jahren |
| Spot | stündlich | Restkapazität, günstigster Preis, Instanz kann entzogen werden |

Für deutschsprachige Leser ist der relevante Punkt nicht der Rabatt, sondern die Umkehrung: Wer bei Vultr monatlich kündbar bleibt, zahlt den Listenpreis, hat aber auch keine Bindung. Genau das ist bei den hiesigen Anbietern selten.

## Was „ab 2 €“ in deutschen Preislisten bedeutet

IONOS bewirbt Cloud VPS mit „ab 2 €/Monat“, und auf derselben Seite steht der entscheidende Satz: Die Preise sind inklusive Mehrwertsteuer, die Angebote gelten nur für begrenzte Zeit und hängen teils von Mindestvertragslaufzeiten ab. Der Einstiegspreis ist also keine dauerhaft verfügbare Preislinie, sondern eine befristete Aktion mit Bedingungen.

Bei netcup lässt sich der Zusammenhang zwischen Laufzeit und Preis direkt ablesen, weil die Lite-Tarife nach Vertragsbindung gestaffelt sind:

| Tarif | Laufzeit | Preis pro Monat (netto) |
| --- | --- | --- |
| VPS pico (1 vCore, 1 GB, 30 GB SSD) | 12 Monate | 2,21 € |
| VPS nano (2 vCore, 2 GB, 60 GB SSD) | 6 Monate | 3,69 € |
| VPS Lite 1 (2 vCore, 4 GB, 80 GB SSD) | 6 Monate | 5,86 € |
| VPS Lite 2 (4 vCore, 8 GB, 160 GB SSD) | 3 Monate | 9,50 € |
| VPS Lite 3 (8 vCore, 16 GB, 320 GB SSD) | 2 Monate | 16,66 € |
| VPS Lite 4 (16 vCore, 32 GB, 640 GB SSD) | 1 Monat | 30,86 € |

Der günstigste monatlich kündbare Tarif der Lite-Reihe kostet 30,86 € netto. Dieselbe Rechenleistungsklasse mit sechs Monaten Bindung liegt bei 5,86 €. Wer die 2,21 € liest und „günstig“ denkt, bindet sich für ein Jahr an 1 GB RAM. Das ist kein Betrug, aber es ist der Preis dafür, dass der Anbieter planen kann, und dieser Preis gehört zur Kalkulation.

Bei Vultr fällt diese Staffel weg. Dafür ist der Listenpreis höher als der deutsche Aktionspreis: $2,48 für 0,5 GB, $5,00 für 1 GB. Wer nur ein Wochenende lang etwas ausprobieren will, fährt mit stündlicher Abrechnung trotzdem billiger als mit jedem Jahresvertrag.

## Netto oder brutto: der Unterschied sind schnell 19 Prozent

netcup gibt für den VPS 500 G12.5 (2 vCore, 4 GB RAM, 64 GB SSD, 12 Monate Laufzeit) 8,26 € netto und 9,50 € inklusive 19 % Mehrwertsteuer an. IONOS schreibt den Preis direkt inklusive Steuer auf die Seite. Wer die 8,26 € mit einer Bruttoangabe eines anderen Anbieters vergleicht, vergleicht zwei verschiedene Dinge und kommt zu einem Ergebnis, das um die Umsatzsteuer daneben liegt.

Für Selbstständige und Unternehmen ist der Nettopreis die relevante Zahl, weil die Vorsteuer zurückkommt. Für Privatkunden zählt der Bruttobetrag. Bei Vultr kommt ein dritter Faktor dazu: Die Preise sind in US-Dollar ausgegeben. Wechselkurs und Umsatzsteuer auf der Rechnung entscheiden darüber, was am Ende vom Konto geht, und der Kurs schwankt zwischen Bestellung und Abrechnung.

Rechnen Sie vor dem Vergleich alle Angebote auf dieselbe Basis: brutto, gleiche Laufzeit, gleicher Währungsstand.

## Wo die Billigtarife enden

Die günstigsten Tarife sind nicht nur kleiner, sie können auch weniger. Drei belegte Beispiele:

- **netcup:** VPS pico und VPS nano lassen sich nicht mit Local Block Storage erweitern. Bei allen anderen VPS-Tarifen wächst der Zusatzspeicher in Stufen bis 4 TB, bei Root-Servern bis 8 TB, berechnet mit 0,012 € pro GB und Monat zuzüglich Mehrwertsteuer.
- **OVHcloud:** Die Local-Zone-Variante der VPS unterstützt laut Anbieter weder Windows noch Plesk, cPanel oder Docker, zusätzliche IP-Adressen und Loadbalancer sind ebenfalls nicht verfügbar. Wer später eine zweite IP oder einen Loadbalancer braucht, kommt dort nicht weiter.
- **IONOS:** Die Plesk-Obsidian-Lizenz (Web Host Edition, 5 €/Monat) setzt mindestens einen VPS Linux S voraus und ist mit dem Einstiegsmodell VPS Linux XS nicht kompatibel. Auf Linux braucht Plesk zusätzlich mindestens 20 GB Speicher, auf Windows 32 GB. Inklusive ist genau eine IPv4-Adresse, jede weitere kostet 5 €/Monat.

Daraus folgt eine Checkliste, die vor der Bestellung zehn Minuten kostet und später Tage:

1. Welche Software kommt auf den Server? Plesk, cPanel, Docker, Windows?
2. Brauchen Sie mehr als eine öffentliche IPv4-Adresse?
3. Soll der Speicher später unabhängig vom Tarif wachsen können?
4. Ist ein Loadbalancer oder ein zweiter Standort geplant?
5. Wie viel RAM braucht die Anwendung im schlechtesten Fall, nicht im Durchschnitt?

Wer Punkt 1 mit „Plesk“ beantwortet, sollte den Einstiegstarif streichen und einen Tarif mit mindestens 20 GB Speicher wählen. Wer Punkt 3 mit „ja“ beantwortet, sollte bei netcup nicht zu pico oder nano greifen.

## Backups: im Tarif enthalten oder pro Gigabyte bezahlt

OVHcloud hat tägliche Backups in die neue VPS-Reihe aufgenommen, mit Wiederherstellungspunkten bis zu sieben Tage zurück, dreifach im selben Rechenzentrum kopiert und mit wählbarem Erstellungszeitpunkt. IONOS behandelt Backups als Option: Acronis ab 6 Cent pro GB und Monat. Bei einem Server mit 80 GB belegtem Speicher sind das knapp 5 € monatlich zusätzlich, und diese Position fehlt in jedem Preisvergleich, der nur die Tarifzeile liest.

netcup führt in den Tarifmerkmalen Snapshots und eine Remote-Konsole auf. Ein tägliches automatisches Backup steht dort nicht als Tarifbestandteil.

Klären Sie bei jedem Anbieter, ob ein Rücksetzpunkt ohne Zusatzbuchung existiert. Ein Snapshot, den Sie selbst vor jedem Update auslösen, ersetzt kein tägliches Backup, und ein Backup im selben Rechenzentrum ersetzt keine externe Kopie.

## Stoppen heißt bei Vultr nicht abschalten

Vultr rechnet ab dem Moment ab, in dem eine Instanz bereitgestellt wird, und zwar unabhängig davon, ob sie läuft oder gestoppt ist. Die Abrechnung endet erst, wenn die Instanz gelöscht wird. Wer abends den Server herunterfährt und morgens wieder startet, spart nichts.

Das ist der Punkt, an dem sich stündliche Abrechnung und Gewohnheiten aus der Vertragswelt treffen. Bei einem Monatsvertrag ist der Preis fix, egal ob der Server läuft. Bei Vultr kostet ein vergessener Testserver pro Monat weiter Geld, bis jemand ihn löscht. Für Testumgebungen heißt das: nach dem Test löschen, nicht stoppen.

Zusätzlich gilt laut Vultr: Für Dienste werden keine Zahlungen erstattet, alle Zahlungen sind endgültig, und Guthaben ist nicht rückzahlbar. Es gibt also keine Geld-zurück-Frist, innerhalb derer man aus einem Fehlkauf herauskommt. Bei netcup ist das ähnlich geregelt, dort sind die VPS-Tarife ausdrücklich von der Zufriedenheitsgarantie der Root-Server ausgenommen.

## Der $300-Credit: was er wirklich abdeckt

Vultr führt auf seiner Coupon-Seite mehrere Aktionscodes, darunter **FLY300VULTR** mit $300 Startguthaben, **FLYTWOHUNDRED** mit $200, **250VULTRFLY** mit $250 und **VULTRMATCH**, bei dem Vultr die erste Einzahlung bis $100 verdoppelt. Alle richten sich an Neukunden, gelten nur für ausgewählte Produkte und lassen sich nicht mit anderen Aktionen kombinieren.

Die Bedingungen des $300-Guthabens sind an wenigen Stellen vollständig dokumentiert, und sie entscheiden darüber, ob die Aktion etwas bringt:

- Für die Gutschrift muss eine Kreditkarte oder PayPal hinterlegt werden.
- Mehrfachkonten sind nicht berechtigt.
- Ungenutztes Guthaben verfällt nach 30 Tagen.
- Das Guthaben ist keine Gutschrift auf der Rechnung, sondern ein Verbrauchsguthaben. Was nicht verbraucht wird, kommt nicht als Geld zurück.

Die Einblendung auf der Startseite war zuletzt bis Anfang November befristet. Prüfen Sie vor der Bestellung, ob der Code noch aktiv ist, und lesen Sie die Bedingungen im Konto, nicht in einem fremden Blogbeitrag.

Praktisch heißt das: Der $300-Credit lohnt sich für ein Projekt, das innerhalb von 30 Tagen einen echten Testlauf braucht, etwa einen Lasttest, eine Migration oder den Vergleich zweier Standorte. Für ein dauerhaft laufendes Projekt ist VULTRMATCH die bessere Wahl, weil verdoppeltes Echtgeld nicht verfällt. Wer den Credit nimmt und den Server nach drei Wochen noch laufen hat, zahlt ab Tag 31 den regulären Preis.

👉 [Aktuelle Codes und Konditionen direkt bei Vultr prüfen](https://bit.ly/VuLtr)

## Wo die Daten liegen

OVHcloud bewirbt VPS in Deutschland und Europa damit, dass der Dienst nicht in den Geltungsbereich des US-amerikanischen CLOUD Act fällt und vor außereuropäischer Einflussnahme geschützt ist. IONOS nennt nach ISO 27001 zertifizierte Rechenzentren und bietet einen gesonderten Vertrag zur Auftragsverarbeitung im Sinne des Bundesdatenschutzgesetzes an.

Das sind zwei verschiedene Argumente. Das eine betrifft den Rechtsraum, in dem der Anbieter sitzt, das andere die Vertrags- und Zertifizierungsgrundlage. Wenn für Ihr Projekt eine Auftragsverarbeitung nach DSGVO oder ein EU-Standort aus Compliance-Gründen vorgeschrieben ist, klären Sie beides vor der Bestellung: Firmensitz des Anbieters, Standort des Rechenzentrums, Verfügbarkeit eines AVV. Bei Vultr stehen diese Angaben nicht in den Tarifdaten, sie gehören deshalb auf Ihre eigene Prüfliste und nicht in eine Empfehlung.

## Welcher Tarif für welches Projekt

**Blog, Portfolio, Testumgebung:** 1 vCPU, 1 GB RAM, 25 GB SSD für $5,00. Für statische Seiten und ein kleines WordPress mit wenigen Plugins reicht das. Bei mehr als zwei oder drei Plugins mit Datenbankzugriff wird es eng.

**n8n, Docker, kleine API, Datenbank:** 2 vCPU, 4 GB RAM, 80 GB Local SSD für $20,00. Das ist die Stufe, unter der Docker-Workflows und eine kleine Postgres-Instanz unangenehm werden. 3 TB Traffic sind in dieser Klasse enthalten.

**WordPress mit mehreren Instanzen oder ein Shop:** oberhalb von 4 GB RAM. Eine konkrete Zahl wäre hier geraten, deshalb der Weg über die Tarifseite: Eine Stufe höher, stündlich abgerechnet, zwei Wochen messen, dann entscheiden. Genau dafür ist das Abrechnungsmodell da.

**Gameserver:** CPU-lastig, oft nur zu bestimmten Zeiten ausgelastet. Stündliche Abrechnung ohne Mindestlaufzeit passt besser zu einem Server, der abends voll läuft und nachts leer ist, als ein Jahresvertrag.

**Agentur mit Plesk:** Plesk kostet bei IONOS 5 €/Monat zusätzlich und verlangt mindestens 20 GB Speicher auf Linux. Wer Plesk braucht, sollte den Tarif nach dem Speicherbedarf wählen und nicht nach dem Einstiegspreis.

Wer nur einen SSH-Zugang für gelegentliche Tests braucht, ist mit 0,5 GB RAM für $2,48 ausreichend versorgt. Mehr als 90 % der Leser, die einen VPS für ein laufendes Projekt suchen, brauchen diese Stufe nicht und werden mit ihr auch nicht glücklich.

## Häufige Fragen

**Was kostet ein VPS in Deutschland im Monat?**
Zwischen 2 und 20 Euro für die üblichen Einstiegs- bis Mittelklasse-Tarife. IONOS bewirbt „ab 2 €“ inklusive Mehrwertsteuer als befristete Aktion, netcup startet bei 2,21 € netto mit zwölf Monaten Laufzeit, Vultr bei $2,48 für 0,5 GB und $5,00 für 1 GB ohne Laufzeit.

**Monatlich oder jährlich buchen?**
Hängt davon ab, ob Sie den Server länger als ein Quartal brauchen. Bei netcup kostet derselbe Tarif monatlich kündbar 30,86 € statt 5,86 € bei sechs Monaten Bindung. Bei Vultr gibt es diese Staffel nicht, dafür liegt der Listenpreis über dem deutschen Aktionspreis.

**Kann ich später upgraden oder den Standort wechseln?**
IONOS erlaubt das Upgrade jederzeit im Control Center. Bei OVHcloud ist ein Upgrade nur innerhalb desselben Rechenzentrums möglich, ein Wechsel des Standorts ist damit nicht verbunden. Wer den Standort wechseln will, braucht in beiden Fällen einen neuen Server und eine Migration.

**Sind Backups inklusive?**
Bei OVHcloud in der neuen VPS-Reihe ja, mit sieben Tagen Wiederherstellung. Bei IONOS nein, Acronis kostet ab 6 Cent pro GB und Monat. Bei Vultr gehören Backup und Snapshot nicht zum Tarifpreis und sollten vor der Bestellung auf der Preisseite geprüft werden.

**Gibt es eine Geld-zurück-Garantie?**
Bei Vultr nicht: Zahlungen sind endgültig, Guthaben ist nicht rückzahlbar. Bei netcup sind VPS-Tarife von der Zufriedenheitsgarantie ausgenommen, die für Root-Server gilt. Wer unsicher ist, sollte den günstigsten Tarif für einen Monat nehmen und messen, statt direkt den großen zu buchen.

## Die Entscheidung in zwei Sätzen

Sie brauchen einen Server, den Sie nach dem Test wieder löschen können, ohne aus einem Vertrag herauszukommen: der 1-GB-Tarif für $5,00, stündlich abgerechnet. Sie brauchen eine Umgebung, in der Docker-Container, eine Datenbank und ein paar Automationen gleichzeitig laufen: 2 vCPU mit 4 GB RAM für $20,00.

Zwei Dinge vor dem Klick auf „Deploy“: die Instanz nach dem Test löschen statt stoppen, und den Aktionscode samt Ablaufdatum im Konto prüfen, bevor Sie ihn als festen Rabatt einkalkulieren.

👉 [Vultr-Tarife vergleichen und Instanz starten](https://bit.ly/VuLtr)
