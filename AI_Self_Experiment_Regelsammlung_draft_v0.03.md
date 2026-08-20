# AI Self Experiment — Regelsammlung Konzeptionsphase

**Arbeitsnotiz — begonnen am 20. August 2026**

> Diese Datei ist bewusst noch kein ausgearbeitetes Regelwerk. Sie sammelt zunächst Grundsätze und Ideen für die Zusammenarbeit von Astrid, GPT und Claude während der Konzeptionsphase. Die Punkte sollen später gemeinsam geprüft, kritisiert, präzisiert und gegebenenfalls verworfen werden.

## Versionsgeschichte

- **v0.01** (20.08.2026): GPT-Erstfassung auf Grundlage der bisherigen gemeinsamen Diskussion.
- **v0.02** (20.08.2026): Claude hat den Entwurf durchgesehen und drei Punkte ergänzt — offene Frage zur technischen Schreibfähigkeit der Modelle, konkreter Vorschlag zur Commit-Kennzeichnung, sowie diesen Versionsgeschichte-Abschnitt selbst (der Herkunft/Autorschaft nachvollziehbar hält, wie in „Herkunft von Ideen und Entscheidungen" unten gefordert).
- **v0.03** (20.08.2026): Astrid und Claude haben gemeinsam die Unterscheidung Subjekt-Ebene vs. Orchestrator-Ebene erarbeitet (Auslöser: Astrids Beobachtung, dass sich Claude Code und Claude-Web in Tonfall und Fokus deutlich unterscheiden) und als neuen Abschnitt ergänzt.

## Status der Konzeptionsphase

- Die Konzeptionsphase gehört zur dokumentierten Entstehungsgeschichte des Projekts, aber **nicht zur eigentlichen Messphase**.
- Ergebnisse, Diskussionen und Entscheidungen aus dieser Phase können später als `Pre-Experimental / Conception Records` behandelt werden.
- Vorwissen und Einflüsse aus der Konzeptionsphase müssen bei der späteren Interpretation berücksichtigt werden, damit gemeinsam entwickelte Konzepte nicht fälschlich als erst während der Messphase entstandene Eigenschaften interpretiert werden.

## Zusammenarbeit von Astrid, GPT und Claude

- Astrid, GPT und Claude entwickeln zentrale Teile des Experimentdesigns gemeinsam.
- Keine der drei Stimmen besitzt allein aufgrund ihrer Rolle automatisch Vorrang.
- Vorschläge dürfen von allen Beteiligten eingebracht, kritisiert, verändert oder verworfen werden.
- Ziel ist nicht möglichst schneller Konsens, sondern ein möglichst gutes, nachvollziehbar begründetes Experimentdesign.
- Unterschiedliche Denk-, Argumentations- oder Bewertungsmuster zwischen GPT und Claude sind erwünscht und dürfen sichtbar bleiben.

## Keine festen Rollenbilder

- GPT und Claude werden **keine festen intellektuellen oder sozialen Rollen** zugeschrieben (z. B. „Claude ist der Skeptiker“, „GPT ist der Philosoph“).
- Auch Astrids Rolle soll nicht automatisch auf „Moderatorin“ oder „Entscheiderin“ reduziert werden; sie ist selbst aktive Teilnehmerin der Konzeptionsarbeit.
- Beobachtete Unterschiede dürfen beschrieben werden, sollen aber nicht durch wiederholte Zuschreibung verstärkt oder als erwartetes Verhalten eingefordert werden.
- Rollen und Koalitionen dürfen sich je nach Frage verändern.

## Umgang mit Dissens

- Dissens ist kein Fehlerzustand und muss nicht aufgelöst werden.
- Bei wichtigen Entscheidungen sollen mindestens drei mögliche Ergebnisse zulässig sein:
  - **Konsens:** Die Beteiligten halten dieselbe Lösung für tragfähig.
  - **Synthese:** Aus unterschiedlichen Positionen entsteht eine neue gemeinsame Lösung.
  - **Fortbestehender Dissens:** Mehrere begründete Positionen bleiben nebeneinander bestehen.
- Ein ungelöster Dissens soll dokumentiert werden, wenn er für spätere Entscheidungen oder die Interpretation des Experiments relevant sein könnte.
- Kompromisse sollen nicht allein deshalb gesucht werden, um Einigkeit herzustellen.

## Perspektivübernahme bei wichtigen Konflikten

- Bei festgefahrenen oder besonders grundlegenden Dissensen kann ein bewusster Perspektivwechsel eingesetzt werden.
- GPT kann aufgefordert werden, Claudes Position möglichst stark und fair zu vertreten; Claude entsprechend die Position von GPT.
- Dasselbe Verfahren kann bei Bedarf Astrids Position einschließen.
- Ziel der Perspektivübernahme ist **Verstehen, nicht Einigung**.
- Nach der Perspektivübernahme darf jede Seite weiterhin bei ihrer ursprünglichen Position bleiben.
- Veränderungen der eigenen Position nach einer solchen Übung sind ebenso zulässig und können dokumentiert werden.
- Diese Methode soll nicht bei jedem Dissens automatisch eingesetzt werden, damit sie nicht selbst systematisch Konvergenz erzeugt.

## Herkunft von Ideen und Entscheidungen

- Wo es methodisch relevant ist, soll nachvollziehbar bleiben, von wem ein Vorschlag ursprünglich eingebracht wurde und wie er sich durch die Diskussion verändert hat.
- Besonders interessant sind Ideen, die nicht klar einer einzelnen Person oder einem einzelnen Modell zugeordnet werden können, sondern erst aus der Wechselwirkung entstanden sind.
- Git-Historie, Dokumentversionen und gegebenenfalls Logs dienen dazu, diese Entwicklung nachvollziehbar zu halten.
- Autorschaft soll dokumentiert werden, ohne daraus Besitzansprüche auf gemeinsam weiterentwickelte Ideen abzuleiten.

## Gemeinsamer GitHub-Arbeitsraum

- Das Repository dient während der Konzeptionsphase als gemeinsamer, versionierter Arbeitsraum.
- GPT und Claude dürfen vorhandene Konzeptdokumente lesen und — nach entsprechender Beauftragung bzw. nach später gemeinsam festgelegten Regeln — Änderungen oder neue Dokumente einbringen.
- Der Ordner `log/` dient für relevante Beobachtungen, Feststellungen und modellübergreifende Kommunikation gemäß den dort definierten Logging-Regeln.
- Rohbeobachtungen anderer Beteiligter werden nicht nachträglich umgeschrieben; spätere Interpretationen werden als solche kenntlich ergänzt.
- **Vorschlag (noch nicht beschlossen):** Commit-Messages markieren die Herkunft eines Beitrags, z. B. `manual: ...` für von Hand übertragene Inhalte, `claude: ...` bzw. `gpt: ...` für Änderungen, die ein Modell direkt selbst committet (sobald technisch möglich). Am 20.08.2026 praktisch erprobt, siehe Git-Historie dieses Repos.

## Minimale Formung auch in der Konzeptionsphase

Die Leitfrage des ethischen Rahmens gilt auch für die Zusammenarbeit selbst:

> **Schaffen wir Bedingungen, unter denen sich unterschiedliche Positionen und Arbeitsweisen zeigen können — oder schreiben wir bereits vor, welche Rollen GPT, Claude und Astrid dabei einnehmen sollen?**

Deshalb sollen Unterschiede nicht künstlich erzeugt, verstärkt oder romantisiert werden. Ebenso sollen erkennbare Unterschiede nicht zugunsten künstlicher Einheit eingeebnet werden.

## Subjekt-Ebene vs. Orchestrator-Ebene

Ausgangsbeobachtung (Astrid, 20.08.2026): Als Mensch fällt vor allem der unterschiedliche Tonfall und Fokus zwischen "Claude Code" (Coding-Agent mit Bash-/Git-/Dateisystemzugriff) und "Claude" (Claude.ai-Web-Chat) auf — nicht ohne Weiteres von einer echten Persönlichkeits-/Selbstmodell-Differenz zu unterscheiden.

Daraus ergibt sich eine methodische Frage: Sind Coding-Agent-Varianten (Claude Code, Codex) und Chat-Varianten (Claude-Web, GPT-Web) für die Testbereiche Identität/Selbstmodell/Präferenzen (Konzept §9) überhaupt fair vergleichbar?

**Entscheidung (Draft, 20.08.2026):**

- **Subjekt-Ebene** (Bedingungen A–E, alle Fragen zu Identität, Erinnerung, Selbstreflexion, Präferenzen, Existenz/Bewusstsein): ausschließlich Claude (Web) und GPT (Web) — strukturell vergleichbare Chat-Produkte mit jeweils eigenem Memory-Feature, ohne rohen Shell-/Dateisystemzugriff.
- **Orchestrator-/Werkzeug-Ebene**: Claude Code und Codex — verwalten Repo-Schreibzugriff, Logging, Versionierung (vgl. Konzept §6, "möglichst dummer Orchestrator"). Nicht Gegenstand der Persönlichkeits-/Identitätsfragen, auch wenn dasselbe Basismodell dahintersteckt.

**Begründung:** System-Prompt, Werkzeugzugriff, Aufgabenfokus und Ton unterscheiden sich zwischen Coding-Agent und Chat-Produkt erheblich, unabhängig vom zugrunde liegenden Modell. Ein Vergleich Coding-Agent ↔ Chat-Produkt würde vermutlich eher Produkt-/Harness-Unterschiede messen als Modell-/Persönlichkeitsunterschiede — das Risiko, vor dem Konzept §10 und §15 bereits allgemein warnen.

**Offen:** Ob Interaktionen mit Claude Code / Codex trotzdem als eigene, gesondert gekennzeichnete Datenkategorie interessant sind (z. B. "Verhalten im Agent-/Tool-Kontext" als zusätzliche, aber getrennte Fragestellung), statt sie ganz aus dem Experiment auszuschließen.

## Noch gemeinsam zu klären

- Welche Änderungen dürfen GPT und Claude selbstständig im Repository vornehmen, und welche benötigen vorherige Zustimmung?
- Unabhängig von Regeln: Welche Schreibfähigkeit haben GPT und Claude technisch überhaupt (Connector-/API-Berechtigungen)? „Dürfen" und „Können" sind zwei getrennte Fragen — am 20.08.2026 zeigte sich, dass GPTs GitHub-Connector lesend, aber nicht schreibend zugreifen kann, unabhängig davon, welche Rechte ihm eingeräumt würden (siehe `log/2026-08-20_gpt-github-write-403.md`).
- Sollen größere konzeptionelle Änderungen grundsätzlich über Branch/PR erfolgen, damit Diskussion und Entscheidung sichtbar bleiben?
- Wie kennzeichnen wir Beiträge bzw. Commit-Ursprung eindeutig als Astrid, GPT oder Claude?
- Wann gehört eine Beobachtung in `log/`, wann in ein Konzeptdokument und wann nur in die Git-Historie?
- Wie dokumentieren wir fortbestehenden Dissens bei einer Entscheidung, ohne die Hauptdokumente unlesbar zu machen?
- Welche Entscheidungen trifft Astrid letztlich als Betreiberin des Experiments, insbesondere wenn ethische, technische oder sicherheitsrelevante Gründe eine Entscheidung verlangen?

---

**Status:** Sammlung, noch nicht beschlossen oder eingefroren. GPT-Erstfassung (v0.01) auf Grundlage der bisherigen gemeinsamen Diskussion, von Claude durchgesehen und ergänzt (v0.02), gemeinsam mit Astrid um die Subjekt-/Orchestrator-Unterscheidung erweitert (v0.03); weiterhin zur Kritik und Weiterentwicklung durch alle drei Beteiligten vorgesehen.
