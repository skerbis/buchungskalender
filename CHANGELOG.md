Changelog
=========

Version 1.2.1 beta - 03.07.2022
-------------------------------

* FE-Javascript erweitert, sodass keine überschneidenden Termine markiert werden können
* Buchungsseite über Einstellungen definierbar.
* Minikalender übernimmt Link zur Buchungsseite aus den Einstellungen
* Kalendernavigation übersetzt "Monat/e" über sprog buka_month / buka_months Platzhalter, wenn sprog installiert ist
* In der Demo das Ui-Kit JS vom allgemeinen JS getrennt
* Demo aktualisiert
* Zahlreiche Detailverbesserungen
* Status "Blockiert" implementiert - damit lassen sich Termine im Frontend blockieren, im Backend ist dennoch eine Buchung auf diese Termine möglich
* Mehrsprachigkeit verbessert


Version 1.2 - 15.04.2022
------------------------

* Fix Klick auf Kalendereintrag öffnet Detailansicht
* Storno Datensatz immer ermöglichen, auch bei überschneidenden Terminen
* Kalender Blätterfunktion verbessert
* Objekttabelle mit Reihenfolge prio versehen
* Weiterer Streifenkalender in linearer Ansicht
* Datenbankerweiterung um Teilnehmer und Zusatzleistungen, zusätzliche Felder
* Datenbankerweiterung um Buchungstyp
* Buchungsliste im AddOn als yform Liste mit Suchfeldern
* Fix: FE Auswahl Anreise und Abreise nicht mehr über gebuchte Termine möglich
* Englisches Backend
* Grundkonfiguration für zweite Währung


Version 1.1.2 - 23.01.2022
--------------------------

* Verbesserung Labeldarstellung im Streifenkalender
* Labeldarstellung bei Blockierung von Kombinationsobjekten durch Einzelbuchungen


Version 1.1.1 - 26.12.2021
--------------------------

* Im Backend wird eine Validierung eingeführt, sodass sowohl über yform als auch direkt in der Buchungsliste keine Doppelbuchungen vorgenommen werden können.
* Demo geupdated für REX 5.13.1
* Fix: für offline Objekte wird auch der Name in der Buchungsliste angezeigt
* Fix: im Streifenkalender wird nun auch für den Januar die korrekte Jahreszahl angezeigt
* Doku erweitert


Version 1.1.0 - 25.12.2021
--------------------------

Der Streifenkalender wird eingeführt. Der Streifenkalender wird direkt als Startseite gezeigt. Über den Streifenkalender kann man die Buchungen auch direkt aufrufen.

* Streifenkalender für Übersichtsdarstellung
* Verbesserte ical Synchronisation
* Datenbankerweiterung für Zusatzleistungen
* Datenbankerweiterung für Teilnehmer/Gäste
* Umbau auf yform 4beta7
* Die Dokumentation wird erweitert


Version 1.0.0 - 28.07.2021
--------------------------

Viele schicke Verbesserungen. Das Update ist uneingeschränkt kompatibel zur Vorversion. Es wurden keine Änderungen an der Datenbank vorgenommen.

* Buchungen können im Backend aus dem Kalender mit Shift+Click aufgerufen und bearbeitet werden
* Buchungen können aus der Liste der AddOn Page direkt bearbeitet werden
* Nach der Bearbeitung einer Buchung im AddOn landet man wieder auf der Ursprungsseite (Liste bzw. Kalenderansicht)
* Module können auf der Setup Seite einzeln installiert oder upgedated werden
* E-Mail Templates können auf der Setup Seite einzeln installiert oder upgedated werden
* Blätterbugfix im Kalender beseitigt
* Standardwerte für Konfiguration
* Settings und Setup nur für Admin
* Abhängigkeit yform hinzugefügt


Version 0.9.0 . 26.04.2021
--------------------------

Erster Wurf, basierend auf ferien-am-tressower-see.de

