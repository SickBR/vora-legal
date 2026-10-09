---
title: VORA – Privacy Policy / Datenschutzerklärung
---

# VORA – Privacy Policy / Datenschutzerklärung

[English](#english) · [Deutsch](#deutsch)

*Last updated / Stand: October 2026*

---

<a id="english"></a>

## English

VORA is a Discord bot for moderation, tickets, role menus, a level system, an economy, a server log and welcome messages.
This page explains which data VORA processes and for how long.

### Who is responsible?

Justin Dennis Blawat, operator of VORA
Contact for privacy questions: [blawatjustin@gmail.com](mailto:blawatjustin@gmail.com)

For everything Discord itself stores, [Discord's Privacy Policy](https://discord.com/privacy) applies.

### What VORA stores

VORA only stores what its features need on a server. The data is kept in a database on the server of the
hosting provider Bot-Hosting.net, which runs VORA for the operator and can technically access the data it hosts.

| Feature | Stored data |
|---|---|
| Moderation | Discord ID of the affected person and the moderator, type of action, reason, time, duration of timeouts |
| Tickets | Discord ID of the opener and the staff member, category, **the description that was entered**, reason for closing, times |
| Role menus & auto role | Role and channel IDs, titles, labels and emojis of the menus |
| Settings | Channel IDs for log and welcome message, the welcome text, the language, retention periods |
| AutoMod by VORA (only if turned on) | Settings (thresholds, penalty steps, allowed websites, exempt roles). A violation is stored like any warning as a case: Discord ID, reason (e.g. "AutoMod: caps spam"), time and weight (1 to 3). **The message text is not stored.** The same retention periods apply as for all cases |
| Economy (only if turned on and used) | Discord ID, Lumen balance, daily streak (current and best), time of the last daily bonus |
| Level system (only if turned on) | Discord ID and XP (level and rank are calculated from it) and which reward roles were already given |
| Privacy | The time VORA left a server (needed for the deletion period below) |

### What VORA does not store

- **No message contents are stored.** For the level system VORA only learns *that* and *where* someone wrote and counts XP.
  Only if the team turns on VORA's own AutoMod (caps, repeats, emojis, links), VORA reads the text of messages
  **briefly in memory**, checks it and forgets it immediately. For repeat detection VORA keeps only a fingerprint (hash), not
  the text, for the set time (at most 2 minutes). Admins, members with "Manage Server" or "Manage Messages", bots and exempt roles
  are never checked. `/purge` deletes messages without reading or storing them.
- **No online status and no activities.**
- **No data outside Discord**, no sharing with third parties, no advertising, no tracking.

The operating log (console) contains technical entries with Discord IDs, for example for errors, but no contents.
It is not stored permanently.

### Why, and on what legal basis

The data is only used to provide the features the server team has set up: making moderation traceable, handling
tickets and assigning roles. The legal basis is the legitimate interest in a safe and organised server
(Art. 6(1)(f) GDPR).

### How long data is kept

- **Moderation cases and closed tickets** are deleted automatically after a period. The default is 1 year; the
  server team can choose 30 days to 5 years. An admin can delete single cases at any time.
- **Warnings** stop counting after 90 days by default (adjustable); until the deletion period they stay stored
  for traceability.
- Settings, role menus, XP and Lumen balances stay as long as VORA is on the server.
- **If VORA is removed from a server, it automatically deletes all data of that server after 30 days.** The
  period protects against data loss from an accidental removal. If VORA returns within the 30 days, the data is kept.
- **Backups:** The database is backed up daily and the last 7 copies are kept. Deleted data can therefore remain
  in a backup for up to 7 more days.

### Your rights

You have the right of access, rectification, erasure, restriction of processing and objection. Write to
[blawatjustin@gmail.com](mailto:blawatjustin@gmail.com) and include your Discord ID. You can also lodge a
complaint with a data protection supervisory authority.

---

<a id="deutsch"></a>

## Deutsch

VORA ist ein Discord-Bot für Moderation, Tickets, Rollenmenüs, ein Levelsystem, eine Economy, ein Server-Log und
Willkommensnachrichten. Diese Seite erklärt, welche Daten VORA verarbeitet und wie lange.

### Wer ist verantwortlich?

Justin Dennis Blawat, Betreiber von VORA
Kontakt für Datenschutzfragen: [blawatjustin@gmail.com](mailto:blawatjustin@gmail.com)

Für alles, was Discord selbst speichert, gilt die [Datenschutzerklärung von Discord](https://discord.com/privacy).

### Was VORA speichert

VORA speichert nur, was die Funktionen auf einem Server brauchen. Die Daten liegen in einer Datenbank auf dem
Server des Hosting-Anbieters Bot-Hosting.net, der VORA für den Betreiber ausführt und technisch auf die dort
gehosteten Daten zugreifen kann.

| Funktion | Gespeicherte Daten |
|---|---|
| Moderation | Discord-ID der betroffenen Person und des Moderators, Art der Maßnahme, Begründung, Zeitpunkt, Dauer bei Timeouts |
| Tickets | Discord-ID von Ersteller und Bearbeiter, Kategorie, **die eingegebene Beschreibung**, Grund beim Schließen, Zeitpunkte |
| Rollenmenüs & Autorole | Rollen- und Kanal-IDs, Titel, Beschriftungen und Emojis der Menüs |
| Einstellungen | Kanal-IDs für Log und Begrüßung, der Begrüßungstext, die Sprache, Aufbewahrungsfristen |
| AutoMod von VORA (nur wenn eingeschaltet) | Einstellungen (Schwellen, Strafstufen, erlaubte Internet-Seiten, Ausnahme-Rollen). Ein Verstoß wird wie jede Verwarnung als Fall gespeichert: Discord-ID, Grund (z. B. „AutoMod: Caps-Spam“), Zeitpunkt und Gewicht (1 bis 3). **Der Nachrichtentext wird nicht gespeichert.** Es gelten dieselben Fristen wie für alle Fälle |
| Economy (nur wenn eingeschaltet und genutzt) | Discord-ID, Lumen-Kontostand, tägliche Serie (aktuell und Rekord), Zeitpunkt des letzten täglichen Bonus |
| Levelsystem (nur wenn eingeschaltet) | Discord-ID und XP-Stand (daraus ergeben sich Level und Platz) sowie welche Belohnungsrollen schon vergeben wurden |
| Datenschutz | Zeitpunkt, an dem VORA einen Server verlassen hat (für die Löschfrist unten) |

### Was VORA nicht speichert

- **Keine Nachrichteninhalte gespeichert.** Für das Levelsystem erfährt VORA nur, *dass* und *wo* jemand geschrieben hat,
  und zählt daraus XP. Nur wenn das Team VORAs eigenen AutoMod einschaltet (Caps, Wiederholungen, Emojis, Links), liest VORA
  den Text der Nachrichten **kurz im Arbeitsspeicher**, prüft ihn und vergisst ihn sofort wieder. Für die
  Wiederholungs-Erkennung merkt sich VORA nur einen Fingerabdruck (Hash), keinen Text, für die eingestellte Zeit (höchstens
  2 Minuten). Admins, Mitglieder mit „Server verwalten“ oder „Nachrichten verwalten“, Bots und Ausnahme-Rollen werden nie
  geprüft. `/purge` löscht Nachrichten, ohne sie zu lesen oder zu speichern.
- **Keinen Online-Status und keine Aktivitäten.**
- **Keine Daten außerhalb von Discord**, keine Weitergabe an Dritte, keine Werbung, kein Tracking.

Das Betriebsprotokoll (Konsole) enthält technische Einträge mit Discord-IDs, z. B. bei Fehlern, aber keine
Inhalte. Es wird nicht dauerhaft gespeichert.

### Wofür und auf welcher Grundlage

Die Daten dienen nur dazu, die vom Server-Team eingerichteten Funktionen bereitzustellen: Moderation
nachvollziehbar zu machen, Tickets zu bearbeiten und Rollen zu vergeben. Rechtsgrundlage ist das berechtigte
Interesse an einem sicheren und organisierten Server (Art. 6 Abs. 1 lit. f DSGVO).

### Wie lange gespeichert wird

- **Moderationsfälle und geschlossene Tickets** werden nach einer Frist automatisch gelöscht. Standard ist
  1 Jahr, das Server-Team kann 30 Tage bis 5 Jahre einstellen. Einzelne Fälle kann ein Admin jederzeit löschen.
- **Verwarnungen** zählen standardmäßig nach 90 Tagen nicht mehr (einstellbar), bis zur Löschfrist bleiben sie
  für die Nachvollziehbarkeit gespeichert.
- Einstellungen, Rollenmenüs, XP und Lumen-Kontostände bleiben, solange VORA auf dem Server ist.
- **Wird VORA von einem Server entfernt, löscht VORA nach 30 Tagen automatisch alle Daten dieses Servers.**
  Die Frist schützt vor Datenverlust durch ein versehentliches Entfernen. Kommt VORA innerhalb der 30 Tage
  zurück, bleiben die Daten erhalten.
- **Sicherungskopien:** Die Datenbank wird täglich gesichert, die letzten 7 Kopien bleiben erhalten. Gelöschte
  Daten können deshalb noch bis zu 7 Tage in einer Sicherung stehen.

### Deine Rechte

Du hast das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung und Widerspruch.
Schreib dazu an [blawatjustin@gmail.com](mailto:blawatjustin@gmail.com) und nenne deine Discord-ID. Du kannst
dich außerdem bei einer Datenschutz-Aufsichtsbehörde beschweren.
