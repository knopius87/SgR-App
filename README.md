# SgR-App
Antirassismus-Schule
Interaktiver Lernpfad – README & Dokumentation
Version 4  ·  Für Schülerinnen und Schüler der Sekundarstufe I
1. Über die App
Die Antirassismus-Schule ist eine interaktive Lernapp für Jugendliche der Sekundarstufe I (10–16 Jahre). Sie ermöglicht es Schülerinnen und Schülern, eigenständig oder im Unterricht antirassistische Kompetenzen zu entwickeln – in drei aufeinander aufbauenden Themenbereichen.

Pädagogische Grundlage
Die Inhalte basieren auf drei Quellen: den Themenblättern im Unterricht Nr. 110 »Alltäglicher Rassismus« der Bundeszentrale für politische Bildung (bpb), dem Ally-Arbeitsbuch der Königin-Luise-Schule Köln sowie der Einleitung des Arbeitshefts »Gegen Rassismus«.

Kernprinzipien
•	Kein Reproduzieren rassistischer Inhalte: Keine Aufgabe verlangt das Aufschreiben oder Wiederholen diskriminierender Begriffe oder Aussagen.
•	Ich-Perspektive durchgehend: Alle Reflexionsaufgaben sind Handlungsaufträge an die eigene Person – nicht Analysen der Gesellschaft.
•	Datenschutz by Design: Die App läuft vollständig im Browser. Es werden keine Daten gespeichert, übertragen oder protokolliert.
•	Offline-fähig: Die App ist eine einzelne HTML-Datei ohne Server, Datenbank oder externe Abhängigkeiten.

2. Aufbau und Struktur
Die App besteht aus 30 Modulen in drei Themenbereichen. Jedes Modul enthält 4–5 Aufgaben und einen abschließenden Handlungsauftrag, der im persönlichen Handlungstresor gespeichert wird.

Thema	Module	Aufgaben je Modul
🔍 Erkennen	10 Module	4–5 Aufgaben
💬 Reflektieren	10 Module	4–5 Aufgaben
✊ Handeln	10 Module	4–5 Aufgaben
Gesamt	30 Module / ~9 Stunden

Aufgabentypen
•	Einzelauswahl (Quizfragen): Eine richtige Antwort aus drei Optionen. Direktes Feedback mit Erklärung.
•	Mehrfachauswahl: Mehrere richtige Antworten möglich. Auswahl und gemeinsame Auswertung.
•	Handlungsauftrag (Freitext): Ein persönlicher Auftrag an sich selbst. Wird im Handlungstresor gespeichert.

Thema 1: Erkennen
Die 10 Module des ersten Themenbereichs bauen Grundwissen über Rassismus auf:
–	Was ist Rassismus? – Definitionen, Machtkomponente, Unterschied zu Vorurteil
–	Alltagsrassismus – Erscheinungsformen im täglichen Leben
–	Struktureller Rassismus – Systeme und Institutionen
–	Kulturrassismus & moderne Formen – Ethnopluralismus, neue Sprache
–	Kolonialismus & seine Folgen – Geschichte und Gegenwart
–	Sprache & rassistische Begriffe – Wirkung von Worten
–	Das Konzept »Wir« und »Die« – Othering
–	Rassismus in Institutionen – strukturelle Diskriminierung
–	Rassismus & Antisemitismus – Gemeinsamkeiten und Unterschiede
–	Wiederholung & Vertiefung – BIPoC, Kernkonzepte

Thema 2: Reflektieren
Die 10 Reflexionsmodule fördern Selbstwahrnehmung und kritisches Denken:
–	Privileg erkennen – unsichtbare Vorteile wahrnehmen und nutzen
–	Vorurteile & Gehirn – Autopilot und unbewusste Programme
–	Innocent Racism – Wirkung ohne Absicht
–	Ally sein – aktive Solidarität
–	Empathie & Perspektivwechsel – andere Lebensrealitäten verstehen
–	Sprache verlernen – Verlernbuch, kulturelle Aneignung
–	Stereotype hinterfragen – Mechanismen erkennen
–	Rassismus in Medien – Sündenbockmechanismen, Online-Rassismus
–	Identität & Zugehörigkeit – Intersektionalität
–	Antirassismus im Alltag – tägliche Praxis

