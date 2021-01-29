# Leistungsbeschreibung OpenProject Enterprise Cloud

Stand: 2021-01-28 

Dieses SLA (Service Level Agreement / Dienstleistungsgütevereinbarung) ergänzt den Servicevertrag zwischen [OpenProject](https://www.openproject.org/de/impressum/) und dem Kunden. Es spezifiziert den Service-Level in Bezug auf den Service [OpenProject Enterprise Cloud](https://www.openproject.org/de/hosting/). Wir können dieses SLA von Zeit zu Zeit nach eigenem Ermessen aktualisieren.

## 1. Unterstützung

### 1.1 Service-Level für den Support

 OpenProject stellt seine Dienste in verschiedenen Support-Servicestufen zur Verfügung, die wie folgt definiert sind:

| Support-Servicestufe                                     | Professional Support                           | Premier Support        | Corporate Support      |
| -------------------------------------------------------- | ---------------------------------------------- | ---------------------- | ---------------------- |
| Servicezeiten                                            | Mo-Fr, 09:30-17:30 Uhr                         | Mo-Fr, 09:30-17:30 Uhr | Mo-Fr, 09:00-18:00 Uhr |
| Antwortzeit –  kritischer Fehler                         | 8 h                                            | 6 h                    | 2 h                    |
| Antwortzeit –  Hauptfehler                               | Best effort (nach besten Kräften und Gewissen) | 12 h                   | 6 h                    |
| Antwortzeit – Nebenfehler                                | Best effort (nach besten Kräften und Gewissen) | 48 h                   | 24 h                   |
| Geplanter  Bereitschaftsdienst und Upgrade-Unterstützung | -                                              | Inklusive              | Inklusive              |
| Priorisierte Entwicklung und Eskalation                  | -                                              | Inklusive              | Inklusive              |

### 1.2 Prioritäten bei Vorfällen

**Kritische Fehler** sind Vorfälle, die die Nutzung von OpenProject verhindern oder erheblich beeinträchtigen, z. B. durch Fehlfunktionen, falsche Ergebnisse oder Reaktionszeiten, und die nicht mit zumutbaren organisatorischen Mitteln behoben werden können (kritische Bedienungsfehler).

*Beispiel:*

- Anzeige einer bildschirmfüllenden Fehlermeldung beim Zugriff auf die OpenProject-Landingpage.

**Hauptfehler** sind Störungen, die ohne größere Schwierigkeiten umgangen werden können oder die einen Teil von OpenProject betreffen, der die Nutzung nicht direkt oder wesentlich beeinträchtigt.

*Beispiel:*

- Die OpenProject-Anwendung sendet keine automatischen E-Mail-Benachrichtigungen.

**Nebenfehler** sind Vorfälle, die Funktionalitäten betreffen, die für die Benutzer nicht häufig relevant sind und die von geringer Bedeutung sind, so dass der Benutzer die Funktionalität nicht über einen längeren Zeitraum benötigt.

*Beispiel:*

- Beim Zugriff auf eine bestimmte Arbeitspaketabfrage wird die Fehlermeldung "Internal Server Error" angezeigt.

- Das Abspeichern eines Kostenberichts ist nicht möglich.

- In der Projektübersichtsseite überschneiden sich zwei Widgets, die aber noch nutzbar sind.


### 1.3 Kommunikationskanal für den Support

 OpenProject stellt seine Supportleistungen mit unterschiedlichen Kommunikationskanälen wie folgt zur Verfügung:

|Support-Servicestufe                      |Professional  Support |Premier  Support |Corporate  Support |
| ----------------------------------------- | --------------------- | ---------------- | ------------------ |
|Ticket                                    |-                     |Enthalten        |Enthalten          |
|E-Mail                                    |Enthalten             |Enthalten        |Enthalten          |
|Telefon                                   | -                     |Enthalten        |Enthalten          |
|Remote login / remote hands              | - |Enthalten        | Enthalten |
|Dedizierter Support-Verantwortlicher     | - | - | Enthalten         |
|Anzahl Supportkontakte (auf Kundenseite) |1                     |3                |8                  |

## 2. Serviceverfügbarkeit

### 1.1 Verfügbarkeit

OpenProject GmbH wird die Dienste zu 99,9 % der Zeit verfügbar machen, ausgenommen entschuldigte Ausfallzeiten. In einem bestimmten Kalendermonat berechnen wir die *Serviceverfügbarkeit* wie folgt: 

**Serviceverfügbarkeit = Gesamtminuten, in denen die Services verfügbar sind x 100 / (Gesamtminuten im Monat – Entschuldigte Ausfallzeiten)**

### 2.1 Entschuldigte Ausfallzeit

Als entschuldigte Ausfallzeit wird die Zeitspanne bezeichnet, in der die Dienste nicht verfügbar sind aufgrund von:

1.  Geplante Wartung;

2.  Notfall-Wartung;

3.  Beta-Dienste;

4.  Ereignisse höherer Gewalt; und

5.  Handlungen oder Unterlassungen von Ihnen, Ihren autorisierten Nutzern oder Dritten, die in Ihrem Namen oder auf Ihre Anweisung hin handeln, einschließlich einer nicht autorisierten Nutzung der Dienste, eines Verstoßes gegen den Vertrag oder die Richtlinien zur akzeptablen Nutzung (Acceptable Use Policy) oder einer Nutzung oder Konfiguration der Dienste, die die Empfehlungen oder angekündigten Grenzen von OpenProject überschreitet.


### 2.2 Planmäßige Wartung

Zu den **planmäßigen Wartungsarbeiten** gehören alle Wartungsarbeiten, die in den folgenden Zeitfenstern durchgeführt werden oder für die wir eine angemessene Vorankündigung oder Abstimmung mit Ihnen im Vorfeld der Wartungsarbeiten vornehmen.

| Standort des  Rechenzentrums | Wartungsfenster          |
| ---------------------------- | ------------------------ |
| Europäische Union            | 6:00 Uhr - 08:00 Uhr MEZ |

### 2.3 Notfallwartung

**Notfallwartung** bedeutet jede Wartung, die außerhalb der geplanten Wartungsfenster ohne vorherige Ankündigung durchgeführt wird, wenn eine solche Wartung vernünftigerweise und dringend erforderlich ist, um die Integrität, Verfügbarkeit oder Sicherheit von Online-Systemen zu schützen.

### 2.4 SLA-Gutschriften

Sie haben Anspruch auf eine Gutschrift in Höhe von 5 % der jeweiligen monatlichen Gebühren für jede volle Stunde Ausfallzeit, die über die Serviceverfügbarkeitsziele hinausgeht. (Zum Beispiel erhalten Sie eine Gutschrift in Höhe von 5 % für eine Ausfallzeit zwischen 1 und 60 Minuten, die über die Serviceverfügbarkeitsziele hinausgeht, eine Gutschrift in Höhe von 10 % für eine Ausfallzeit zwischen 61 und 120 Minuten, usw.) Um eine Gutschrift zu erhalten, müssen Sie sich innerhalb von 30 Tagen nach dem Ereignis, das zu der Gutschrift geführt hat, an den Support wenden. Gutschriften basieren auf unserer Überwachung, dürfen 100 % der anwendbaren monatlichen Gebühren nicht überschreiten, können nicht übertragen oder kumuliert werden, verfallen bei Ablauf oder Beendigung der Vereinbarung und werden nicht ausgezahlt oder als Erstattung gewährt.

## 3. Backup

### 3.1 Datenbank

Es werden automatisierte Amazon Relational Database Service (RDS) Backups durchgeführt. Tägliche Snapshots und Transaktionsprotokolle werden 30 Tage lang aufbewahrt, um eine punktgenaue Datenwiederherstellung innerhalb dieses Zeitrahmens zu ermöglichen. Sowohl Snapshots als auch Transaktionsprotokolle werden sicher in S3 gespeichert.

OpenProject Enterprise Cloud unterstützt nicht die Verwendung von Sicherungsdaten für das Rollback von Änderungen.

### 3.2 Anhänge

Anhänge werden ebenfalls sicher in S3 gespeichert. Der S3-Speicher ist verschlüsselt und wird über mehrere Verfügbarkeitszonen innerhalb derselben Region repliziert. Dies bietet eine Verfügbarkeit von 99,99 %. Darüber hinaus sind Dateien versioniert. Das heißt, selbst wenn sie gelöscht werden, können sie im Bedarfsfall wiederhergestellt werden. Die Anhänge und ihre Versionen bleiben über die gesamte Laufzeit des Abonnements erhalten.

## 4. Software-Aktualisierungen

OpenProject wird die Software, die den Service zur Verfügung stellt, innerhalb von 10 Tagen nach einer Freigabe auf die höchste freigegebene [Version](https://docs.openproject.org/release-notes/) der OpenProject-Anwendung aktualisieren. OpenProject kann auch noch nicht freigegebene Patches für die Software installieren, falls diese den Dienst verbessern. Jede installierte Softwareversion wird von OpenProject vor dem Einsatz getestet. Sollte das Update eine Ausfallzeit erfordern, wird OpenProject den Kunden mit einer Frist von 3 Tagen über die geplante Ausfallzeit informieren.

## 5. Richtlinie zur akzeptablen Nutzung

Sie dürfen unseren Geschäftsbetrieb oder unsere Fähigkeit, Dienstleistungen für andere Kunden zu erbringen, nicht beeinträchtigen und keine Handlungen vornehmen oder die Dienstleistungen nutzen, die das Netzwerk oder die Systeme, die zur Erbringung dieser Dienstleistungen verwendet werden, übermäßig belasten. Insbesondere dürfen Sie den Dienst nicht für andere Anwendungsfälle als Projektmanagement, Teamzusammenarbeit, Produktmanagement und Product Lifecycle Management nutzen.

Sie dürfen ohne unsere vorherige schriftliche Genehmigung keine Schwachstellen- oder Penetrationstests des Netzwerks oder der Systeme von OpenProject durchführen.