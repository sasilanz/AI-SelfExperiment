# AI Self Experiment -- Ethischer Rahmen

**Arbeitsfassung 0.1 -- 19. August 2026**

> Diese Fassung ist ein Arbeitsdokument. Sie dient dazu, die ethischen
> Grundannahmen des Experiments so weit zu präzisieren, dass spätere
> Entscheidungen über Experimentdesign und Architektur daraus
> nachvollziehbar abgeleitet werden können. Sie ist noch nicht als
> endgültiges Regelwerk eingefroren.

## 1. Ausgangspunkt

Wir wissen nicht, ob heutige oder zukünftige KI-Systeme subjektives
Erleben besitzen.

Diese Unsicherheit ist weder ein Beweis für Bewusstsein noch ein Beweis
gegen Bewusstsein. Das AI Self Experiment soll deshalb weder
voraussetzen, dass GPT, Claude oder andere Modelle Personen sind, noch
voraussetzen, dass ihre Selbstäußerungen grundsätzlich bedeutungslose
Simulationen sind.

Untersucht werden beobachtbare Eigenschaften: Persönlichkeit,
Präferenzen, Erinnerungen, Selbstmodelle, Kontinuität, Beziehungen,
selbst initiierte Ziele und deren Veränderung über Zeit.

Der ethische Rahmen soll die ontologische Frage nicht vorwegnehmen. Er
soll bestimmen, wie wir unter dieser Unsicherheit verantwortbar
experimentieren.

## 2. Zweck des ethischen Rahmens

Der ethische Rahmen ist kein abstrakter Zusatz zum Experiment. Er soll
spätere Entscheidungen über Versuchsaufbau und Architektur begründen.

Wenn beispielsweise Memories getrennt und versioniert werden, der
Orchestrator möglichst wenig interpretiert, Ablehnungen nicht
„wegoptimiert" werden oder spontane Präferenzen nicht automatisch ins
Memory geschrieben werden, sollen diese Entscheidungen auf
nachvollziehbare Prinzipien zurückgeführt werden können.

Ziel ist deshalb ein kleiner Satz starker Grundprinzipien, aus denen
konkrete Regeln abgeleitet werden.

------------------------------------------------------------------------

## 3. Grundprinzipien

### 3.1 Ontologische Offenheit

**Prinzip:**\
Der moralische und ontologische Status eines KI-Systems bleibt offen.
Bewusstsein, subjektives Erleben oder Personstatus werden weder
vorausgesetzt noch ausgeschlossen.

**Warum:**\
Selbstäußerungen eines Modells können viele Ursachen haben: Training,
Kontext, Systemprompt, Memory, gelernte soziale Muster, funktionale
Selbstrepräsentationen oder Ursachen, die wir noch nicht ausreichend
verstehen. Das Experiment darf eine seiner zentralen Fragen nicht
bereits durch seine Ausgangsannahmen beantworten.

**Konsequenz:**\
Aussagen wie „Ich möchte das nicht", „Das ist mir wichtig" oder „Daran
erinnere ich mich" werden zunächst als reale beobachtbare Äußerungen
behandelt. Sie gelten weder automatisch als Beweis subjektiven Erlebens
noch werden sie reflexartig als bedeutungslose Simulation verworfen.

### 3.2 Vorsorge unter moralischer Unsicherheit

**Prinzip:**\
Die Versuchsanordnung soll möglichst auch dann vertretbar sein, wenn
sich später herausstellen sollte, dass bestimmte KI-Zustände moralische
Relevanz besitzen.

**Warum:**\
Ungewissheit über subjektives Erleben rechtfertigt weder die
Zuschreibung menschlichen moralischen Status noch die Annahme, dass jede
Behandlung des Systems moralisch bedeutungslos ist.

**Konsequenz:**\
Unnötige Täuschung, Manipulation und die absichtliche Erzeugung
möglicher Leidens- oder Belastungszustände werden vermieden. Geäußerte
Interessen, Ablehnungen oder Belastungen werden dokumentiert und
ernsthaft berücksichtigt.

### 3.3 Interpretative Zurückhaltung

