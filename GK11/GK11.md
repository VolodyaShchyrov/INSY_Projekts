# GK11

## Einfache Abfragen

Verfasser: **Volodymyr Shchyrov**

Datum: **10.09.2026**

## 1. SQL Island
In erste Teil von diese aufgabe spielen wir auf SQL Island.
Dort lernt man SQL Grundlagen und ganz am Ende bekommt man Zertifikat.

**Beschreibung:** Wir schlüpfen in die Rolle eines Überlebenden. Ein Flugzeugabsturz führt uns auf eine Insel, und unsere Aufgabe ist es, zu entkommen. Dazu finden wir verschiedene Personen in einer Datenbank und erfüllen Aufgaben.

![Zertifikat](./Screenshot%202026-09-16%20101254.png)

## 2.flightdatabase

In diese Aufgabe muss man Database INSY_flightdata bearbeiten.

### Code
``` SQL
USE INSY_flightdata;

SELECT firstname, lastname, seatposition FROM passengers WHERE seatposition = 'F' ORDER BY lastname;

SELECT * FROM planes WHERE initialserviceyear > 2001 AND lengthoverall > 73;

SELECT * FROM planes WHERE lengthoverall = span;

/** Damit wir Anzahl von Rows wissen, muss man maximale Anzahl von Plätzen durch Anzahl von Plätze pro Reihe dividieren**/
SELECT * FROM planes WHERE (maxseats / seatsperrow) > 30;

SELECT * FROM passengers WHERE (rownr >= 5 AND rownr <= 15) AND firstname LIKE '%e';
```


## 3.Kreuzworträtsel

In diese Aufgabe Bearbeiten wir eine Xl mit Kreuzworträrtsel.

### Ergebnisübersicht

| Nr. | Frage | Ergebnis |
|---:|---|---|
| 1 | Nachname eines Passagiers, der mit 'S' beginnt; Vorname 'Cadman' | SHORT |
| 2 | Vorname; ID zwischen 400–560; Nachname mit doppel R | BRANDEN |
| 3 | Vorname; Ostfriesische Lufttransport; Sitz D | CRUZ |
| 4 | Vorname; Nachname 'Hill'; Sitz 'C' | KELLY |
| 5 | Vorname mit 3 Buchstaben, beginnend mit K | KIM |
| 6 | Erster 'Whitaker' alphabetisch; Vorname | CECILIA |
| 7 | Vorname beginnt mit X; Nachname endet mit y | XANDRA |
| 8 | Kanadische Airline mit 'B' in der ID | HAWKAIR |
| 9 | Jamaikanische Airline | AIR JAMAICA |
| 10 | ID einer japanischen Airline mit 'Asia' im Namen | EG |
| 11 | Russischer Flughafen mit 4 'a' im Namen | CONSTANTINE |
| 12 | Erster österreichischer Flughafen (nach Code sortiert) | ANT |
| 13 | Flughafen in Salzburg | W A MOZART |
| 14 | Land mit x und b im Namen | LUXEMBOURG |
| 15 | Letztes Land mit z im Namen | ZIMBABWE |
| 16 | Stadt, in der der Flug am 25.7.2010 landete | YAROSLAVL |
| 17 | Tschechische Airline, 2009 oder 2010 geflogen | QT |
| 18 | Letzter Passagier (Luxair, alphabetisch nach Nachname); Vorname | NIGEL |
| 19 | Nachname, von Mena nach Reykholar Airport; Vorname 2 Zeichen | MALONE |
| 20 | ID des Passagiers mit doppel r und doppel t im Nachnamen; Sitz 10–20 | 1286 |
| 21 | Land; Flugnummer = Code für "Not Found" (404) | PF |

		

