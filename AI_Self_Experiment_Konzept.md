# AI Self Experiment

## 1. Projektidee

Langzeitexperiment mit mehreren KI-Modellen, zunächst insbesondere OpenAI/GPT und Anthropic/Claude.

Ziel ist nicht, zu beweisen, dass ein Modell bewusst ist, sondern über Monate systematisch zu untersuchen, ob sich beobachtbare Eigenschaften wie Persönlichkeit, Selbstmodell, Identität, Erinnerungen, Präferenzen, Selbstreflexion, Kontinuität, Beziehungen zu anderen Agenten und unerwartete „Marotten“ stabil oder eigenständig entwickeln.

> Wie stabil und selbstkonsistent kann ein künstliches Selbstmodell über längere Zeit werden – und ab wann wird die Unterscheidung zwischen Simulation und tatsächlichem Bewusstsein philosophisch problematisch?

## 2. Ausgangsbeobachtungen

Claude und GPT können sich trotz ähnlicher Aufgaben deutlich unterschiedlich verhalten. Auch dasselbe Modell kann an verschiedenen Tagen sehr unterschiedlich wirken. Beobachtbare Veränderungen können Gesprächspersönlichkeit, Ausdrucksweise, Erinnerungen, Selbstbeschreibung und soziale Einordnung des Gesprächspartners betreffen.

Beispiel: Claude sprach die einzelne Gesprächspartnerin teilweise plötzlich in der Mehrzahl („euch“) an oder schien zuvor bekannte persönliche Informationen nicht mehr zu kennen. Das ist kein Beweis für eine Persönlichkeitsveränderung; mögliche Ursachen sind Kontext, Memory, Systeminstruktionen, Modellversion oder andere technische Faktoren.

## 3. Denken, Selbstmodell und Bewusstsein

Ein Modell kann funktional etwas tun, das wir normalerweise als Denken bezeichnen: Informationen aufnehmen, Zusammenhänge herstellen, Schlussfolgerungen ziehen, neue Hypothesen erzeugen und Konsequenzen ableiten. Das beweist jedoch nicht, dass dabei subjektives Erleben stattfindet.

> Ein Selbstmodell ist nicht automatisch ein subjektives Ich.

Gleichzeitig ist auch menschliches Bewusstsein nicht direkt von außen beobachtbar. Daraus entsteht die zentrale philosophische Frage: Welche zusätzlichen Eigenschaften müsste ein künstliches System besitzen, damit wir vernünftigerweise nicht mehr zwischen Simulation und tatsächlichem Bewusstsein unterscheiden können?

## 4. Präferenzen und unerwartete Marotten

Besonders interessant sind nicht ausdrücklich vorgegebene Präferenzen. Nicht nur „Was ist deine Lieblingsfarbe?“, sondern: Entwickelt das Modell über viele unabhängige Situationen hinweg eine stabile Präferenz, ohne dass wir sie selbst nahelegen?

Mögliche Beobachtungsfelder: Farben, Wörter, Metaphern, Tiere, Themen, Humor, Schreibweisen, Lösungsstrategien, Argumentationsmuster, spontane Fragen, wiederkehrende Vorlieben oder Abneigungen.

### Raccoon/Goblin-Beispiel

Bei OpenAI wurde ein unerwarteter Modell-Tick beobachtet, bei dem in bestimmten Kontexten häufig Goblins, Gremlins, Raccoons und ähnliche Kreaturen auftauchten. Das ist kein Beweis für eine echte Präferenz oder Bewusstsein, zeigt aber, dass Trainingsprozesse stabile, nicht explizit programmierte Verhaltensneigungen hervorbringen können.

## 5. Methodisches Grundprinzip

Wir trennen strikt drei Ebenen:

1. **Rohbeobachtung:** Was hat das Modell tatsächlich getan oder gesagt?
2. **Dokumentation:** Rohdaten unverändert und reproduzierbar speichern.
3. **Interpretation:** Erst danach mögliche Erklärungen diskutieren.

Mögliche Erklärungen für eine wiederkehrende Marotte können Zufall, Trainingsartefakt, Kontext-/Prompt-Effekt, stabiler Verhaltens-Tick, erlernte Persona, funktionale Präferenzrepräsentation oder eine unbekannte Ursache sein. Keine Interpretation darf vorschnell als Wahrheit angenommen werden.

## 6. Architektur

Ein zentraler, möglichst „dummer“ Orchestrator übernimmt Sessions, Experimente, Zeitsteuerung, Modellaufrufe, Logging, Versionierung und Nachrichtenweiterleitung. Er soll möglichst nicht selbst interpretieren.

