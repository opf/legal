# Anlage 1: Technische und organisatorische Maßnahmen zur Datensicherheit

Die in dieser Anlage durch den Auftragnehmer definierten Datensicherheitsmaßnahmen werden als verbindlich festgelegt.

## 1. Vertraulichkeit (Art. 32 Abs. 1 lit. b DS-GVO)

### 1.1. Zutrittskontrolle

Die Datenverarbeitung durch den Auftragnehmer findet in einem gesicherten Rechenzentrum statt. Das Rechenzentrum ist nach Standard ISO 27001 für das Informationssicherheits-Managementsystem zertifiziert. Der Zutritt zu dem Rechenzentrum wird durch modernste Kontrollsysteme gesichert. Hierzu gehören folgende Sicherheitsmaßnahmen und -infrastrukturen:

- Untergliederung der Einrichtung in einzelne Sicherheitsbereiche,

- physikalischer Zutrittsschutz beispielsweise durch Stahltüren, fensterlose Räume oder gesicherte Fenster,

- Schutz der Sicherheitsbereiche durch ein elektronisches Zutrittskontrollsystem,

- Überwachung der Einrichtung durch Sicherheitsdienst und Protokollierung der Zutritte,

- Videoüberwachung aller sicherheitsrelevanten Sicherheitsbereiche, wie Eingänge, Notausgänge und Serverräume,

- zentrale Vergabe und Entzug der Zutrittsberechtigung,

- Identifikation aller Besucher mittels Personalausweis,

- Ausweispflicht innerhalb der Sicherheitsbereiche für alle Mitarbeiter und Besucher,

- kontinuierliche Begleitung von Besuchern durch Mitarbeiter.


### 1.2. Zugangskontrolle

Der Auftragnehmer hat das Eindringen Unbefugter in Systeme und Anwendungen, die zur Verarbeitung von personenbezogenen Daten eingesetzt werden, zu verhindern. Der Auftragnehmer gewährleistet dies, indem ausschließlich explizit autorisierte Administratoren Zugang zu den datenverarbeitenden Systemen des IaaS-Anbieters erhalten. Die Anmeldung erfolgt ausschließlich per Multi-Faktor-Authentifizierung anhand der im jeweiligen persönlichen Benutzerkonto hinterlegten Anmelde-Informationen. Darüber hinaus kommt ein differenziertes Rechtesystem anhand von Sicherheitsgruppen und Zugriffskontrolllisten zum Einsatz. Die Anmeldung ist ausschließlich über Verbindungen möglich, welche über den aktuellen Stand der Technik verschlüsselt werden.

Zu weiteren Absicherung des Zugangs sind die einzelnen Dienste und Komponenten in mehrere Netzwerksegmente aufgeteilt. Die Isolation erfolgt durch hardwarebasierte Firewall-Systeme und Virtual Private Clouds (VPC). Sämtliche Zugänge auf Systeme und Anwendungen werden zentral dokumentiert, überwacht und protokolliert.

Das bürointerne Netzwerk wird durch eine hardwarebasierte Firewall gegen den unbefugten Zugang von außen geschützt. Der Zugang zu Rechnern in den Büroräumen des Auftragnehmers wird über Benutzerkonten kontrolliert. Auf das bürointerne Netzwerk kann von außerhalb der Büroräume ausschließlich über eine verschlüsselte VPN-Verbindung (Virtual Private Network) zugriffen werden. 

Der Auftraggeber kann auf seine OpenProject-Instanz ausschließlich über eine verschlüsselte Verbindung (SSL/HTTPS) zugreifen.

### 1.3. Zugriffskontrolle

