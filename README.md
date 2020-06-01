# FIDO Guide

> DISCLAIMER: This project is in a very early stage. All the information you find might be outdated or wrong.
> The Readme and all documentation is in german. In future it will also be published in several languages.

Der FIDO Guide ist eine Datenbank und eine Übersichtsseite von allen vorhandenen FIDO zertifizierten Sicherheitsschlüssel.
Die Datenbank ist dabei eine einfache JSON Datei um so die Collaboration zu ermöglichen.

## Motivation

Ich möchte eine informierende Webseite erschaffen ähnlich wie [caniuse.com](http://caniuse.com) um die Verbreitung und die 
Akzeptanz von FIDO zu unterstützen. Dabei ist es wichtig, dass hier auch viele Menschen zusammenarbeiten können, sich
austauschen und einen Beitrag zur Datenbank leisten können.

Der erste Schritt ist eine Basis Datenbank zu erschaffen mit den aktuellen Sicherheitsschlüssel von bekannten
Anbietern bereitzustellen. Diese Datenbank kann über eine einfache Webseite bei Github Pages abgerufen werden in
Form einer filterbaren Tabelle. Die Tabelle soll Preise, Bezugsquelle und Eigenschaften der Schlüssel auflisten.

Zweiter Schritt sollen Tutorials bereitgestellt werden, bei dem Entwickler von Webseiten oder anderen
Programmiersprachen das FIDO Protokoll implentieren können. Dabei sollen Tutorials und Beispielcodes so einfach und
plain werden wie möglich. Bei plain meine ich, dass keine Frameworks bei der Basisimplementierung verwendet werden.

Als dritter Schritt kommt eine Wissensdatenbank in Form einer umfangreichen Dokumentation zustande mit der
FIDO erläutert wird, wie Sicherheitsschlüssel und das Protokoll funktioniert. Forschungen (Papers) sollen dabei auch
nicht zu kurz kommen.

Ganz zum Schluss wird erst auf eine richtige Datenbank wie Postgres oder MariaDB gesetzt und mit einer
REST API verknüpft um so externen Webseiten einen Zugang anzubieten.

## Probleme mit FIDO

FIDO ist zwar bekannt aber nicht weit verbreitet. Die Gründe sind wie folgt:
- Wenige Informationen was welcher Schlüssel was kann
- Wenige Anbieter
- WebAuthn Implementierung traut sich nicht so rüber
- Es kostet Geld

Viele Menschen wollen für ihre Sicherheit kein Geld ausgeben, dabei kostet ein FIDO zertifizierter Sicherhheitsschlüssel
nur paar Kröten.

## Roadmap

- Erstellen einer Basis Datenbank mit den bekanntesten Schlüssel
- Tabellarische Übersicht der erhältlichen Sicherheitsschlüssel und deren Eigenschaften
- Pflegen eines Githubs mit Möglichkeit zur Collaboration
- Mehrsprachigkeit
- Wissensdatenbank für Recherchen und Forschungen anbieten
- REST API mit Datenbank anbieten für externe Webseiten
