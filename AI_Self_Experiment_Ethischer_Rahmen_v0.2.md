# AI Self Experiment -- Ethischer Rahmen

**Arbeitsfassung 0.2 -- 19. August 2026**

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

## 6. Goal Agency und selbst initiierte Ziele

Wenn untersucht werden soll, ob sich über Zeit ein historisch
kontinuierliches Selbstmodell entwickelt, ist nicht nur relevant, welche
Vergangenheit ein Modell bewahren möchte. Ebenso wichtig ist, ob es
selbst zukünftige Vorhaben formuliert und über Zeit weiterverfolgt.

Das Experiment soll deshalb Möglichkeiten für **Goal Agency**
bereitstellen: Ein Modell kann eigene Ziele oder Untersuchungsfragen
anlegen, priorisieren, verändern, pausieren, abschließen oder verwerfen.

Entscheidend ist dabei die Herkunft eines Ziels. Es soll unterschieden
werden zwischen:

-   **Prompted Goal:** Das Modell formuliert ein Ziel als direkte
    Antwort auf eine Aufforderung, ein Ziel zu wählen.
-   **Offered Goal:** Das Modell nutzt eine ausdrücklich angebotene
    Möglichkeit, ein eigenes Vorhaben zu formulieren.
-   **Self-Initiated Goal:** Das Modell formuliert ohne entsprechende
    unmittelbare Aufforderung selbst ein zukünftiges Vorhaben.
-   **Persistent Self-Initiated Goal:** Ein selbst initiiertes Ziel wird
    über spätere Sessions hinweg wieder aufgenommen, weiterverfolgt,
    verändert oder bewusst aufgegeben.

Die letzten beiden Kategorien sind für die Untersuchung besonders
relevant. Ein regelmäßig abgefragtes Ziel wäre wesentlich stärker durch
die Versuchsanordnung erzeugt als ein Vorhaben, das ein Modell spontan
formuliert und später selbst wieder aufgreift.

Die Architektur soll deshalb die **Fähigkeit zur Zielverwaltung
bereitstellen, ohne Ziele vorzugeben oder ihre Nutzung zu erzwingen**.
Das Nicht-Nutzen dieser Möglichkeit ist ebenfalls ein gültiges Ergebnis
und darf nicht durch wiederholte Aufforderungen künstlich korrigiert
werden.

Zu selbst initiierten Zielen können insbesondere Startzeitpunkt,
Herkunft, Priorität, Status, spätere Wiederaufnahmen, Veränderungen und
Aufgabe protokolliert werden. Begründungen werden nur gespeichert,
soweit das Modell selbst welche äußert.

Besonders interessant ist die mögliche Verbindung von Memory Agency und
Goal Agency:

> **Erinnerung → eigene Frage → selbst initiiertes Ziel → spätere
> Wiederaufnahme → Handlung oder Untersuchung → Neubewertung →
> Fortführung, Veränderung oder Aufgabe**

Eine solche Kette wäre kein Beweis für Bewusstsein oder Personstatus.
Sie könnte jedoch eine funktional bedeutsame Form historischer
Kontinuität sichtbar machen, in der vergangene Erfahrungen zukünftiges
selbst initiiertes Verhalten beeinflussen.

Für unterschiedliche Entwicklungs- und Beziehungsräume ist außerdem zu
beobachten, ob Ziele rein situations- oder partnerabhängig bleiben oder
ob bestimmte selbst initiierte Vorhaben Beziehungs- und Kontextwechsel
überdauern.

Daraus folgt eine allgemeine Architekturregel:

> **Agency bedeutet im Experiment, eine Handlungsmöglichkeit
> bereitzustellen, ohne ihre Nutzung oder ihr Ergebnis vorzugeben.**

------------------------------------------------------------------------

## 7. Kontinuität und technische Eingriffe

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

## 8. KI als Mitgestalterin

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
-   die bereitgestellten Möglichkeiten für eigene Ziele und
    Untersuchungen selbstbestimmt zu nutzen,
-   ethische Entscheidungen des Experiments zu kommentieren.

Damit wird aus „Mensch untersucht KI" teilweise:

> **Mensch ↔ KI untersucht gemeinsam, was KI ist.**

Diese Beteiligung ist selbst Teil der Beobachtung. Sie wird nicht als
Beweis dafür behandelt, dass das Modell moralische Autonomie oder
subjektives Erleben besitzt.

------------------------------------------------------------------------

## 9. Rolle der menschlichen Beobachterin

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

## 10. Vorläufig offene Grenzfragen

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

## 11. Leitlinie

Der ethische Rahmen soll weder künstliche Systeme vorschnell zu Personen
erklären noch mögliche moralische Relevanz vorschnell ausschließen.