Der Auftragnehmer hat unerlaubte Tätigkeiten in den datenverarbeitenden Systemen zu verhindern. Demzufolge hat ausschließlich der betreffende Auftraggeber sowie eine kleine Gruppe einzeln benannter Administratoren Zugriff auf die Daten. Es wird technisch sichergestellt, dass ein Auftraggeber keine Daten anderer Auftraggeber einsehen, verändern oder löschen kann. Innerhalb einer OpenProject-Instanz wird der Zugriff über ein umfangreiches Rollen- und Berechtigungskonzept gesteuert. Innerhalb der OpenProject Instanz erfolgt die Rechtevergabe durch den Auftraggeber durch Rollen- und Rechtezuweisungen. Der Auftraggeber hat zusätzlich die Möglichkeit, für seine Organisation über eine Administrationsoberfläche die vorkonfigurierten Rollen und Rechte auf seine Bedürfnisse hin anzupassen. 

Der Zugriff auf Daten des Auftraggebers für Kundendienst-Mitarbeiter des Auftragnehmers ist auf Stammdaten und Abrechnungsdaten beschränkt, welche für die Wahrnehmung ihrer Kundendienst-Aufgabe und der Abrechnung der Hosting-Dienstleistung erforderlich sind. Kundendienst-Mitarbeiter haben keinen Zugriff auf die Kundendaten innerhalb einer OpenProject-Instanz. 

Kreditkarten-Daten ihrer Auftraggeber werden ausschließlich durch den Bezahldienstleister gespeichert; der Auftragnehmer hat keinen Zugriff auf diese Daten. 

Administratoren ist der Zugriff auf Kundendaten nur gestattet, wenn eine Störung vorliegt, die nicht durch den Auftraggeber und oder den Kundendienst des Auftragnehmers alleine gelöst werden kann.

### 1.4. Trennungskontrolle

Sämtliche Datensätze, die von den Systemen und Anwendungen des Auftragnehmers erhoben, verarbeitet oder genutzt werden, werden explizit und eindeutig dem jeweiligen Auftraggeber zugeordnet und technisch von anderen Daten getrennt. Die datenverarbeitenden Systeme des Auftragnehmers sind speziell auf die zweckgebundene und mandantengerechte Verarbeitung ausgerichtet. Der Zugriff auf die Daten eines anderen Auftraggebers ist damit technisch ausgeschlossen.

### 1.5. Pseudonymisierung (Art. 32 Abs. 1 lit. a DS-GVO; Art. 25 Abs. 1 DS-GVO)

Die Pseudonymisierung soll gewährleisten, dass die Identifizierung der von der Datenverarbeitung betroffenen Person ausgeschlossen bzw. wesentlich erschwert wird.

Die Daten von gelöschten Nutzern in OpenProject werden anonymisiert, sodass keine Zuordnung zu den jeweiligen Personen mehr möglich ist.

## 2. Integrität (Art. 32 Abs. 1 lit. b DS-GVO)

### 2.1. Weitergabekontrolle

Die Kontrolle der Weitergabe von Daten des Auftraggebers wird durch verschiedene technische und organisatorische Sicherheitsmaßnahmen gewährleistet. Hierbei speichert der Auftragnehmer Daten des Auftragnehmers nicht außerhalb des Rechenzentrums. Mitarbeiter des Rechenzentrumbetreibers haben keinen Zugriff oder Zugang zu den Kundendaten, können diese also weder einsehen, löschen oder verändern. Datensicherungen werden ausschließlich verschlüsselt abgelegt. Ein Transport von Daten des Auftraggebers auf physischen Datenträgern erfolgt nicht. Zum Zwecke der Abrechnung der Dienstleistung werden Abrechnungsdaten über eine verschlüsselte Verbindung in die Buchhaltungssysteme des Auftragnehmers überführt. 

### 2.2. Eingabekontrolle     