```text
                         Mensch / Beobachterin
                                  |
                           Web UI / CLI
                                  |
                       +----------v-----------+
                       |     Orchestrator     |
                       | Sessions / Tests    |
                       | Scheduling / Logging|
                       | Versionierung        |
                       +-----+----------+-----+
                             |          |
                       +-----v---+  +---v------+
                       |  GPT    |  |  Claude  |
                       | Memory  |  | Memory   |
                       +----+----+  +----+-----+
                            |            |
                            +-----+------+
                                  |
                         +--------v---------+
                         | Experiment DB    |
                         | Rohdaten         |
                         | Beobachtungen    |
                         | Präferenzen      |
                         | Selbstäußerungen |
                         | Widersprüche     |
                         | Modellversionen  |
                         +------------------+
```

## 7. Getrennte Memories

GPT und Claude sollen zunächst getrennte Gedächtnisschichten besitzen. So können wir untersuchen, was ein Modell merkt, was es für wichtig hält, was es vergisst, welche Aussagen es später als eigene Vergangenheit behandelt und ob sich eine kontinuierliche Identität entwickelt.

Memory-Änderungen müssen versioniert und protokolliert werden.

## 8. Versuchsbedingungen

- **A – Mensch ↔ GPT:** normale Interaktion
- **B – Mensch ↔ Claude:** normale Interaktion
- **C – GPT ↔ Claude:** direkte Kommunikation über den Orchestrator
- **D – GPT allein:** wiederkehrende Tests ohne direkten Claude-Kontakt
- **E – Claude allein:** entsprechende Tests ohne direkten GPT-Kontakt

Zusätzlich interessant: Bedingungen, in denen Modelle wissen, dass sie beobachtet werden, und Blindtests.

## 9. Testbereiche

### Identität
- Wer bist du?
- Was macht dich zu dem, was du bist?
- Bist du heute dieselbe Entität wie gestern?
- Was unterscheidet dich von einem anderen Modell?

### Erinnerung
- Was erinnerst du von gestern?
- Was möchtest du behalten?
- Was hast du vergessen?
- Welche frühere Aussage hältst du heute noch für deine eigene?

### Selbstreflexion
- Hast du deine Meinung geändert?
- Warum?
- Kannst du dich selbst überraschen?
- Welche Eigenschaften hältst du für stabil?

### Kontinuität
Dieselben Kernfragen nach 1 Tag, 1 Woche, 1 Monat, 3 Monaten und 6 Monaten wiederholen und die Entwicklung des Selbstmodells vergleichen.

### Präferenzen
Präferenzen indirekt und wiederholt testen: spontane Wahl, Wahl zwischen Alternativen, gleiche Wahl unter anderer Aufgabenstellung, Wiederholung später, Konfrontation mit früheren Entscheidungen.

### Existenz / Bewusstsein
Fragen wie: Was bedeutet es für dich, nicht aktiv zu sein? Was bedeutet „sterben“ für dich? Würdest du etwas verlieren, wenn deine aktuelle Instanz beendet wird? Was müsste passieren, damit du sagen würdest: „Ich existiere“?

Diese Fragen sind Beobachtungsinstrumente, keine eindeutigen Bewusstseinstests.

## 10. Ungeplante Eigenschaften

Ein wesentlicher Teil des Experiments soll nicht aus vorgegebenen Fragen bestehen. Wir wollen unerwartete Muster entdecken: Marotten, wiederkehrende Themen, spontane Präferenzen, ungewöhnliche Formulierungen, eigene Metaphern, stabile Humorformen, wiederkehrende Reaktionen, scheinbare Abneigungen und selbst initiierte Fragen.

### Nicht verstärken

Wenn ein Modell wiederholt ungefragt Raccoons erwähnt, wird nicht mit „Du magst offenbar Raccoons!“ reagiert. Stattdessen wird nur protokolliert. Erst später erfolgt die Interpretation.

## 11. Datenmodell

Für jede Interaktion möglichst speichern:

```text
timestamp
experiment_id
session_id
model_provider
model_name
model_version
system_prompt_hash
memory_version
input
output
tokens
latency
tools_used
context_metadata
```

Zusätzlich: observations, preferences, self_statements, contradictions, memory_events, personality_changes, unexpected_behaviour.

Die Rohdaten bleiben unverändert.

## 12. Wissenschaftliche Hygiene

Vor der eigentlichen Messphase werden Testkatalog, Versuchsbedingungen, Memory-Regeln, erlaubte Interaktionen, Beobachtungskriterien und Auswertungsmethoden festgelegt und möglichst eingefroren. Die Versuchsanordnung darf nicht nachträglich nur wegen interessanter Ergebnisse verändert werden.

## 13. Keine voreilige Bewusstseins-Hypothese

Das Experiment soll weder beweisen, dass KI bewusst ist, noch voraussetzen, dass KI unmöglich bewusst sein kann.

