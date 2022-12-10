# StayHomeVideoRental

An entity-relationship model of the StayHome company illustrating the operational tasks and conditions described in the
Case Study.

Die Fallstudie „StayHome Video Rental“
Diese Fallstudie beschreibt eine Firma, die wir StayHome nennen wollen. Sie verleiht Videos
und Computerspiele an registrierte Kunden. Die erste Filiale (branch) wurde 1982 in London
eröffnet. Das Unternehmen ist seither stark gewachsen und unterhält inzwischen viele Filialen
im gesamten Vereinigten Königreich. Das Unternehmen und sein Kerngeschäft werden
nachfolgend beschrieben:
Mitarbeiter (staff)
StayHome hat aktuell insgesamt ca. 1000 Mitarbeiter in 100 Filialen. Jede Filiale hat einen
Manager und mehrere Gruppenleiter (supervisors). Der Manager ist für das Tagesgeschäft
einer Filiale gesamtverantwortlich und jeder Supervisor ist einer Gruppe von Assistenten
(assistants) vorgesetzt. Ein Mitarbeiter ist genau einer Filiale zugeordnet.
Videos (videos)
Jede Filiale besitzt eine Anzahl von Videos für die Ausleihe. Jedes Video wird
unternehmensweit durch eine Katalognummer identifiziert. Der Katalog wird zentral
verwaltet. In jeder Filiale entscheidet der Manager, welche Videos zur Ausleihe in seiner
Filiale angeboten werden. Natürlich gibt es üblicherweise mehrere Kopien eines Videos in
einer Filiale und eine bestimmte Kopie wird durch eine Exemplarnummer eindeutig
gekennzeichnet. Die Exemplarnummern sind über alle Filialen hinweg eindeutig. Für jedes
Video werden neben dem Titel Informationen über den Regisseur, Produzenten, die
Schauspieler und ihre jeweilige Rolle geführt. Diese Informationen dienen dazu, den Kunden
bei der Auswahl von Videos zu unterstützen.
Computerspiele (computer games)
StayHome verleiht auch Computerspiele für PlayStations, Xbox und Nintendo GameCube.
Die Katalogisierung und Identifikation von Kopien ist genau so organisiert wie die Videos.
Selbstverständlich gibt es keinen Regisseur oder Schauspieler und anstelle des Produzenten
wird die Herstellerfirma gespeichert. Zusätzlich wird das Genre (z.B. Strategie, Autorennen,
Ballerspiel, etc) erfasst.
Kunden (customers)
Bevor ein Video ausgeliehen werden kann, muss ein Kunde sich bei StayHome registrieren.
Er/sie hat dazu ein Formular mit seinen persönlichen Daten (Name, Vorname, Adresse,
Geburtstag) auszufüllen. Ein Mitarbeiter legt das Formular in einem Ordner ab und stellt
einen Mitgliedsausweis.
StayHome hat z.Zt. etwa 100000 Mitglieder. Ein Kunde kann sich in mehreren Filialen
registrieren. Sehen Sie Schwierigkeiten, wenn sich ein Kunde mehrfach registriert?
Mit dem Mitgliedsausweis kann ein Kunde bis zu 10 Videos oder Spiele ausleihen. Dies
erfolgt in der Form, dass ein Mitarbeiter einen Ausleihzettel für jede ausgeliehene Kopie
ausfüllt und sie Ordner für die Ausleihe abheftet. Wird die Kopie wieder zurückgegeben,
werden das Rückgabedatum und der Leihbetrag erfasst. Welche Schwächen besitzt dieses
Ausleihverfahren?

StayHome hat auf Grund der Firmengröße zunehmend Schwierigkeiten, die wachsende
Datenmenge zu verwalten und den Ausleihprozess zu beherrschen. Um den bisherigen Erfolg
zu sichern, hat der Firmenchef (CEO, Chief Executive Officer) entschieden, eine Datenbank-
Anwendung entwickeln zu lassen, auf die über das Web zugegriffen werden kann. Diese
Anwendung soll neben der Verwaltung der Mitarbeiter, Kunden, Videos/Spielen und den
Kopien auch alle „offenen“ Ausleihen eines Kunden anzeigen können. Mit dieser Liste kann
ermittelt werden, ob ein Kunde das Ausleihmaximum erreicht hat oder ob die Leihfrist
überschritten ist.
Zusätzlich sollen Kunden dabei unterstützt werden, nach Videos oder Spielen zu suchen, auch
wenn Sie den Titel nur unvollständig kennen oder alle Videos eines Regisseurs oder
Schauspielers zu ermitteln. Wenn ein Video gefunden wurde, soll auch seine Verfügbarkeit
überprüft werden können.
Der Manager möchte zusätzlich wissen, wie viele Kopien von einem Mitarbeiter jeweils
verliehen wurden.