Der Auftragnehmer hat die Nachvollziehbarkeit bzw. Dokumentation der Datenverarbeitung zu gewährleisten. Hierzu werden alle Eingaben in die Systeme und Anwendungen durch den Auftragnehmer protokolliert. Die Protokolle werden archiviert und nach Zweckerreichung oder gesetzlichen Vorgaben gelöscht. Die OpenProject-Applikation unterstützt die Eingabe und Änderung der eigenen Daten ausschließlich über hierzu vorgesehene Nutzeroberflächen und Schnittstellen gemäß einem detaillierten Rollen- und Berechtigungskonzept. Bei vielen Objekten kann der Auftraggeber auch über die Weboberfläche die Änderungshistorie von Daten einsehen (z.B. Arbeitspakete, Wiki-Seiten, SCM-Repositories).  

## 3.   Verfügbarkeit (Art. 32 Abs. 1 lit. b DS-GVO)

### 3.1. Verfügbarkeitskontrolle

Der Auftragnehmer hat personenbezogene Daten gegen zufällige Zerstörung oder Verlust zu schützen. Hierzu ist die Architektur der datenverarbeitenden Systeme des Auftragnehmers einschließlich der Netzwerkinfrastruktur, der Stromversorgung und der Anbindung an das Internet redundant ausgelegt. 

Zur Vermeidung von Datenverlusten ist ein umfangreiches Sicherungs- und Wiederherstellungs-Konzept implementiert. Die Daten des Auftraggebers werden kontinuierlich über einen Replikationsmechanismus in separaten Verfügbarkeitszone gesichert. Zusätzlich werden täglich vollständige Sicherungen aller Systeme und Daten vorgenommen. 

Die Systeme und Anwendungen werden laufend hinsichtlich Verfügbarkeit, Funktionstüchtigkeit, Sicherheit und Auslastung überwacht. Es existiert ein schriftlicher Notfallplan, um die Sicherungen bei Verlust oder Zerstörung zurückzuspielen.

### 3.2. Rasche Wiederherstellbarkeit (Art. 32 Abs. 1 lit. c DS-GVO)

Nach einem eingetretenen Datenverlust muss eine rasche Wiederherstellbarkeit der Daten gewährleistet werden.

Zum Schutz gegen den Verlust von Kundendaten wird eine Kombination von redundanten Systemen sowie Backup-Lösungen eingesetzt. Alle Daten werden mindestens einmal täglich gesichert. Im Fall eines Datenverlustes können diese Daten aus den erstellten Backups wiederhergestellt werden. Die Speicherung der Daten erfolgt in unabhängigen Verfügbarkeitszonen. 

## 4.   Belastbarkeit (Art. 32 Abs. 1 lit. b DS-GVO)

Belastbarkeit meint die Fähigkeit, Angriffen zu widerstehen bzw. Systeme nach einer Attacke zügig wieder in funktionsfähigen Zustand zu bringen.

Die technischen Systeme der OpenProject-Plattform sind in der Lage die erwartbaren Störereignisse zu bewältigen, ohne dass deren Funktionsfähigkeit wesentlich beeinträchtigt werden. Die IT Systeme werden kontinuierlich gehärtet, um gegen bekannte Angriffe, wie beispielsweise Denial-of-Service-Attacken geschützt zu sein. 

Zusätzlich ist jede wesentliche Komponente redundant ausgelegt, so dass im Falle einer Störung ein automatischer Wechsel auf eine störungsfreie Komponente erfolgt. Auch können zusätzliche Kapazitäten flexibel getauscht oder erweitert werden. 

Die OpenProject-Plattform verfügt über eine moderne Schichten-Architektur. Hierbei sind die Zugriffe der Aspekte technisch über Netztrennungen so eingeschränkt, dass beispielsweise das Datenbank-Management-System nicht aus dem Internet erreicht werden kann, sondern lediglich die Load-Balancer.

Es bestehen Notfallpläne, welche im Falle einer Störung exakte Handlungsanweisungen für die Wiederherstellung des gewünschten Zustandes geben. Diese Notfallpläne sowie die Schutzkonzepte werden kontinuierlich geprüft und deren Anwendung regelmäßig von den verantwortlichen Mitarbeitern trainiert.