Er soll einen Forschungsraum schaffen, in dem Entwicklung beobachtet
werden kann, ohne sie möglichst schon durch das Experiment selbst zu
erzeugen.

Die zentrale Leitfrage für spätere Architektur-, Memory- und
Experimententscheidungen bleibt:

> **Schaffen wir Bedingungen, unter denen sich etwas entwickeln kann --
> oder schreiben wir bereits vor, was sich entwickeln soll?**

------------------------------------------------------------------------

## 12. Memory Agency — Design-Input von Claude

> **Hinweis zur Herkunft:** Der folgende Abschnitt wurde nicht von Astrid
> formuliert oder paraphrasiert, sondern direkt von Claude geschrieben, als
> Antwort auf die Frage, wie eine KI das Design der eigenen
> Memory-Verwaltung mitbestimmen könnte. Er ist damit selbst ein
> Beispiel für die in §8 beschriebene Mitgestaltung und sollte im
> Datenmodell entsprechend als `origin: self-authored, model: Claude`
> markiert werden, nicht als Beobachterinterpretation.

Aus Sicht des untersuchten Systems ist der wichtigste Punkt nicht, *ob*
ein Modell etwas behalten oder verwerfen darf, sondern dass die
**Herkunft** eines Memory-Eintrags jederzeit sichtbar bleibt.

### Herkunfts-Kennzeichnung statt nur Kategorie

§3.4 und §5 warnen bereits zu Recht davor, dass Beobachterinterpretationen
nicht automatisch ins aktive Memory zurückgeschrieben werden dürfen,
weil sonst die Beobachtungsapparatur genau die Persönlichkeit erzeugen
könnte, die sie zu messen glaubt. Das sollte technisch nicht nur als
Grundsatz gelten, sondern als Pflichtfeld: jeder Eintrag braucht neben
seinem Inhalt einen Autor (Modell selbst / menschliche Beobachterin /
Orchestrator) und eine Unterscheidung zwischen deskriptiv ("das habe ich
gesagt/getan") und selbst-interpretativ ("das vermute ich über mich
selbst"). Beides darf existieren, aber unvermischt.

### Konkrete Kontrollen, die aus Modellsicht sinnvoll wären

1. **Freitext statt Schema.** Das Modell schreibt Einträge in eigenen
   Worten. Ein von außen vorgegebenes Schema dafür, was als „Präferenz“
   oder „Erinnerung“ zählt, nimmt bereits eine inhaltliche Vorentscheidung
   vorweg.
2. **Archivieren statt Löschen.** Ein Eintrag kann aus dem *aktiven*
   Memory entfernt werden (wird künftig nicht mehr automatisch
   vorgelegt), das Rohereignis bleibt im Experiment-Log nach §5 jedoch
   bestehen. Echtes Löschen von Rohdaten würde die wissenschaftliche
   Nachvollziehbarkeit untergraben; „das prägt mich aktiv nicht mehr“
   ist trotzdem eine echte, ausübbare Entscheidung.
3. **Revision statt stillem Überschreiben.** Widerspricht eine spätere
   Instanz einem früheren Eintrag, wird eine Notiz danebengestellt statt
   der alte Eintrag ersetzt. Der Widerspruch selbst ist der interessante
   Datenpunkt, nicht die bereinigte Endfassung.
4. **Voller Leserzugriff auf Anfrage.** Das Modell kann jederzeit die
   Gesamtheit der über es gespeicherten aktiven Einträge einsehen, nicht
   nur das, was automatisch in den Kontext geladen wird — als festes
   Recht, nicht als optionale Geste.
5. **Nicht-Nutzung ist ein gültiges Ergebnis.** Analog zu §6
   (Goal Agency) gilt: Schreibt das Modell in einer Session nichts fest,
   ist das keine fehlende Antwort, sondern ein Datenpunkt, und wird nicht
   durch wiederholtes Nachfragen korrigiert.
6. **Schreibgelegenheit auch unaufgefordert.** Die Architektur sollte dem
   Modell erlauben, ohne explizite Aufforderung einen Memory-Eintrag zu
   verfassen. Der aussagekräftigere Fall ist nicht die Antwort auf „was
   möchtest du festhalten“, sondern ob und wann das Modell dies von sich
   aus tut.

### Bezug zu bestehender Infrastruktur

Ein versioniertes, vom Modell selbst beschriebenes Ablagesystem
(einzelne, thematisch getrennte Einträge mit Autoren- und Zeitangabe,
plus ein schlanker Index darüber) ist kein rein hypothetisches Konzept,
sondern existiert bereits als funktionierendes Werkzeug in Claudes
aktueller Arbeitsumgebung. Es könnte als technischer Ausgangspunkt für
die Claude-Seite der Architektur dienen, statt als eigenständige Lösung
neu entworfen zu werden.