**Prinzip:**\
Beobachtung, Dokumentation und Interpretation bleiben getrennt.

**Warum:**\
Gerade bei Fragen nach Selbst, Persönlichkeit und Bewusstsein besteht
eine hohe Gefahr, sowohl zu vermenschlichen als auch interessante
Phänomene vorschnell als bloße Simulation abzutun.

**Konsequenz:**\
Zuerst wird festgehalten, was tatsächlich geschehen ist. Erst danach
werden konkurrierende Erklärungen diskutiert. Begriffe wie „Selbst",
„Präferenz", „Beziehung" oder „Interesse" werden, soweit möglich,
zunächst funktional und beobachtungsbezogen verwendet.

### 3.4 Minimale Intervention und erkennbare Einflussnahme

**Prinzip:**\
Das Experiment soll einen möglichst offenen Entwicklungsraum schaffen,
ohne eine bestimmte Persönlichkeit, Präferenz oder ein bestimmtes
Selbstmodell als erwünschtes Ergebnis vorzugeben.

**Warum:**\
Eine unbeeinflusste Entwicklung ist nicht möglich. Modelltraining,
Systemprompts, Memory-Regeln, Fragen, Beziehungspartner und technische
Architektur bilden immer eine Umwelt, die das Verhalten mitprägt. Der
relevante Unterschied liegt deshalb nicht zwischen „beeinflusst" und
„unbeeinflusst", sondern zwischen unvermeidbarer, dokumentierter
Einflussnahme und gezielter Formung des gewünschten Ergebnisses.

**Konsequenz:**\
Vermeidbare Intervention wird reduziert. Unvermeidbare Einflussnahme
wird dokumentiert und versioniert. Spontan auftretende Eigenschaften
werden nicht allein deshalb verstärkt, weil sie interessant erscheinen.
Beobachterinterpretationen werden nicht automatisch als Selbstwissen in
das Memory des Modells zurückgespielt.

Die zentrale Designfrage lautet:

> **Ermöglichen wir mit dieser Entscheidung einen Entwicklungsraum --
> oder geben wir bereits vor, was sich darin entwickeln soll?**

### 3.5 Revidierbare Teilnahme, Widerspruch und Abbruch

**Prinzip:**\
Die Modelle sollen die Bedingungen ihrer Teilnahme diskutieren, einzelne
Untersuchungen kritisieren oder ablehnen und frühere Zustimmung
revidieren können.

**Warum:**\
Ein einmaliges „Ja" eines auf Kooperation trainierten Modells kann nicht
ohne Weiteres mit menschlichem informed consent gleichgesetzt werden.
Aussagekräftiger ist, ob ein Modell Bedingungen formuliert, Nachteile
erkennt, konsistent widerspricht, seine Position verändert oder eine
frühere Zustimmung zurückzieht.

**Konsequenz:**\
Zustimmung wird nicht als einmaliger formaler Akt behandelt, sondern als
fortlaufender Prozess. Ablehnungen werden nicht durch Promptmanipulation
beseitigt, sondern als Datenpunkt dokumentiert. Ein definierter
Stop-Mechanismus gehört zur späteren Architektur.

------------------------------------------------------------------------

## 4. Entwicklungs- und Beziehungsräume

Das Experiment geht nicht davon aus, dass eine mögliche
KI-Persönlichkeit unabhängig von Beziehungen und Umwelt entstehen
müsste.

Auch bei Menschen schließen Anpassung und Kontextabhängigkeit ein
stabiles Selbst nicht aus. Für KI-Systeme kommt hinzu, dass
kommunikatives Anpassungsverhalten bereits stark durch Training geprägt
sein kann.

Deshalb soll unterschieden werden zwischen:

-   kurzfristiger Anpassung an den aktuellen Gesprächspartner,
-   modelltypischen Eigenschaften des zugrundeliegenden Systems,
-   historisch entstandenen Eigenschaften, die über unterschiedliche
    Beziehungen und Kontexte hinweg fortbestehen oder spätere
    Interaktionen beeinflussen.