Thema 3: Handeln
Die 10 Handlungsmodule trainieren konkrete Zivilcourage:
–	Zivilcourage – Grundlagen und Haltung
–	Handlungsoptionen in konkreten Situationen – was tun?
–	Racial Profiling & Behörden – Rechte kennen
–	Als Ally handeln – Fallbeispiele
–	Schule ohne Rassismus – Schulkultur gestalten
–	Mit Betroffenen kommunizieren – zuhören, fragen, stärken
–	Antirassismus in sozialen Medien – online handeln
–	Vorbilder & Gemeinschaft – Motivation und Netzwerk
–	Fehler machen & weitermachen – Lernprozess
–	Mein Weg nach vorne – persönliches Manifest

3. Der Handlungstresor
Der Handlungstresor ist das Herzstück der App. Er ist ein privater, geschützter Bereich, in dem ausschließlich persönliche Handlungsaufträge gespeichert werden.

Was im Tresor landet
Jedes Modul endet mit einem Handlungsauftrag – einem konkreten Ich-Versprechen. Beispiele: »Wenn ich pauschalisiere, stelle ich mir diese Fragen: …« oder »Als Ally werde ich diese Woche konkret Folgendes tun: …« Diese Einträge landen im Tresor und sind jederzeit abrufbar.

Tresor-Funktionen
•	Alle Einträge mit Datum, Modulname und ursprünglichem Auftrag angezeigt
•	Einträge können einzeln gelöscht werden
•	Beim Abschluss jedes Moduls direkter Sprung in den Tresor
•	Vollständig privat – kein Datenzugriff von außen möglich

Datenschutzhinweis
Der Tresor speichert ausschließlich im Arbeitsspeicher des Browserfensters (JavaScript-Variable). Beim Schließen des Tabs ist alles gelöscht. Es gibt keine localStorage-, Cookie- oder Netzwerkspeicherung. Die App ist vollständig offline-fähig.

4. Technische Details
Systemvoraussetzungen
•	Moderner Browser (Chrome, Firefox, Safari, Edge) – keine Installation
•	Internet nur beim ersten Öffnen erforderlich (für Google Fonts Inter)
•	Funktioniert auf Desktop, Tablet und Smartphone
•	Empfohlene Mindest-Bildschirmbreite: 360 px

Dateibeschreibung
antirassismus-lernapp-v4.html
Einzelne HTML-Datei (~1,5 MB). Enthält alle 30 Module, CSS, JavaScript und Spiellogik in einer Datei. Kann auf einem Schulserver, USB-Stick oder direkt im Browser geöffnet werden.

Design
•	Schrift: Inter (Google Fonts) mit System-Fallback
•	Hintergrund: Dunkelblau (Erdatmosphäre) mit Erdkugel-Orb und Sternenhimmel
•	Akzentfarben: Regenbogenfarben als Symbol für Diversität (Titelleiste, Buttons, Abzeichen)
•	Kontrastoptimiert für Lesbarkeit auf dunklem Grund
•	OLED-freundlich: Schwarze Hintergrundflächen sparen Akku

Gamification
•	Punktesystem: 10 Punkte pro richtig beantworteter Aufgabe
•	Abzeichen: pro Themenbereich eines, plus »Vollständig«-Abzeichen
•	Fortschrittsbalken: zeigt Verlauf innerhalb eines Moduls
•	Modulkarten: nach Abschluss visuell als »Fertig« markiert

