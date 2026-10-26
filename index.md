---
title: VORA – Privacy Policy / Datenschutzerklärung
---

# VORA – Privacy Policy / Datenschutzerklärung

[English](#english) · [Deutsch](#deutsch)

*Last updated / Stand: 26 October 2026*

---

<a id="english"></a>

## English

VORA is a Discord bot for moderation, AutoMod, tickets, role menus, a level system, profiles, the game VORA World,
a server log and welcome messages. This page explains which data VORA processes and for how long.

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
| AutoMod: Discord's rules (only if turned on) | Nothing at VORA: the rules, including a custom word list, are stored by Discord |
| AutoMod: VORA's own checks (only if turned on) | Settings (thresholds, penalty steps, allowed websites, exempt roles and channels). A violation is stored like any warning as a case: Discord ID, reason (e.g. "AutoMod: caps spam"), time and weight (1 to 3). **The message text is not stored.** The same retention periods apply as for all cases |
| VORA World (only if turned on and used) | **One account per person for all servers:** Discord ID, Lumen (cash and bank), daily streak, character, clothes and other items (owned, equipped, when received), housing (where someone lives, bought homes, rent due and unpaid rent, lock after an eviction), starter quests (which were claimed, simple counters such as "meals eaten" or "total wages"), a short pose (e.g. after eating), job, skills, needs, bank card and statement (last 50 bookings). Also on which servers the person plays (only server and Discord ID, for the "this server" leaderboard) and when they last played (for the deletion period). No message contents |
| Level system (only if turned on) | Discord ID and XP (level and rank are calculated from it) and which reward roles were already given |
| Profile | Earned badges with date (also without using the profile oneself: when someone else views it, and every hour for places 1 to 3 of the leaderboards) and the "About me" text the person wrote themselves (at most 120 characters, no links), per server and person. The profile picture is drawn only for display, using the person's Discord avatar and name, and is not stored |
| Privacy | The time VORA left a server (needed for the deletion period below) |

### What VORA does not store

- **No message contents are stored.** For the level system VORA only learns *that* and *where* someone wrote and counts XP.
  Only if the team turns on VORA's own AutoMod (caps, repeats, floods, emojis, links, attachment spam), VORA reads the text of
  messages **briefly in memory**, checks it and forgets it immediately. For repeat detection VORA keeps only a fingerprint (hash),
  not the text, and only in memory: for the period the team has set (30 seconds by default, at most 2 minutes); after that it is
  deleted within 10 seconds. Admins, members with "Manage Server" or "Manage Messages", bots and exempt roles are never checked.
  `/purge` deletes messages without reading or storing them.
- **No online status and no activities.**
- **`/warns`:** Every member can view their own active warnings with reason and expiry date (visible only to them). This is
  also a simple way to see the data VORA holds about one's warnings.
- **Warned members receive a direct message** from VORA with the server name, the reason, the number of their active
  warnings and when the warning expires (the team can turn this off). VORA does not store this message.
- **No data outside Discord**, no sharing with third parties, no advertising, no tracking.

The operating log (console) contains technical entries with Discord IDs, for example for errors, but no contents.
It is not stored permanently.

### Why, and on what legal basis

The data is only used to provide the features the server team has set up: making moderation traceable, handling
tickets and assigning roles. The legal basis is the legitimate interest in a safe and organised server
(Art. 6(1)(f) GDPR).

### How long data is kept

- **Moderation cases and closed tickets** are deleted automatically after a period. The default is 1 year; the
  server team can choose 30 days to 5 years. An admin can delete single cases at any time. A ticket that was never
  fully created because of a malfunction is deleted after one day.
- **Warnings** stop counting after 90 days by default (adjustable); until the deletion period they stay stored
  for traceability.
- Settings, role menus and XP stay as long as VORA is on the server.
- **If VORA is removed from a server, it automatically deletes all data of that server after 30 days.** The
  period protects against data loss from an accidental removal. If VORA returns within the 30 days, the data is kept.
- **Exception VORA World:** The game progress belongs to the person, not to a server, and is valid on all servers. It is
  therefore kept when VORA leaves a server; only the entry that the person plays on that server is deleted. Everyone can
  delete their World account at any time (`/world` → Profile → "Delete account", with confirmation). The progress is then
  gone on all servers; starting again is possible at any time. No server team can give or change Lumen.
- **Unused World accounts:** If someone does not use VORA World for **12 months**, VORA deletes their account automatically
  (progress, list of servers and the time of last use). Opening `/world`, every click in it, the World commands (`/daily`,
  `/balance` …) and one's own `/profile` count as use.
- **Operator tools for VORA World** (only the bot owner, in `/owner`): The owner can view an account, correct Lumen, reset an
  account and ban people. Every change needs a reason and is logged (Discord ID, action, amount, reason, time). The log is
  deleted automatically after **90 days**. A ban (Discord ID, reason, time) stays until the operator lifts it; it also stays
  when the person deletes their account, because a ban would otherwise be pointless. Banned people appear in no leaderboard.
- **Backups:** The database is backed up daily and the last 7 copies are kept. Deleted data can therefore remain
  in a backup for up to 7 more days; after that it is gone there too.

### Your rights

You have the right of access, rectification, erasure, restriction of processing and objection. Write to
[blawatjustin@gmail.com](mailto:blawatjustin@gmail.com) and include your Discord ID. You can also lodge a
complaint with a data protection supervisory authority.

---

<a id="deutsch"></a>

## Deutsch

VORA ist ein Discord-Bot für Moderation, AutoMod, Tickets, Rollenmenüs, ein Levelsystem, Profile, das Spiel VORA World,
ein Server-Log und Willkommensnachrichten. Diese Seite erklärt, welche Daten VORA verarbeitet und wie lange.

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
| AutoMod: Discords Regeln (nur wenn eingeschaltet) | Nichts bei VORA: Die Regeln samt eigener Wortliste liegen bei Discord |
| AutoMod: VORAs eigene Prüfung (nur wenn eingeschaltet) | Einstellungen (Schwellen, Strafleiter, erlaubte Internet-Seiten, Ausnahme-Rollen und -Kanäle). Ein Verstoß wird wie jede Verwarnung als Fall gespeichert: Discord-ID, Grund (z. B. „AutoMod: Caps-Spam“), Zeitpunkt und Gewicht (1 bis 3). **Der Nachrichtentext wird nicht gespeichert.** Es gelten dieselben Fristen wie für alle Fälle |
| VORA World (nur wenn eingeschaltet und genutzt) | **Ein Konto pro Person für alle Server:** Discord-ID, Lumen (Bargeld und Bank), tägliche Serie, Charakter, Kleidung und andere Teile (Besitz, ausgerüstet, Erhalt-Zeitpunkt), Wohnen (wo man wohnt, gekaufte Immobilien, Fälligkeit und offene Miete, Sperre nach einem Rauswurf), Start-Aufgaben (welche abgeholt, einfache Zähler wie „gegessen“ oder „Lohn gesamt“), kurze Pose (z. B. nach dem Essen), Job, Fähigkeiten, Versorgung, Bankkarte und Kontoauszug (letzte 50 Buchungen). Dazu, auf welchen Servern die Person spielt (nur Server- und Discord-ID, für die Rangliste „Dieser Server“), und wann sie zuletzt gespielt hat (für die Löschfrist). Kein Nachrichteninhalt |
| Levelsystem (nur wenn eingeschaltet) | Discord-ID und XP-Stand (daraus ergeben sich Level und Platz) sowie welche Belohnungsrollen schon vergeben wurden |
| Profil | Verdiente Abzeichen mit Datum (auch ohne eigene Nutzung: wenn jemand anderes das Profil ansieht und stündlich für die Plätze 1 bis 3 der Ranglisten) und der selbst geschriebene „Über mich“-Text (höchstens 120 Zeichen, ohne Links), pro Server und Person. Das Profilbild wird nur zum Anzeigen gezeichnet (mit dem Discord-Avatar und dem Namen der Person) und nicht gespeichert |
| Datenschutz | Zeitpunkt, an dem VORA einen Server verlassen hat (für die Löschfrist unten) |

### Was VORA nicht speichert

- **Keine Nachrichteninhalte gespeichert.** Für das Levelsystem erfährt VORA nur, *dass* und *wo* jemand geschrieben hat,
  und zählt daraus XP. Nur wenn das Team VORAs eigenen AutoMod einschaltet (Caps, Wiederholungen, Fluten, Emojis, Links,
  Anhang-Spam), liest VORA den Text der Nachrichten **kurz im Arbeitsspeicher**, prüft ihn und vergisst ihn sofort wieder.
  Für die Wiederholungs-Erkennung merkt sich VORA nur einen Fingerabdruck (Hash), keinen Text, und nur im Arbeitsspeicher:
  so lange wie den Zeitraum, den das Team eingestellt hat (Standard 30 Sekunden, höchstens 2 Minuten), danach wird er
  innerhalb von 10 Sekunden gelöscht. Admins, Mitglieder mit „Server verwalten“ oder „Nachrichten verwalten“, Bots und
  Ausnahme-Rollen werden nie geprüft. `/purge` löscht Nachrichten, ohne sie zu lesen oder zu speichern.
- **Keinen Online-Status und keine Aktivitäten.**
- **`/warns`:** Jedes Mitglied kann seine eigenen aktiven Verwarnungen mit Grund und Ablaufdatum selbst ansehen (nur für
  sich sichtbar). Das ist zugleich eine einfache Auskunft über die eigenen Daten.
- **Verwarnte Mitglieder bekommen eine Direktnachricht** von VORA mit Servername, Grund, Zahl ihrer aktiven Verwarnungen
  und dem Ablaufdatum der Verwarnung (das Team kann das abschalten). VORA speichert diese Nachricht nicht.
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
  Ein Ticket, das wegen einer Störung nie fertig angelegt wurde, wird nach einem Tag gelöscht.
- **Verwarnungen** zählen standardmäßig nach 90 Tagen nicht mehr (einstellbar), bis zur Löschfrist bleiben sie
  für die Nachvollziehbarkeit gespeichert.
- Einstellungen, Rollenmenüs und XP bleiben, solange VORA auf dem Server ist.
- **Wird VORA von einem Server entfernt, löscht VORA nach 30 Tagen automatisch alle Daten dieses Servers.**
  Die Frist schützt vor Datenverlust durch ein versehentliches Entfernen. Kommt VORA innerhalb der 30 Tage
  zurück, bleiben die Daten erhalten.
- **Ausnahme VORA World:** Der Spielstand gehört der Person, nicht einem Server, und gilt auf allen Servern. Er bleibt
  deshalb erhalten, wenn VORA einen Server verlässt; gelöscht wird dabei nur der Eintrag, dass die Person auf diesem Server
  spielt. Jede Person kann ihr World-Konto jederzeit selbst löschen (`/world` → Profil → „Konto löschen“, mit Rückfrage).
  Danach ist der Spielstand auf allen Servern weg; ein neuer Start ist jederzeit möglich. Kein Server-Team kann Lumen
  vergeben oder ändern.
- **Unbenutzte World-Konten:** Wer VORA World **12 Monate** nicht nutzt, dessen Konto löscht VORA automatisch (Spielstand,
  Server-Liste und der Zeitpunkt der letzten Nutzung). Als Nutzung zählt jedes Öffnen von `/world`, jeder Klick darin, die
  World-Befehle (`/daily`, `/balance` …) und das eigene `/profile`.
- **Werkzeuge des Betreibers für VORA World** (nur der Bot-Owner in `/owner`): Er kann ein Konto ansehen, Lumen korrigieren,
  ein Konto zurücksetzen und Personen sperren. Jede Änderung braucht einen Grund und steht im Protokoll (Discord-ID, Aktion,
  Betrag, Grund, Zeitpunkt). Das Protokoll wird nach **90 Tagen** automatisch gelöscht. Eine Sperre (Discord-ID, Grund,
  Zeitpunkt) bleibt bestehen, bis der Betreiber sie aufhebt; sie bleibt auch, wenn die Person ihr Konto löscht, weil eine
  Sperre sonst wirkungslos wäre. Gesperrte erscheinen in keiner Rangliste.
- **Sicherungskopien:** Die Datenbank wird täglich gesichert, die letzten 7 Kopien bleiben erhalten. Gelöschte
  Daten können deshalb noch bis zu 7 Tage in einer Sicherung stehen, danach sind sie auch dort weg.

### Deine Rechte

Du hast das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung und Widerspruch.
Schreib dazu an [blawatjustin@gmail.com](mailto:blawatjustin@gmail.com) und nenne deine Discord-ID. Du kannst
dich außerdem bei einer Datenschutz-Aufsichtsbehörde beschweren.