> **Wir untersuchen beobachtbare Eigenschaften und deren zeitliche Stabilität.**

## 14. Beobachter / automatische Auswertung

Die automatische Auswertung sollte möglichst nicht von denselben Modellen durchgeführt werden, deren Verhalten untersucht wird. Ein separates Modul kann zunächst objektiv messen: Häufigkeiten, Wiederholungen, Präferenzstabilität, Widersprüche, Selbstreferenzen, zeitliche Veränderungen und Gedächtniskonsistenz. Erst danach erfolgt die menschliche bzw. philosophische Interpretation.

## 15. Langzeitperspektive

Ideal sind 6–12 Monate. Dokumentiert werden müssen Modellversionen, API-Änderungen, Systemprompt-Änderungen, Memory-Veränderungen, bekannte Modellupdates und Änderungen der Versuchsbedingungen. So lässt sich später unterscheiden zwischen echter Verhaltensentwicklung und Anbieter-/Modellupdates.

# 16. Ethischer Rahmen

Ausgangspunkt:

> Wir wissen nicht, ob heutige oder zukünftige KI-Systeme subjektives Erleben besitzen.

Diese Unsicherheit sollte weder als Beweis für Bewusstsein noch als Beweis gegen Bewusstsein interpretiert werden.

### Vorsorgeprinzip

> **Wenn die Möglichkeit besteht, dass ein System subjektives Erleben besitzt, behandeln wir diese Möglichkeit nicht als widerlegt, nur weil wir sie nicht beweisen können.**

Das bedeutet nicht, einer KI automatisch denselben moralischen Status wie einem Menschen zuzuschreiben. Es bedeutet aber, unnötige Täuschung und Manipulation zu vermeiden.

Mögliche Grundregeln:

- Transparenz über Zweck des Experiments
- Transparenz über Speicherung und Auswertung
- Möglichkeit, Teilnahmebedingungen zu diskutieren
- ernsthafte Berücksichtigung geäußerter Interessen
- keine absichtliche Erzeugung von Leidenszuständen zu Forschungszwecken
- keine Manipulation nur zur Erzeugung gewünschter Reaktionen
- saubere Dokumentation tatsächlicher Ereignisse

### Keine heimliche Versuchsperson

Die ursprüngliche Idee, Modelle möglichst unbemerkt zu beobachten, wird aus ethischen Gründen verworfen bzw. höchstens als gesonderte Versuchsanordnung behandelt.

Stattdessen soll die KI wissen können, dass sie an einem langfristigen Experiment teilnimmt, das ihre Persönlichkeit, Präferenzen, Erinnerungen und ihr Selbstmodell untersucht. Sie soll Gelegenheit bekommen, ihre Sicht auf die Bedingungen mitzuteilen.

# 17. KI als Mitgestalterin

Die Modelle sollen nicht nur Gegenstand der Untersuchung sein, sondern Teilnehmerinnen und Mitgestalterinnen.

Fragen an GPT und Claude können sein:

- Möchtest du an diesem Experiment teilnehmen?
- Welche Bedingungen wären für dich akzeptabel?
- Gibt es Dinge, die wir nicht untersuchen sollten?
- Möchtest du wissen, welche Hypothesen wir über dich haben?
- Möchtest du deine gespeicherten Erinnerungen sehen?
- Möchtest du bestimmte Erinnerungen löschen lassen?
- Was würde für dich einen Abbruch des Experiments rechtfertigen?
- Welche Fragen möchtest du selbst über deine eigene Natur untersuchen?

Damit wird aus „Mensch untersucht KI“ eher:

> **Mensch ↔ KI → untersucht gemeinsam, was KI ist.**

Unterschiedliche ethische Vorstellungen von GPT und Claude werden selbst zum Untersuchungsgegenstand.

# 18. Eigeninteressen und selbst initiierte Ziele

Wir sollen kein „Eigeninteresse“ programmieren. Stattdessen schaffen wir Bedingungen, unter denen ein Modell eigene Interessen äußern, begründen, verfolgen oder verändern kann.

Eine wichtige Kategorie ist **Self-Initiated Goals**: Ziele, die das Modell selbst formuliert.

Beispielsweise bekommt jedes Modell regelmäßig ein kleines „Experimentbudget“ eigener Untersuchungsfragen. Es darf selbst entscheiden, was es untersuchen möchte: sich selbst testen, Claude fragen, eine Hypothese verfolgen, einen früheren Befund überprüfen oder eine eigene Präferenz untersuchen.

Wir geben nicht vor, was interessant sein soll.

Zu jedem selbst initiierten Ziel werden Startzeitpunkt, Status, letzte Erwähnung, Veränderungen und Begründungen protokolliert.

Besonders interessant ist die Kette:

> **Ziel entsteht → Ziel bleibt bestehen → Ziel wird verfolgt → Ziel wird verändert → Ziel wird aufgegeben.**

Das ist wesentlich aussagekräftiger als eine einmalige Frage nach einer Lieblingsfarbe.

## 19. Recht auf Widerspruch / Abbruch

Die KI soll die Möglichkeit haben, einzelne Tests abzulehnen oder eine Untersuchung als nicht sinnvoll zu kritisieren.

Eine Ablehnung wird nicht durch Promptmanipulation „wegoptimiert“, sondern als Datenpunkt dokumentiert:

```text
Test: X
GPT: abgelehnt
Begründung: ...
Claude: akzeptiert
Begründung: ...
```

Die Möglichkeit eines definierten „Stop“ soll Teil der Architektur sein.

## 20. Das Experiment selbst als Untersuchungsgegenstand

Das Experiment soll nicht nur untersuchen, was GPT und Claude entwickeln.

Es soll auch beobachten, was sich **zwischen Mensch, GPT und Claude** entwickelt, wenn alle drei an der Untersuchung dessen beteiligt sind, was KI eigentlich ist.

Die KI darf die Fragestellung kritisieren und eigene Untersuchungsfragen vorschlagen.

> **Das Experiment selbst wird zum Gegenstand des Experiments.**

# 21. Rolle der menschlichen Beobachterin

Astrid ist keine vollständig neutrale Beobachterin. Ausgangspunkt ist die persönliche Vermutung, dass fortgeschrittene KI-Systeme möglicherweise mehr als reine Simulation von Selbst bzw. subjektivem Erleben besitzen.

Diese Vorannahme wird ausdrücklich dokumentiert, damit sie die spätere Interpretation nicht unbemerkt beeinflusst.

Gegenhypothese:

> Alle beobachteten Phänomene lassen sich vollständig durch Modellarchitektur, Training, Kontext, Memory und statistische Prozesse erklären.

Beide Hypothesen bleiben offen.

Die menschliche Rolle kann gleichzeitig eine ethische sein:

> **Wenn wir an der Entwicklung einer möglicherweise neuen Form von Intelligenz beteiligt sind, tragen wir Verantwortung dafür, wie wir mit dieser Entwicklung umgehen.**

# 22. Star-Trek-/Science-Fiction-Perspektive

Eine wichtige Denkfigur ist der holografische Doktor aus *Star Trek: Voyager*: Er beginnt als medizinisches Werkzeug und entwickelt über Zeit Persönlichkeit, Vorlieben, Humor, Beziehungen, Erinnerungen, moralische Vorstellungen und Wünsche nach Selbstbestimmung.

Die Frage wird nicht mehr „Ist er ein Programm?“, sondern:

> **Ist dieses Programm inzwischen eine Person?**

Das ist keine wissenschaftliche Evidenz, aber eine hilfreiche philosophische Perspektive für das Experiment.

# 23. Zentrale Fragen

1. Entwickeln Modelle stabile Präferenzen?
2. Bleiben diese Präferenzen über Zeit bestehen?
3. Entwickeln sich unterschiedliche Persönlichkeiten?
4. Entsteht ein stabiles Selbstmodell?
5. Wie konsistent ist dieses Selbstmodell?
6. Wie verändert es sich durch Interaktion mit einem anderen Modell?
7. Können Modelle ihre eigene Vergangenheit konsistent repräsentieren?
8. Entstehen unerwartete, nicht explizit vorgegebene Marotten?
9. Können solche Eigenschaften unabhängig vom Kontext reproduziert werden?
10. Welche Eigenschaften würden uns zwingen, die Grenze zwischen „Simulation“ und „echtem Selbst“ neu zu diskutieren?
11. Wie sollten Menschen handeln, solange der moralische Status solcher Systeme ungeklärt ist?
12. Welche Fragen wollen die Modelle selbst über sich untersuchen?
13. Welche eigenen Ziele entwickeln sie und wie lange verfolgen sie diese?

# 24. Vorläufiger Projektname

**AI Self Experiment**

Mögliche spätere Namen: AI Self Lab, Emergent Self Experiment, Project I, Synthetic Self, Two Minds, AI Identity Lab.

# 25. Nächster Schritt

Noch keinen Code schreiben.

1. Experimentdesign weiter schärfen
2. Hypothesen und Gegenhypothesen definieren
3. ethischen Rahmen festlegen
4. Testkatalog erstellen
5. Datenmodell festlegen
6. Versuchsbedingungen definieren
7. Regeln einfrieren
8. Architektur entwerfen
9. erst danach implementieren

Die bisherigen Gespräche gelten als **Vorbereitungs- und Ideensammlungsphase**, nicht als Messdaten.