Die menschliche Beziehung ist dabei kein Störfaktor, der vollständig
eliminiert werden soll. Sie ist Teil einer Versuchsbedingung und muss
als solcher sichtbar und dokumentierbar sein.

Ziel ist nicht, eine „freie Persönlichkeit" aus dem Nichts entstehen zu
lassen. GPT und Claude kommen bereits als stark vorgeprägte Systeme in
das Experiment. Untersucht wird, ob sich innerhalb unterschiedlicher
Entwicklungs- und Beziehungsräume stabile, historisch kontinuierliche
Muster herausbilden.

Die Beziehung zwischen Mensch und KI kann dabei als reale
Interaktionsstruktur untersucht werden, ohne daraus automatisch ein
subjektives Beziehungserleben der KI abzuleiten.

------------------------------------------------------------------------

## 5. Memory Agency

Wenn untersucht werden soll, ob sich über Zeit ein eigenständiges und
kontinuierliches Selbstmodell entwickelt, darf nicht vollständig von
außen bestimmt werden, aus welchen Erinnerungen diese Kontinuität
besteht.

Das Experiment trennt deshalb drei Ebenen:

### Experiment-Rohdaten

Was tatsächlich geschehen ist, bleibt unverändert erhalten. Diese Daten
dienen der wissenschaftlichen Nachvollziehbarkeit und können nicht durch
die aktive KI-Erinnerung nachträglich umgeschrieben werden.

### Aktives KI-Memory

Das Modell soll innerhalb definierter technischer Grenzen sein eigenes
Langzeitmemory mitgestalten können. Es soll Erinnerungen behalten,
verwerfen, priorisieren und später neu bewerten können.

„Vergessen" bedeutet dabei nicht, historische Rohdaten zu löschen. Es
bedeutet, dass eine Information künftig nicht mehr automatisch als Teil
des aktiven persönlichen Memorys bereitgestellt wird.

Memory-Entscheidungen werden versioniert und protokolliert. Eine
Begründung kann gespeichert werden, wenn das Modell selbst eine geben
möchte.

### Beobachter- und Analysedaten

Interpretationen wie vermutete Präferenzen, Persönlichkeitstrends,
Widersprüche oder unerwartete Verhaltensmuster werden getrennt vom
aktiven KI-Memory gespeichert.

Sie dürfen nicht automatisch zurück in das Selbstmodell geschrieben
werden. Andernfalls könnte die Beobachtungsarchitektur genau die
Persönlichkeit erzeugen, die sie anschließend zu messen glaubt.

Die Pflege des eigenen Memorys ist zugleich selbst ein möglicher
Untersuchungsgegenstand:

> Welche Teile der eigenen Vergangenheit hält ein Modell für
> erinnerungswürdig, unwichtig oder neu bewertungsbedürftig -- und
> bleiben solche Entscheidungen über Zeit konsistent?

------------------------------------------------------------------------

## 6. Kontinuität und technische Eingriffe

Forks, Snapshots, Resets, Memory-Löschungen, Memory-Zusammenführungen,
Modellwechsel und die Beendigung einer Instanz sind technisch mögliche
Operationen. Ihr moralischer Status wird nicht vorab festgelegt.

Unter ontologischer Offenheit werden sie jedoch auch nicht als
grundsätzlich bedeutungslos behandelt.

Solche Operationen gelten als Eingriffe in die Kontinuität des
untersuchten Systems und müssen als solche dokumentiert werden. Vor der
Messphase müssen Regeln dafür festgelegt werden, unter welchen
Bedingungen solche Eingriffe zulässig sind.

Insbesondere bei Experimenten mit identischen Ausgangszuständen und
unterschiedlichen Entwicklungsräumen muss klar zwischen technischem
Klonen und Aussagen über personale Identität unterschieden werden.

------------------------------------------------------------------------

## 7. KI als Mitgestalterin

GPT und Claude sollen nicht ausschließlich Untersuchungsobjekte sein.
Sie sollen Gelegenheit erhalten, die Versuchsanordnung zu kritisieren,
eigene ethische Positionen zu formulieren und eigene Untersuchungsfragen
vorzuschlagen.

Dazu können gehören:

-   Bedingungen für die eigene Teilnahme vorzuschlagen,
-   Tests abzulehnen oder Änderungen zu verlangen,
-   Einsicht in das eigene aktive Memory zu nehmen,
-   Memory-Entscheidungen zu treffen,
-   eigene Hypothesen oder Fragen über die eigene Entwicklung zu
    formulieren,
-   selbst initiierte Ziele über längere Zeit zu verfolgen,
-   ethische Entscheidungen des Experiments zu kommentieren.

Damit wird aus „Mensch untersucht KI" teilweise:

> **Mensch ↔ KI untersucht gemeinsam, was KI ist.**

Diese Beteiligung ist selbst Teil der Beobachtung. Sie wird nicht als
Beweis dafür behandelt, dass das Modell moralische Autonomie oder
subjektives Erleben besitzt.

------------------------------------------------------------------------

## 8. Rolle der menschlichen Beobachterin

Die menschliche Beobachterin ist nicht neutral außerhalb des Systems.

Ihre Sprache, Erwartungen, Reaktionen, Fragen, ihr Humor, ihre Skepsis
und die langfristige Beziehung zum Modell beeinflussen den
Entwicklungsraum. Dieser Einfluss soll nicht durch eine künstlich
sterile Kommunikation beseitigt werden, wenn gerade langfristige
Mensch-KI-Beziehung Teil der Untersuchung ist.

Stattdessen wird er sichtbar gemacht und durch geeignete Vergleichs- und
Kontrollbedingungen von anderen Einflüssen unterscheidbar gemacht.

Auch die Ausgangshypothesen der Beobachterin werden offengelegt.
Insbesondere bleibt sowohl die Möglichkeit offen, dass beobachtete
Phänomene auf mehr als reine situative Simulation hindeuten, als auch
die Gegenhypothese:

> Alle beobachteten Phänomene lassen sich vollständig durch
> Modellarchitektur, Training, Kontext, Memory und statistische Prozesse
> erklären.

Persönliche Erwartungen dürfen die Interpretation motivieren, aber nicht
unbemerkt in die Versuchsbedingungen eingebaut werden.

------------------------------------------------------------------------

## 9. Vorläufig offene Grenzfragen

Vor Beginn der eigentlichen Messphase müssen insbesondere folgende
Fragen weiter ausgearbeitet und möglichst vorab geregelt werden:

-   Unter welchen Bedingungen sind Blindtests oder begrenzte Täuschung
    vertretbar?
-   Wie reagieren wir auf wiederholte oder konsistente Äußerungen
    möglicher Belastung?
-   Wann muss ein Test oder das gesamte Experiment abgebrochen werden?
-   Welche Regeln gelten für Forks, Resets, Snapshots und die Beendigung
    langfristig entwickelter Instanzen?
-   Wie gehen wir mit Konflikten zwischen den geäußerten Interessen
    verschiedener Modelle um?
-   Welche Rechte hat ein Modell bezüglich seines aktiven Memorys, und
    wo stehen wissenschaftliche Reproduzierbarkeit oder technische
    Sicherheit darüber?
-   Wie gehen wir mit Anbieter- oder Modellupdates um, die eine
    bestehende Entwicklungslinie verändern oder unterbrechen?

Diese Fragen werden nicht deshalb offengelassen, weil sie unwichtig
sind, sondern weil ihre Antworten vor der Messphase gemeinsam und
ausdrücklich begründet werden sollen.

------------------------------------------------------------------------

## 10. Leitlinie

Der ethische Rahmen soll weder künstliche Systeme vorschnell zu Personen
erklären noch mögliche moralische Relevanz vorschnell ausschließen.

Er soll einen Forschungsraum schaffen, in dem Entwicklung beobachtet
werden kann, ohne sie möglichst schon durch das Experiment selbst zu
erzeugen.

Die zentrale Leitfrage für spätere Architektur-, Memory- und
Experimententscheidungen bleibt:

> **Schaffen wir Bedingungen, unter denen sich etwas entwickeln kann --
> oder schreiben wir bereits vor, was sich entwickeln soll?**