5. Einsatz im Unterricht
Empfohlene Einsatzszenarien
•	Einzelarbeit (Hausaufgabe, Freiarbeit): Schüler*innen wählen selbst Module und arbeiten im eigenen Tempo.
•	Unterrichtsbegleitung: Lehrkraft öffnet spezifische Module als Einstieg oder Vertiefung zu einem Thema.
•	Projektwochen: Themenblöcke als mehrstündige Einheit (z.B. alle 10 Erkennen-Module an einem Tag).
•	SV-Arbeit: Module zu »Schule ohne Rassismus« als Grundlage für Schulinitiativen.

Zeitbedarf
•	Pro Modul: ca. 8–12 Minuten
•	Pro Themenbereich (10 Module): ca. 90–120 Minuten
•	Vollständiger Lernpfad (30 Module): ca. 5–6 Stunden

Pädagogische Hinweise
•	Keine Lehrkraftpräsenz erforderlich: Die App ist selbsterklärend und autonom nutzbar.
•	Kein Leistungsdruck: Punkte sind motivational, nicht benotbar. Die Anzahl der Versuche ist nicht sichtbar.
•	Reflexionen sind vertraulich: Handlungsaufträge bleiben auf dem Gerät der Schüler*in – keine Lehrkraft sieht sie.
•	Anschlusskommunikation empfohlen: Nach dem Tresor-Eintrag können Klassen-Gespräche geführt werden (freiwillig und ohne Einsicht in Einzeleinträge).

Hinweis zur Sensibilität
Die App wurde so konzipiert, dass keine rassistischen Inhalte reproduziert oder gelesen werden müssen. Alle Beispiele in Quizfragen beschreiben Mechanismen, ohne verletzende Begriffe zu verwenden. Reflexionsaufgaben sind ausschließlich nach innen gerichtet.

6. Quellen & Grundlage
Die Inhalte der App basieren auf folgenden Materialien:

•	Gugel, Günther: Alltäglicher Rassismus. Themenblätter im Unterricht Nr. 110. Bundeszentrale für politische Bildung (bpb), 2. Auflage 2017.
–	Einschließlich Lehrerblätter 01–06 sowie Kopiervorlagen und Arbeitsblätter A und B
•	Ally sein – Broschüre zur antirassistischen Bildungsarbeit. Königin-Luise-Schule Köln.
•	Einleitung Arbeitsheft gegen Rassismus. Königin-Luise-Schule Köln.

Zitierte Personen und Werke in den Modulen:
–	Hannah Arendt: Elemente und Ursprünge totaler Herrschaft
–	Victoria B. Robinson: »Innocent Racism« (Gedicht/Essay)
–	Astrid Messerschmidt: Rassismuskritische Bildungsarbeit
–	Andreas Zick: Spielarten des Rassismus
–	Nelson Mandela, Martin Luther King Jr., Banksy (Zitate)
–	Antidiskriminierungsbüro (ADB): Sprache schafft Wirklichkeit, Köln 2013

7. Versionshinweise
Version 4 – finale Version nach mehrstufiger Qualitätsprüfung.

•	Version 1: Grundstruktur mit 3 × 4 Modulen, helles Design
•	Version 2: Erweiterung auf 3 × 6 Module, Warm-Slate-Farbschema
•	Version 3: Erdhintergrund & Regenbogendesign, Handlungstresor eingeführt
•	Version 4: Vollständige 30 Module, Inter-Schrift, Qualitätsprüfung, alle Reflexionsfragen überarbeitet, JS-Bugs behoben

Entwicklung
Entwickelt mit Unterstützung von Claude (Anthropic) auf Basis pädagogischer Anforderungen einer Lehrkraft. Alle Inhalte wurden gegen die Quellmaterialien geprüft und auf antirassistische Konsistenz überarbeitet.

»Mit uns fängt es an, dass der Rassismus aufhört.«
Arbeitsheft gegen Rassismus, Königin-Luise-Schule Köln