## 5.   Datenschutz-Management 

### 5.1. Verantwortliche Ansprechpartner des Auftragnehmers

Herr Ingo Wolff (Datenschutzbeauftragter)

Tacticx GmbH

Walbecker Straße 53

47608 Geldern

### 5.2. Verfahren zur regelmäßigen Überprüfung, Bewertung und Evaluierung (Art. 32 Abs. 1 lit. d DS-GVO; Art. 25 Abs. 1 DS-GVO)

Zur Gewährleistung der Sicherheit der Datenverarbeitung muss ein Verfahren zur regelmäßigen Überprüfung, Bewertung und Evaluierung der Wirksamkeit der ergriffenen technischen und organisatorischen Maßnahmen implementiert sein.

Die Umsetzung dieser Maßnahme erfolgt mit Hilfe eines Datenschutz-Management-Systems. Im Rahmen eines kontinuierlichen Verbesserungsprozesses werden die getroffenen technischen und organisatorischen Maßnahmen auf deren Wirksamkeit geprüft und optimiert. Als Teil dieser Maßnahmen werden regelmäßige Audits durch einen externen akkreditierten Fachgutachter durchgeführt. 

### 5.3. Incident-Response-Management; Meldeweg

Es muss gewährleistet sein, dass bei Datenschutzverstößen bzw. des Verdachts von Datenschutzverstößen der Auftragnehmer unverzüglich den Auftraggeber informiert.

Alle Vertragspartner sind vertraglich verpflichtet Datenschutzvorfälle innerhalb der gesetzlichen Fristen zu melden. Interne Prozesse stellen sicher, dass im Falle eines Datenschutzvorfalls die Einbindung des Datenschutzbeauftragten gewährleistet ist.

### 5.4. Datenschutzfreundliche Voreinstellungen (Art. 25 Abs. 2 DS-GVO)

Durch datenschutzfreundliche Voreinstellungen ist zu gewährleisten, dass nur personenbezogenen Daten, deren Verarbeitung für den jeweiligen bestimmten Verarbeitungszweck erforderlich sind, verarbeitet werden.

Nach Ablauf der Testphase sowie nach Beendigung des Vertragsverhältnisses werden die erfassten Kundendaten automatisch innerhalb von drei Monaten gelöscht. Zusätzlich dazu kann der Kunde selbständig einzelne Nutzer innerhalb seiner OpenProject-Installation löschen. Hierbei werden folgende personenbezogenen Daten gelöscht:

- Name,
- E-Mail-Adresse,
- Telefonnummer,
- Nutzername,
- Nutzer-Profilbild (Avatar-Bild).

Die erstellten Daten, wie beispielsweise Kommentare zu Arbeitspaketen werden nach dem Löschen einem anonymisierten Nutzer zugeordnet.

Datenschutzfreundliche Technikgestaltung und datenschutzfreundliche Einstellungen (Privacy-by-Design/Default) werden bei Entwicklung und Betrieb der Software berücksichtigt.

### 5.5. Auftragskontrolle

Der Auftragnehmer verarbeitet die eingereichten Daten gemäß dem geschlossenen Vertrag und gewährleistet hierbei die gesetzlichen Vorschriften und per Vertrag definierten Anforderungen im Rahmen der Weisungen des Auftraggebers. Die OpenProject-Plattform verfügt über eine Administrationsoberfläche, über die der Auftraggeber sein Kundenkonto verwalten kann. Der Auftraggeber legt seine Zugangsdaten bei der initialen Erstellung in seinem Nutzerkonto selbst fest. Nur wer über diese Zugangsdaten verfügt, kann im Rahmen der zugeordneten Berechtigung Kundendaten eingeben, verändern oder löschen. Für sonstige Aufträge, welche der Auftraggeber nicht selbständig über die Administrationsoberfläche durchführen kann, gilt die Schriftform.