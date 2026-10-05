# WwxSkin

[![Symcon](https://img.shields.io/badge/Symcon-WebFront--Skin-red.svg?style=flat-square)](https://www.symcon.de/service/dokumentation/entwicklerbereich/sdk-tools/sdk-skins/)
[![Product](https://img.shields.io/badge/Symcon%20Version-6.4-blue.svg?style=flat-square)](https://www.symcon.de/produkt/)
[![Version](https://img.shields.io/badge/Skin%20Version-1.6.20240703-orange.svg?style=flat-square)](https://github.com/Wilkware/WwxSkin)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-green.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

WebFront-Skin für Symcon

## Inhaltsverzeichnis

1. [Funktionen](#1-funktionen)
2. [Größe](#2-größe)
3. [Kompatibilität](#3-kompatibilität)
4. [Installation](#4-installation)
5. [Versionshistorie](#5-versionshistorie)

### 1. Funktionen

Eine vollständige Dokumentation und Erklärung der vorgenommenen Anpassungen und Erweiterungen kann auf <https://wilkware.de/ip-symcon-skins/> nachgelesen werden.  
Hier eine kurze Aufzählung der getätigten Anpassungen:

* Die Höhe von Variablen ist immer gleich, unabhängig von Schaltern und Aktionen (feste Höhe).
* Die Breite von Slidern ist auf maximal 120 Pixel festgelegt, d.h. die Darstellung ist unabhängig von der Textlänge der Variablen.
* Die minimale Breite von Buttons ist auf 29 Pixel festgesetzt für ein besseres Spaltenlayout bei mehreren Buttons übereinander.
* Bringt ein eigenes Login-Logo mit (nur wenn man den Skin als Standard-Login-Skin verwendet).
* Nachrichten (Notification Messages) werden mit weißer Schrift auf orangefarbenem Hintergrund dargestellt.
* Dialoge sind etwas zentraler und transparent, d.h. sie verdecken nicht mehr die Menüleiste und sind farblich an den Skin angelehnt (nicht mehr einfach schwarz).
* Die Abstände zwischen den Widgets rechts in der Menüleiste wurden verkleinert.
* Scrollbars werden auf dem PC (Google Chrome) sehr reduziert (schmal) dargestellt, damit sich das Layout nicht verschiebt.
* Vordefinierte Tabellen-Styles (Olive, Blue, Orange, Dark, Light und Lines) werden mitgeliefert. Zusätzlich gibt es einfache vordefinierte Styles für links, rechts und mittig ausgerichtete Spalten.
* Farbpicker nur per Color-Box und nicht über das Pinsel-Symbol.
* Werte-Auswahldialog höher für mehr Werte ohne Scrollen.

### 2. Größe

* <40kB

### 3. Kompatibilität

Dieser Skin für Symcon wurde mit folgenden Versionen getestet:

* Symcon 6.x (alle Versionen)
* Symcon 7.x (alle Versionen)

Die Kompatibilität mit Versionen vor Symcon 6.0 sollte gegeben sein, wurde aber nicht getestet!

### 4. Installation

Wie ein Skin installiert wird, ist hier beschrieben (<https://www.symcon.de/service/dokumentation/modulreferenz/skin-control/>)  
oder

1. Symcon Management Console öffnen
2. Zu "Objektbaum > Logische Baumansicht > Kern Instanzen > Skins" navigieren
3. Schaltfläche "Hinzufügen" klicken
4. Folgende URL eingeben: <https://github.com/wilkware/WwxSkin>
5. Mit "OK" bestätigen

### 5. Versionshistorie

v1.6.20240703

* _NEW_: Pinsel-Symbol für Farbauswahl versteckt (Farbpicker nur noch per Color-Box aktivierbar)
* _NEW_: Werte-Auswahldialog (eigene Profile) vergrößert (höher) für mehr Werte ohne Scrollen
* _NEW_: Tabellenkopf-Farben erweitert (`light`, `dark` (Türkis) und `lines` in Vorbereitung auf TileVisu v7)

v1.5.20211227

* _NEW_: Dialog (Popup-Modul) in Größe, Position und Transparenz angepasst
* _NEW_: Widget-Styles auf verfügbaren Platz optimiert
* _NEW_: Vordefinierte Styles für Ausrichtung von Tabellenspalten (links, rechts und mittig)
* _FIX_: Update des Wilkware Login-Logos
* _FIX_: Alternierende Tabellenzellen

v1.4.20200205

* _NEW_: Neues Nachrichtenlayout (weiß/orange)
* _NEW_: Vordefinierte Tabellenlayouts hinzugefügt
* _FIX_: Scrollbar-Styles angepasst

v1.3.20190405

* _NEW_: Wilkware Login-Logo hinzugefügt

v1.2.20190404

* _NEW_: Scrollbars für Chrome Browser (PC) modifiziert (App-like)
* _NEW_: Skin-Logo-Icon hinzugefügt (WwxLogo)

v1.1.20190312

* _NEW_: Minimale Breite für Buttons
* _FIX_: Maximale Breite von Slidern auf 120 Pixel heraufgesetzt

v1.1.20190224

* _NEW_: Maximale Breite für Slider hinzugefügt

v1.0.20180116

* _NEW_: Initialversion

## Entwickler

Seit nunmehr über 10 Jahren fasziniert mich das Thema Haussteuerung. In den letzten Jahren betätige ich mich auch intensiv in der Symcon Community und steuere dort verschiedenste Skripte und Module bei. Ihr findet mich dort unter dem Namen @pitti ;-)

[![GitHub](https://img.shields.io/badge/GitHub-@wilkware-181717.svg?style=for-the-badge&logo=github)](https://wilkware.github.io/)

## Spenden

Die Software ist für die nicht-kommerzielle Nutzung kostenlos, über eine Spende bei Gefallen des Skins würde ich mich freuen.

[![PayPal](https://img.shields.io/badge/PayPal-spenden-00457C.svg?style=for-the-badge&logo=paypal)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=8816166)

## Lizenz

Namensnennung - Nicht-kommerziell - Weitergabe unter gleichen Bedingungen 4.0 International

[![License](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-EF9421.svg?style=for-the-badge&logo=creativecommons)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
