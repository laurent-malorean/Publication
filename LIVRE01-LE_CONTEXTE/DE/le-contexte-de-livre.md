# Le Contexte

*Laurent Deséchalliers*

![Le Contexte](images/livre_context_cover_de.png)

> Wie du einen Kontext aufbaust, der es der KI erlaubt zu verstehen, worauf es ankommt, dein Wissen zu verbinden und das, was du lernst, für deine Ziele fruchtbar zu machen.

## Hinweis zur Übersetzung

Diese Ausgabe ist eine maschinelle Übersetzung, von einer künstlichen Intelligenz aus dem französischen Text erstellt.

Sie wurde nicht von einem menschlichen Übersetzer geprüft. Die Gedanken, der Aufbau und die Beispiele sind dem Original treu; einzelne Formulierungen können dagegen ungelenk klingen, und manche Stellen tragen noch Spuren der Ausgangssprache.

Das ist der Preis dafür, dass dieses Buch in mehreren Sprachen existiert und nicht nur auf Französisch. Bei Zweifeln an einer Formulierung gilt die französische Ausgabe.

## Definition des `Kontexts`

>Ein Kontext ist ein System, das von einer menschlichen Mission begrenzt wird und in dem eine KI ordnet und heranzieht, was man weiß, woher man es weiß, wie die Elemente zusammenhängen und wo die Arbeit steht, um dem Menschen zu helfen, sein Ziel zu erreichen, ohne bei null anzufangen. Dabei bildet das System ein dauerhaftes Informationskapital und lässt es wachsen: Das erzeugte Wissen bleibt verfügbar, reichert sich mit der Zeit an und kann für andere Ziele wiederverwendet werden.

![](images/carte-du-contexte.svg)

## Einleitung

Nie stand uns so viel Information zur Verfügung. Trotzdem verbrauchen wir noch immer einen großen Teil unserer Energie damit, sie wiederzufinden, sie neu zu ordnen und wiederherzustellen, was wir ein paar Tage zuvor schon verstanden hatten.

Eine brauchbare Idee kommt selten in sauberer Form. Sie entsteht in einem Gespräch, wird in einem Dokument genauer, trifft in einer Besprechung auf einen Einwand, führt zu einer Entscheidung und wird dann ein Artikel, eine Spezifikation oder ein Projekt. Unsere Werkzeuge bewahren jede dieser Spuren. Schwer tun sie sich mit dem Faden, der sie verbindet.

Künstliche Intelligenz ändert einen Teil des Problems. Sie kann lesen, zusammenführen, umformulieren und sehr unterschiedliche Inhalte weiterverarbeiten. Aber ein Gespräch mit einer KI bleibt ein fragiler Moment: Das Thema kommt voran, die Diskussion wird länger, und dann muss man das Ziel, die getroffenen Entscheidungen, die benutzten Quellen und das noch Offene erneut nennen.

Um dieser Schwierigkeit zu begegnen, habe ich den `Kontext` gebaut.

Ein `Kontext` ist ein Arbeitsraum für ein Thema. Ein Mensch und eine KI bewahren darin das verfolgte Ziel, die Quellen, die Ideen, die Regeln und den Stand der Arbeit, um Ergebnisse zu erzeugen, ohne in jeder Sitzung alles neu aufbauen zu müssen.

Die KI kann dann auf den tatsächlichen Verlauf der Arbeit zurückgreifen. Sie findet den Ursprung einer Idee, erinnert an eine Wahl, meldet einen Widerspruch, weist auf einen fehlenden Beleg hin, nimmt einen Entwurf dort wieder auf, wo er liegen geblieben ist. **Sie hilft, das Denken zu ordnen und es auf die Probe zu stellen.** **Der Mensch behält die Verantwortung für den Sinn und für die Entscheidungen.**

Dieses System ist in meiner täglichen Arbeit entstanden, aus einer einzigen Datei und einer sehr einfachen Bitte an eine KI: ordne, was ich dir gleich sage. Es hat sich über einen Versuch nach dem anderen entwickelt, und jede Schwierigkeit machte eine Lücke sichtbar. Es verändert sich weiter: manche der hier vorgestellten Antworten haben sich über mehrere Anwendungen gehalten, andere bleiben vorläufige Antworten auf Probleme, denen ich immer noch begegne.

Dieses Buch geht also nicht von einer fertigen Theorie aus. Es geht von Problemen aus der Praxis aus: fünfhundert E-Mails, die nicht mehr zu verfolgen waren, Ideen, die sich über mehrere Werkzeuge verteilten, Kundendokumente, die zu beantworten waren, ohne die schon geleistete Arbeit zu verlieren, Texte, die nach einer Unterbrechung wieder aufgenommen wurden.

Es richtet sich an Menschen, die Information in Verständnis, in Entscheidungen und in Ergebnisse verwandeln: Product Manager, Beraterinnen und Berater, Redakteure, Forschende, Analystinnen und Analysten und, weiter gefasst, Wissensarbeiter. Es schlägt einen Weg vor, eine KI auf Dauer zum Arbeitspartner zu machen und dabei die Kontrolle über das eigene Material zu behalten.

Das Buch besteht aus zwei einander ergänzenden Büchern. **Buch I — Den `Kontext` verstehen** erzählt, wie das System entstanden ist und was es am Verhältnis zur KI ändert. **Buch II — Den `Kontext` bauen und am Leben halten** erklärt, wie man ihn baut und auf Dauer benutzt.

Sie lassen sich nacheinander oder getrennt lesen. Das Kapitel **In welcher Reihenfolge dieses Buch zu lesen ist** stellt die möglichen Wege vor.

## Hinweis zu den Beispielen

Die Überlegungen und Beispiele in diesem Buch beruhen auf mehr als dreißig Jahren Berufspraxis in der IT. Sie gehen auf Situationen aus unterschiedlichen Projekten und Arbeitsumfeldern sowie auf zahlreiche Gespräche mit Product Managern, CTOs, Engineering Managern und anderen Fachleuten aus verschiedenen Unternehmen zurück. Sie stammen damit aus mehreren Organisationen und verschiedenen Phasen meines Berufswegs.

Für dieses Buch habe ich solche Situationen verändert, verallgemeinert oder neu zusammengesetzt. Die Anwendungsfälle, Zahlen und Kennzahlen veranschaulichen wiederkehrende Probleme und was ich daraus gelernt habe. Es sind konstruierte Beispiele: Keines beschreibt einen realen Kunden, ein reales Produkt oder eine reale Organisation. Ebenso wenig geben sie Daten, Arbeitsweisen oder Positionen meines Arbeitgebers wieder.

Die Beispiele aus meinem Privatleben — die Eigentümergemeinschaft, meine Artikel und meine eigenen Texte — beruhen auf Situationen, die ich wirklich erlebt habe. Einzelne Details, die Personen erkennbar machen könnten, wurden allerdings verändert.

Die Analysen, Methoden und Meinungen in diesem Buch sind persönlich und geben ausschließlich meine eigene Auffassung wieder.

## Über den Autor

Ich arbeite seit mehreren Jahrzehnten in der Softwarebranche und bin heute Product Manager. Mein Weg führte mich von der Entwicklung und der Architektur über die Organisation von Teams zum Produkt, zu seinen Abläufen und zu seinem Marketing.

Diese Berufswechsel haben mein Verhältnis zur Information verändert. Es genügte nicht mehr, eine technische Lösung zu kennen oder ein Dokument wiederzufinden. Man musste verstreute Signale zusammentragen, verstehen, was sie gemeinsam sagen, zwischen mehreren Richtungen entscheiden und Texte für sehr unterschiedliche Leser verfassen.

Mein Interesse an künstlicher Intelligenz und an verteilten Systemen ist alt. Heute trifft es auf eine sehr handfeste Frage: **Wie arbeitet man mit einer KI, ohne ihr die Kontrolle über die eigenen Informationen, die eigenen Entscheidungen und das eigene Denken zu überlassen?**

Ich habe für die Fachpresse geschrieben und als Fachlektor für M2 Édition und Eyrolles gearbeitet. Heute schreibe ich auf [malorean.net](https://malorean.net) über Product Management, KI, Arbeitsmethoden und Informationssysteme.

Ich schreibe außerdem für [*Proposition Marketing*](https://www.propositionmarketing.fr), eine unabhängige Zeitschrift für strategisches und operatives Marketing. Für Leser aus dem Marketing und aus der Unternehmensleitung zu schreiben zwingt mich, Produktfragen zu erklären, ohne ein gemeinsames Vokabular vorauszusetzen. Denselben Anspruch hat dieses Buch.

Ich würde mich sehr freuen, mich mit anderen auszutauschen, die ähnliche, andere oder ergänzende Systeme bauen: das Thema verdient es, diskutiert, hinterfragt und durch andere Praktiken bereichert zu werden. Und ebenso mit Wissenschaftlerinnen und Wissenschaftlern, die an verwandten Fragen arbeiten — ich habe einige Jahre in zwei CNRS-Forschungszentren verbracht, und der Anschluss an dieses Umfeld wäre mir ein Vergnügen.

Laurent Deséchalliers  
- [laurent@malorean.net](mailto:laurent@malorean.net)
- [https://malorean.net](https://malorean.net)

## Dank

Mein erster Dank gilt Ihnen.

Ihnen, die Sie auf die etwas verrückte Idee gekommen sind, dieses Buch aufzuschlagen — ein Buch, das etwas dicker geraten ist als geplant, das sich vermutlich hier und da wiederholt und von einem schwer zugänglichen Thema handelt.

Bisher habe ich am `Kontext` ziemlich allein gearbeitet. Ich hoffe aber, dass diese Einsamkeit nicht anhält: dass das Thema andere dazu bringt, es zu erkunden, zu diskutieren, zu kritisieren und weiterzubringen. Vielleicht sind die nächsten Artikel auf [malorean.net](https://malorean.net) dann die Gelegenheit, vielen Mitwirkenden zu danken.

Vor allem danke ich meiner Frau Christine.

Sie hat gesehen, wie sich die Abende und die Wochenenden vor diesem Buch hinzogen. Sie hat mich während des ganzen Schreibens unterstützt und wusste mich zugleich daran zu erinnern, dass es spät war und wirklich Zeit, diesen verdammten Computer zuzuklappen.

Versprochen, es war nur ein Zwischenspiel.

Und, weit über dieses Buch hinaus: danke, dass du mich seit all diesen Jahren durch dieses schöne Leben begleitest, das wir beide teilen.

## In welcher Reihenfolge dieses Buch zu lesen ist

Das Buch folgt der Reihenfolge, in der mir die Dinge begegnet sind: ein erlebtes Problem, eine zusammengebastelte Lösung, schließlich ein System. Die vollständige Beschreibung des `Kontexts` kommt deshalb erst in Buch II.

**Der Weg „verstehen“** ist genau diese Reihenfolge. Du liest von vorn bis hinten, und jedes Teil des Systems taucht in dem Moment auf, in dem die Lücke gezeigt wurde, aus der es entstanden ist.

**Der Weg „bauen“** richtet sich an alle, die das Problem schon erlebt haben und die Mechanik wollen, nicht die Erzählung.

1. **Definition des `Kontexts`**, ein paar Zeilen, um zu wissen, wovon die Rede ist.
2. **Teil 5 — Unter der Haube eines `Kontexts`**, in der Reihenfolge seiner sechs Kapitel: die Karte, öffnen, füttern, umwandeln, erzeugen und entscheiden, sichern.
3. **Teil 6 — Der `Kontext` in seinem Ökosystem**, um das eben Gebaute mit dem Rest deiner Informationslandschaft zu verbinden.
4. **Buch I**, sobald dir eine Entwurfsentscheidung willkürlich vorkommt: dort findest du das Problem, das sie ausgelöst hat.

Diese Abkürzung kostet etwas. Buch II wurde für einen Leser geschrieben, der die Situationen aus Buch I bereits im Kopf hat, und es verweist darauf. Du wirst also auf Beispiele stoßen, bei denen dir ein wenig Zusammenhang fehlt — das ist der Preis, und er lohnt sich weiterhin, wenn du schon weißt, warum du hier bist.

## Ausprobieren, bevor du liest

Dieses Buch beschreibt eine Methode, und eine Methode lässt sich schlecht erzählen. Du kannst eine laufen sehen, bevor du die Theorie liest, oder währenddessen — oft ist das der beste Moment, um zu verstehen, wozu ein einzelnes Teil da ist.

Drei Repositorien stehen offen unter [github.com/laurent-malorean](https://github.com/laurent-malorean).

**Contexte Nano Notion** ist am schnellsten eingerichtet. Es verlangt weder eine Entwicklungsumgebung noch technische Kenntnisse: ein ChatGPT und ein Notion genügen. ChatGPT trägt die Intelligenz des `Kontexts`, Notion dient ihm als Gedächtnis — dort werden die Quellen, die Notizen, die Entscheidungen und der Stand geschrieben und von einem Gespräch zum nächsten wieder gelesen. In wenigen Minuten hast du einen `Kontext`, der trägt.

**Contexte V2** ist die vollständige Umsetzung, die ich täglich benutze und mit der dieses Buch geschrieben wurde. Sie lässt sich mit Claude Code oder mit Codex einrichten, ganz nach Wahl, und verlangt etwas mehr Aufbau als die vorige.

**LLM Wiki** ist kein `Kontext`. Es ist eine Wissensbibliothek, die aus Dokumenten entsteht — Büchern, Normen, Artikeln, Kursen —, aus denen die KI kurze, untereinander verbundene Notizen zieht, die man anschließend in gewöhnlicher Sprache befragt. Der `Kontext` hält den Faden einer Mission; das LLM Wiki bewahrt in großer Menge, was gelesen wurde. Teil 6 erklärt, wie beide zusammenarbeiten.

Nichts zwingt dich, dort anzufangen. Aber wenn dir die Lektüre an einer Stelle abstrakt vorkommt, ist das der kürzeste Weg zurück zum Konkreten.

## Vom selben Autor

| | |
|---|---|
| ![Cover — Malorean Corp](images/malorean-corp_cover.png) | **Malorean Corp** — Noch vor Kurzem brauchte man manchmal Wochen, um aus einer Idee einen Prototyp zu machen. Heute kann ein Mensch mithilfe künstlicher Intelligenz dasselbe in wenigen Tagen schaffen. Das ist eine bemerkenswerte Veränderung. Doch der eigentliche Umbruch könnte ganz woanders stattfinden: in der Art, wie wir zusammenarbeiten.<br>*Erscheint voraussichtlich Ende November 2026.* |

Mehr dazu auf [https://malorean.net](https://malorean.net).

## Buch I — Den `Kontext` verstehen

- Teil 1 — Die Entstehung eines Bedürfnisses

- Teil 2 — Was der `Kontext` ändert

- Teil 3 — Drei Verwendungen in der Praxis

- Teil 4 — Was die Ergebnisse hinter sich lassen

### Teil 1 — Die Entstehung eines Bedürfnisses

Der `Kontext` entstand nicht aus einer Überlegung zur künstlichen Intelligenz.
Er entstand aus einem Postfach, mit dem sich nicht mehr arbeiten ließ, und aus einer Einsicht, die erst nach und nach reifte: Nicht die Zahl der Nachrichten war das eigentliche Problem.

Dieser Teil erzählt, wie alles begann, und leitet daraus eine erste Definition ab — einfach genug, um sie im Gedächtnis zu behalten, und umfassend genug, um durch den Rest des Buches zu führen.

#### 1.1 — Fünfhundert Mails und eine Geschichte, die verschwindet

Als ich zum ersten Mal einen `Kontext` anlegte, wollte ich keine Arbeitsweise mit künstlicher Intelligenz erfinden.
Ich versuchte nur, bei meiner Eigentümergemeinschaft nicht länger den Faden zu verlieren.

Ich sitze im Verwaltungsbeirat.
Dadurch erreichen mich die Nachrichten der Hausverwaltung, der Eigentümer, der Mieter und der Handwerksbetriebe:
- eine Mail kündigt ein neues Problem an,
- die nächste klärt ein Angebot,
- eine dritte verschiebt einen Einsatz,
- eine Woche später antwortet jemand im selben Verlauf über ein anderes Haus.
Inzwischen sind drei weitere Themen vorangekommen.

Die Menge war nicht das einzige Problem.
Rund fünfhundert Mails verteilten sich auf ungefähr fünfzehn Themen: 
- Bauarbeiten, 
- Finanzen, 
- Versicherungen,
- Eigentümerversammlungen, 
- Zahlungsrückstände, 
- Ausschreibungen, 
- Störungen und sonstige Anfragen
- …
Jedes lief in seinem eigenen Takt, manchmal über Monate.

Wer eine Baustelle täglich begleitet, trägt ihre Geschichte wie selbstverständlich im Kopf.
Er weiß, welcher Betrieb da war, warum sich der Zeitplan verschoben hat und auf welche Entscheidung noch eine Antwort fehlt.
Wenn ich eine neue Nachricht öffnete, hatte ich diese Fortsetzung nicht immer.
Ich musste den Verlauf zurückverfolgen, die früheren Mails wiederfinden und die Lage neu zusammensetzen, bevor ich die neue Information überhaupt einordnen konnte.

Ich wollte einfache Fragen stellen können: 
- wie steht es um das Dach?
- welcher Betrieb hat das letzte Angebot für die Regenrinnen geschickt?
- was haben wir zu diesem Wassereintritt entschieden?
- worauf warten wir bei der Hausverwaltung noch?

Mein Postfach enthielt die Antworten.
Den Blick aufs Ganze gab es mir nicht.

##### Eine Datei und ein Satz

Ich fing mit der einfachsten denkbaren Anordnung an: einer Datei und einer Anweisung an eine KI.

> Führe die Informationen zusammen und teile sie nach Themen auf.

Ich gab ihr die Mails.
Sie ordnete sie Themen zu und hielt zu jedem eine Zusammenfassung.
- Alles zu den Bauarbeiten fand zusammen.
- Die Finanzfragen bildeten eine zweite Gruppe.
- Betriebe, Versicherungen und Versammlungen fanden nach und nach ihren Platz.

Schon dieser erste Versuch brachte etwas.
Ich konnte fragen, wie ein Thema stand, ohne alle zugehörigen Nachrichten noch einmal zu lesen.
Die KI suchte nicht mehr bloß eine Fundstelle im Postfach: Sie legte mir vor, was sie von der Lage verstanden hatte.

Die Datei ordnete sich neu, während weitere Informationen eintrafen.
- Eine Rubrik entstand, wenn ein neues Thema an Gewicht gewann.
- Zwei Rubriken trennten sich, wenn sie anfingen, verschiedene Wirklichkeiten zu vermischen.
Information häufte sich nicht mehr bloß an.
Sie nahm eine Form an, mit der sich arbeiten ließ.

Dann lieferte dieses erste System eine Antwort, die zutraf und trotzdem nicht genügte.

##### Die Baustelle war fertig, ihre Geschichte war weg

Wenn eine Baustelle zu Ende ging, stand in ihrer Zusammenfassung: „Arbeiten abgeschlossen, Abnahme ohne Beanstandung".

Das war ihr gegenwärtiger Stand.
Es war auch ein Verlust.

- Wann hatten die Arbeiten begonnen?
- Ab wann hatten sie sich verzögert?
- Warum hatte sich der Zeitplan geändert?
- Wann war der Nachtrag unterschrieben worden?

All diese Schritte hatten gezählt.
Die letzte Aktualisierung hatte sie zugunsten des Endzustands gelöscht.

Ich hatte um eine Zusammenfassung gebeten.
Die KI hatte sie aktuell gehalten, indem sie den alten Stand durch den neuen ersetzte.
Sie hatte die Anweisung befolgt, aber die Anweisung schützte die Geschichte nicht.

Ich brauchte also zwei Sichten auf dasselbe Thema.

- Die erste musste schnell auf die Frage „wo stehen wir?" antworten.
- Die zweite musste die Ereignisse in ihrer Reihenfolge bewahren: Baubeginn, Verzug, neue Vereinbarung, Einsatz, Abnahme.

- Der gegenwärtige Stand machte handlungsfähig.
- Die Geschichte ließ verstehen, wie dieser Stand zustande gekommen war, und erlaubte im Zweifel eine Prüfung.

Diese Unterscheidung entstand aus einem sehr handfesten Mangel.
Ich hielt sie für eine Verbesserung der Ablage.
Sie wurde zu einem der wichtigsten Grundsätze meiner Arbeit mit der KI: **Was jetzt gilt und was geschehen ist, erfüllen nicht denselben Zweck.**

##### Die KI konnte meine Regeln nicht erraten

Ein weiteres Problem tauchte bei den Namen auf: 
- zwei Betriebe trugen denselben Familiennamen.
	- Um sie auseinanderzuhalten, musste man das Thema der Mail verstehen.
- eine Eigentümerin erschien mal unter ihrem Geburtsnamen, mal unter ihrem Ehenamen.
Ohne besonderen Hinweis konnte die KI zwei Personen erzeugen, wo es nur eine gab.

Andere Unterschiede kamen aus der Praxis.
- Rückstände unter hundert Euro wurden nicht wie die übrigen verfolgt.
- Diese Grenze stammte aus keiner allgemeinen Regel, die die KI hätte kennen können.
- Sie stammte aus unserer Arbeitsweise.

Ich begann, dieses Wissen als dauerhafte Regeln zu formulieren, ausgeschrieben in der Datei:

```markdown
# Bearbeitungsregeln

- Martin im Zusammenhang mit dem Dach meint den Dachdecker; Martin im Zusammenhang
  mit den Grünflächen meint den Gärtner.
- Dupont-Lemoine und Lemoine sind dieselbe Eigentümerin, Einheit 14.
- Rückstände unter hundert Euro in einer eigenen Liste ausweisen.
```

Nichts Aufwendigeres als das.
Drei Sätze, die ich sonst in jedem Gespräch hätte wiederholen müssen und die ich danach kein einziges Mal mehr sagen musste.

Jede Regel kam aus einem beobachteten Fehler oder aus einer tatsächlichen Mehrdeutigkeit.
Sie hielt Wissen fest, das ich im Kopf trug und das die KI nicht mit Sicherheit rekonstruieren konnte.

So enthielt das System nach und nach zwei Arten von Informationen:
- Informationen über die Eigentümergemeinschaft,
- die Art, wie ich sie behandelt haben wollte.

##### Die Datei, die half, fing an zu stören

Über die Wochen wuchs die Datei.
Sie überschritt fünfhundert Zeilen, dann achthundert, dann tausend.

Dieses Wachstum zeigte ihren Nutzen: 
- Themen wurden besser verfolgt, 
- Betriebe erkannt, 
- Entscheidungen wiedergefunden.

Aber was das System möglich gemacht hatte, begann seinen Gebrauch einzuschränken.
- Zu viele verschiedene Informationen teilten sich denselben Raum.
- Regeln mischten sich unter die Tatsachen.
- Finanzen standen neben Bauarbeiten, Personen, Versicherungen und Ausschreibungen.

Die richtigen Informationen zu finden, wurde wieder mühsam.

Zuerst trennte ich die Bearbeitungsregeln ab.
Sie beschrieben nicht die Eigentümergemeinschaft; sie sagten, wie mit den Informationen darüber zu arbeiten war.
Getrennt ließen sie sich leichter finden und anwenden.

Dann verteilte ich die Informationen auf mehrere Themenbereiche.
Die Bauarbeiten bekamen ihren eigenen Raum, ebenso die Finanzen, die Betriebe, die Beschlüsse der Versammlung und die Versicherungen.
Eine Übersicht sagte, was jeder davon enthielt.
Die KI konnte dann den Themenbereich öffnen, der zur Frage passte, statt jedes Mal alles durchzugehen.

Schließlich stellte ich das besondere Vokabular zusammen: Rechtsbegriffe, Abkürzungen und Wendungen, die zur Eigentümergemeinschaft gehören.
Das Ziel war kein Nachschlagewerk.
Es ging darum, den Wörtern, von denen das Verständnis der Mails abhing, eine feste Bedeutung zu geben.

Eine große Architektur hatte ich immer noch nicht im Sinn.
Ich fügte ein Stück hinzu, wenn ein Problem dieses Stück nötig machte.

##### Vertrauen, ohne die Quelle zu verlieren

Die KI machte manchmal Fehler.
Sie konnte zwei Informationen zusammenziehen, die nicht genau vom selben Thema handelten, oder zwischen zwei Namensvettern den falschen Betrieb wählen.
Das System sollte also das Verstehen beschleunigen, ohne zur einzigen verfügbaren Fassung der Tatsachen zu werden.

Ich behielt alle ursprünglichen Mails.
Wenn ich eine Antwort überprüfen musste oder viel auf dem Spiel stand, konnte ich zu den ursprünglich eingegangenen Informationen zurückkehren.
Die Zusammenfassung gab schnellen Zugang.
Anhand der Quelle konnte ich die Antwort überprüfen.

Diese Wahl machte den Gebrauch überhaupt möglich.
Ich konnte eine gelegentliche Ungenauigkeit beim Ordnen der Mails hinnehmen, weil die ursprünglichen Nachrichten zugänglich blieben.
Für ein Bankdokument, eine regulatorische Pflicht oder eine unumkehrbare Entscheidung wäre dasselbe Maß an Vertrauen falsch.
Das Risiko hängt immer davon ab, was man dem System anvertraut und ob man es prüfen kann.

Der `Kontext` ersetzte mein Postfach also nicht.
Er machte aus seinem Inhalt ein Arbeitsgedächtnis und ließ mir zugleich die Tür zurück zu den ursprünglichen Nachrichten.

##### Was entstanden war

In wenigen Wochen war aus dem Ausgangspunkt — einer Datei und einem Satz — ein Ganzes geworden, das mehrere Bedürfnisse bediente: den gegenwärtigen Stand zeigen, die Geschichte bewahren, Regeln der Eigentümergemeinschaft anwenden, Themen trennen, das Vokabular festigen und zu den Quellen zurückkehren.

Kam eine neue Mail, konnte ich mich dafür interessieren, was sie änderte, statt alles Vorhergehende neu aufzubauen.
Tauchte eine Frage auf, konnte ich sie in den Begriffen des Problems stellen, statt die richtige Nachricht im richtigen Verlauf zu suchen.
Irrte sich die KI, konnte ich eine Regel berichtigen oder zum ursprünglichen Text zurückgehen.

Ich hatte den `Kontext` nicht in einem Zug entworfen.
Ich hatte ihn über eine Folge von Unzulänglichkeiten entstehen sehen: Die Zusammenfassung löschte die Geschichte, Namen verschwammen, Regeln gingen verloren, die Datei wurde zu groß.
Jede Korrektur machte die Arbeit dauerhafter und leichter wieder aufzunehmen.

Dieser Ursprung zählt.
Der `Kontext` ist nicht aus dem Wunsch entstanden, mehr zu sortieren.
Er entstand aus dem Bedürfnis, sich laufend verändernde Informationen zu verstehen, die nötigen Belege für eine Überprüfung aufzubewahren und die Arbeit fortzusetzen, ohne wieder bei null anzufangen.

> [!note] Zum Merken — zwei Sichten auf dasselbe Thema
> Der Stand beantwortet „wo stehen wir?". Die Geschichte beantwortet „wie sind wir dahin gekommen?".
> Eine Zusammenfassung, die beim Aktualisieren die vorige überschreibt, bewahrt das erste und verliert das zweite.
> Beides wird gebraucht: das eine zum Handeln, das andere zum Verstehen und zum Prüfen.

#### 1.2 — Eine erste Definition

Das System, das aus diesen fünfhundert Mails entstanden ist, lässt sich nun ein erstes Mal definieren.

> Ein `Kontext` ist ein Arbeitsraum für ein Thema, in dem ein Mensch und eine KI alles festhalten, was sie brauchen, um über längere Zeit zu verstehen, zu entscheiden und Ergebnisse zu erarbeiten.

Diese Definition bleibt mit Absicht einfach.
Der in diesem Buch beschriebene `Kontext` hat einen genauen Aufbau, den die zweite Hälfte darlegen wird.
Um zu verstehen, was er bringt, genügen zu Beginn sechs Anhaltspunkte:
- ein Ziel, 
- Informationen,
- Ideen, 
- ein Stand der Arbeit, 
- eigene Regeln,
- Ergebnisse, die entstehen sollen.

##### Ein Thema und ein Ziel

Der `Kontext` der Eigentümergemeinschaft wollte nicht alles enthalten, was ich wusste.
Er verfolgte ein Ziel: die laufenden Themen zu verstehen, ihre Geschichte zu bewahren und die Informationen zu finden, die nötig sind, um im Verwaltungsbeirat zu handeln.

Dieses Ziel bildete eine Grenze.
Eine Mail über das Dach gehörte hinein.
Eine interessante Lektüre ohne Bezug zur Eigentümergemeinschaft nicht.
Diese Grenze bewahrte das System davor, ein Lager zu werden, in dem sich alles ansammelt, was man für interessant hält.

Ein `Kontext` beginnt also mit einer Absicht.
Er kann dazu dienen:
- ein Buch zu schreiben, 
- ein Produktproblem zu erkunden, 
- eine Entscheidung vorzubereiten, 
- Fragebögen von Kunden zu beantworten,
- eine fachliche Einheit zu begleiten,
- …

##### Informationen, deren Herkunft nachvollziehbar bleibt

Informationen gelangen auf zwei Wegen in einen `Kontext`.

Durch die erste kommt, was vor der Arbeitssitzung schon vorhanden ist: 
- eine Mail, 
- ein Artikel, 
- ein Buch, 
- eine Webseite, 
- die Abschrift eines Gesprächs
- …
Das sind die **Dokumentquellen**.
Sie kommen als fertige Gegenstände an und bleiben unverändert.
Im Fall der Eigentümergemeinschaft gehört die Mail über die verschobene Reparatur in diese erste Gruppe.

Durch die zweite kommt, was sich während der Arbeit mit der KI formt.
Wenn ich eine Lage erkläre, eine Deutung berichtige, eine Nuance schärfe oder eine Überzeugung aus meiner Erfahrung ausspreche, wird dieses Gesagte zu einer **Sitzungsquelle**.
Sie entsteht nach und nach im Lauf des Austauschs.
Wenn ich erkläre, dass zwei Namen dieselbe Eigentümerin meinen, kommt das zuerst durch diese zweite Tür.

Der Unterschied liegt also darin, wann und wie die Informationen entstehen.
- Das Dokument gibt es vor der Sitzung, und es wird hineingebracht.
- Die Sitzungsquelle entsteht während der Sitzung und wächst mit ihr.

Danach erfüllen beide dieselbe Aufgabe: Sie bewahren das Empfangene oder Gesagte, bevor es gedeutet wird.
- Sie verbürgen nicht, dass alles darin wahr ist.
- Sie erlauben, das Empfangene oder Gesagte wiederzufinden und danach seine Verlässlichkeit einzuschätzen.

Aus diesen Quellen kann der `Kontext` dann eine Idee, eine Regel oder einen Stand der Arbeit ableiten.
Das daraus gewonnene Wissen wird an anderer Stelle festgehalten.
Wenn ein Datum falsch scheint, wenn zwei Personen verwechselt wurden oder wenn eine Deutung fragwürdig wird, kann man so zu ihrem Ursprung zurückgehen.

##### Brauchbar gemachte Ideen

Quellen anzuhäufen genügt nicht.
Fünfhundert gut aufbewahrte Mails bleiben fünfhundert Mails zum Lesen.

Der `Kontext` verwandelt diese Quellen daher nach und nach in nutzbares Wissen.
Er lässt entstehen:
- Themen, 
- wichtige Tatsachen, 
- Regeln, 
- Unterscheidungen, 
- offene Fragen,
- Beziehungen.

Ein einzelner Austausch tritt in die Geschichte der Baustelle ein, zu der er gehört.
Mehrere Erwähnungen desselben Betriebs bereichern ein gemeinsames Wissen.
Eine Berichtigung verhindert, dass sich eine Verwechslung wiederholt.

Dieser Zwischenschritt zählt, weil er die Information brauchbar macht.
- Die Quellen halten fest, was empfangen oder gesagt wurde.
- Das geordnete Wissen hilft dabei, zu verstehen und zu handeln.

Bei komplexeren Arbeiten werden manche Ideen mehrfach dienen: dasselbe Produktwissen speist eine Entscheidung, eine Spezifikation und eine Dokumentation; dieselbe geprüfte Tatsache hilft, mehrere Kundenfragebögen zu beantworten.
Das Ergebnis ändert sich, während die Idee und ihre Herkunft verfügbar bleiben.

##### Ein Arbeitsstand, an den man anknüpfen kann

Laufende Arbeit hat immer einen aktuellen Stand: was man weiß, was unsicher bleibt, was entschieden wurde und was als Nächstes ansteht.

Bei der Eigentümergemeinschaft beantwortete der Stand eine unmittelbare Frage: wo steht diese Baustelle heute?
Ihre Geschichte beantwortete eine andere: wie sind wir dahin gekommen?
Das System brauchte beides, um ein wirkliches Wiederaufnehmen möglich zu machen.

Diese Unterscheidung geht über das Begleiten einer Baustelle hinaus.
Wenn ich das Schreiben eines Textes oder das Erkunden eines Produktproblems unterbreche, will ich mehr wiederfinden als eine Sammlung von Dokumenten.
Ich will wissen:
- was gesichert ist, 
- welcher Punkt noch wackelt,
- welche Handlung die Arbeit wieder in Gang bringt.

Der `Kontext` bewahrt diese Fortsetzung außerhalb des Gesprächs.
- Die Sitzung mit der KI darf aufhören.
- Die Arbeit behält einen Stand, zu dem die nächste Sitzung zurückkehren kann.

##### Regeln, die zur Arbeit gehören

Die KI verfügt über allgemeines Wissen.
Was eine Lage besonders macht, kennt sie dagegen größtenteils nicht: 
- die beiden Betriebe mit demselben Namen, 
- die Art, wie ein Team ein Kundensignal einordnet, 
- den Beweisgrad, der vor einer veröffentlichten Behauptung erwartet wird
- den Ton, der für ein Buch gewählt wurde,
- …

Der `Kontext` hält diese Regeln bei der Arbeit, die sie leiten.
Sie lassen sich berichtigen, wenn die Erfahrung ihre Grenze zeigt.
Danach greifen sie, ohne dass der Mensch sie in jeder Anfrage wiederholen müsste.

Diese Regeln geben der KI nicht die Verantwortung für die Arbeit.
Sie machen ausdrücklich, was der Mensch von ihr erwartet.
Der Mensch setzt das Ziel, bringt Quellen und Informationen ein oder bestätigt sie, berichtigt Deutungen und trifft die Entscheidungen.
Die KI nimmt Informationen auf, stellt Verbindungen her, ordnet, hinterfragt, formuliert um und bereitet innerhalb dieser Vorgaben Ergebnisse vor.

##### Ergebnisse, die zu einem Bedarf passen

Der `Kontext` bleibt auf das gerichtet, was er möglich machen soll.

Bei der Eigentümergemeinschaft konnte das Ergebnis sein:
- eine Antwort auf eine Frage, 
- ein Überblick über den Stand der Arbeiten,
- die Vorbereitung eines Gesprächs.
In anderen Verwendungen wird es sein: 
- ein Artikel, 
- ein Kundenfragebogen, 
- eine Dokumentation.

Dieser Arbeitsraum kann mehrere Ergebnisse hervorbringen, weil er die zugrunde liegenden Quellen vor ihrer endgültigen Ausarbeitung bewahrt.
Die Quellen sind nicht im ersten Dokument eingeschlossen, das sie verwendet.
Die Ideen bleiben für eine andere Frage oder ein anderes Publikum verfügbar.

Diese Fähigkeit unterscheidet den `Kontext` von einem bloßen Archiv.
- Ein Archiv erlaubt aufzubewahren.
- Der `Kontext` regelt, wie das Aufbewahrte wieder aufgenommen und umgeformt wird.

##### Eine Form, die ganz einfach anfangen kann

In meiner Praxis nimmt ein `Kontext` die Form von Dateien an, die ich lesen, verschieben und unabhängig von dem Werkzeug aufbewahren kann, das mir beim Arbeiten hilft.
Diese Form erfüllt mein Bedürfnis nach Kontrolle und Beständigkeit.
Andere Umsetzungen sind möglich, solange sie dieselben Aufgaben erfüllen.

Der erste `Kontext` hatte dennoch nichts Aufwendiges.
Er passte in eine Datei.
Er wuchs, als seine Grenzen sichtbar wurden.
Dieser Verlauf bleibt wichtig: Man muss nicht das ganze in diesem Buch beschriebene System bauen, um die Idee zu erproben.

Ein Thema, ein Ziel und einige erste Quellen genügen.
- Die KI hilft, sie zu ordnen.
- Der Mensch sieht, was fehlt, ergänzt eine Regel, bewahrt eine Quelle oder trennt zwei Informationen, die nicht dieselbe Rolle haben.
- Die Architektur entsteht im Takt der Probleme, denen man begegnet.

Der `Kontext` bezeichnet also weniger eine bestimmte Ordnerstruktur als eine dauerhafte Arbeitsbeziehung zwischen einem Menschen, einer KI und Informationen, die auf ein Ziel hin geordnet werden.

Der nächste Teil untersucht, was dieses Verhältnis ändert.
Ein Gespräch mit einer KI kann schon fruchtbar sein.
Der Übergang zum `Kontext` beginnt, wenn dieses Gespräch in einer Umgebung stattfindet, die sein Ziel, seine Geschichte und seinen Arbeitsstand über den aktuellen Moment hinaus bewahrt.

> [!note] Zum Merken — die sechs Anhaltspunkte eines `Kontexts`
> Ein Ziel, das eine Grenze zieht, Informationen mit nachvollziehbarer Herkunft, nutzbar gemachte Ideen, ein Arbeitsstand, an den man anknüpfen kann, eigene Regeln und Ergebnisse, die entstehen sollen.
> Diese sechs Anhaltspunkte genügen für den Anfang.
> Die Architektur kommt danach, wenn ein Problem sie nötig macht.

### Teil 2 — Was der `Kontext` ändert

Ein Gespräch mit einer KI kann bereits viel bewirken.
Es erklärt, formuliert um, schlägt vor und liefert oft eine bessere Antwort als die, auf die man allein gekommen wäre.

Dieser Teil fragt also, was ein `Kontext` dem hinzufügt.
Die Antwort liegt nicht in der Qualität ihrer Antworten, sondern in dem, was von einer Sitzung zur nächsten erhalten bleibt: eine Arbeit, die dort weitergeht, wo sie aufgehört hat, und Dokumente, die ihre Widersprüche bewahren, statt sie zu glätten.

#### 2.1 — Vom Gespräch zur Arbeit, die man wieder aufnehmen kann

Ein Gespräch mit einer KI kann ganz einfach beginnen.

Ich gebe ihr eine noch unklare Idee.
Sie formuliert sie um.
Ich bitte um eine Gliederung, dann um eine zweite.
Sie bringt einen Einwand, an den ich nicht gedacht hatte.
Ich schärfe meine Absicht, verwerfe eine Spur, vertiefe eine andere.
In wenigen Minuten bringt das Gespräch etwas voran, das sonst vielleicht lange vor einem leeren Blatt gelegen hätte.

Das ist eine der großen Stärken des Chats: eine Frage genügt zum Anfangen.
Für eine kurze Aufgabe passt diese Form sehr gut. Ich bitte um eine Zusammenfassung, eine Erklärung, ein paar Möglichkeiten. Die Antwort kommt, ich benutze sie, und das Gespräch darf enden.

Das Verhältnis ändert sich, wenn die Arbeit länger dauert.

##### Fünf Sätze, bevor ich schreiben kann

Ich öffne ein sechs Tage altes Gespräch wieder, um einen Text aufzunehmen, den ich in der Woche davor begonnen hatte.
Bevor ich eine einzige Zeile schreiben kann, tippe ich das hier:

> Nimm den Text über die Qualität der Einsatzberichte wieder auf.
> Er richtet sich an Betriebsleiter, nicht an Entwickler.
> Das Kürzen des Formulars hatten wir verworfen, für eine Entscheidung ist es zu früh.
> Die Zahl zu den Audits stammt aus einem einzigen Gespräch, behandle sie als Annahme.
> Wir waren beim dritten Abschnitt.

Fünf Sätze, um die KI in eine Arbeit zurückzuholen, die sie sechs Tage zuvor schon vor sich hatte.

Alles, was ich gerade getippt habe, gab es schon, bevor ich es tippte:
Der Blickwinkel, das Publikum, die Entscheidung, die schwache Stelle und der Punkt im Text standen im vorigen Gespräch.
Ich habe sie bloß aus meinem eigenen Gedächtnis hervorgeholt, weil das Gespräch sie nur in der zeitlichen Reihenfolge bewahrt hatte.

Die Arbeit folgt einer anderen Logik.
- Eine Anweisung vom Anfang muss am Ende noch gelten.
- Eine gestern ergänzte Quelle muss einen morgen geschriebenen Absatz tragen können.
- Eine alte Entscheidung muss verhindern, dass dieselbe Diskussion wieder aufgeht.
- Ein offener Punkt muss zum richtigen Zeitpunkt wieder auftauchen.

Je länger das Gespräch wird, desto mehr muss der Mensch diese Ordnung im Kopf halten.
Beginnt eine neue Sitzung, baut er die Lage für die KI neu auf: Hier ist das Ziel, hier ist, was sich geändert hat, hier ist der Ton, hier sind die Entscheidungen, hier waren wir.

Der Chat bleibt nützlich.
Für die Kontinuität bleibt jedoch der Mensch verantwortlich, der den Chat benutzt.

##### Dem, was bleiben soll, einen Ort geben

Ein `Kontext` ändert das Verhältnis, indem er der Arbeit einen Raum gibt, der vom Gespräch getrennt ist.

Das Gespräch bleibt der Ort des Austauschs.
Dort wird gefragt, erkundet, geschärft und berichtigt.
Was bleiben soll, wandert in den Arbeitsraum: 
- das Ziel, 
- die Quellen, 
- die Regeln, 
- die gefestigten Ideen, 
- die Entscheidungen, 
- die Texte,
- der Stand der Dinge.

Der Unterschied mag gering scheinen.
Er entspricht dem zwischen einer Besprechung und dem Projekt, um das es geht.
Eine gute Besprechung kann ein Projekt voranbringen, aber das Projekt steckt nicht ganz im Gedächtnis der Besprechung.
Die Dokumente, die Entscheidungen und die Aufgaben bestehen nach ihrem Ende weiter.

Die vollständige Abschrift des Chats aufzubewahren hätte nicht dieselbe Wirkung.
Sie ist wertvoll, wenn man genau wiederfinden will, was gesagt wurde, aber sie folgt der Form des Gesprächs: eine Frage, eine Antwort, eine Korrektur, ein Abschweifen, eine Rückkehr zum Thema.
Um die Arbeit aufzunehmen, müsste man diese Folge noch einmal lesen und entscheiden, was jetzt zählt.

Der `Kontext` dagegen formt das Gesagte um.
- Eine Korrektur wandert dorthin, wo sie die Rückkehr des Fehlers verhindern kann.
- Eine Entscheidung bleibt als Entscheidung sichtbar.
- Eine Quelle bleibt mit dem verbunden, was sie stützt.
- Ein Text besteht in seiner letzten vollständigen Fassung.

So wird aus der Erinnerung eine Grundlage für das weitere Handeln.
Sie soll nicht nur die Vergangenheit bewahren.
Sie bereitet den nächsten Schritt vor.

##### Eine Seite, um zweiunddreißig Texte wiederzufinden

Was das ändert, habe ich gemessen, als ich die Arbeit an diesem Buch wieder aufnahm.

Das Manuskript zählte damals zweiunddreißig Texte.
Manche Teile waren geschrieben, andere noch leer.
Ein Abschnitt war geteilt worden, weil er unverhältnismäßig viel Platz einnahm.
Zwei Stellen warteten darauf, dass ich sie gegenlese.
Eine Behauptung stützte sich auf kein konkretes Beispiel aus der Praxis und musste überarbeitet werden.

Für sich genommen ist keiner dieser Punkte schwer zu verstehen.
Zusammen bilden sie jedoch eine Lage, die man neu aufbauen muss, bevor man eine einzige brauchbare Zeile schreiben kann.

Ich könnte die zweiunddreißig Texte öffnen, die Gliederung noch einmal lesen, meine alten Gespräche durchgehen und die offen gebliebenen Anmerkungen suchen.
Diese Ausgrabungsarbeit würde Zeit kosten und einen Zweifel hinterlassen: Habe ich genau den Punkt vergessen, der einen Fehler verhindern sollte?

Stattdessen öffne ich den `Kontext` des Buches.
Er reicht mir eine Datei für den Wiedereinstieg, in der an jenem Morgen ungefähr das stand:

```markdown
# Wiederaufnahme

## Wo wir stehen
Es gibt zweiunddreißig Texte, von der Gliederung bis zum Schluss.
Die technischen Teile sind geschrieben; die ersten beiden bleiben zu theoretisch.

## Was vor dem Weitermachen zu wissen ist
Der angesprochene Leser kennt das Thema noch nicht: Er verliert den Faden, sobald ein Begriff vor einem konkreten Beispiel aus der Praxis kommt.
Die Behauptung über das Scheitern der Dokumentensysteme stützt sich noch auf keine persönliche Erfahrung.

## Die nächste Handlung
Die Eröffnung rund um den Fall der fünfhundert Mails der Eigentümergemeinschaft neu schreiben.

## Was offen geblieben ist
Zwei Stellen warten darauf, dass ich sie gegenlese.
Mehrere Quellen sind eingegangen, ohne zu Notizen umgeformt worden zu sein.
```

Eine Seite, in weniger als einer Minute gelesen.
Ich weiß, was zu tun ist, und habe keinen der zweiunddreißig Texte geöffnet.

##### Weitermachen ist nicht dasselbe wie wieder aufnehmen

**Weitermachen heißt, die nächste Handlung zu kennen.**
**Wieder aufnehmen heißt, den Sinn der Arbeit zurückzugewinnen, bevor man diese Handlung ausführt.**

Eine Aufgabenliste kann mir sagen, dass eine Quelle zu bearbeiten ist.
Sie erklärt mir nicht, warum diese Quelle Vorrang hat, welchen Teil des Buches sie erhellen soll oder welches Risiko sie beheben soll.

Zum Wiederaufnehmen brauche ich mehr:

- das Ziel, das die Arbeit verfolgt;
- den Punkt, an dem sie wirklich angekommen ist;
- die Entscheidungen, die den Fortgang noch lenken;
- die schwachen Stellen, die nicht vergessen werden dürfen;
- eine nächste Handlung, die genau genug ist, um wieder anzufangen.

Die Datei liest sich übrigens in dieser Reihenfolge.
„Zweiunddreißig Texte“ gibt ein Maß.
„Er verliert den Faden, sobald ein Begriff vor einem konkreten Beispiel aus der Praxis kommt“ gibt eine Richtung.
Die nächste Handlung folgt aus beidem und benennt den genauen Fall, der das Buch eröffnen soll.

Die Wiederaufnahme hat einen Gedankengang wiederhergestellt, nicht bloß eine Position in einer Liste.

Sie versucht deshalb nicht, mir jede Einzelheit der vorigen Sitzung wieder in den Kopf zu setzen.
Eine zu kurze Zusammenfassung löscht den Grund einer Entscheidung.
Ein zu langer Bericht schiebt den Augenblick hinaus, in dem die Arbeit wieder anfängt.

##### Eine Unterbrechung sucht sich ihren Zeitpunkt nicht aus

Anfangs stellte ich mir die Wiederaufnahme als Folge eines sauberen Abschlusses vor.
Eine Sitzung würde enden, ihr Stand sorgfältig zusammengefasst und die nächste Handlung notiert.

Die Praxis folgt diesem Drehbuch selten.
- Eine Besprechung beginnt.
- Der Akku geht leer.
- Der Tag endet früher als gedacht.
- Etwas anderes Dringendes nimmt den Platz des Themas ein.
Der Augenblick, in dem dieses Gedächtnis am nützlichsten ist, ist genau der, in dem man das Ende nicht vorbereitet hat.

Der `Kontext` wird deshalb während der gesamten Arbeit so gepflegt, dass der Wiedereinstieg jederzeit möglich bleibt.
Entscheidungen finden ihren Platz, wenn sie fallen, Aufgaben, wenn sie formuliert werden, Quellen, wenn sie hereinkommen.

Der leichte Wiedereinstieg wird zu einer Eigenschaft des Systems und verlangt keine außergewöhnliche Disziplin mehr vom Benutzer.

Der Mensch behält dennoch eine entscheidende Rolle.
Er kann urteilen, dass die vorgeschlagene nächste Handlung nicht mehr Vorrang hat, dass eine alte Entscheidung wieder aufzumachen ist oder dass eine neue Tatsache das Ziel verändert.
Das Gedächtnis legt den Weg nicht fest.
Es macht den Weg sichtbar, von dem aus man beschließt, ihn zu ändern.

Die fünf Sätze, die ich beim Wiederöffnen meines Gesprächs immer neu tippte, tippe ich nicht mehr.
Sie stehen irgendwo geschrieben, und jemand anderes als ich liest sie zu Beginn jeder Sitzung an meiner Stelle nach.

> [!note] Zum Merken — Chat, Umgebung und Wiedereinstieg
> Der Chat ist der Ort des Austauschs; der `Kontext` ist der Ort dessen, was bleiben soll.
> Ein Gespräch legt seine Informationen in der Reihenfolge ab, in der sie gesagt wurden; eine Arbeit verlangt eine andere.
> Weitermachen heißt, die nächste Handlung zu kennen; wieder aufnehmen heißt, den Sinn der Arbeit zurückzugewinnen, bevor man sie ausführt.
> Eine Unterbrechung kündigt sich nicht an: Die Möglichkeit zum Wiedereinstieg entsteht während der Arbeit, nicht erst beim Abschließen.

#### 2.2 — Zwei Kunden, ein Whitepaper und ein Widerspruch, den man behält

Bis hierher habe ich den `Kontext` und einige seiner Auswirkungen beschrieben.
Aber wie sieht er wirklich aus, wenn man ihn öffnet?
Was sieht man in den Dateien?
Wie lassen mehrere Quellen Ideen entstehen, die einzeln richtig sein können und trotzdem schwer zusammenzubringen sind?

Das Thema dieses erfundenen `Kontexts` ist einfach: verstehen, warum manche Techniker unvollständige Einsatzberichte abliefern, bevor entschieden wird, ob sich das Produkt ändern soll.

Seine Mission passt in wenige Zeilen:

> Verstehen, was die Qualität der Einsatzberichte verschlechtert. Die Schwierigkeiten beim Ausfüllen, die Zwänge der Organisation und die Bedürfnisse aus der Datennutzung auseinanderhalten. Keine Lösung wählen, bevor mehrere Quellen gegeneinander gehalten wurden.

Diese Mission gibt der Arbeit eine Richtung.
Sie verlangt, ein Problem zu verstehen, noch nicht, eine Funktion zu entwerfen.

##### Eine erste Aussage macht eine Idee sichtbar

Das erste in den `Kontext` gegebene Dokument ist die Abschrift eines Gesprächs mit einer Betriebsleiterin.

Sie erklärt:

> „Die Techniker füllen ihre Berichte oft am Freitag aus. Draußen kommt ihnen das Formular zu lang vor. Am Ende der Woche haben sie einen Teil der Einzelheiten vergessen."

Die KI bewahrt dieses Gespräch als **Quelle**.
Danach hält sie eine daraus gewonnene Idee auf einer eigenen Karte fest, die ich **atomare Notiz** nenne:

> **Ein zu anspruchsvolles Ausfüllen kann manche Techniker dazu bringen, den Bericht aufzuschieben und Einzelheiten zu verlieren.**

Diese Formulierung sagt nicht, dass alle Techniker so handeln, und auch nicht, dass die Länge des Formulars die einzige Ursache ist.
Sie hält den Kern der Aussage fest: In der geschilderten Organisation wird das Ausfüllen aufgeschoben, und ein Teil der Information verschwindet zwischen dem Einsatz und dem Aufschreiben.

Die Quelle bleibt verfügbar.
Die Notiz ersetzt sie nicht; sie macht ihre Hauptidee leichter auffindbar und leichter gegen das Folgende zu halten.

##### Die zweite Aussage bereichert dieselbe Notiz

Einige Wochen später kommt ein zweites Gespräch in den `Kontext`.

Diesmal berichtet ein Betriebsleiter:

> „Wir haben zwölf Felder zur Pflicht gemacht, um die Datenqualität zu verbessern. Jetzt schreiben manche Techniker ‚keine Besonderheiten' oder setzen einen Strich, nur um abschicken zu können."

Diese Aussage beschreibt nicht genau dasselbe Verhalten.
Die Techniker aus dem ersten Gespräch schieben das Ausfüllen auf.
Die aus dem zweiten füllen das Formular aus, umgehen aber, was es verlangt.

Beide Quellen betreffen dennoch dieselbe Kernidee: Ein Zwang, der mehr Informationen bringen soll, kann am Ende die tatsächliche Qualität des Eingetragenen mindern.

Das zweite Gespräch wird daher mit der ersten **atomaren Notiz** verknüpft.
Es ersetzt die erste Quelle nicht und schafft keine konkurrierende Idee.
Es bereichert die Notiz, indem es eine andere Form desselben Problems sichtbar macht: nach dem aufgeschobenen Ausfüllen die Vollständigkeit zum Schein.

Die Notiz kann jetzt sagen:

> **Ein zu anspruchsvolles Ausfüllen kann manche Techniker dazu bringen, den Bericht aufzuschieben oder zu umgehen, zu Lasten der gesammelten Information.**

Zwei Quellen sind angegeben.
Jede behält ihre Rolle und ihre Grenzen.
Die Notiz wird fester, ohne zu behaupten, zwei Aussagen genügten, um das Ausmaß des Phänomens zu messen.

##### Das Whitepaper macht eine andere Idee sichtbar

Danach füge ich ein Whitepaper über die Nutzung von Einsatzdaten hinzu.

Das Dokument vertritt eine andere Anforderung.
Um wiederkehrende Störungen zu verstehen, Anlagen zu vergleichen und bestimmte Audits vorzubereiten, braucht ein Unternehmen ausreichend strukturierte Berichte.
Schreibt jeder Techniker in ein Freitextfeld, was er will — oder trägt gar nichts ein —, wird das Ausfüllen vielleicht leichter, aber die Daten verlieren einen großen Teil ihres gemeinsamen Nutzens.

Diese **Quelle** macht die früheren Aussagen nicht weniger wahr.
Die geschilderten Techniker schieben weiter auf oder umgehen weiter.
Das PDF macht eine andere Wirklichkeit sichtbar: Jeden Zwang zu streichen hätte ebenfalls seinen Preis.

Die KI könnte versucht sein, diese Teile in die erste Notiz zu verschmelzen und sie als allgemeinen Kompromiss neu zu schreiben.
Das wäre ein Fehler.
Das Whitepaper schränkt die in den Gesprächen beobachtete Tatsache nicht ein; es bringt eine andere Aussage.

Es erzeugt also eine zweite **atomare Notiz**:

> **Strukturierte Berichte sind nötig, um Einsätze zu vergleichen und Einsatzdaten zu nutzen.**

Der `Kontext` enthält nun zwei verschiedene Ideen:

- der Zwang beim Ausfüllen kann die tatsächlich gesammelte Information verschlechtern;
- das Fehlen von Struktur kann die spätere Nutzung dieser Information verschlechtern.

Beide Notizen können zugleich wahr sein.
Trotzdem ziehen sie die Produktentscheidung in entgegengesetzte Richtungen.

##### Der Gegensatz muss zwischen den Notizen sichtbar bleiben

Die Aufgabe des `Kontexts` ist es nicht, die erste Notiz so lange zu ändern, bis der Widerspruch verschwindet.
Er muss beide Aussagen bewahren und ihre Beziehung ausdrücklich machen.

Eine **thematische Notiz** kann dann sagen, was ihr Zusammentreffen verstehen lässt:

> **Die Qualität eines Berichts hängt von einer Spannung ab zwischen dem Aufwand beim Ausfüllen und der Struktur, die seine Nutzung verlangt.**

Diese dritte Notiz ist kein diplomatischer Mittelwert.
Sie ersetzt keine der beiden atomaren Notizen.
Sie zeigt das neue Problem, das entsteht, wenn man sie zusammen liest.

Der Widerspruch wird auch im Arbeitsstand festgehalten: Wie lassen sich strukturierte Informationen gewinnen, ohne dass das Ausfüllen aufgeschoben oder die Vorgaben umgangen werden?
Keine der drei Quellen liefert darauf bislang eine Antwort.

##### Das sieht man auf dem Bildschirm

Der `Kontext` dieses Beispiels besteht als kleiner Ordner voller Dateien.
Sein Aufbau ist nicht der Begriff selbst: Er ist meine derzeitige Art, ihm eine greifbare Form zu geben.

```text
contexte-qualite-comptes-rendus/
├── 00-frame/
│   ├── mission.md
│   └── directives.md
├── 01-state/
│   ├── state.md
│   └── contradictions.md
├── 03-sources/
│   ├── SRC00001-entretien-exploitation.md
│   ├── SRC00002-entretien-exploitation.md
│   └── SRC00003-livre-blanc-donnees-intervention.md
├── 04-notes/
│   ├── atomic/
│   │   ├── ATO00001-la-contrainte-de-saisie.md
│   │   └── ATO00002-des-comptes-rendus-structures.md
│   └── thematic/
│       └── THM00001-la-qualite-depend-de-la-saisie.md
└── 05-outputs/
    └── questions-prochain-entretien.md
```

Jetzt kannst du die seit Beginn des Buches benutzten Wörter an sichtbare Gegenstände knüpfen.

- Die **Mission** erklärt, warum der Ordner existiert.
- Die **Quellen** bewahren, was vor der Deutung eingegangen ist.
- Die **atomaren Notizen** halten verschiedene Ideen fest.
- Die **thematische Notiz** macht ihre Spannung verständlich.
- Der **Stand** sagt, was diese Spannung offen lässt.
- Das **Ergebnis** bereitet die nächste Handlung vor.

Nichts davon verlangt eine geheimnisvolle Software.
VS Code (es könnte aber auch die Codex-App oder Claude Cowork sein) ist hier bloß das Fenster, durch das ich den `Kontext` erreiche.
Der `Kontext` selbst steckt in den Dateien, in ihren Aufgaben und in den Beziehungen, die zwischen ihnen bewahrt werden.

##### Die Rückmeldung stützt sich auf die bisherige Arbeit

Ein paar Tage später nehme ich die Arbeit wieder auf und schlage der KI vor:

> „Vielleicht sollten wir alle Felder freiwillig machen."

In einem einzelnen Gespräch könnte die KI diese Idee verteidigen, eine leichtere Oberfläche vorschlagen oder ihre Vorteile aufzählen.
Im `Kontext` trifft sie auf die beiden atomaren Notizen und auf die Spannung zwischen ihnen.

Sie kann dann antworten:

> Dieser Vorschlag würde einen Teil der in den Gesprächen geschilderten Reibung wohl verringern. Er steht allerdings dem im Whitepaper festgestellten Bedarf an strukturierten Daten entgegen. Die Quellen zeigen zwei wirkliche Zwänge; sie erlauben noch nicht, zwischen Vereinfachung, schrittweisem Ausfüllen, Spracheingabe oder einer Anpassung der Felder an die Einsatzart zu wählen.

Diese Rückmeldung kommt nicht aus allgemeinem Wissen über Product Management.
Sie stützt sich auf die laufende Arbeit.
Die KI weiß, welche Frage wir zu verstehen suchen, welche Ideen von welchen Quellen gestützt werden und welcher Widerspruch offen bleibt.

Sie entscheidet nicht an meiner Stelle.
Sie verhindert bloß, dass meine neue Eingebung eine der schon festgestellten Wirklichkeiten auslöscht.

##### Das erste Ergebnis bereitet die nächste Quelle vor

**Der Stand** des `Kontexts` sagt nicht: „ein neues Formular entwerfen".
Er trennt, was gesichert scheint, von dem, was unsicher bleibt.

> **Was gesichert scheint**  
> Zwänge beim Ausfüllen können Aufschieben und Umgehen auslösen. Genug Struktur bleibt nötig, um die Berichte zu nutzen.
>
> **Was offen bleibt**  
> Wir wissen noch nicht, welche Reibung am schwersten wiegt und welche Angaben unbedingt strukturiert bleiben müssen.
>
> **Nächste Handlung**  
> Ein Gespräch vorbereiten, das die Ursachen des Problems auseinanderhält, statt sofort eine Lösung zu präsentieren.

Das erste Ergebnis ist also bescheiden: ein Fragenleitfaden für die neuen Gespräche.
Er soll verstehen lassen, wann ausgefüllt wird, welche Zwänge vor Ort gelten, wie nützlich die einzelnen Felder wirklich sind und welche Formen das Umgehen annimmt.

Das Ergebnis entscheidet den Widerspruch nicht.
Es bereitet die Erkenntnisse vor, mit denen sich der Widerspruch später vielleicht auflösen lässt.

##### Ein Arbeitsgegenstand, keine Maschine, die alles verschmilzt

Dieses Beispiel zeigt auch einen Fehler, den die KI machen kann: eine neue Quelle in eine bestehende Notiz pressen zu wollen, weil die Themen ähnlich aussehen.

Eine **atomare Notiz** darf wachsen, wenn mehrere Quellen dieselbe Aussage betreffen.
Genau das geschieht mit den beiden Gesprächen.
Aber das Whitepaper ist kein neuer Beleg für diese Aussage.
Es stützt eine andere Idee, die eine eigene Notiz verdient.

Die Unterscheidung zählt.
Wenn jeder Widerspruch die vorige Notiz überschreibt, glättet *das gesammelte Wissen* am Ende alle Spannungen.
Das Wissen wirkt stimmig, entspricht aber nicht mehr dem, was die Quellen wirklich beigetragen haben.

Der `Kontext` verbürgt nicht, dass die KI immer die richtige Grenze wählt.
Der Mensch muss eine Verschmelzung ablehnen, eine neue Notiz verlangen und die zwischen ihnen geschaffene Beziehung prüfen können.
Der Aufbau macht diese Berichtigung möglich und dauerhaft; er trifft sie nicht von selbst.

Jetzt hast du den Gegenstand gesehen: 
- **Quellen**, die unversehrt bleiben, 
- **atomare Notizen**, von denen jede ihren eigenen Kern behält,
- eine **thematische Notiz**, die zusammenbringt, ohne zu verschmelzen, 
- einen **Widerspruch**, der offen bleibt, und ein **Ergebnis**, das den Fortgang vorbereitet.

Die folgenden Kapitel können zu den Verwendungen des `Kontexts` zurückkehren und danach seinen Aufbau anhand dieser nun sichtbaren Elemente genauer öffnen.

> [!note] Zum Merken — ein Widerspruch wird bewahrt
> Zwei Quellen können zugleich wahr sein und die Entscheidung in entgegengesetzte Richtungen ziehen.
> Eine atomare Notiz wächst, wenn eine Quelle dieselbe Aussage stützt; eine andere Aussage verdient eine eigene Notiz.
> Zu verschmelzen, damit die Spannung verschwindet, erzeugt stimmiges Wissen, das nicht mehr zu den Quellen passt.

### Teil 3 — Drei Verwendungen in der Praxis

Die beiden vorigen Teile haben gesagt, was der `Kontext` verändert.
Dieser Teil zeigt ihn bei der Arbeit, an drei Verwendungen, die ich wirklich praktiziere.

Einen Kundenfragebogen beantworten, einen Artikel aus einem noch ungeformten Gedanken schreiben, ein Produktthema mitten in einem zerstückelten Tag reifen lassen.
Drei Zeiträume, drei Arten von Material, drei Empfänger — und jedes Mal dieselbe Bewegung: wiederfinden, was schon verstanden wurde, es umformen und dann etwas erzeugen, ohne aufzubrauchen, was dazu gedient hat.

#### 3.1 — Einen Kundenfragebogen beantworten, ohne die geleistete Arbeit zu verlieren

Der erste Kundenfragebogen, den ich mit diesem System bearbeitet habe, hatte dreiundvierzig Fragen.

Zu beantworten waren die Architektur des Produkts, seine Sicherheit, die Sicherungen, die Betriebskontinuität und der Datenschutz.
Ein Teil der Angaben stand in unserer Dokumentation.
Andere steckten in Konfigurationsdateien.
Für manche mussten wir das Team fragen, das den Dienst betreibt.

Wir mussten sieben technische Quellen zusammentragen und mit dem Team hin und her gehen.
Das kam zum eigentlichen Schreiben hinzu: verstehen, was der Interessent wissen wollte, die Angabe finden, prüfen, ob sie noch stimmte, entscheiden, was wir mitteilen durften, und die Antwort dann in das erwartete Format bringen.

Das war keine Ausnahmelage.
Jeder neue Interessent schickte sein eigenes Dokument.
Einmal war es eine Tabelle, ein andermal eine Word-Datei oder ein PDF.
Die Referenzsysteme wechselten, die Formulierungen auch, aber dieselben Themen kamen wieder.

Und doch hatten wir jedes Mal das Gefühl, von vorn anzufangen.
Das Antworten dauerte drei bis sechs Stunden und band mehrere Personen, ohne Gewähr, dass aus dem Interessenten ein Kunde wird.
Dann ging das Dokument hinaus, und die Arbeit blieb in der verschickten Datei eingeschlossen.

Mein erstes Ziel war also einfach: Wenn der nächste Fragebogen käme, wollte ich nicht wieder bei null anfangen.

##### Eine glaubwürdige, aber falsche Antwort

Die naheliegendste Lösung war, die alten Fragebögen aufzubewahren und ihre Antworten wiederzuverwenden.

Wir haben schnell gemerkt, warum das nicht reichte.

In manchen eingegangenen Dokumenten standen schon Antworten.
Sie konnten aus einer Vorlage stammen, von einem anderen Anbieter oder aus einem früheren Austausch.
In einem davon hieß es, die Zertifizierung ISO 9001 stamme von 2017.
Der Satz sah völlig brauchbar aus.
Er war genau, schon geschrieben und stand der richtigen Frage gegenüber.

Das richtige Datum war 2018.

Der Fehler betraf ein einziges Jahr, aber er machte ein viel größeres Problem sichtbar.
Eine alte Antwort sieht aus wie Wissen.
Sie hat eine bejahende, beruhigende Form.
Trifft eine KI sie in einem Dokument, kann sie sie mühelos übernehmen.
Und doch sagt ihr Vorhandensein weder, wer sie geschrieben hat, noch worauf sie beruht, noch ob sie unser Produkt wirklich beschreibt.

Da habe ich verstanden, dass ich keine Bibliothek von Antworten zum Abschreiben bauen durfte.
Zu bauen war ein Gedächtnis dessen, was wir wirklich zu antworten wussten.

Der eingegangene Fragebogen behielt einen Wert: Er zeigte, was der Kunde wissen wollte.
Aber für sich allein konnte er die Antwort nicht belegen.
Diese Unterscheidung wurde zu einer Regel des `Kontexts`: Das Dokument des Kunden enthält die Frage; die Antwort muss mit einer Angabe verbunden bleiben, die wir geprüft haben.

##### Die Tatsachen bewahren statt der Formulare

Wir fingen an, aus den Fragebögen herauszuziehen, was dem nächsten dienen konnte.

Die Fragen wurden nicht mehr nur nach Kunde oder Nummer abgelegt.
Wir führten sie nach Thema zusammen: Sicherungen, Authentifizierung, Verschlüsselung, Unterauftragnehmer, Hosting, Betriebskontinuität.
Eine Frage mit der Nummer „14.6.l" bei einem Interessenten konnte so zu einer Frage „CL-072" bei einem anderen treten, wenn beide dasselbe Thema betrafen.

Für jedes dieser Themen bewahrte der `Kontext` die bestätigten Tatsachen und ihre Herkunft.
Eine Antwort konnte sich auf eine offizielle Dokumentation stützen, auf eine geprüfte Konfiguration, auf einen Test oder auf die Bestätigung des zuständigen Teams.
Wir hielten auch das Datum der Bestätigung fest und die Grenzen dessen, was wir sagen durften.

Diese Arbeit brachte nicht immer eine vollständige Antwort hervor.
Sie machte auch die Lücken sichtbar.

Fehlte eine Angabe, musste das System das sagen.
Es bereitete eine genaue Frage an das betroffene Team vor und nannte die Zeilen des Fragebogens, die diese Antwort vervollständigen würde.
Eine fehlende Angabe versteckte sich damit nicht mehr hinter einem glaubwürdigen Satz.
Sie wurde zu einer benennbaren Handlung.

Schließlich trennten wir, was der Prüfung einer Antwort diente, von dem, was an den Kunden gehen konnte.
Die Einzelheit einer Konfiguration konnte für den internen Gegenleser unentbehrlich sein und trotzdem nicht ins öffentliche Dokument gehören.
Der `Kontext` bereitete also die Formulierung für den Interessenten vor und bewahrte daneben die Belege und Vorbehalte, die für ihre Freigabe nötig waren.

Nach und nach änderte sich das Ziel.
Es ging nicht mehr nur darum, den vorliegenden Fragebogen fertigzustellen.
**Jede geprüfte Antwort sollte die Arbeit für die nächsten verringern.**

##### Der vierte Fragebogen

Der vierte Fragebogen hatte hundertfünfzehn Fragen, weit mehr als der erste.

Diesmal begannen wir nicht mehr bei einer Ansammlung verstreuter Dateien.
Der `Kontext` kannte die wiederkehrenden Themen schon und wusste, wo die zugehörigen Tatsachen zu finden waren.
Sechsundneunzig vollständige Antworten entstanden unmittelbar aus dem aufgebauten Gedächtnis und aus den Quellen des Produkts, ohne neue Erhebung.

Das System ordnete auch den Rest des Dokuments ein.
Manche Antworten waren belastbar, verlangten aber eine letzte Prüfung.
Andere blieben unsicher.
Einige ließen sich mit den vorhandenen Angaben nicht geben.

Vor allem hatten die Lücken ihre Art geändert.
Wir verbrachten keine Stunden mehr damit, aufs Geratewohl zu suchen, wer was wusste.
Die noch offenen Punkte entsprachen kaufmännischen Entscheidungen — etwa der Dauer einer Zusage — oder einzelnen technischen Bestätigungen.
Die verbleibende Arbeit war sichtbar, zuweisbar und begrenzt.

An diesem Ergebnis konnte ich sehen, was es wirklich heißt, einen Fragebogen „automatisch" zu beantworten.
Es geht nicht darum, eine KI alle Felder mit Zuversicht füllen zu lassen.
Es geht darum, sofort vorzubereiten, was vorzubereiten ist, bei jeder Antwort zu zeigen, wie sicher sie ist, und klar abzugrenzen, was noch ein menschliches Urteil verlangt.

##### Zehn Minuten heißt nicht hundert Prozent Gewissheit

In meiner Praxis ist die Vorbereitung eines Kundenfragebogens von drei bis sechs Stunden auf etwa zehn Minuten für 80 bis 90 % des Dokuments gesunken.

Diese Zahl könnte einen falschen Eindruck erwecken.
Sie heißt nicht, dass 80 bis 90 % der Antworten augenblicklich sicher und geeignet sind, das Unternehmen zu binden.
Sie heißt, dass das Dokument weitgehend vorbereitet ist: Die bekannten Antworten stehen, die Quellen sind gefunden, die schwachen Stellen sind markiert, und die fehlenden Angaben sind in genaue Anfragen verwandelt.

Das Gegenlesen durch Menschen bleibt unentbehrlich.
Es trifft allerdings die richtigen Stellen.
Statt seine Zeit damit zu verbringen, alte Dateien zu durchwühlen und dieselben Leute noch einmal zu bemühen, kann der Gegenleser die Zusagen prüfen, entscheiden, was offengelegt wird, und sich auf die neuen oder unsicheren Antworten konzentrieren.

Der wichtigste Gewinn ist also nicht allein der Weg von mehreren Stunden zu ein paar Minuten.
Es ist die veränderte Art der Arbeit.

Der erste Fragebogen hatte eine Untersuchung verlangt.
Die folgenden haben von allem profitiert, was diese Untersuchung gelehrt hatte.
Ein falsches Datum wurde zu einer Regel der Vorsicht.
Eine von einem Team erhaltene Bestätigung wurde zu einer wiederverwendbaren Tatsache.
Eine unbeantwortete Frage wurde zu einer bekannten Lücke statt zu einem Versehen.

Der Interessent bekommt nach wie vor sein Dokument.

Das Unternehmen dagegen verliert nicht mehr, was es beim Vorbereiten gelernt hat.

> [!note] Zum Merken — eine Antwort gilt so viel wie ihr Beleg
> Eine alte Antwort sieht aus wie Wissen: bejahend, gut geformt, und stumm über ihre Herkunft und ihr Datum.
> Die geprüften Tatsachen und ihre Herkunft bewahren, nicht die schon ausgefüllten Formulare.
> Eine ausgesprochene Lücke ist mehr wert als ein glaubwürdiger Satz: Sie wird zu einer Frage an jemanden.

#### 3.2 — Einen Artikel aus einem noch ungeformten Gedanken schreiben

Die Artikel, die ich in meinem Blog veröffentliche, beginnen selten am Rechner, vor einer sorgfältig vorbereiteten leeren Seite.

Eine Idee taucht nach einer Schwierigkeit auf, nach einem ausprobierten Werkzeug, nach einem Gespräch oder nach einem Sinneswandel.
Manchmal kommt sie beim Gehen, in öffentlichen Verkehrsmitteln oder auf meinem Sofa.
Ich spüre, dass sie einen Text verdient, aber ich kenne weder ihren genauen Blickwinkel noch die Reihenfolge, in der sie erzählt werden muss.

In diesem Augenblick nehme ich oft mein Telefon.

Ich benutze es nicht bloß, um eine Sprachnotiz aufzunehmen oder einen Text zu diktieren, den ich später abtippe.
**Ich beginne ein Gespräch mit der KI.**
Sie hört zu, antwortet und hakt nach, während ich nachdenke.
Dieses Gespräch landet in derselben Arbeitsumgebung, die ich später am Rechner wiederfinde.
Ich kann also weit weg vom Schreibtisch anfangen, ohne eine einzelne Notiz zu erzeugen, die danach übertragen und neu gedeutet werden müsste.

##### Einen entstehenden Gedanken abladen

Ich lege einen `Kontext` mit einem einfachen Ziel an: den Artikel schreiben.
Dann gebe ich ihm alles, was ich im Kopf habe.

Manchmal zwei Stunden lang spreche ich über einen ersten Punkt, dann über einen zweiten, und kehre zum ersten zurück.
Ich erzähle eine Erfahrung, springe zu einem Schluss, füge eine Einzelheit hinzu, öffne eine neue Spur und lasse die vorige eine Weile liegen.
Ich kann dieselbe Idee viermal wiederholen, weil sie mir in verschiedenen Formen wiederkommt.
Ich kann auch etwas behaupten und eine Stunde später das Gegenteil sagen, weil sich mein Denken während des Gesprächs verschoben hat.

Diese Unordnung ist kein Missgeschick, das man vor dem Anfangen ausräumen müsste.
Sie ist oft die wirkliche Form einer Idee, solange sie noch entsteht.

Das Gespräch mit der KI erlaubt mir weiterzugehen, ohne zu früh eine Struktur aufzuzwingen.
Eine Antwort lässt mich eine Erinnerung schärfen.
Eine Frage zeigt, dass ich gerade einen Schritt übersprungen habe.
Eine Umformulierung zeigt mir, dass das, was ich für selbstverständlich hielt, es noch nicht ist.
Ich berichtige, ich schränke ein, und ich gehe in eine andere Richtung weiter.

Der `Kontext` bewahrt dieses Gesagte als Sitzungsquelle.
Er behält nicht nur die saubersten Sätze.
Er bewahrt auch die Anläufe, das Zögern und die Widersprüche, an denen sich später erkennen lässt, wie sich das Denken bewegt hat.

Die KI führt danach die vier Formulierungen derselben Idee zusammen, statt sie als vier verschiedene Ideen zu behandeln.
Sie meldet zwei unvereinbare Behauptungen, findet die Einschränkung, die eine Stunde später kam, und stellt ein Beispiel neben den Grundsatz, den es erhellt.
**Sie lässt die Unordnung nicht verschwinden: Sie macht sie bearbeitbar.**

Dieser erste Schritt befreit mich von einer verfrühten Wahl.
Ich muss noch nicht entscheiden, welcher Satz den Artikel eröffnet, ob eine Idee einen Abschnitt verdient oder in welcher Reihenfolge die Ereignisse zu erzählen sind.
Ich will erst einmal ausleeren, was ich im Kopf habe, ohne die Ideen entwischen zu lassen, die ihn nur durchqueren.

Der `Kontext` weiß allerdings, warum dieser Stoff da ist.
Er bekommt kein Gespräch ohne Ziel.
Er bekommt den noch ungeordneten Stoff eines zu bauenden Artikels.

##### Die KI als Partnerin beim Reifen benutzen

Sobald dieser erste Stoff abgelegt ist, frage ich die KI, was fehlt.

Sie greift eine zu schnelle Behauptung auf, eine nie erklärte Voraussetzung, eine Stelle, die nur trägt, wenn der Leser meine Erfahrung schon kennt.
Sie verlangt ein Beispiel.
Sie führt zwei zu verschiedenen Zeitpunkten geäußerte Ideen zusammen.
Manchmal schlägt sie eine Spur vor, die glaubwürdig aussieht und die ich ablehne, weil sie nicht zu dem passt, was ich erlebt habe.

Ich antworte, ich schärfe, ich berichtige.
Dieses Gespräch bringt den Artikel noch nicht hervor.
Es verdichtet seinen Stoff.

Die Rolle der KI ist wichtig, aber ihr Platz bleibt klar.
Sie verfügt über alles, was ich hineingegeben habe, und sucht darin schneller nach Spannungen als ich.
Was ich wirklich vertreten will, weiß sie dagegen nicht, solange ich es nicht formuliert habe.
Sie öffnet die Frage; ich entscheide, ob diese Frage es wert ist, den Text zu verschieben.

Dieser Austausch verkürzt die Zeit bis zur Begegnung mit einer Schwäche.
Allein hätte ich zwei Tage später entdeckt, dass ein Beispiel fehlt oder dass mein Schluss auf einem nie erklärten Schritt beruht.
Die KI löst diese Entdeckung aus, solange die Idee noch leicht zu überarbeiten ist.

##### Quellen ergänzen, wenn die Erfahrung nicht mehr reicht

Meine Artikel gehen oft von dem aus, was ich erlebt habe.
Der Stoff von außen behält trotzdem seine Rolle:

- ein Verweis gibt dem, was ich beobachtet habe, einen Namen;
- eine Dokumentation bestätigt eine Funktionsweise;
- ein anderer Autor vertritt eine benachbarte Position oder zeigt eine Grenze, der ich nicht begegnet war;
- eine weitere Recherche zeigt, dass meine Erfahrung nur einen Sonderfall abdeckt.

Diese Dokumente treten als **Dokumentquellen** in den `Kontext` ein.
Ihre Rolle unterscheidet sich von der meiner ersten Worte.
Die **Sitzungsquelle** bewahrt, was ich behaupte und was ich von meiner Erfahrung verstehe.
Die **Dokumentquellen** bringen einen Stoff, den ich dieser Erfahrung gegenüberstellen kann.

Der Artikel kann dann unterscheiden, was ich beobachtet habe, was eine Quelle feststellt und was eine Deutung bleibt.
Diese Unterscheidung schützt den Text vor einer häufigen Versuchung: eine persönliche Erfahrung als allgemeine Regel auszugeben.

##### Quellen in wiederverwendbare Ideen verwandeln

An diesem Punkt geht der `Kontext` nicht unmittelbar von den Quellen zur Gliederung des Artikels über.
Er verwandelt den rohen Stoff zuerst in **atomare Notizen**.

Jede Notiz hält eine eigenständige Idee aus dem Gespräch oder aus einem Dokument fest:
- eine Behauptung, die ich vertreten will;
- ein Beispiel, das ihr eine greifbare Form gibt;
- eine Einschränkung, die ihre Reichweite begrenzt;
- einen Einwand, auf den der Artikel antworten muss;
- eine Tatsache von außen, die meine Erfahrung bestätigt oder ihr widerspricht.

Die Notiz bewahrt ihre Herkunft.
So kann ich die Idee verstehen, ohne das ganze Gespräch noch einmal zu lesen, und danach zur Quelle zurückgehen, wenn ich eine Formulierung prüfen oder ihren Zusammenhang wiederfinden muss.

Diese Umformung ändert die Art, den Artikel vorzubereiten.
- Das Gespräch folgte der Bewegung meines Denkens; die Notizen versammeln nun, was von derselben Idee handelt, auch wenn diese Teile eine Stunde auseinanderlagen oder aus zwei verschiedenen Quellen kamen.
- Eine zentrale Notiz kann den Blickwinkel des Artikels sichtbar machen.
- Andere bringen ihm Beispiele, Belege, Einwände oder Folgen.

Diese Notizen sind noch weder Absätze noch eine fertige Gliederung.
**Sie bleiben dem Ergebnis gegenüber neutral: Dieselbe Idee wird diesen Artikel, einen Vortrag oder eine andere Arbeit speisen können.**

##### Vor dem Schreiben über die Gliederung gehen

Wenn der Stoff ausreicht, verlange ich eine Gliederung.

Dieser Schritt hindert mich daran, unmittelbar von einem reichen Gespräch zu einem Text überzugehen, der bloß dessen Reihenfolge folgen würde.
Eine Diskussion kommt durch Rückgriffe, Berichtigungen und Assoziationen voran.
Ein Artikel muss einen Leser führen, der weder die Diskussion noch ihre Geschichte kennt.

Die Gliederung legt diesen Verlauf fest.
Sie sagt, was zuerst verstanden werden muss, wohin das Hauptbeispiel gehört, welcher Einwand zu behandeln ist und was der Schluss wirklich behaupten darf.

Die KI schlägt aus dem vorhandenen Stoff eine Struktur vor.
Ich verschiebe sie, ziehe sie enger, lehne die Teile ab, die einer Nebenspur zu viel Gewicht geben.
Zwei oder drei Runden genügen oft für eine klare Richtung.

Danach folgt das Schreiben.

An diesem Punkt erzeugt die KI den Text nicht aus einer vagen Anweisung.
Sie arbeitet mit einem Bestand an Ideen und Themen aus meiner erzählten Erfahrung, mit Antworten auf Fragen, mit Quellen und mit einer bestätigten Gliederung.
Sie fasst die Wiederholungen zusammen, rückt die Beispiele an ihren Platz und macht aus gewundener Rede lesbare Prosa.

Ich lese das Ergebnis gegen und suche drei genaue Abweichungen:

- eine verschwundene Einschränkung;
- eine Stelle, die zu behauptend geworden ist;
- eine Formulierung, die die Idee verrät.

Ich berichtige sie und entscheide dann über die veröffentlichte Fassung.

##### Was der `Kontext` einer kurzen Arbeit bringt

Ein Artikel lässt sich in ein oder zwei Tagen schreiben.
Er scheint nicht dasselbe Gedächtnis zu brauchen wie ein über Jahre begleitetes Produkt oder ein Buch mit Dutzenden Kapiteln.

Gerade dieser leichte Fall zeigt, dass die Dauer nicht das Einzige ist, worum es geht.

Der `Kontext` hält die ersten Worte, die ergänzten Quellen, die gestellten Fragen, die gewählte Gliederung und den vollständigen Text zusammen.
Bricht die Arbeit ab, finde ich ihren Stand wieder.
Wird ein Satz fragwürdig, kann ich zu seinem Ursprung zurückgehen.
Geht eine beim Schreiben aufgetauchte Idee über den Artikel hinaus, kann sie gesondert festgehalten werden und eine spätere Arbeit speisen.

Nicht alles davon verdient es unbedingt, unbegrenzt aufbewahrt zu werden.
Ein kleiner `Kontext` kann sein Ziel erreichen, seinen Artikel hervorbringen und danach archiviert werden.
Sein Wert liegt in der Fortsetzung, die er der Arbeit während ihrer Entstehung gegeben hat, und in der Spur, die er hinterlässt, falls man später verstehen muss, wie der Text diese Richtung nahm.

Die Veröffentlichung selbst kann weitere Aufgaben auslösen: eine Zusammenfassung vorbereiten, den Text an mehrere Sprachen anpassen oder erzeugen, was für die Online-Stellung nötig ist.
Diese Schritte verlängern dasselbe Ergebnis, unter Regeln, die der `Kontext` schon kennt.

Die ganze Bewegung bleibt einfach: Eine Erfahrung wird Rede, diese Rede trifft auf Fragen und Quellen, der Stoff wird eine Gliederung, und die Gliederung wird ein Text.

Die KI beschleunigt jede Umformung, und der `Kontext` hält den Faden, der von einer zur nächsten führt.

Nichts an dieser Bewegung gehört allein dem langen Schreiben.
Sie beginnt, sobald eine Idee mehr verdient als eine im Telefon vergessene Sprachnotiz.

> [!note] Zum Merken — Unordnung ist Stoff
> Ein entstehender Gedanke wiederholt sich, widerspricht sich und geht zurück: Das ist seine normale Form und kein Fehler, den man vor dem Anfangen beheben müsste.
> Der `Kontext` bewahrt dieses Gesagte als Sitzungsquelle und macht es danach bearbeitbar.
> Die Gliederung schiebt sich zwischen das Gespräch und den Text, weil ein Leser der Reihenfolge einer Diskussion nicht folgt.

#### 3.3 — Ein Produktthema mitten im Durcheinander reifen lassen

Die beiden vorigen Kapitel sind jeweils einem einzigen Thema von Anfang bis Ende gefolgt.
Dieses Kapitel beschreibt, wie ein typischer Tag eines Product Managers wirklich aussieht: Mehrere Themen, Anfragen und Zeitläufe kommen gleichzeitig voran.

Ich bin der einzige Product Manager in meinem Unternehmen.
Das heißt, ein großer Teil der Informationen rund um das Produkt landet am Ende bei mir.

Am selben Tag sagt ein Kunde einen Satz, der mir wichtig erscheint.
- Er besteht aus wenigen Worten.
- Ich weiß noch nicht, ob er ein Problem zeigt, das andere Nutzer teilen, oder bloß eine besondere Schwierigkeit, aber ich will ihn nicht verlieren.

Etwas später bekomme ich ein Whitepaper über die Entwicklung einer fachlichen Frage.
- Diesmal passt der Stoff nicht mehr in einen Satz, sondern steckt in einem PDF von mehreren Dutzend Seiten.
- Ich weiß noch nicht, was mir davon nützt, und auch nicht, ob das Dokument bestätigt, was ich vor Ort beobachte.

Dann sprechen mich die Entwickler auf eine Funktion an, die gerade gebaut wird.
- Eine Frage ist zu beantworten, ein Verhalten festzulegen oder eine vor Wochen getroffene Annahme noch einmal anzusehen.

Währenddessen will der CPO zwei Wetten auf einen anderen Teil des Produkts durchgehen.

Ein Gespräch mit dem Support zeigt schließlich, dass eine fachliche Dokumentation fehlt.
- Ein Teil dieser Dokumentation gibt es bisher nur in meinem Kopf.

Am Ende des Tages bin ich über drei oder vier verschiedene Themen gegangen (oder mehr).
Ich habe ein Zitat von wenigen Worten bekommen, ein ganzes Dokument, eine Frage zu einer laufenden Entwicklung, eine zu treffende Entscheidung und einen Bedarf an Dokumentation.

**Das ist kein besonders schlechter Tag: Es ist ein gewöhnlicher.**

##### Eingänge, die weder dieselbe Größe noch dasselbe Ziel haben

Das Durcheinander im Product Management kommt nicht allein von der Menge der Informationen.
Es kommt von ihrer verschiedenen Art.

Jeder dieser fünf Eingänge schaut auf einen anderen Augenblick im Leben des Produkts:

- der Satz eines Kunden ist ein schwaches Signal, von dem ich noch nicht weiß, ob es weitere ankündigt;
- ein PDF gibt einen allgemeinen Blick auf ein Fachgebiet;
- ein Gespräch mit den Entwicklern betrifft, was wir gerade bauen;
- eine Anfrage des Supports betrifft, was schon vorhanden ist und erklärt werden muss;
- eine Frage des CPO zwingt dazu, mehrere mögliche Zukünfte zu vergleichen.

Diese Teile sind nicht dafür gedacht, in ein einziges Dokument zu wandern.
- Sie sprechen nicht alle vom selben Thema und liegen nicht im selben Augenblick des Produktlebens.
Sammle ich sie bloß in einer Notizliste, bewahre ich die Informationen, schiebe aber die Arbeit des Verstehens auf den Tag, an dem ich sie brauche.

`Kontexte` erlauben mir, mehrere Fäden nebeneinander zu halten.
- Das Zitat tritt zu dem Thema, zu dem es zu gehören scheint, auch wenn seine Bedeutung noch unsicher ist.
- Das PDF wird mit seiner Herkunft bewahrt und lässt sich auswerten, um die wenigen wirklich nützlichen Ideen (**atomare Notizen**) herauszuziehen.
- Das Gespräch mit den Entwicklern tritt zur Arbeit an der laufenden Funktion.
- Die vom Support gemeldete Lücke wird zu einer zu leistenden Arbeit, statt eine zwischen zwei Besprechungen gehörte Bemerkung zu bleiben.

Nicht alles wird sofort in Wissen verwandelt: 
- der Satz des Kunden bleibt vielleicht mehrdeutig, 
- das Whitepaper wenig einschlägig, 
- die Ahnung in der folgenden Woche widerlegt.

Der `Kontext` macht das Eingehende nicht klüger.
Er gibt ihm einen Ort, eine Herkunft und die Chance, zur rechten Zeit wiedergefunden zu werden.

**Der `Kontext` fasst das Durcheinander, ohne es abschaffen zu wollen.**

##### Während Informationen hereinkommen, hören die Anfragen nach Ergebnissen nicht auf

Der Tag besteht nicht nur daraus, Stoff aufzunehmen und abzulegen: Es muss auch etwas entstehen.

Der Support bittet mich zum Beispiel um eine fachliche Dokumentation zu einer Funktion, an der wir noch arbeiten.
- Sie muss erklären, wie sie arbeitet, die wichtigen Fälle festhalten und denen, die Kunden begleiten, etwas an die Hand geben, womit sie richtig antworten können.

Am selben Tag will ich vielleicht einen Artikel für den Unternehmensblog fertigstellen.
- Dieser Artikel handelt nicht unbedingt von derselben Funktion.
- Er kann aber dasselbe fachliche Thema betreffen: das Metier, dem das Produkt dient, eine wiederkehrende Schwierigkeit der Nutzer oder eine Veränderung ihrer Praxis.

Die beiden Dokumente greifen dann auf einen Teil desselben Wissens zurück, ohne dasselbe zu erzählen.
- Die Dokumentation für den Support erklärt das Produkt so, wie es arbeitet.
	- Sie muss genau sein, betrieblich brauchbar und auf die Fragen der Nutzer zugeschnitten.
- Der Artikel entfaltet eine Erfahrung, ein fachliches Problem oder einen Gedankengang.
	- Er kann einige derselben Ideen aufgreifen, ordnet sie aber für einen anderen Leser und zu einem anderen Zweck.

Ich muss nicht zweimal alles neu aufbauen, was ich über das Thema weiß.
- Der `Kontext` bewahrt einen Zwischenstoff (die **atomaren Notizen** und **thematischen Notizen**), der noch weder die Dokumentation noch der Artikel ist.
- Aus diesem Stoff kann die KI mehrere Zusammenstellungen vorbereiten: eine um den Gebrauch des Produkts herum, die andere um die weitere fachliche Frage.

Ich lese natürlich beide Ergebnisse gegen.
- Eine Dokumentation für den Support legt fest, wie das Produkt verstanden wird.
- Ein Artikel legt meinen Standpunkt fest.
Aber ich verwende meine Zeit darauf, Substanz und Ausrichtung zu prüfen, statt dieselben Elemente wiederzufinden und von vorn zu schreiben.

Diese Bewegung kann am selben Tag stattfinden.
Während neue Informationen hereinkommen, erlaubt schon geordnetes Wissen, die Dokumente hervorzubringen, die das Unternehmen oder ich brauchen.

##### Ein kleiner Satz kann zu einem Produktthema werden

Das am Morgen gehörte Zitat löst nicht zwangsläufig eine Entscheidung aus.
- Für sich genommen beweist es vielleicht nichts.
- Ein anderer Kunde äußert womöglich einige Wochen später eine ähnliche Schwierigkeit. 
- Ein Gespräch bringt eine Einschränkung.
- Das an jenem Tag aufgegriffene Whitepaper gibt der beobachteten Entwicklung vielleicht einen Namen.
- Eine Zahl aus dem Support zeigt, dass das Problem öfter wiederkommt als gedacht.

Diese Teile treffen zu verschiedenen Zeiten und in verschiedenen Formen ein.
- Der `Kontext` erlaubt, sie zusammenzubringen, ohne ihre Herkunft zu löschen.
- Er kann anmerken, 
	- dass eine neue Bemerkung einem schon bewahrten Signal ähnelt,
	- einen Widerspruch sichtbar machen,
	- fragen, was zwischen zwei Deutungen entscheiden würde.

Nach und nach kann ein einzelner Satz zu einem Thema werden, an dem sich zu arbeiten lohnt.
Dann habe ich schon einen Teil seiner Geschichte: die ersten Signale, die Dokumente, die es erhellen, was sie bestätigt, was ihnen widerspricht und die noch offenen Fragen.

Der `Kontext` hilft diesem Stoff zu reifen.
- Er entscheidet nicht, dass das Problem wichtig ist, und wählt die Lösung nicht an meiner Stelle.
Die Produktwette bleibt meine Verantwortung.
- Dafür kann ich diese Entscheidung mit mehr treffen als einer vagen Erinnerung oder einer Reihe verstreuter Dokumente.

Dasselbe System begleitet danach die Arbeit: 
- Gespräche ergänzen, 
- eine Annahme den Tatsachen gegenüberstellen, 
- Szenarien vorbereiten, 
- eine Argumentation für den CPO erstellen,
- Spezifikationen schreiben,
- …

Ein kleines, mitten am Tag aufgefangenes Signal kann so lange genug weiterleben, um zu einer wirklichen Entscheidung zu werden.

##### Eine aufgegebene Idee kann weiter reifen

Nicht jede Erkundung geht bis in die Produktion.

Ich habe an Verwendungen künstlicher Intelligenz gearbeitet, die interessant aussahen, die die verfügbare Technik aber noch nicht ordentlich umsetzen konnte.
- Die Idee war nicht unbedingt schlecht.
- Der Zeitpunkt war es.

Im üblichen Ablauf hätte die Erkundung ein paar Dokumente hervorgebracht und wäre nach dem Abbruch in einem Ordner verschwunden.
- Ein oder zwei Jahre später hätte man diese Dateien wiederfinden, sich an die Ausgangsannahmen erinnern und verstehen müssen, warum wir aufgehört hatten.

Mit einem `Kontext` lässt sich die Erkundung samt ihrem Weg archivieren: die ersten Signale, die erdachten Szenarien, die Versuche, die angetroffenen Grenzen und der Grund des Abbruchs.
- Entwickelt sich die Technik weiter, kann ich diese Arbeit wieder aufnehmen, ohne aus einem alten negativen Ergebnis eine endgültig schlechte Idee zu machen.

Ich finde wieder, was wir tun wollten, aber auch, warum es nicht ging.
Ich kann dann prüfen, ob das Hindernis noch besteht, behalten, was noch gilt, und das Denken von dort aus weiterführen.

Das Reifen eines Produktthemas ist also nicht immer ein durchgehender Weg.
- Es kann mit einem Satz beginnen, sich über Monate anreichern, abbrechen und wieder aufgenommen werden, wenn sich Produkt, Markt oder Technik geändert haben.

##### Ordnung entstehen lassen, ohne den Tag zu bremsen

Mein Tag bleibt zerstückelt.
- Die Kunden stimmen ihre Bemerkungen nicht mit den Anfragen des Supports ab.
- Die Entwickler wählen nicht den Augenblick, in dem ich gerade ein PDF zu Ende gelesen habe.
- Die vorzubereitenden Entscheidungen halten nicht inne, während ich eine Dokumentation oder einen Artikel schreibe.

Der `Kontext` verwandelt diese Wirklichkeit nicht in eine saubere Abfolge von Aufgaben.

Er erlaubt jedem Bruchstück, eine Fortsetzung zu behalten.
- Ein kleiner Satz und ein langes Dokument dürfen hereinkommen, ohne dieselbe Behandlung zu bekommen.
- Mehrere Themen dürfen vorankommen, ohne sich zu vermischen.
- Schon bearbeitetes Wissen darf mehreren Ergebnissen dienen, ohne im ersten eingeschlossen zu werden.
- Eine unterbrochene Idee darf warten, ohne ihre ganze Geschichte zu verlieren.

So benutze ich ihn im Product Management: nicht, um meinen Tag ruhiger zu machen, sondern um zu verhindern, dass seine Bewegung zerstreut, was ich lerne.

Das Durcheinander kommt weiter herein.

Es geht nur nicht mehr als Verlust wieder hinaus.

Diese drei Verwendungen haben eines gemeinsam, das ich noch nicht benannt habe: Jede endet mit etwas, das weggeht — eine verschickte Antwort, ein veröffentlichter Artikel, eine getroffene Entscheidung.

Der nächste Teil sieht sich an, was bleibt, wenn das Ergebnis weg ist.

> [!note] Zum Merken — mehrere Fäden nebeneinander
> Der Satz eines Kunden und ein fünfzigseitiges PDF verlangen eine andere Behandlung und ein anderes Ziel.
> Der `Kontext` gibt jedem Bruchstück einen Ort, eine Herkunft und die Chance, zur rechten Zeit wiedergefunden zu werden.
> Eine aufgegebene Erkundung behält ihre Gründe für den Abbruch: Sie lässt sich wieder aufnehmen, wenn sich Technik oder Markt ändern.

### Teil 4 — Was die Ergebnisse hinter sich lassen

Jede der drei vorigen Verwendungen endet mit einem abgegebenen Ergebnis.
Dieser Teil sieht sich an, was bleibt, wenn es weg ist.

Als Faden dient eine einzige Frage, zweimal im Abstand von sechs Monaten gestellt.
Beim ersten Mal passt die Antwort in eine Tabellenzelle.
Beim zweiten gibt es diese Antwort noch, aber sie genügt nicht mehr: Was fehlt, ist der Gedankengang, der sie hervorgebracht hat, und die Beziehungen zwischen den Dokumenten, die ihn stützten.

#### 4.1 — Die Antwort passt in eine Zelle, der Gedankengang nicht

Gehen wir zu einem der Fragebögen aus dem vorigen Teil zurück.

Die Frage steht in Zelle D47 einer Tabelle:

> Sind Ihre Sicherungen im Ruhezustand verschlüsselt?

Die endgültige Antwort wird drei Zeilen lang sein.
Um sie zu schreiben, muss ich allerdings mehrere Dinge zusammenbringen:
- unsere Dokumentation beschreibt, wie die Sicherungen allgemein arbeiten;
- eine Konfigurationsdatei zeigt die tatsächlich geltende Einstellung;
- das Ops-Team bestätigt, wie diese Einstellung in der Produktion greift;
- die Rechtsabteilung sagt, was wir einem Interessenten mitteilen dürfen.

Ich gehe von der Tabelle zur Dokumentation, von der Dokumentation zur Konfiguration und dann von einem Austausch mit dem Ops-Team zu einer rechtlichen Entscheidung.
Schließlich kehre ich in die Zelle D47 zurück und schreibe die Antwort hinein.

Das Dokument geht hinaus.

##### Drei Zeilen am Ende einer Kette

**Die Zelle enthält das Ergebnis der Arbeit.**
**Sie zeigt nicht den Weg, der es hervorgebracht hat.**

Sie sagt nicht:
- welche Dokumentation ich herangezogen habe;
- welche Einstellung ich geprüft habe;
- wer ihre Geltung bestätigt hat;
- welche Formulierung freigegeben wurde;
- welche Vorbehalte aus dem an den Interessenten geschickten Text herausgenommen wurden.

Diese Dinge gibt es trotzdem.
Sie haben jede der drei Zeilen bestimmt, und während ich antworte, ist ihr Zusammenhang in meinem Kopf klar.

Ist das Dokument einmal verschickt, verschwindet diese Einheit.
Die Tabelle bewahrt die Antwort, aber nicht den Gedankengang, der es erlaubte, ihr zu trauen.

##### Jedes Werkzeug hat seine Arbeit getan

Das Problem kommt nicht von schlechter Ablage.
- Die Dokumentation steht sehr wohl im Dokumentationsbereich.
- Die Konfiguration bleibt im Produkt.
- Die Antwort des Teams bleibt in ihrem Gesprächsfaden.
- Die rechtliche Entscheidung hat ihren eigenen Ort.
- Die Zelle D47 steht an ihrem Platz im Dokument des Interessenten.

Jedes Werkzeug hat den Gegenstand bewahrt, den man ihm anvertraut hatte.
Keines hatte die Aufgabe, den ganzen Gedankengang zu bewahren.

Um ihn wieder aufzubauen, muss man wissen, welche Elemente zu suchen sind, wo sie zu suchen sind und welche Rolle jedes gespielt hat.
Dieses Wissen trägt weiterhin die Person, die die Antwort vorbereitet hat.

##### Das Ergebnis flacht ab, was es hervorgebracht hat

Ein Ergebnis muss dem Empfänger etwas vorlegen, das zu ihm passt.
- Der Interessent erwartet eine klare Antwort, nicht das vollständige Protokoll der Untersuchung, die sie erbracht hat.

Diese Vereinfachung ist nötig.
Sie wird teuer, wenn das Ergebnis die einzige Spur der Arbeit bleibt.

Das Endergebnis ist immer kürzer als der Weg dorthin — die verschickte Antwort ebenso wie der veröffentlichte Artikel oder die Produktentscheidung.
Bleibt nur das Ergebnis, muss die nächste Arbeit einen Teil dieses Weges neu gehen.

##### Dem Gedankengang eine Adresse geben

Der `Kontext` ersetzt weder die Tabelle noch die Dokumentation, noch die Konfiguration, noch den Austausch mit den Teams.
- Er gibt der Arbeit, die sie verbindet, eine gemeinsame Adresse.

Die Frage D47, die herangezogenen Elemente, die erhaltenen Freigaben und die entstandene Antwort gehören zum selben Thema.
Sie können ihre ursprüngliche Form und ihren ursprünglichen Ort behalten und im `Kontext` trotzdem verbunden bleiben.

Die Zelle erfüllt weiter ihre Aufgabe: dem Interessenten zu antworten.
Der `Kontext` erfüllt eine andere: zu bewahren, was es erlauben wird, diese Antwort zu verstehen, zu prüfen und wieder aufzunehmen.

Sechs Monate später wird dieser Unterschied entscheidend.

> [!note] Zum Merken — das Ergebnis bewahrt den Gedankengang nicht
> Eine Antwort kann drei Zeilen lang sein und trotzdem von mehreren Quellen, Freigaben und Vorbehalten abhängen.
> Die Werkzeuge bewahren jeweils ihren eigenen Gegenstand; die Beziehungen zwischen ihnen trägt weiterhin der Mensch.
> Der `Kontext` gibt der Arbeit, die diese Elemente verbindet, eine Adresse, ohne ihre Ursprungswerkzeuge zu ersetzen.

#### 4.2 — Sechs Monate später genügt die Antwort nicht mehr

Sechs Monate nach der Zelle D47 stellt ein neuer Interessent dieselbe Frage zur Verschlüsselung der Sicherungen.
- Ich finde die alte Antwort in zehn Sekunden.
- Sie ist klar, gut geschrieben und bereit zum Übernehmen.

Und doch sitze ich davor und kann sie nicht gebrauchen.

Drei Fragen genügen, um mich aufzuhalten:
- woher kam diese Antwort: aus der Dokumentation, aus der beobachteten Einstellung oder aus dem, was mir das Ops-Team an jenem Tag erklärt hat?
- hatte die Rechtsabteilung genau diese Formulierung freigegeben oder eine vorsichtigere?
- ist die Einstellung heute noch dieselbe?

**Die Antwort hat überlebt; was es erlaubte, ihr zu trauen, ist verschwunden.**

##### Finden heißt noch nicht wieder aufnehmen

Die alte Zelle gibt mir einen Text zurück.
Sie gibt mir nicht zurück: 
- seinen Beweisgrad,
- seine Grenzen, 
- und auch nicht die Prüfungen, die vor einer erneuten Verwendung nötig sind.

Ohne ein anderes Gedächtnis muss ich die ganze Untersuchung des vorigen Kapitels wiederholen, in umgekehrter Reihenfolge.
Ich fange nicht ganz bei null an, denn eine Antwort habe ich schon.
Ich fange aber an, ohne zu wissen, welcher Teil der Arbeit noch gilt.

Es ist der Fehler mit der auf 2017 statt auf 2018 datierten Zertifizierung, diesmal von unseren eigenen Antworten her gesehen: der Satz ist klar, er stammt von uns, und sein Beleg ist unsichtbar geworden.

##### Die Rolle jedes Elements wiederfinden

Im `Kontext` steht die alte Antwort nicht allein.
Sie bewahrt die Beziehungen, die der Gedankengang dahinter brauchte:

```text
Dokumentation ── beschreibt ──┐
Konfiguration ─ bestätigt ────┼──▶ Antwort D47
Ops-Team ─── differenziert ───┤
Rechtsabteilung ─ gibt frei ──┘
```

Die Verben ändern, was ich mit jedem Element anfangen kann.
- Die Dokumentation beschreibt die allgemeine Funktionsweise; für sich allein belegt sie die geltende Einstellung nicht.
- Die Konfiguration bestätigt diese Einstellung zu einem bestimmten Zeitpunkt; sie entscheidet nicht, was mitgeteilt werden darf.
- Das Ops-Team bringt eine Differenzierung, die aus dem laufenden Betrieb stammt.
- Die Rechtsabteilung gibt eine Formulierung für den Interessenten frei.

Ich finde nicht mehr bloß vier Gegenstände in der Nähe einer Antwort.
Ich finde die Rolle wieder, die jeder von ihnen gespielt hat.

Diese Genauigkeit hindert eine Quelle daran, mehr zu belegen, als sie wirklich feststellt.
Sie zeigt außerdem, welche Prüfung nach einiger Zeit zu wiederholen ist.

##### Prüfen, was sich geändert haben kann

Der `Kontext` macht aus der alten Antwort keine dauerhafte Wahrheit: 
Er bereitet ihre Prüfung vor.
- Die Dokumentation kann noch gelten, während sich die Konfiguration geändert hat.
- Die Konfiguration kann unverändert sein, während die freigegebene Formulierung zu überarbeiten ist.
- Eine Differenzierung des Ops-Teams kann nach einer Weiterentwicklung des Produkts weggefallen sein.

Die Beziehungen machen diese Unterschiede sichtbar.
Ich kann die Elemente prüfen, die sich geändert haben können, ohne die ganze Untersuchung aufs Geratewohl zu wiederholen.

Die endgültige Antwort wird vielleicht dieselbe sein wie vor sechs Monaten.
Der Unterschied ist, dass ich weiß, warum ich sie noch verwenden darf.

##### Die Beziehungen bewahren, die der Arbeit dienen

Es geht nicht darum, alle Dokumente miteinander zu verbinden.
- Zwei Dateien können ein Wort teilen, ohne am selben Gedankengang teilzunehmen.

Eine Beziehung verdient es, bewahrt zu werden, wenn sie ändert, wie man versteht, prüft, entscheidet oder herstellt.
- Im Fall von D47 genügen vier Beziehungen: beschreiben, bestätigen, differenzieren und freigeben.

Sie erlauben, konkrete Fragen zu beantworten:
- worauf beruht diese Antwort?
- welcher Teil ist heute zu prüfen?
- wer hatte freigegeben, was wir mitteilen durften?
- was würde diese Antwort hinfällig machen?

Der `Kontext` versucht also nicht, eine Gesamtkarte von allem zu bauen, was ich weiß.
Er bewahrt das Gewebe, das eine bestimmte Arbeit braucht.

##### Die Maschine öffnen

Buch I hat gezeigt, wie der `Kontext` entstanden ist, was er am Umgang mit der KI ändert und wie er mehrere Verwendungen begleitet.
Der Fall D47 macht sichtbar, was noch zu verstehen bleibt.
- Wie bewahrt man die Mission einer Arbeit, ohne sie in jeder Sitzung zu wiederholen?
- Wohin gehören die Quellen, die Ideen, die Entscheidungen und die Ergebnisse, damit sie verschiedene Rollen behalten?
- Wie lädt man die Informationen, die gerade nützlich sind, ohne alles ins Gespräch zu holen?

Buch II wird diese Maschine öffnen.
Es wird den vollständigen Weg von Informationen durch einen `Kontext` verfolgen: von ihrem Eintreffen über ihre Umformung bis zu dem, was sie hervorbringen und wie die Arbeit wieder aufgenommen wird.

> [!note] Zum Merken — wiederfinden, was Vertrauen erlaubt
> Eine Antwort wiederzufinden genügt nicht: Man muss wiederfinden, was ihre Verwendung noch erlaubt.
> Eine benannte Beziehung nennt die genaue Rolle einer Quelle, einer Freigabe oder eines Vorbehalts.
> Der `Kontext` bereitet die Prüfung vor, indem er zeigt, was die Antwort trägt und was sich geändert haben kann.

## Buch II — Den `Kontext` bauen und am Leben halten

- Teil 5 — Unter der Haube eines `Kontexts`

- Teil 6 — Der `Kontext` in seinem Ökosystem

### Teil 5 — Unter der Haube eines `Kontexts`

Bisher wurde der `Kontext` über das beschrieben, was er möglich macht.
Dieser Teil öffnet ihn.

Er zeigt zuerst seinen vollständigen Verzeichnisbaum und begleitet dann eine Arbeitssitzung von Anfang bis Ende: öffnen und den Stand wiederfinden, Material hereinholen, es in Ideen verwandeln, ein Ergebnis herstellen, entscheiden und schließlich speichern, damit die nächste Sitzung beginnen kann, ohne irgendetwas neu aufzubauen.

Das Beispiel, das durch diese sechs Kapitel läuft, ist frei erfunden: verstehen, warum manche Techniker unvollständige Einsatzberichte abliefern, bevor entschieden wird, ob sich das Produkt ändern soll.

#### 5.1 — Die vollständige Karte

In Teil 2 habe ich den `Kontext` zur Qualität der Einsatzberichte zurückgelassen: 
- drei Quellen, 
- zwei atomare Notizen, 
- eine thematische Notiz,
- einen Leitfaden für das nächste Gespräch.
Damals habe ich darauf geschaut, was er zu verstehen erlaubte.
Jetzt öffne ich den Ordner selbst.

Hier der vollständige Verzeichnisbaum der Fassung, die ich in diesem Buch verwende:

```text
contexte-qualite-comptes-rendus/
├── README.md               allgemeine Navigation, generiert
├── offline.md              der Briefkasten zwischen den Sitzungen
│
├── 00-frame/               was eine dauerhafte Richtung vorgibt
│   ├── README.md           Navigation des Bereichs, generiert
│   ├── mission.md          das Ziel, die Frage, die Grenzen
│   ├── directives.md       die Regeln dieser Mission
│   └── loading.md          was beim Öffnen gelesen wird
│
├── 01-state/               der Stand der Arbeit
│   ├── README.md           Navigation des Bereichs, generiert
│   ├── state.md            Gesichertes, Offenes, Schulden
│   ├── synthesis.md        was dauerhaft geworden ist
│   ├── todo.md             die anstehenden Handlungen
│   ├── decisions.md        die Entscheidungen, die den Kontext prägen
│   ├── contradictions.md   was in Spannung bleibt
│   ├── handoff.md          die Anleitung zum Wiedereinstieg
│   ├── checkpoints.md      die kompakte Folge der Zustände
│   └── health.md           das Ergebnis der letzten Prüfung
│
├── 02-history/             die sachliche, datierte Spur
│   ├── README.md           die Rolle dieser Spur, generiert
│   └── YYYY-MM-DD.md       die Ereignisse des Tages
│
├── 03-sources/             was empfangen oder gesagt wurde
│   ├── README.md           die Liste der Quellen, generiert
│   ├── ingestion-log.md    was gelesen wurde, was es ergab
│   ├── documents/
│   │   ├── README.md       die Liste der Dokumente, generiert
│   │   ├── raw/            die Originaldateien
│   │   ├── fulltext/       ihr auswertbarer Volltext
│   │   └── SRC00001-….md   Identität, Herkunft, Zustand
│   └── sessions/
│       ├── README.md       die Liste der Sitzungen, generiert
│       └── SESSION-….md    das während der Arbeit Gesagte
│
├── 04-notes/               das aus den Quellen gewonnene Wissen
│   ├── README.md           die Karte der Notizen, generiert
│   ├── atomic/             eine Idee pro Notiz — ATO00001-….md
│   ├── thematic/           ein verbindender Blickwinkel — THM00001-….md
│   ├── glossary/           ein festgelegter Begriff — GLO00001-….md
│   └── decision-records/   eine Entscheidung — DRE00001-….md
│
└── 05-outputs/             was für eine Verwendung entsteht
    ├── README.md           die Liste der Ergebnisse, generiert
    ├── _draft/             die Ergebnisse in Arbeit
    ├── questions-entretien.md   ein Leitfaden zum Weitermachen
    ├── note-de-cadrage.md       eine Synthese zum Entscheiden
    └── presentation-equipe.md   dieselben Erkenntnisse, neu formuliert
```

Die Nummern geben eine Lesereihenfolge vor, keine Rangordnung des Werts:
- Rahmen und Stand geben der Arbeit ihre Richtung;
- die Geschichte erlaubt es, ihren Verlauf zu prüfen;
- die Quellen bewahren das Material, die Notizen machen Wissen daraus;
- die Ergebnisse geben ihm eine Form für einen Empfänger.

##### Sechs Bereiche, sechs Aufgaben

`00-frame/` beantwortet die Frage „warum bin ich hier, und unter welchen Regeln?".
Dieser Bereich ändert sich selten, und das aus gutem Grund: die Mission zu ändern würde verwandeln, wie ich sämtliche Quellen, sämtliche Aufgaben und sämtliche Ergebnisse beurteile.
```text
contexte-qualite-comptes-rendus/
├── 00-frame/               was eine dauerhafte Richtung vorgibt
│   ├── README.md           Navigation des Bereichs, generiert
│   ├── mission.md          das Ziel, die Frage, die Grenzen
│   ├── directives.md       die Regeln dieser Mission
│   └── loading.md          was beim Öffnen gelesen wird
```

`01-state/` beantwortet „wo stehe ich jetzt?".
Dieser Bereich bewegt sich mit der Arbeit und lässt mich Gesichertes von einer Vermutung unterscheiden, eine künftige Handlung von einer bereits getroffenen Entscheidung, eine vorübergehende Schwierigkeit von einem Widerspruch, der sichtbar bleiben soll.
```text
contexte-qualite-comptes-rendus/
├── 01-state/               der Stand der Arbeit
│   ├── README.md           Navigation des Bereichs, generiert
│   ├── state.md            Gesichertes, Offenes, Schulden
│   ├── synthesis.md        was dauerhaft geworden ist
│   ├── todo.md             die anstehenden Handlungen
│   ├── decisions.md        die Entscheidungen, die den Kontext prägen
│   ├── contradictions.md   was in Spannung bleibt
│   ├── handoff.md          die Anleitung zum Wiedereinstieg
│   ├── checkpoints.md      die kompakte Folge der Zustände
│   └── health.md           das Ergebnis der letzten Prüfung
```

`02-history/` beantwortet „was ist wirklich geschehen?".
Dieser Bereich erzählt die Sitzung nicht schön: er bewahrt ihre nützlichen Fakten, eine hinzugefügte Quelle, eine aufgegebene Spur, eine getroffene Entscheidung, eine angelegte Notiz.
Ich sehe selten hinein, aber er wird entscheidend an dem Tag, an dem mir der gegenwärtige Stand widersprüchlich vorkommt.
```text
contexte-qualite-comptes-rendus/
├── 02-history/             die sachliche, datierte Spur
│   ├── README.md           die Rolle dieser Spur, generiert
│   └── YYYY-MM-DD.md       die Ereignisse des Tages
```

`03-sources/` beantwortet „welches Material habe ich bekommen?".
Ein Dokument von außen tritt unveränderlich ein, mein eigenes Wort tritt im Lauf der Sitzungen ein.
In beiden Fällen bleibt die Quelle getrennt von dem, was der `Kontext` daraus verstehen wird.
```text
contexte-qualite-comptes-rendus/
├── 03-sources/             was empfangen oder gesagt wurde
│   ├── README.md           die Liste der Quellen, generiert
│   ├── ingestion-log.md    was gelesen wurde, was es ergab
│   ├── documents/
│   │   ├── README.md       die Liste der Dokumente, generiert
│   │   ├── raw/            die Originaldateien
│   │   ├── fulltext/       ihr auswertbarer Volltext
│   │   └── SRC00001-….md   Identität, Herkunft, Zustand
│   └── sessions/
│       ├── README.md       die Liste der Sitzungen, generiert
│       └── SESSION-….md    das während der Arbeit Gesagte
```
Das Blatt `SRC00001-….md` enthält weder das Dokument noch seine Zusammenfassung.
Es beantwortet alles, was ich darüber wissen muss:
- woher es kommt und warum ich es hinzugefügt habe;
- wo Original und Volltext zu finden sind;
- ob die Extraktion geglückt ist;
- wie viel Vertrauen ihm zusteht;
- ob seine Lektüre bereits Notizen ergeben hat.

Es macht den Zustand der Quelle also sichtbar, ohne das Material selbst anzurühren.

`04-notes/` beantwortet „was habe ich gelernt?".
- Eine atomare Notiz hält eine Idee fest.
- Eine thematische Notiz verbindet mehrere Ideen.
- Das Glossar legt ein Wort genauer fest.
- Ein Decision Record bewahrt die Gründe einer Entscheidung.
```text
contexte-qualite-comptes-rendus/
├── 04-notes/               das aus den Quellen gewonnene Wissen
│   ├── README.md           die Karte der Notizen, generiert
│   ├── atomic/             eine Idee pro Notiz — ATO00001-….md
│   ├── thematic/           ein verbindender Blickwinkel — THM00001-….md
│   ├── glossary/           ein festgelegter Begriff — GLO00001-….md
│   └── decision-records/   eine Entscheidung — DRE00001-….md
```

`05-outputs/` beantwortet „was mache ich mit diesem Wissen?".
Entwürfe und Ergebnisse leben dort, in der Form, die ihr Publikum erwartet:
- ein Gesprächsleitfaden;
- ein Artikel;
- eine Spezifikation;
- eine Präsentation;
- eine Entscheidung, neben anderen möglichen Formen.
```text
contexte-qualite-comptes-rendus/
└── 05-outputs/             was für eine Verwendung entsteht
    ├── README.md           die Liste der Ergebnisse, generiert
    ├── _draft/             die Ergebnisse in Arbeit
    ├── questions-entretien.md   ein Leitfaden zum Weitermachen
    ├── note-de-cadrage.md       eine Synthese zum Entscheiden
    └── presentation-equipe.md   dieselben Erkenntnisse, neu formuliert
```

##### Die Welt der Ideen: Bausteine für mehrere Bauten

Die Trennung zwischen `04-notes/` und `05-outputs/` trägt eine der wichtigsten Stärken des `Kontexts`.
Notizen und Glossar bilden dort eine *Welt der Ideen*: eine Menge von Wissensbausteinen, unbegrenzt wiederverwendbar, die nicht mehr rohes Material und noch kein für jemanden bestimmtes Ergebnis sind.

```text
03-sources/
     │
     ▼
04-notes/                       die Welt der Ideen
├── ATO00001                    eine festgehaltene Idee
├── ATO00002                    eine weitere festgehaltene Idee
└── THM00001                    eine Lesart ihrer Beziehung
     │
     ├──> questions-entretien.md
     ├──> note-de-cadrage.md
     └──> presentation-equipe.md
```

In meinem Beispiel wurden die Mühe beim Ausfüllen und der Bedarf an strukturierten Daten festgehalten, bevor ich wusste, in welcher Form sie dargestellt würden.
- der Gesprächsleitfaden zieht daraus Fragen, 
- die Rahmennotiz zieht daraus das, was auf dem Spiel steht,
- die Präsentation zieht daraus eine Erzählung für das Team.

Diese drei Ergebnisse besitzen das Wissen nicht, das sie verwenden.
- Sie wählen einen Teil davon aus und setzen ihn für einen bestimmten Bedarf, ein bestimmtes Publikum und ein bestimmtes Format neu zusammen.
- Ein Ergebnis schöpft die Notizen, aus denen es gemacht ist, also nicht aus: die Bausteine bleiben für einen anderen Bau verfügbar.

Ohne diese Zwischenwelt zwänge mich jedes neue Ergebnis, die Quellen wieder zu öffnen, die Verbindungen erneut herzustellen und dieselben Erkenntnisse noch einmal zu formulieren.

**Der `Kontext` bewahrt nicht nur das schon Hergestellte: er baut eine dauerhafte Fähigkeit auf, erneut herzustellen.**

##### Nicht alle Dateien entwickeln sich gleich

Der Baum wird erst dann wirklich lesbar, wenn ich weiß, wie sich jedes seiner Elemente entwickelt.

Manche Dateien werden neu geschrieben, um die beste jetzt verfügbare Lage zu zeigen:

- `state.md`;
- `handoff.md`;
- die Entwürfe in `05-outputs/_draft/`.

Andere werden nur länger, um das Vergangene zu bewahren:
- die Sitzungsquellen;
- die datierte Geschichte;
- die Synthese;
- die Reihe der Checkpoints.

Die empfangenen Dokumente bleiben unverändert, und eine durch eine andere ersetzte Notiz bleibt einsehbar.
Die `README.md`-Dateien schließlich werden aus dem Vorhandenen erzeugt: sie von Hand zu korrigieren schüfe eine zweite Fassung der Wirklichkeit, die mit der Zeit abweichen würde.

Diese Vielfalt erklärt, warum mir eine einzige große Datei nicht mehr genügte.
Man hätte von ein und demselben Text verlangen müssen, 
- die Gegenwart zu zeigen, 
- das Vergangene zu bewahren, 
- Rohes aufzunehmen, 
- Ideen festzuhalten,
- ein fertiges Ergebnis zu tragen.

##### Ein Skelett statt eines Rezepts zum Abschreiben

Dieses Skelett ist keine Dokumentation neben dem `Kontext`: es ist ein wirklicher Ordner, den ich kopiere.
- Jede Datei kommt dort mit den Abschnitten an, die sie enthalten soll, und mit ein paar Hinweisen, sodass zwei `Kontexte`, die Monate auseinander entstanden sind, dieselben Anhaltspunkte teilen.

Die Struktur bleibt dennoch anpassbar.
Ein `Kontext` kann aufnehmen: 
- eine eigene Regel, 
- ein für sein Fach typisches Ergebnis,
- eine Quelle einer bisher unbekannten Art.

Der gemeinsame Sockel bewahrt vor allem die drei Grenzen, die meine Arbeit braucht: 
- das Stabile und die Gegenwart, 
- das Rohe und das Gedeutete, 
- das Wissen und seine Darstellung.

##### Mit dem `Kontext` sprechen

Bisher habe ich Ordner und Dateien gezeigt.
Man könnte daraus schließen, dass ich jeden von ihnen öffnen muss, wissen muss, wohin zu schreiben ist, und jede Information selbst verschieben muss.
So arbeite ich nicht.

Ich spreche mit der KI:

> Öffne den `Kontext` zur Qualität der Einsatzberichte.

> Füge dieses Dokument als Quelle hinzu.

> Mach aus dieser Quelle Notizen.

> Speichere die Arbeit.

Hinter jeder dieser Bitten steht ein Ablauf, den ich einmal geschrieben habe und den die KI in jeder Sitzung wieder aufnehmen kann.
- In Claude Code und Codex trägt ein solcher wiederverwendbarer Ablauf einen Namen: einen **Skill**.

Der Skill zum Öffnen nennt zum Beispiel:
- was vor dem Beginn aufzunehmen ist;
- welche Dateien grundsätzlich zu lesen sind;
- was auf der Festplatte bleiben soll, bis die Aufgabe es verlangt;
- wie ein Problem zu melden ist;
- welche Information mir zurückzugeben ist, damit ich sofort handeln kann.

Ich muss diese Schritte nicht jedes Mal neu angeben.
- Ich bitte einfach darum, den `Kontext` zu öffnen.

Das Gespräch trägt meine Absicht im Augenblick.
- Der Skill trägt die verlässliche Art, die wiederkehrenden Handgriffe auszuführen.

Mein System hat so einige feste Verben:
- einen `Kontext` anlegen;
- ihn öffnen und die laufende Arbeit wiederfinden;
- eine Quelle hinzufügen oder eine Sitzung bewahren;
- die Quellen in Notizen verwandeln;
- den Stand der Arbeit speichern;
- seine Stimmigkeit prüfen;
- ihn archivieren, sobald er sein Ziel erreicht hat.

Nicht jeder Austausch mit der KI läuft über einen Skill.
Ich denke, frage, korrigiere und entscheide weiterhin in gewöhnlicher Sprache.

**Skills umrahmen nur die Vorgänge, die immer dieselben Schritte verlangen.**
- Sie verhindern zum Beispiel, dass eine Quelle verwandelt wird, ohne ihre Herkunft zu bewahren, oder dass eine Sitzung endet, ohne den Wiedereinstieg vorzubereiten.

Der Ablauf bleibt stabil, das Urteil wird deshalb nicht automatisch.
Zwei Modelle können eine Notiz unterschiedlich formulieren.
Sie müssen dennoch dieselben Elemente heranziehen, dieselben Grenzen achten und dieselben Prüfungen durchführen.

Skills zu teilen gibt jemandem also nicht meinen `Kontext`.
Es gibt ihm dieselbe Art, seinen eigenen anzulegen und am Leben zu halten.

Mehr werde ich über ihre Mechanik nicht sagen.

Skills sind weder eine Erfindung noch eine Besonderheit des `Kontexts`.
Claude Code und Codex bieten sie gerade dafür an, wiederverwendbare Abläufe zu beschreiben, und ihre Dokumentation erklärt besser, als ich es hier könnte, wie man sie anlegt und benutzt.

Was zum `Kontext` gehört, ist die Wahl der Fähigkeiten, die man ihm gibt: anlegen, öffnen, füttern, verwandeln, speichern, prüfen und archivieren.
Es ist auch die Reihenfolge, in der sie aufeinander folgen, und die Grenzen, die jede von ihnen achten muss.

Die Dateien bewahren, was der `Kontext` weiß.
Die Skills ordnen die Handgriffe, durch die er sich verändert.

Die Karte liegt offen.
Der Rundgang kann jetzt so beginnen, wie eine wirkliche Sitzung beginnt: indem man den `Kontext` öffnet.

> [!note] Zum Merken — das Skelett eines `Kontexts`
> Ein neuer `Kontext` kommt bereits möbliert an: sechs Bereiche, von denen jeder eine andere Frage beantwortet.
> Die Nummern geben eine Lesereihenfolge vor, keine Rangordnung des Werts.
> Was den Baum lesbar macht, ist nicht seine Form, sondern zu wissen, wie sich jede Datei entwickelt.
> Claude Code und Codex liefern den Mechanismus der Skills; der `Kontext` bestimmt die wiederkehrenden Handgriffe, ihre Reihenfolge und ihre Grenzen.

#### 5.2 — Öffnen: Mission und Gegenwart wiederfinden

Seit meiner letzten Sitzung zu den Einsatzberichten sind zwei Wochen vergangen — jenen Dokumenten, in denen ein Techniker festhält, was er nach einem Einsatz an einer Anlage vorgefunden und getan hat.
- Die Gespräche und die Notizen liegen noch da, an ihrem Platz.

Öffne ich sie aber aufs Geratewohl, verbringe ich eine halbe Stunde damit, wiederherzustellen, was ich schon wusste, und ich stelle es schlecht wieder her.
- Das Öffnen beginnt deshalb mit einem viel kleineren Kern: dem Rahmen, dem Stand und dem Wiedereinstieg.

Ich muss das alles nicht anfordern. Ich rufe den Skill zum Öffnen auf, und er spult seinen Ablauf ab.

##### Zuerst finde ich wieder, warum ich hier bin

Die erste Datei, die die KI liest (über ihren Skill zum Öffnen eines Kontexts), ist `00-frame/mission.md`.
Ihre Vorlage stellt fünf Fragen:

```markdown
# Mission

## Das Ziel
Was soll dieser `Kontext` möglich machen?

## Die zentrale Frage
Welche Frage leitet das Sortieren und das Erkunden?

## Was zum Thema gehört
Welches Material darf hereinkommen?

## Was nicht zum Thema gehört
Was wird abgelehnt, auch wenn es interessant wirkt?

## Das erwartete Ergebnis
Was will man herstellen, sofern man es schon weiß?
```

In meinem ist der Anfang so ausgefüllt:

```markdown
## Das Ziel
Verstehen, was die Qualität der Einsatzberichte verschlechtert.

## Die zentrale Frage
Wie lässt sich brauchbare Information sammeln, ohne dass das Ausfüllen abschreckt?

## Was nicht zum Thema gehört
- Eine Oberfläche wählen, bevor mehrere Quellen gegeneinandergehalten wurden.
- Von einem einzigen Gespräch aus verallgemeinern.

## Das erwartete Ergebnis
Die Produktentscheidungen und die nächsten Gespräche vorbereiten.
```

Eine Mission, die nur „die Einsatzberichte verbessern" sagte, würde mir wenig Richtung geben.
Die zentrale Frage dagegen macht manche Dokumente schon jetzt wichtiger als andere, und das Nicht-Thema hindert eine verführerische Idee daran, meine Erkundung stillschweigend in ein Lösungsvorhaben zu verwandeln.
- Das Ergebnis darf dagegen unbekannt bleiben.
- Ich schreibe diese Ungewissheit auf, statt einen verfrühten Ausgang zu erfinden: der `Kontext` weiß dann, dass er noch erkundet.

##### Die Regeln, die ich aufgestellt hatte, warten auf mich

Zwei ähnliche Missionen können verschiedene Vorsichtsmaßnahmen verlangen.
`directives.md` bewahrt diese Regeln bei der Arbeit:
- Vertraulichkeit,
- Beweisniveau,
- Wortschatz,
- Freigabe oder erwartete Form
- ...

Die Vorlage ist bewusst einfach: eine Regel, ein Datum, eine Formulierung im Befehlston.

```markdown
# Direktiven

- (2026-09-11) Jedes Gespräch vor der Aufnahme anonymisieren: den Namen des Befragten durch seine Funktion ersetzen, den Namen des Unternehmens und das Land aber bewahren.
- (2026-09-11) Unterscheiden, was die Quellen zeigen, von dem, was wir daraus ableiten.
- (2026-09-11) Keine Lösung vorschlagen, bevor die tatsächliche Praxis dokumentiert ist.
```

Eine Direktive taugt nur, wenn sie eine künftige Handlung leiten kann.
- „Vorsichtig sein" überlässt mir die ganze Auslegung von Neuem;
- „Beobachtung von Ableitung unterscheiden" gibt mir eine genaue Prüfung in dem Moment, in dem ich eine Notiz oder ein Ergebnis schreibe.

Eine Direktive ist aber nicht nur eine Anweisung, die ich beim Öffnen einer Datei wiederfinde.
Sie ist eine dauerhafte Regel, die der `Kontext` jedes Mal anwenden muss, wenn eine Handlung in ihren Bereich fällt.

Ich füge zum Beispiel die Abschrift eines neuen Gesprächs hinzu.
Ich bitte den `Kontext` einfach, sie aufzunehmen (über den dafür vorgesehenen Skill), ohne daran zu denken, darauf hinzuweisen, dass sie den Namen der befragten Person enthält.
Die Direktive zur Anonymisierung greift trotzdem während der Aufnahme: bevor der Skill die Abschrift als Quelle speichert, ersetzt er diesen Namen durch die Funktion des Befragten und bewahrt zugleich den Namen des Unternehmens und das Land.

Ich muss mich nicht genau in dem Augenblick an die Regel erinnern, in dem sie nötig wird.
Der `Kontext` erinnert sich für mich daran.

Die Direktiven hören also nicht auf zu wirken, sobald das Öffnen vorbei ist.
Sie bleiben die ganze Sitzung über anwendbar und begleiten die verschiedenen Handgriffe des `Kontexts`:
- beim Hinzufügen einer Quelle schützt die Regel zur Anonymisierung die Identität des Befragten;
- beim Anlegen einer Notiz trennt die Regel zum Beweisniveau das, was die Quelle zeigt, von dem, was wir daraus ableiten;
- beim Vorbereiten eines Ergebnisses verhindert die letzte Direktive, eine Lösung zu früh als gesichert darzustellen.

Der Skill, der eine Handlung ausführt, muss zuerst die Direktiven bestimmen, die sie betreffen, und dann prüfen, ob sein Ergebnis sie einhält.

```text
Anfrage
   ↓
anwendbare Direktiven
   ↓
Handlung des Skills
   ↓
Prüfung des Ergebnisses
```

Die Direktiven umgeben die Handlung auf diese Weise: sie binden sie vor der Ausführung und dienen danach dazu, ihr Ergebnis zu prüfen.
Sie handeln nicht allein und wissen nicht alles.
Es sind die Skills, die sie im richtigen Moment wirksam machen.

Die Mission sagt, wohin es geht.
Die Direktiven begleiten jeden Handgriff des `Kontexts`, damit ich mich nicht bei jedem Schritt an die schon beschlossenen Vorsichtsmaßnahmen erinnern muss.

##### Nicht alles verdient es, wieder geöffnet zu werden

Mein Ordner enthält Dutzende von Quellen und Notizen.
Sie alle bei jedem Öffnen zu laden würde die Prioritäten in der Masse ertränken.
`loading.md` wählt deshalb einen festen Kern:

```markdown
## Immer

- `00-frame/mission.md`
- `00-frame/directives.md`
- `01-state/state.md`
- `01-state/todo.md`
- `01-state/handoff.md`

## Auf Anfrage

- die für eine Prüfung nötigen Quellen
- die Notizen zum bearbeiteten Thema
- der aktive Entwurf
```

Alles bleibt erreichbar, aber nicht alles wird in den Kontext der KI geladen.
`loading.md` benennt die Elemente, die unentbehrlich sind, um die Mission zu verstehen, eine Anfrage zu deuten und zu handeln, ohne die schon aufgestellten Regeln zu verlieren.
- Der Rest bleibt auf der Festplatte und wird nur bei Bedarf herangezogen.
- Eine alte Quelle kann unentbehrlich sein, um eine Behauptung zu prüfen, ohne in jeder Sitzung Platz im aktiven Kontext zu belegen.

Was in `loading.md` steht, hängt vom `Kontext` ab.
- Ein Buch lädt bei jedem Öffnen seinen Aufbau, eine Produkterkundung ihre zentrale thematische Notiz.
- Das Prinzip bleibt dasselbe: 
	- mit genug Information beginnen, um handeln zu können, 
	- den Rest dann holen, wenn die Aufgabe es rechtfertigt.

##### Wo ich wirklich stand

Die Mission bleibt stabil; `01-state/state.md` dagegen ist dafür gemacht, sich zu ändern.
Sie besteht aus drei Blöcken:

```markdown
# Stand

## Was wir wissen
- Das verspätete Ausfüllen führt im ersten Gespräch zu einem Verlust an Einzelheiten.
- Manche Pflichtfelder werden im zweiten umgangen.

## Was unsicher bleibt
- Wir wissen nicht, welche Felder nach dem Ausfüllen tatsächlich wiederverwendet werden.

## Die Schulden
- Das Whitepaper wurde hinzugefügt, seine Verlässlichkeit ist aber noch einzuschätzen.
```

Der Stand erzählt nicht die ganze Geschichte und fasst nicht alle Notizen zusammen: er legt das beste Verständnis dar, über das ich von der Arbeit selbst verfüge.

`state.md` wendet sich zugleich an die KI und an den Menschen.

Für die KI ist sie ein dauerhaftes Arbeitsgedächtnis.
- Bei jedem Öffnen geladen, nennt sie ihr das Gesicherte, auf das sie zurückgreifen kann, die Unsicherheiten, die sie bewahren muss, und die Schulden, die sie nicht vergessen darf.
- Ohne sie müsste sie diesen Stand in jeder neuen Sitzung aus den Quellen und den Notizen neu aufbauen.

Für mich spielt sie die Rolle eines Armaturenbretts.
- In wenigen Zeilen kann ich prüfen, was der `Kontext` für gesichert hält, was er noch für unsicher hält und welche Arbeiten unvollständig bleiben.
- Ich kann diesen Stand dann korrigieren, wenn er nicht meinem Verständnis entspricht.

Ein paar Dutzend Zeilen genügen so der KI, um die Arbeit wieder aufzunehmen, ohne Gesichertes und Vermutungen zu verwechseln, und mir, um das Verständnis zu prüfen, auf das sie sich stützt.

`todo.md` zieht daraus die Handlungen:

```markdown
## Läuft
- T-001 — Ein Gespräch über die tatsächliche Nutzung der Pflichtfelder vorbereiten.

## Zu tun
- T-002 — Prüfen, welche Daten den Audits dienen.

## Erledigt
- T-003 — Die ersten beiden Gespräche vergleichen. — abgeschlossen am 2026-09-10
```

Ich öffne `todo.md` nicht unbedingt, um sie selbst zu ändern.
Ich kann einfach sagen:

> Füge eine Aufgabe hinzu, um zu prüfen, welche Daten den Audits dienen.

Der `Kontext` legt eine Zeile an, gibt ihr eine Kennung und setzt sie in den richtigen Abschnitt.

Eine Aufgabe kann auch während der Arbeit auftauchen.
- Bringt die Analyse einer Quelle eine nötige Prüfung hervor, schlägt mir die KI vor, sie aufzunehmen, statt sie im Gespräch verschwinden zu lassen.
- Sie macht nicht stillschweigend aus jeder Idee eine neue Pflicht: wenn eine Aufgabe die Prioritäten ändert oder zusätzliche Arbeit nach sich zieht, bleibe ich für die Entscheidung zuständig.

Ist die Arbeit getan, kann ich bitten:

> Schließe die Aufgabe T-002 ab (oder eine ungefähre Beschreibung der Aufgabe, und die KI findet den richtigen Verweis).

Der `Kontext` löscht die Zeile nicht.
Er verschiebt sie nach `Erledigt`, fügt ihr Abschlussdatum hinzu und nennt, wo es nützlich ist, das Ergebnis oder das Element, das sie als beendet gelten lässt.
- Eine erledigte Aufgabe verschwindet nicht.
- Ihr Dasein erspart mir, dieselbe Arbeit noch einmal zu tun, und erklärt mir, warum eine Spur nicht mehr verfolgt wird.

`todo.md` ist also keine ein für alle Mal geschriebene Liste.
Sie ist die Warteschlange der Handlungen des `Kontexts`: die KI sieht darin nach, was zu tun bleibt, hält sie auf dem Laufenden, wenn die Arbeit vorankommt, und bewahrt die erledigten Aufgaben, um sie nicht noch einmal zu beginnen.

##### Womit ich wieder anfange

`handoff.md` ist die letzte Datei des Kerns.
Sie wird bei jedem Speichern neu geschrieben, um auf eine sehr konkrete Lage zu antworten: jemand kommt jetzt an, ein Mensch oder eine KI, ohne irgendetwas vom vorigen Gespräch.
Was muss er wissen, um ohne Fehlgriff wieder anzufangen?

```markdown
# Wiedereinstieg

## Wo wir stehen
Drei Quellen haben eine Spannung zwischen leichtem Ausfüllen und späterer Auswertung sichtbar gemacht.

## Was vor dem Weitermachen zu wissen ist
Die beiden Gespräche beschreiben besondere Lagen, während das Whitepaper einen allgemeinen Standpunkt vertritt.
Dieses Material macht eine Spannung sichtbar, erlaubt aber noch nicht, ihr Ausmaß zu messen oder zu schließen, dass es sie in allen Organisationen gibt.

## Die nächste Handlung
Die Fragen vorbereiten, mit denen sich die tatsächlich genutzten Felder bestimmen lassen.

## Was offen geblieben ist
Wie viel Struktur die Audits brauchen, bleibt unbekannt.
```

Die nächste Handlung ist einzig und sofort ausführbar.
Eine Liste von zehn Möglichkeiten gäbe mir die Arbeit des Priorisierens zurück, die mir diese Datei gerade ersparen soll.

Der Befehl zum Öffnen nimmt also auf, was während des Schlafs des `Kontexts` abgelegt wurde, liest diesen Kern und kündigt mir dann jene Handlung an.
- Er findet seinen Zweck wieder, bevor er seine Einzelheiten wiederfindet, und meine zwei Wochen Abwesenheit kosten nur noch eine Minute Lesen.
- Die Sitzung kann jetzt neues Material aufnehmen, ohne ihre Richtung zu verlieren.

> [!note] Zum Merken — der Kern beim Öffnen
> Einen `Kontext` wieder zu öffnen heißt nicht, seinen Inhalt noch einmal zu lesen, sondern einen kleinen Kern zu laden: die Mission, die Direktiven, den Stand und den Wiedereinstieg.
> Die Mission sagt, wohin es geht, die Direktiven bestimmen die Bedingungen des Wegs.
> Ein brauchbarer Wiedereinstieg benennt eine einzige Handlung, die sich sofort ausführen lässt.

#### 5.3 — Füttern: das Material hereinlassen

Die Sitzung beginnt, und drei Dinge kommen gleichzeitig an.
- Ein Betriebsleiter schickt mir die Mitschrift eines Gesprächs,
- ein Einfall kommt mir während des Austauschs,
- eine Notiz, die ich tags zuvor liegen ließ, wartet in einer InBox (Notizverwaltung, E-Mail …).
Diese drei Materialien treten nicht auf dieselbe Weise in den `Kontext` ein, und jedes hat seinen Skill.

##### Ein Dokument kommt als fertiger Gegenstand an

Ein Dokument von außen wird mit seiner Originaldatei, seinem auswertbaren Text und einem Blatt bewahrt, das erlaubt, es zu verfolgen.

```text
03-sources/documents/
├── SRC00001-entretien-exploitation.md
├── raw/
│   └── SRC00001-entretien-exploitation.pdf
└── fulltext/
    └── SRC00001-entretien-exploitation.md
```

Das Blatt `SRC00001-entretien-exploitation.md` kann diese Form annehmen:

```markdown
---
added: 2026-09-11
kind: pdf
intention: Gespräch
raw: raw/SRC00001-entretien-exploitation.pdf
fulltext: fulltext/SRC00001-entretien-exploitation.md
extraction: ok
reliability: medium
---

# Gespräch mit der Betriebsleiterin

## Warum es hier ist

Verstehen, was die Techniker daran hindert, auswertbare Einsatzberichte zu liefern.

## Deutung — nicht analysiert

Die Leiterin beschreibt einen Gegensatz zwischen der Schnelligkeit des Ausfüllens vor Ort und dem Bedarf an strukturierten Daten für die Auswertung.

## Abdeckung

- Mobiles Ausfüllen
- Pflichtfelder
- Wiederverwendung der Daten

## Was es ergeben hat

- Nach der Analyse zu ergänzen
```

Dieses Blatt fasst das Dokument nicht unbedingt zusammen.
Es beantwortet zuerst praktische Fragen der Handhabung: 
- woher kommt es, 
- warum habe ich es hinzugefügt, 
- kann ich seinen Inhalt lesen,
- wie viel Vertrauen steht ihm zu?

Der Abschnitt `Deutung — nicht analysiert` stellt eine erste Lektüre unter Quarantäne.
Er verhindert, dass ein beim Import formulierter Eindruck sofort wie gesichertes Wissen behandelt wird.

Kommt eine Quelle als PDF, als Webseite oder in einem anderen schwer direkt auswertbaren Format an, erzeugt die Extraktion davon eine Textfassung, die Mensch und KI lesen können.
- Dieser Vorgang erzeugt noch kein Wissen: er macht das Material lediglich zugänglich, ohne das Originaldokument zu verändern.

Die Umwandlung kommt danach.
- Der extrahierte Text wird analysiert, damit atomare Notizen, thematische Notizen, Glossarbegriffe oder Entscheidungen zum Vorschein kommen.
- Diese Notizen speisen die *Welt der Ideen*, in der das Material der Quellen zu einer Menge wiederverwendbarer Wissensbausteine wird.

Das Maß an Verlässlichkeit ist kein Urteil über die hinzugefügten Quellen.
- Es sagt schlicht, wie dieses Material zu verwenden ist: einzelner Erfahrungsbericht, geprüfte Angabe, vertragliches Dokument oder noch zu bestätigende Vermutung.

Nicht alles nützliche Material liegt schon in einem Dokument vor.
Ein Teil steckt in meiner Erfahrung, meinen Erinnerungen, meinen Beobachtungen oder den Unterscheidungen, die ich beim Arbeiten treffe.

Wenn ich sie während einer Sitzung im Austausch mit der KI ausspreche, treten auch sie in den `Kontext` ein.
- Sie werden nicht automatisch zu gesicherten Tatsachen
- Sie bewahren ihre Herkunft und lassen sich später anderen Quellen gegenüberstellen.

Material hinzuzufügen heißt also ebenso, ein Dokument aufzunehmen, wie das zu bewahren, was die Person, der der `Kontext` gehört, in das Gespräch einbringt.

##### Das Wissen der Person tritt über die Sitzung ein

Eine Sitzung ist kein ein für alle Mal geliefertes Dokument.
Sie baut sich im Lauf des Austauschs auf.
Sie wird in `03-sources/sessions/SESSION-2026-09-12.md` festgehalten, was diese Form annehmen kann:

```markdown
# Sitzung vom 12. September 2026

## 09:41 — KI

Verbessern die Pflichtfelder wirklich die Qualität, oder verschieben sie den Aufwand nur auf den Techniker?

## 09:42 — Autor

In den Gesprächen sichern die Pflichtfelder vor allem, dass überhaupt ein Wert eingetragen wurde.
Sie sichern weder seine Genauigkeit noch seinen Nutzen.
Wenn der Techniker den späteren Zweck eines Feldes nicht versteht, füllt er es so schnell wie möglich aus, um weiterzukommen.
Der Zwang verbessert also die scheinbare Vollständigkeit, kann den Aufwand aber verschieben, ohne die wirklich auswertbare Information zu verbessern.
...
```

Nicht alles, was die KI sagt, muss bewahrt werden.
Eine Frage, ein Einwand oder eine Umformulierung, die die Arbeit verändert, verdient es dagegen sehr wohl.
- Mein Wort und das der KI bleiben getrennt.
- So kann ich die Herkunft einer Idee wiederfinden und meine Absicht von einem Vorschlag des Systems unterscheiden.

Eine Sitzung darf ungeordnet sein.
- Ihre Aufgabe ist, die wirkliche Bewegung des Denkens einzufangen, nicht eine tadellose Zusammenfassung vorzulegen.

##### Der Briefkasten spricht mit dem `Kontext`, während er geschlossen ist

Ein Einfall kommt mir außerhalb einer Sitzung, im Zug oder mitten in einer Besprechung und ohne Internetzugang.
- Er tritt dann in den Briefkasten ein.
- Dieser Briefkasten ist die Datei `offline.md`, die in der Wurzel des `Kontexts` liegt.
- Es genügt, in diese Markdown-Datei zu schreiben.

Sie kann diese Form annehmen:

```markdown

Fragen, ob die Techniker die Pflichtfelder mit allgemeinen Werten umgehen.
```

Beim nächsten Öffnen des Kontexts wird diese Notiz gelesen, mit der laufenden Arbeit verglichen und dann an der richtigen Stelle aufgenommen.
Sie kann zu einer Aufgabe, einer Gesprächsfrage oder einer Notiz werden — oder verschwinden, wenn sie nicht mehr zur Sache gehört.

##### Hinzufügen heißt noch nicht verstehen

Ist dieses Material einmal eingetreten, enthält mein Baum mehrere Quellen und die Spur der laufenden Sitzung.

```text
03-sources/
├── documents/
│   ├── SRC00001-entretien-exploitation.md
│   ├── SRC00002-entretien-exploitation.md
│   └── SRC00003-livre-blanc-donnees-intervention.md
└── sessions/
    └── SESSION-2026-09-11.md
```

Diese Dateien beweisen, dass das Material verfügbar ist.
Sie beweisen nicht, dass es verstanden wurde.

Die Datei `03-sources/ingestion-log.md` unterscheidet die beiden Vorgänge.
Für jede Quelle gibt sie an, ob die Analyse vollständig, teilweise oder zu überarbeiten ist, mit einem Fingerabdruck des Inhalts und ein paar Notizen zur Verarbeitung.

Diese Unterscheidung wird wesentlich, wenn ein Dokument ersetzt wird, eine Extraktion sich ändert oder eine Sitzung abbricht.
Der `Kontext` kann die Analyse dann wieder aufnehmen, ohne so zu tun, als wüsste er alles.

Das Material ist eingetreten.
Mir bleibt, es in Ideen zu verwandeln, die genau genug sind, um verbunden, besprochen und wiederverwendet zu werden.

> [!note] Zum Merken — die Quelle
> Ein Dokument, ein Wort aus der Sitzung und eine Notiz von außerhalb treten durch drei verschiedene Türen ein und behalten jeweils ihre ursprüngliche Form.
> Eine Quelle bewahrt das Material und den Beleg, nie die Deutung, die man daraus ziehen wird.
> Hinzufügen heißt nicht verstehen: das Aufnahmeprotokoll unterscheidet, was vorhanden ist, von dem, was aufgenommen wurde.

#### 5.4 — Verwandeln: von den Quellen zu den Ideen

Jetzt habe ich drei Quellen vor mir.
- Zwei Gespräche beschreiben die Reibung, die die Formulare verursachen,
- Ein Whitepaper vertritt die Notwendigkeit strukturierter Daten.

Die Versuchung wäre, sofort zu entscheiden und zu schreiben, dass Pflichtfelder der Qualität schaden.
Das hieße zu schnell vorgehen: der `Kontext` muss diese Beiträge bewahren, ohne sie in einer einzigen Schlussfolgerung aufgehen zu lassen.

Ich rufe also den Skill auf, der die Notizen anlegt und fortschreibt: er liest, was noch nicht verarbeitet wurde, und zieht Ideen daraus.

##### Ich ziehe eine Idee heraus, die allein steht

Eine Quelle enthält selten eine schon gebrauchsfertige Idee.
- Ein Gespräch mischt Tatsachen, Beispiele, Meinungen, Zögern und Einzelheiten, die zur erzählten Lage gehören.
- Es zu verwandeln heißt nicht, alles zusammenzufassen, sondern die Ideen herauszuziehen.

Der Weg besteht aus drei Schritten:

```text
Bericht          „Wenn das Formular zu lang ist, tragen manche Techniker 
      |            einen allgemeinen Wert ein, um fertig zu werden."
      ↓
Beobachtung       Allgemeine Werte werden manchmal verwendet, um 
      |              das Ausfüllen zu beschleunigen.
      ↓
Feste Idee       Ein zu anspruchsvolles Ausfüllen kann die 
                                  Einsatzberichte ärmer machen.
```

Eine starke Idee ist weder eine spektakuläre Formel noch eine endgültige Wahrheit.
- Sie hat einen klaren und festen Schwerpunkt, 
- Lässt sich außerhalb des Textes verstehen, der sie hervorgebracht hat
- Bleibt so umrissen, dass sie bestätigt, differenziert oder widerlegt werden kann.
- Sie bewahrt zudem ihre Herkunft und ihre Grenzen, damit ein einzelner Bericht nicht zur allgemeinen Regel wird.

Die KI liest die Quelle im Licht der Mission und der Direktiven und hält sie dann gegen die schon vorhandenen Notizen.
Sie legt eine neue Notiz an, wenn die Idee neu ist; sonst reichert sie die vorhandene um die zusätzliche Nuance oder Grenze an.

Sie tut diese Arbeit, ohne mich jede Formulierung bestätigen zu lassen.
Ich kann die Notizen danach durchsehen und verbessern.
- Kommt während der Sitzung eine Mehrdeutigkeit auf, fragt sie mich; 
- Entdeckt sie später einen Widerspruch, den sie nicht auflösen kann, bewahrt sie ihn, statt an meiner Stelle zu entscheiden.

```text
04-notes/
└── atomic/
    └── ATO00001-la-contrainte-de-saisie-peut-appauvrir-les-comptes-rendus.md
```

```markdown
---
id: ATO00001
status: active
sources: [SRC00001, SRC00002]
---

# Ein zu anspruchsvolles Ausfüllen kann die Einsatzberichte ärmer machen

## Hauptidee

Wenn das Formular den Einsatz verlangsamt, tragen die Techniker womöglich allgemeine Werte ein oder kürzen ihre Beschreibung auf das erwartete Mindestmaß.

## Warum das wichtig ist

Eine formal strukturierte Angabe kann sauber wirken und die Wirklichkeit vor Ort trotzdem schlechter beschreiben.

## Nuancen und Grenzen

Die beiden Gespräche erlauben nicht, die Häufigkeit des Phänomens zu messen.

## Herkunft / Beleg

- SRC00001: Beispiele für allgemeine Werte, die verwendet werden, um schneller fertig zu sein.
- SRC00002: nach dem Hinzufügen von Pflichtfeldern beobachteter Rückgang der Genauigkeit.

## Verbindungen

- Gegensatz zu ATO00002.
```

Der Titel trägt eine Aussage, nicht bloß ein Thema.
Die Notiz bleibt verständlich, ohne dass ich die Dokumente wieder öffnen müsste, aus denen sie stammt, und bewahrt zugleich die Verbindungen, mit denen ich ihre Herkunft prüfen kann.

Eine atomare Notiz ist beim ersten Wurf nicht festgeschrieben.
- Sie kann eine Nuance, einen neuen Beleg oder eine Beziehung gewinnen, ohne ihre Identität zu verlieren.

Das Whitepaper bringt eine zweite Notiz hervor: strukturierte Daten sind nötig, um zu vergleichen, zusammenzufassen und zu automatisieren.
- Diese Idee bleibt von der ersten getrennt, weil sie etwas anderes behauptet.

##### Ich weigere mich, zu früh zu entscheiden

Die beiden Ideen scheinen einander zu widersprechen, und ich habe noch nicht genug Material, um zwischen ihnen zu entscheiden.
Ich eröffne also einen Widerspruch.

```markdown
## C-001 — Strukturieren, ohne das Ausfüllen zu verschlechtern

- Auf der einen Seite: vorgeschriebene Felder können die Beschreibungen aus dem Feld ärmer machen.
- Auf der anderen: die Auswertung im großen Maßstab verlangt vergleichbare Daten.
- Worum es geht: bestimmen, welche Angaben schon beim Ausfüllen strukturiert sein müssen und welche es später werden können.
- Eröffnet am: 2026-09-11
```

Der Widerspruch bewahrt mich vor zwei spiegelbildlichen Fehlern: zu früh eine Seite zu wählen oder die Uneinigkeit in einer vagen Formulierung zu glätten, die niemanden stört.
- Er bleibt offen, bis eine Entscheidung, eine neue Quelle oder eine Umformulierung ihn auflöst.

Nicht jede Ungewissheit verdient diese Behandlung.
- Ich behalte sie den Spannungen vor, die wirklich auf dem weiteren Gedankengang oder auf der Güte einer Entscheidung lasten.

##### Ich verbinde, was diese Ideen gemeinsam sagen

Während der Aufnahme legt die KI nicht nur atomare Notizen an.
- Sie untersucht auch die Beziehungen zwischen den herausgezogenen Ideen und den schon vorhandenen Notizen.
- Bilden mehrere von ihnen ein Ganzes, das sich nicht auf eine einzige Aussage zurückführen lässt, legt sie im selben Vorgang eine thematische Notiz an und setzt die Verbindungen, die sie zusammenhalten.

Ich muss keinen zweiten Befehl geben.
- Das Anlegen der atomaren Notizen, ihr Zusammenführen und das mögliche Auftauchen einer thematischen Notiz gehören zu ein und derselben Aufnahme.

```markdown
---
id: THM00001
status: active
sources: [ATO00001, ATO00002]
---

# Die Qualität hängt am Ausfüllen und an der Auswertung

## Blickwinkel

Die Qualität eines Einsatzberichts lässt sich nicht allein an der Zahl der ausgefüllten Felder beurteilen.

## Zusammenfassung

Das System muss genug Struktur bekommen, um die Daten auszuwerten, ohne das Ausfüllen künstlich oder teuer zu machen.

## Verbundene Notizen

- ATO00001 — Ein anspruchsvolles Ausfüllen kann die Einsatzberichte ärmer machen.
- ATO00002 — Strukturierte Daten sind für die Auswertung nötig.

## Spannungen

- C-001 — Strukturieren, ohne das Ausfüllen zu verschlechtern.
```

Die thematische Notiz stellt nicht nur Zusammenfassungen nebeneinander.
Sie schlägt eine Lesart ihrer Beziehungen vor und zeigt, was offen bleibt.

##### Mir fällt auf, dass ein Wort nicht für alle dasselbe bedeutet

Ein Teil der Uneinigkeit kommt manchmal vom Wortschatz.
Das Glossar legt dann den in diesem `Kontext` gewählten Sinn fest.

```markdown
## Strukturierte Angabe

Information, die in einer ausdrücklichen Form festgehalten wird, die ihren Vergleich oder ihre automatische Verarbeitung erlaubt.

Nicht zu verwechseln mit: einem Feld, das der Benutzer beim Einsatz zwingend ausfüllen muss.

Beispiele: Art der Störung, Stillstandsdauer, betroffenes Gerät.
```

Diese lokale Definition soll nicht allgemeingültig werden.
- Sie verhindert schlicht, dass zwei Notizen oder zwei Menschen mit demselben Wort von verschiedenen Dingen sprechen.

##### Bausteine, die gegenüber dem Ergebnis neutral sind

Eine Notiz gehört zur *Welt der Ideen*, solange sie ein Wissen festhalten will, statt bei einem Publikum eine Wirkung zu erzielen.
- Sie darf also nicht zu früh zum Aufhänger eines Artikels, zu einer Folie, zu einem Verkaufsargument oder zu einem Stück Spezifikation werden.

Diese Neutralität heißt nicht, dass die Notiz vage bleibt.
- Im Gegenteil: ihr Titel behauptet eine genaue Aussage, ihr Inhalt legt die Nuancen dar, und ihre Verbindungen erlauben, ihr Fundament zu prüfen.
- Neutral bleibt ihre Form: sie ist nicht darauf angelegt, einem einzigen Ergebnis zu dienen.

`ATO00001` kann so zu einer Frage nach den Umgehungen im Gesprächsleitfaden werden, zu einem Risiko in der Rahmennotiz oder zu einem Beispiel in der Präsentation für das Team.
`ATO00002` kann eine Frage nach der Nutzung der Daten stützen, eine Produktanforderung begründen oder dem Team erklären, warum freier Text nicht immer genügt.

Die thematische Notiz verschmilzt diese Bausteine nicht zu einem endgültigen Text.
- Sie nennt, was sie zusammen verstehen lassen, und bewahrt die Spannung, die je nach Ergebnis anders zu behandeln sein wird.

Diese Zwischenschicht erspart es, die Analyse für jede Produktion neu zu beginnen.
- Die Quellen bleiben die Belege, 
- die Notizen werden zu abrufbarem Wissen,
- jedes Ergebnis setzt sich aus ihnen nach seinem eigenen Bedarf zusammen.

##### Ich kann von jeder Idee zu ihrem Beleg zurückgehen

An diesem Punkt lassen sich die Beziehungen so darstellen:

```text
SRC00001 ─┐
          ├──> ATO00001 ──┐
SRC00002 ─┘               │
                          ├──> THM00001
SRC00003 ───> ATO00002 ───┘
```

Die benannten Verbindungen lassen mich eine Quelle, die eine Idee bestätigt, von einer unterscheiden, die sie differenziert oder ihr widerspricht.
- Ein Maß an Vertrauen macht sichtbar, was auf mehreren Beobachtungen beruht und was Vermutung bleibt.

Die Abdeckung der Aufnahme zeigt, welche Quellen wirklich zu den Notizen beigetragen haben.
Sie hindert mich daran, ein Dokument für aufgenommen zu halten, nur weil es im Ordner liegt.

Diese Notizen sind nicht für ein bestimmtes Ergebnis geschrieben.
- Sie bilden ein gemeinsames Wissen, das mehrere Ergebnisse speisen kann, ohne abgeschrieben oder in einem von ihnen eingesperrt zu werden.

**Die *Welt der Ideen* ist genau dieses wiederverwendbare Kapital: eine Menge von Bausteinen, fest genug, um wiedergefunden zu werden, und eigenständig genug, um neu zusammengesetzt zu werden.**

> [!note] Zum Merken — die atomare Notiz
> Eine festgehaltene Idee trägt eine Aussage und kein Thema und lässt sich verstehen, ohne das Dokument wieder zu öffnen, aus dem sie stammt.
> Ein Widerspruch wird bewahrt, solange er auf dem Gedankengang lastet, statt zu früh entschieden oder geglättet zu werden.
> Jede Notiz behält die Verbindung zu ihren Quellen, was erlaubt, von der Idee zu ihrem Beleg zurückzugehen.

#### 5.5 — Herstellen und entscheiden

Meine thematische Notiz hat eine genaue Frage hervorgebracht: welche Angaben müssen am Ende des Einsatzes eingetragen werden, und welche lassen sich später ergänzen?

Drei Menschen erwarten jetzt etwas von mir.
- Ein Techniker, den ich befragen muss, 
- ein Gremium, das entscheiden muss, 
- ein Team, dem ich etwas erklären muss.

Ich werde keine drei Untersuchungen führen: ich werde dreimal auf dieselben Notizen zurückgreifen.

Das ist der einzige Moment der Sitzung, in dem mir kein Skill hilft: ein Ergebnis herzustellen ist Schreibarbeit, kein Handgriff, der sich wiederholt.

##### Ich greife dreimal auf denselben Bestand zurück

Der Weg von den Notizen zu den Ergebnissen ist keine Kopie.
Jedes Ergebnis wählt die Bausteine, die ihm nützen, ordnet sie und formuliert sie für seinen Empfänger neu.

| Gemeinsamer Baustein | Gesprächsleitfaden | Rahmennotiz | Präsentation fürs Team |
|---|---|---|---|
| `ATO00001` — Ein zu anspruchsvolles Ausfüllen kann die Einsatzberichte ärmer machen | Fragen, welche Felder umgangen werden und wie | Das Risiko des Qualitätsverlusts beschreiben | Ein Beispiel für Reibung im Feld zeigen |
| `ATO00002` — Strukturierte Daten sind für die Auswertung nötig | Fragen, welche Daten wirklich wiederverwendet werden | Den Bedarf an Vergleich und Automatisierung belegen | Den erwarteten Nutzen fürs Team erklären |
| `THM00001` — Die Qualität hängt am Ausfüllen und an der Auswertung | Das Gespräch um die beiden Anforderungen herum aufbauen | Benennen, was auf dem Spiel steht, und die Entscheidungskriterien | Den roten Faden der Erzählung bauen |
| `C-001` — Strukturieren, ohne das Ausfüllen zu verschlechtern | Die Spannung in zu prüfende Fragen verwandeln | Sie als zu lösendes Problem bewahren | Sie sichtbar machen, ohne eine verfrühte Lösung anzukündigen |

Derselbe Bestand bringt so drei Zusammenstellungen hervor, ohne dass ein Ergebnis alles übernähme oder die Notizen ersetzte, die es speisen.

Vor allem erlaubt mir diese Trennung, das Wissen nur ein einziges Mal zu berichtigen.
- Differenziert eine neue Quelle `ATO00001`, gehen meine nächsten Ergebnisse von diesem angereicherten Baustein aus, statt eine alte Formulierung zu wiederholen, die über mehrere Dokumente verstreut ist.

##### Ich beginne mit dem Dringendsten: dem nächsten Gespräch

Mein erster Bedarf ist, das Gespräch mit einem Techniker vorzubereiten.
Das Ergebnis beginnt im Raum der Entwürfe.

```text
05-outputs/
└── _draft/
    └── questions-prochain-entretien.md
```

```markdown
# Fragen für das nächste Gespräch

1. Welche Felder halten Sie während eines Einsatzes am stärksten auf?
2. Was tragen Sie ein, wenn die verlangte Angabe nicht verfügbar ist?
3. Welche Angaben könnten Sie nach dem Einsatz nachtragen?
4. Welche Daten müssen sofort stimmen, damit sie für die Auswertung nützen?
```

Die Notizen wollen eine wiederverwendbare Idee bewahren.
Das Ergebnis dagegen wählt einen Empfänger, eine Form und eine erwartete Handlung.

Einmal durchgesehen und freigegeben, verlässt die Datei `_draft/` und wandert direkt nach `05-outputs/`.
Der Umzug zeigt einen Reifegrad an, keinen Unterschied der Dokumentgattung.

Bisher habe ich nur hergestellt: ich habe für drei Publikumsgruppen in Form gebracht, was ich schon wusste.
Der Rest dieses Kapitels gehört zu einem ganz anderen Handgriff.
Irgendwann muss man aufhören wiederzugeben und entscheiden — und was ich entscheide, muss sich in sechs Monaten wiederfinden lassen.

##### Das Decision Record bewahrt die Wahl, die das Ergebnis prägt

„Einen Techniker befragen, bevor eine Spezifikation geschrieben wird" ist keine Entscheidung darüber, was geliefert wird.
- Ist dieses Gespräch schlicht die nächste Handlung, gehört es in `01-state/todo.md`.
- Müssen alle Erkundungsarbeiten diese Regel einhalten, wird sie zu einer Direktive in `00-frame/directives.md`.
In beiden Fällen rechtfertigt sie kein Decision Record.

Das Decision Record entsteht, wenn die Arbeit mehrere mögliche Richtungen hervorbringt und diejenige zu wählen ist, die das Produkt, den Text, die Methode oder ein anderes Ergebnis des `Kontexts` prägen wird.
Es bewahrt dann, was zu entwerfen oder zu liefern beschlossen wurde, die verworfenen Alternativen, die Gründe der Wahl und die in Kauf genommenen Folgen.

In meinem Beispiel geht es bei der Entscheidung also nicht um die Organisation der Gespräche.
Es geht um eine fachliche Entscheidung: 
- sämtliche Angaben am Ende des Einsatzes verlangen, 
- nur freien Text bewahren, 
- oder zulassen, dass der Bericht in einem zweiten Schritt ergänzt wird.

Ein brauchbares Decision Record überlässt den Kern der Wahl nicht der Person, die sie umsetzen wird.
Drei Menschen, die es lesen, müssen denselben Geltungsbereich, dieselben erwarteten Verhaltensweisen und dieselben Grenzen verstehen.
Technische Einzelheiten ohne prägende Wirkung dürfen offen bleiben, aber keine von ihnen darf die Entscheidung stillschweigend verändern können.

```text
04-notes/
└── decision-records/
    └── DRE00001-limiter-la-cloture-a-quatre-informations.md
```

So sieht das aus, wenn es geschrieben ist.
Die Vorlage ist lang, weil sie den ganzen Gedankengang bewahrt, der die Entscheidung verständlich und überprüfbar macht — wer mit Decision Records schon vertraut ist, kann direkt zum Kommentar danach springen.

```markdown
---
uuid: 0d5efbe2-1eac-4ad7-94c1-29f68adcf001
id: DRE00001
created: 2026-09-11
updated: 2026-09-11
status: accepted
decided_by: Produktteam
decided_on: 2026-09-11
supersedes: null
superseded_by: null
sources: [ATO00001, ATO00002, THM00001]
---

# Den Abschluss eines Einsatzes auf vier Pflichtangaben begrenzen

## Entscheidung

Damit ein Einsatz als abgeschlossen gilt, müssen genau vier Angaben vorliegen:

1. Das betroffene Gerät, entweder schon auf dem Einsatzschein vermerkt oder beim Abschluss eingetragen.
2. Datum und Uhrzeit des tatsächlichen Einsatzendes.
3. Der Zustand des Geräts am Ende des Einsatzes: wieder in Betrieb, im eingeschränkten Betrieb belassen oder außer Betrieb gelassen.
4. Eine nicht leere Zusammenfassung der ausgeführten Arbeiten oder des Grundes, warum das Gerät nicht wieder in Betrieb genommen werden konnte.

Keine weitere Angabe bedingt den Abschluss.

Nach dem Abschluss kann der Bericht um die Art der Störung, ihre festgestellte Ursache, die Art der ausgeführten Arbeiten, die ersetzten Teile und die Ausfalldauer des Geräts ergänzt werden, ohne den Abschluss des Einsatzes in Frage zu stellen.
Der Techniker kann diese ergänzenden Angaben eintragen, der Betriebsleiter muss sie aber binnen vierundzwanzig Stunden ergänzen oder bestätigen.

Ein noch unvollständiger Bericht bleibt einsehbar.
Er wird als noch zu ergänzen gekennzeichnet, und nach vierundzwanzig Stunden wird der Betriebsleiter benachrichtigt.

## Kontext

Die Techniker müssen ihre Arbeit im Feld abschließen können, ohne ein vollständiges Analyseformular durchzugehen.
Die Betriebsabteilung braucht gleichwohl vergleichbare Angaben, um Störungen, ihre Ursachen, die ausgeführten Arbeiten, die ersetzten Teile und die Ausfalldauern zu analysieren.

## Annahmen

- Der Einsatzschein weist das Gerät in der Regel schon vor Beginn der Arbeiten aus.
- Der Techniker kennt den Zustand des Geräts und kann die ausgeführten Arbeiten beim Abschluss kurz beschreiben.
- Der Betriebsleiter hat die Zeit und die Angaben, die nötig sind, um den vollständigen Bericht binnen vierundzwanzig Stunden zu bestätigen.

## Alternativen

- Alle neun Angaben beim Abschluss verlangen.
- Nur eine freie Zusammenfassung bewahren und die Einsatzangaben nachträglich automatisch daraus ziehen.
- Alle Angaben freistellen und die Qualität erst im Nachhinein prüfen.

## Gründe

Die vier sofortigen Angaben genügen, um den Einsatz zu bestimmen, sein Ende zu datieren, den Zustand des Geräts zu kennen und die ausgeführten Arbeiten zu verstehen.
Die fünf Analyseangaben bleiben nötig, dürfen den Techniker aber nicht daran hindern, seine Arbeit im Feld zu beenden.
Der zweite Schritt weist dem Betriebsleiter ausdrücklich die Verantwortung zu, den Bericht zu ergänzen oder zu bestätigen.

## Grundlage

- ATO00001 beschreibt die Umgehungen, die aus einem zu stark eingezwängten Ausfüllen folgen.
- ATO00002 belegt den Bedarf an vergleichbaren Daten.
- THM00001 verbindet die beiden Anforderungen.

## Folgen

### Positiv

- Der Abschluss verlangt nur vier sofort bekannte Angaben.
- Die für die Analyse der Einsätze nötigen Angaben bleiben verfügbar, nachdem der Bericht ergänzt wurde.
- Die Verantwortung für fehlende Daten ist sichtbar.

### Abwägungen

- Die Kennzahlen zu den Einsätzen können in den vierundzwanzig Stunden nach einem Einsatz unvollständig bleiben.
- Der Betriebsleiter bekommt zusätzliche Bestätigungsarbeit.

### Risiken

- Unvollständige Berichte können sich anhäufen.
- Nachträglich eingetragene Angaben können die im Feld vorgefundene Lage weniger treu wiedergeben.

## Kriterien der Einhaltung

- Ein Einsatz kann nicht abgeschlossen werden, wenn eine der vier sofortigen Angaben fehlt.
- Ein Einsatz kann ohne jede der fünf ergänzenden Angaben abgeschlossen werden.
- Die ergänzenden Angaben können geändert werden, ohne den Abschlusszustand des Einsatzes zu ändern.
- Der Bericht wird in allen Verwendungen als „noch zu ergänzen" oder „vollständig und bestätigt" dargestellt.
- Der Betriebsleiter wird vierundzwanzig Stunden nach dem Abschluss benachrichtigt, wenn der Bericht nicht vollständig und bestätigt ist.

## Verbundene Entscheidungen

- Löst C-001 — Strukturieren, ohne das Ausfüllen zu verschlechtern.

## Quellen

- SRC00001
- SRC00002
- SRC00003
```

Der Status `accepted` zeigt hier an, dass die Entscheidung bestätigt und genau genug ist, um die Umsetzung zu leiten.
- Solange die erwarteten Angaben, die Verantwortlichkeiten oder die Kriterien der Einhaltung unbestimmt bleiben, muss das Decision Record den Status `proposed` behalten.
- Einmal angenommen, wird es als geschichtliche Spur festgeschrieben und ändert sich nicht mehr stillschweigend.

Wird es durch eine neue Entscheidung ersetzt, bleibt das alte Decision Record einsehbar, und die beiden Dateien sind durch `supersedes` und `superseded_by` verbunden.

Diese Kontinuität bewahrt die vollständige Abfolge der Entscheidungen: was beschlossen worden war, auf welcher Grundlage, und welches Element dann dazu führte, anders zu wählen.

Sechs Monate später finde ich also nicht nur die geltende Regel wieder.
Ich kann verstehen, warum eine erste Richtung richtig erschienen war, was sie unzureichend machte und wie die nächste Entscheidung entstand.

Ohne diese Abfolge sieht eine Reihe von Entscheidungen am Ende wie Widersprüchlichkeit aus.
Mit ihr wird sie wieder zur verständlichen Geschichte eines Produkts, das sich verändert.
- Die Alternativen zeigen, was verworfen wurde.
- Die Abwägungen machen sichtbar, was geopfert wurde.
- Die Grundlage verbindet die Entscheidung mit dem Wissen und den Belegen, die sie stützen.

##### Herstellen schöpft nicht aus, was ich weiß

Der Gesprächsleitfaden, die thematische Notiz und das Decision Record behandeln dasselbe Problem, ohne sich zu doppeln, weil sie drei verschiedene Aufgaben erfüllen.
- Die Notiz bewahrt, was der `Kontext` zu wissen glaubt.
- Die Entscheidung bewahrt eine Wahl und ihre Gründe
- Der Leitfaden verwandelt dieses Wissen bei einem bestimmten Empfänger in Handlung.

Ein anderes Ergebnis wird dasselbe gemeinsame Wissen in anderer Form aufgreifen können.
**Herstellen entleert den `Kontext` also nicht: es zeigt, was seine Substanz zu tun erlaubt.**

Mir bleibt, den erreichten Stand festzuhalten, damit die nächste Sitzung wieder anfangen kann, ohne den zurückgelegten Weg neu zusammenzusetzen.

> [!note] Zum Merken — das Decision Record
> Dieselben Notizen speisen mehrere Ergebnisse, und kein Ergebnis verbraucht das Wissen, das es verwendet.
> Ein Decision Record bewahrt eine Entscheidung, die prägt, was entworfen oder geliefert wird, nicht eine auszuführende Handlung.
> Es bewahrt, was verworfen und was geopfert wurde, damit die Wahl überprüfbar bleibt.

#### 5.6 — Speichern und wieder einsteigen

Das Decision Record ist gerade angenommen worden, und in drei Minuten beginnt eine Besprechung.
Ich habe weder die Untersuchung beendet noch auch nur einen Abschnitt, der nach einem Ende aussähe.

Das ist der Normalfall: eine andere Aufgabe verlangt meine Aufmerksamkeit, der Rechner muss neu starten, ich wechsle den Computer, oder das Kontextfenster der KI wird zu voll.
- Speichern antwortet also nicht auf ein Bedürfnis der Arbeit selbst, etwa „die Untersuchung ist fertig".
- Es ist eine technische Absicherung: der Stand des `Kontexts` muss die Sitzung überleben, in der er entstanden ist.

Ich muss jetzt abbrechen, später wieder öffnen und die Arbeit genau dort wiederfinden können, wo ich sie gelassen habe.

Ein Skill übernimmt das, und er muss in wenigen Sekunden erledigt sein: ein teures Speichern wird nicht angestoßen, wenn man in Eile ist — also gerade dann, wenn es am meisten nützt.

##### Die KI hält fest, was man in diesem Augenblick weiß

Die Datei `01-state/state.md` fasst zusammen, was stabil genug ist, um das Weitere auszurichten.

```text
contexte-qualite-comptes-rendus/
└── 01-state/
    └── state.md
```

Im Augenblick des Speicherns kann sie diese Form annehmen:

```markdown
# Aktueller Stand

## Gesichertes Wissen

- Ein zu anspruchsvolles Ausfüllen kann die Einsatzberichte ärmer machen.
- Die Auswertung im großen Maßstab verlangt gleichwohl strukturierte Daten.

## Getroffene Entscheidung

- Der Abschluss verlangt das betroffene Gerät, Datum und Uhrzeit des Endes, den Zustand des Geräts und eine Zusammenfassung der ausgeführten Arbeiten.
- Art und Ursache der Störung, Art der Arbeiten, ersetzte Teile und Ausfalldauer werden nach dem Abschluss ergänzt und binnen vierundzwanzig Stunden vom Betriebsleiter bestätigt.

## Wichtigste Ungewissheit

- Messen, ob diese Trennung die Abschlusszeit wirklich verkürzt, ohne die Güte der Daten zu verschlechtern.

## Wissensschuld

- Noch kein Pilotversuch hat die Abschlusszeit oder den Anteil der nach vierundzwanzig Stunden vollständigen Berichte gemessen.
```

- Eine erledigte Aufgabe kann aus der Todo-Liste verschwinden.
- Ein ungelöster Widerspruch bleibt im Stand sichtbar.

Die Synthese enthält nur, was die Arbeit hinreichend gefestigt hat.
Der Stand wird neu geschrieben, um die Gegenwart zu beschreiben, während die Synthese nach und nach wächst, um das erworbene Verständnis zu bewahren.

##### Ich bereite eine einzige Handlung für mein künftiges Ich vor

Die Datei für den Wiedereinstieg erzählt nicht die ganze Geschichte: sie bereitet den nächsten nützlichen Handgriff vor.

```text
contexte-qualite-comptes-rendus/
└── 01-state/
    └── handoff.md
```

Die Datei `01-state/handoff.md` kann diese Form annehmen:

```markdown
# Wiedereinstieg

## Gegenwärtiger Stand

DRE00001 ist angenommen und C-001 ist gelöst.
Die vier Angaben für den Abschluss und die fünf ergänzenden Angaben stehen fest.

## Worauf zu achten ist

Keine Pflichtangabe beim Abschluss hinzufügen, ohne ein neues Decision Record zu eröffnen, das DRE00001 ersetzt.

## Nächste Handlung

Mit der Umsetzung von DRE00001 beginnen.

## Offen

- Die Bezeichnungen festlegen, die den Technikern für die drei möglichen Zustände des Geräts nach dem Einsatz angezeigt werden.
- Die Messung der Abschlusszeit und des Anteils der nach vierundzwanzig Stunden vollständigen Berichte vorbereiten.
```

Ein brauchbarer Wiedereinstieg benennt eine einzige nächste Handlung.
Eine Liste von zehn Möglichkeiten zwänge die nächste Sitzung, die Entscheidungsarbeit zu wiederholen, die ich gerade getan habe.

##### Ich bewahre eine Spur, um meine Wiedereinstiege zu vergleichen

Die Datei `01-state/checkpoints.md` bewahrt eine Folge kompakter Momentaufnahmen der Lage.

```text
contexte-qualite-comptes-rendus/
└── 01-state/
    └── checkpoints.md
```

Die Datei kann diese Form annehmen:

```markdown
## 2026-09-11

- Quellen: 3
- Atomare Notizen: 2
- Thematische Notizen: 1
- Offene Widersprüche: 0
- Angenommene Decision Records: 1
- Nächste Handlung: mit der Umsetzung von DRE00001 beginnen.

## 2026-09-04

- Quellen: 1
- Atomare Notizen: 1
- Thematische Notizen: 0
- Offene Widersprüche: 0
- Nächste Handlung: den Standpunkt des Betriebs einholen.
```

Diese Aufnahmen zeigen mir die Entwicklung des `Kontexts`, ohne dass ich alle Dateien vergleichen müsste.
Sie lassen mich auch einen Stillstand erkennen oder eine Schuld, die wächst, ohne dass ich es merke.

##### Die KI hält fest, was geschehen ist, nicht was sie davon hält

Die Geschichte zeichnet die wichtigen Ereignisse auf, ohne jeden Austausch nachbilden zu wollen.
In meinem Beispiel werden die Ereignisse des Tages in `02-history/2026-09-11.md` ergänzt.

```text
contexte-qualite-comptes-rendus/
└── 02-history/
    └── 2026-09-11.md
```

Der ergänzte Block kann diese Form annehmen:

```markdown
## 2026-09-11

- SRC00003-livre-blanc-donnees-intervention hinzugefügt.
- ATO00002 und THM00001 angelegt.
- C-001 eröffnet.
- `questions-prochain-entretien.md` freigegeben.
- DRE00001 angenommen und C-001 gelöst.
```

- Der Stand sagt, wo man steht.
- Die Geschichte sagt, was geschehen ist.
- Der Wiedereinstieg sagt, was als Nächstes zu tun ist.

##### Ich lasse die Maschine prüfen, was ich nicht sähe

Beim Speichern verringern ein paar maschinelle Prüfungen das Vergessene.
Ihr Ergebnis wird in `01-state/health.md` geschrieben.

```text
contexte-qualite-comptes-rendus/
└── 01-state/
    └── health.md
```

- Gibt es alle Dateien, auf die verwiesen wird?
- Sind die Kennungen eindeutig?
- Nennt jede Notiz ihre Quellen?
- Wird eine hinzugefügte, aber nicht analysierte Quelle gemeldet?
- Sind ersetzte Entscheidungen mit denen verbunden, die sie ersetzen?
- Ist die nächste Handlung ausdrücklich genannt?

Diese Prüfungen ersetzen mein Urteil nicht.
Sie verhindern schlicht, dass ein Strukturfehler sich als Denkproblem ausgibt.

##### Der vollständige Kreislauf und was er erlaubt

Die allgemeine Bewegung wird jetzt sichtbar.

```text
Öffnen
   ↓
Lesen des Briefkastens
   ↓
Laden von Mission, Stand und Wiedereinstieg
   ↓
Hinzufügen einer Quelle
   ↓
Anlegen oder Fortschreiben der Notizen
   ↓
Herstellen eines Entwurfs
   ↓
Prüfung, Freigabe oder Entscheidung
   ↓
Fortschreiben von Stand, Synthese und Wiedereinstieg
   ↓
Checkpoint und Geschichte
   ↓
Prüfung des Speicherns
   ↓
nächstes Öffnen
```

Ich warte nicht das Ende dieser Kette ab, um zu speichern.
- Ich tue es nach dem Hinzufügen einer Quelle, mitten beim Anlegen einer Notiz, vor einer Entscheidung oder während der Vorbereitung eines Ergebnisses, wenn ich sehe, wie mein Kontextfenster überläuft …

Genau das ist die Aufgabe des Speicherns: **jeden dieser Stände wieder aufnehmbar machen, unabhängig vom laufenden Gespräch**.

Meine Besprechung kann also beginnen.

**Der `Kontext` ist nicht nur ein Verzeichnisbaum: er ist ein System, um über die Zeit hinweg zu denken, das Material hereinlässt, Spannungen bewahrt, Ideen festhält, mehrere Ergebnisse hervorbringt und den Wiedereinstieg vorbereitet.**

Seine Form bleibt bewusst einfach und übertragbar — lesbare Dateien genügen, um die Arbeit beobachtbar, prüfbar und weitergebbar zu machen.

Ist dieser Motor einmal verstanden, taucht eine andere Frage auf: wie tritt der `Kontext` mit den Werkzeugen, den Wissensbeständen und dem wirklichen Produkt in Verbindung, die außerhalb von ihm bestehen?

> [!note] Zum Merken — das Speichern
> Speichern markiert nicht das Ende eines Abschnitts: es ist die Gewähr, dass der Stand die Sitzung überlebt, die ihn hervorgebracht hat.
> Der Stand sagt, wo man steht, die Geschichte, was geschehen ist, der Wiedereinstieg, was als Nächstes zu tun ist.
> Der Kreislauf lässt sich an jedem Punkt unterbrechen, und jeder dieser Punkte bleibt wieder aufnehmbar.

### Teil 6 — Der `Kontext` in seinem Ökosystem

Ein gut geführter `Kontext` verleitet dazu, alles verfügbare Wissen hineinzulegen.

Dieser Teil untersucht, was er draußen lässt und warum.
Er bleibt klein, um denkfähig zu bleiben. Alles, was er nur vorsorglich aufbewahrte, würde unbemerkt altern, während sich das Original anderswo weiter verändert.
Also arbeitet er mit Nachbarn: mit Werkzeugen, deren Aufgabe das Aufbewahren, Messen oder Ausführen ist, und mit anderen `Kontexten`, die sich mit anderen Fragen befassen.

#### 6.1 — Strukturiertes Wissen befragen

Die Einsatzberichte müssen warten: Heute Morgen arbeite ich an einem anderen Thema desselben Produkts, an den Nutzern, die mitten in der Anmeldung abbrechen.
Eine Agentur hat mir gerade ihre Studie geliefert, und ich füge sie dem `Kontext` hinzu: Mehrere Teilnehmende zögern angesichts der Passwortregeln.

Diese Beobachtung erinnert mich an eine Idee, der ich schon begegnet bin: einen großen Aufwand zu verlangen, bevor der Nutzer den Wert des Produkts erkannt hat, kann ihn vertreiben.
- Ich bin fast sicher, dass ich Material zum Thema habe.
- Ich weiß bloß nicht mehr, wo es liegt und welche Wörter ich verwendet hatte.

Habe ich von Anfangsaufwand, von Reibung, von Aktivierung oder von Onboarding gesprochen?
Die Idee ist vielleicht
- einem Buch entnommen worden,
- in einer Notiz zum Produktmanagement entwickelt worden,
- mit einem anderen Nutzerweg verbunden worden,
- ...

Ich könnte mehrere Suchen nach Stichwörtern versuchen und die Treffer einzeln öffnen.
Stattdessen frage ich den `Kontext`:

> Was haben wir schon über den Aufwand gelernt, der verlangt wird, bevor der Nutzer den Wert des Produkts erkennt?

##### Der `Kontext` befragt ein größeres Gedächtnis

Die Antwort steht nicht im aktiven `Kontext`.
Sie kann dagegen in meinem LLM-Wiki stehen, einer gemeinsamen Bibliothek, in der die Tausenden von Notizen aus Büchern, Artikeln, Normen und anderen Dokumenten bereits strukturiert sind.

Das LLM-Wiki und der `Kontext` sind nicht von derselben Art.

Das Wiki ist eine Wissensbasis.
- Es bewahrt strukturierte Notizen (in meinem Fall habe ich die Idee der atomaren Notizen wiederverwendet), die aus dem entstehen, was andere geschrieben haben: eine Definition, ein Grundsatz, ein Studienergebnis, eine Anforderung aus einer Norm.
- Jede Notiz sagt, was man weiß, und woher es kommt.
- Es kann Zehntausende davon enthalten, über Jahre angesammelt und zu Themen ohne Zusammenhang untereinander.

Kein `Kontext` wird diese Menge je fassen, und das ist auch nicht seine Aufgabe.

Aber das Wiki hört dort auf.
- Es sagt nicht, warum dieses Wissen für meine heutige Arbeit wichtig ist, und auch nicht, was ich damit gemacht habe.
- Es verbindet keine Idee mit einer Entscheidung und keine Entscheidung mit dem, was sie mich gekostet hat.

**Das LLM-Wiki ist kein System zum Denken: Es speichert Wissen in großem Umfang, aber es denkt nicht.**

Das Denken lebt im `Kontext`.
Er ist es, der das Warum hinter dem Wie bewahrt: 
- worin die Mission besteht,
- welche Direktiven und Entscheidungen feststehen,
- warum diese Idee für diese Mission gewählt wurde, 
- welche Alternativen ich verworfen habe, 
- was ich aufzugeben bereit war, 
- welcher Widerspruch offen bleibt.
Das gelingt ihm nur, weil er klein bleibt — ein paar Dutzend Notizen, die ein Mensch durchlesen kann.

**Jeder zahlt den Preis seiner Stärke.**
- **Das Wiki gewinnt den Umfang und verliert den Faden.**
- **Der `Kontext` behält den Faden und verzichtet auf den Umfang.**

Genau deshalb müssen sie miteinander sprechen, statt zu verschmelzen.

##### Ich beschreibe die Idee, die ich suche

Ich kopiere nicht das ganze Wiki in den `Kontext` zur Anmeldung.
Ich führe auch nicht erst eine RAG-Abfrage und danach eine Suche in einem Graphen aus.

Ich stelle dem `Kontext` einfach meine Frage:

> Was haben wir schon über den Aufwand gelernt, der verlangt wird, bevor der Nutzer den Wert des Produkts erkennt?

Ich formuliere sie mit meinen eigenen Wörtern.
- Ich muss weder den Titel einer Notiz kennen noch ihren Ort noch den Wortschatz, der zur Zeit ihres Entstehens verwendet wurde.

Der `Kontext` gibt diese Idee über die API des LLM-Wikis weiter.
Alles Übrige geschieht innerhalb des Wikis.

##### Das Wiki sucht nach Bedeutung und dann im Umfeld der Treffer

Das LLM-Wiki findet zuerst die Notizen, die meiner Frage semantisch nahekommen.
- Eine Notiz kann von anfänglicher Reibung, von Aktivierung oder von der Zeit bis zum ersten Nutzen sprechen, ohne das Wort „Aufwand" zu verwenden.

Das ermöglicht sein RAG: bereits strukturiertes Wissen zu finden, das meiner Idee nahekommt, ohne denselben Wortschatz vorauszusetzen.

Danach sieht sich das Wiki in der Umgebung der besten Treffer um.
Sein semantischer Graph folgt den bereits bestehenden Beziehungen zwischen den Notizen und fügt benachbarte Notizen hinzu, die das Thema erhellen können:
- eine Definition, 
- eine Grenze, 
- einen Widerspruch,
- eine ergänzende Idee.

Eine dieser benachbarten Notizen hätte meine Frage vielleicht nie unmittelbar beantwortet.
Sie wird trotzdem wertvoll, weil sie zeigt, unter welchen Bedingungen die Idee gilt oder an welcher Stelle sie aufhört, wahr zu sein.

```text
eine mit meinen Wörtern formulierte Idee
                │
                ▼
das Wiki findet die dem Sinn nach nahen Notizen
                │
                ▼
es fügt ihre nützliche Nachbarschaft hinzu
                │
                ▼
ein paar belegte Verweise kommen zurück
                │
                ▼
der Kontext behält, was seiner Mission dient
```

**Das RAG findet, was ich nicht hätte benennen können.**
**Der Graph macht sichtbar, wonach ich nicht gesucht hätte.**

Für mich bilden diese beiden Vorgänge nur einen.
Ich bitte um Verweise, die zu einem Problem passen; das LLM-Wiki sucht die Idee und ihre Nachbarschaft und gibt mir dann eine kurze Liste.

##### Der `Kontext` bekommt Verweise, keine fertige Antwort

Das Wiki schickt vorhandene Notizen zurück, mit ihrem Inhalt, ihrer Herkunft und ihren Beziehungen.
Es fertigt keine Zusammenfassung an, die mehrere Treffer stillschweigend vermengen würde.

Der `Kontext` kann also jeden Treffer lesen, ihn mit den Beobachtungen zur Anmeldung vergleichen und zu seiner Quelle zurückgehen, wenn ein Beleg zu prüfen ist.
- Manche Notizen betreffen tatsächlich einen Aufwand, der vor dem Zugang zum Produkt auferlegt wird.
- Andere sprechen von einem Aufwand, der später verlangt wird, wenn der Nutzer den Wert schon kennt.
Ihre Nähe zu meiner Frage genügt nicht, um sie gleichwertig zu machen.

Der `Kontext` trifft die Auswahl anhand seiner Mission.
Er kann:
- eine Idee behalten, die den Abbruch während der Anmeldung erhellt,
- einen Widerspruch bewahren,
- eine zu allgemeine Notiz beiseitelegen.

Eine ausgewählte Notiz wird mit ihrer Herkunft und den Quellen, auf denen sie beruht, in den `Kontext` aufgenommen.
Der Rest bleibt im Wiki.

So verfüge ich über ein weit größeres Gedächtnis, ohne jeden `Kontext` in eine Kopie meiner ganzen Bibliothek zu verwandeln.
- Ich muss nicht lernen, wie dieses Gedächtnis erschlossen ist, um es zu nutzen: ich beschreibe die Idee, die ich suche, und prüfe dann die Verweise, die sie mir zurückbringt.

Diese Kette gibt Zugang zu schon strukturiertem Wissen.
- Sie sagt noch nicht, was das Produkt heute wirklich tut.

Um diese andere Frage zu beantworten, muss der `Kontext` die Bibliothek verlassen und unmittelbar den Code, die Tests und das laufende Produkt befragen.

> [!note] Zum Merken — zwei Systeme, eine Tür
> Das LLM-Wiki gewinnt den Umfang und verliert den Faden; der `Kontext` behält den Faden und verzichtet auf den Umfang.
> Ich beschreibe eine Idee mit meinen eigenen Wörtern; das Wiki findet die dem Sinn nach nahen Notizen und fügt ihre nützliche Nachbarschaft hinzu.
> Der `Kontext` bekommt ein paar belegte Verweise und behält nur, was seiner Mission dient.

#### 6.2 — Das tatsächliche Produkt abfragen

Ich lese gerade die Studie zu den Abbrüchen während der Anmeldung noch einmal, als eine Frage hereinkommt:

> Muss ein eingeladener Nutzer wie alle anderen ein Passwort anlegen?

Die Frage wirkt winzig.
Auf die Antwort wartet trotzdem jemand aus dem Support, der einem Kunden antworten muss.

Ich könnte: 
- meine Lektüre unterbrechen, 
- eine Testumgebung öffnen, 
- zwei Konten vorbereiten, 
- die Wege nachspielen,
- vergleichen, was geschieht.

Früher habe ich genau das getan.
- Eine halbe Stunde später hätte ich die Antwort wahrscheinlich.
- Ich hätte auch den Faden meiner Arbeit verloren.

Diesmal stelle ich die Frage dem `Kontext`.

##### Der `Kontext` prüft das Produkt

Der `Kontext` arbeitet mit den Notizen aus der Nutzerstudie und bewahrt diese Studie als Quelle ihrer Aussagen.
- Er trägt außerdem die laufende Mission.
- Er versteht, warum die Frage zählt, aber diese Elemente erlauben ihm nicht, das gegenwärtige Verhalten des Produkts zu kennen.

Ich pflege keine Spezifikation mehr, die dieses Verhalten dauerhaft beschreiben soll.
- Das Produkt ändert sich zu oft, als dass ein parallel gepflegtes Dokument dauerhaft eine getreue Kopie bliebe.

**Die einzige aktuelle Wahrheit ist das, was ausgeliefert ist und in Produktion läuft: der Quellcode der Anwendung.**

In meinem System können Skills außerhalb des `Kontexts` den Quellcode untersuchen und Dokumentation aus der Implementierung erzeugen.
Der `Kontext` ruft denjenigen auf, der Produktfragen beantwortet, und übergibt ihm meine Anfrage.

```text
Frage des Product Managers
            │
            ▼
         Kontext
            │  ruft auf
            ▼
Skill zum Lesen des Produkts
            │  befragt
            ▼
    tatsächliches Produkt
```

Der Skill findet zuerst den Einladungsweg im Code.
Dann folgt er diesem Weg bis zur Regel für das Anlegen des Kontos.

Der Code zeigt das programmierte Verhalten.
Ein Test bestätigt, dass ein eingeladener Nutzer seine Anmeldung über den erhaltenen Link abschließen kann, ohne sofort ein Passwort anzulegen.
Die Konfiguration zeigt, dass für diesen Weg keine kundenspezifische Variante aktiv ist.

Der Skill gibt mir eine fachliche Antwort:

> Ein eingeladener Nutzer kann über seinen Einladungslink auf sein Konto zugreifen, ohne während dieses Schritts ein Passwort anzulegen.
> Entscheidet er sich danach, eines anzulegen, gelten die gewöhnlichen Regeln.
> Die Tests bestätigen den Einladungsweg und das freiwillige Anlegen des Passworts.
> Der Weg zur Wiederherstellung eines vergessenen Passworts wurde nicht untersucht.

Die ersten beiden Sätze kann ich an den Support weitergeben.
Ich kann auch die vom Skill gelieferten Verweise öffnen, wenn ich seine Analyse mit einem Entwickler prüfen will.

Schließlich kann ich diese Antwort mit ihren Belegen, dem Datum der Prüfung und der festgehaltenen Einschränkung im `Kontext` speichern.
- Dem Support zu antworten erledigt einen Fall und hört dort auf.
- Sie im `Kontext` festzuhalten bringt eine geprüfte Tatsache über das Produkt in die *Welt der Ideen* der Mission: Die nächste Frage zum Einladungsweg fängt nicht bei null an, und die Notiz aus der Studie gewinnt, was die Beobachtung allein nicht gab — den genauen Moment, in dem jeder Weg das Passwort verlangt.

##### Eine Antwort taugt so viel wie die Belege, die sie begleiten

Der Skill hat sich nicht damit begnügt, eine plausible Antwort hervorzubringen.
Für jede Aussage nennt er, was er herangezogen hat:
- die im Code vorhandene Regel, 
- den Test, der das Verhalten prüft,
- die Konfiguration, die die aktive Variante bestimmt.

Diese Spur schützt vor einer überzeugenden, aber falschen Antwort.
Sie erlaubt auch, sofort zu sehen, was fehlt.

Hier hat der Skill die Wiederherstellung eines vergessenen Passworts nicht geprüft.
Er sagt es, statt seinen Schluss auf einen Weg auszudehnen, den er nicht gelesen hat.

Je nach Frage können andere Elemente nötig werden.
- Der Code enthält die möglichen Regeln, aber ein Feature-Flag zeigt an, welche aktiv ist.
- Der Aufbau der Datenbank zeigt, was das Produkt speichern kann, während die zugänglichen Daten erlauben, die Lage eines bestimmten Kontos zu verstehen.
- Die Git-Historie und die Pull Requests helfen wiederzufinden, wann sich eine Regel geändert hat und welche Erklärungen mit dieser Änderung bewahrt wurden.
- ...

Der Skill sammelt nur, was er braucht, um die gestellte Frage zu beantworten.
Er liest nicht das ganze Repository ein und macht nicht jede Datei zu einer Quelle des `Kontexts`.

Die Antwort bleibt für den Support, den Vertrieb oder einen Product Manager lesbar.
Die Belege bleiben für die Person verfügbar, die sie prüfen oder die Untersuchung fortsetzen muss.

##### Die Regel zu finden entscheidet nicht, sie zu ändern

Ich kehre zu meiner Studie über die Anmeldung zurück.
Sie hatte mich schon gelehrt, dass die beiden Wege das Anlegen des Passworts nicht im selben Moment zeigen.

Der Skill fügt hinzu, was die Studie nicht sehen konnte.
Der eingeladene Nutzer umgeht die Passwortregel nicht: er trifft später auf sie, und sie ist dann genau dieselbe.

Die Reibung ist für ihn also nicht verschwunden, sie hat den Ort gewechselt.
Diese Genauigkeit verschiebt meine Frage.
Ich frage nicht mehr, wer der Regel unterliegt, sondern in welchem Moment jeder auf sie trifft: bevor er den Wert des Produkts erkannt hat, oder danach.

Der Code hat mich gelehrt, was das Produkt tut.
- Er sagt mir nicht, ob die Regel gut ist, ob sie die Konten wirklich schützt oder ob ihre Kosten für die Nutzer annehmbar sind.

Um zu entscheiden, brauche ich weiterhin die anderen Elemente des `Kontexts`:
- die Beobachtungen der Studie und ihren Zuschnitt;
- die Sicherheitsziele;
- die Gründe, die zu dieser Regel geführt hatten;
- die von einer Änderung erwarteten Folgen.

Der Skill stellt eine Tatsache über das Produkt fest.
Der `Kontext` verbindet diese Tatsache mit den schon vorhandenen Notizen und Entscheidungen und bewahrt zugleich die Quellen, mit denen sich ihre Herkunft prüfen lässt.
**Für die Entscheidung bleibe ich zuständig.**

Entscheide ich mich, das Anlegen des Passworts zu ändern, hält das Decision Record die Wahl, ihren Geltungsbereich und die Gründe fest, die sie stützen.
Nach der Umsetzung kann der Skill zum Produkt zurückkehren und prüfen, ob das neue Verhalten der Entscheidung auch entspricht.

Die Bewegung geht also in beide Richtungen.
Das Produkt liefert die Grundlage für die Überlegungen, dann verändert die Entscheidung das Produkt.

```text
Beobachtungen ──> Ideen ──> Entscheidung
     ▲                           │
     │                           ▼
geprüftes Produkt <────── geändertes Produkt
```

##### Das Warum bewahren, das Was neu aufbauen

> [!note] Der code-zentrische Ansatz
> Der Code ist nicht mehr bloß das Endergebnis der Entwicklung.
> Er wird zur Quelle, aus der ich wieder aufbauen kann, was das gegenwärtige Verhalten des Produkts beschreibt.
> Der `Kontext` bewahrt, was der Code allein nicht erklären kann: die Quellen, den Gedankengang, die Entscheidungen, die verworfenen Alternativen und die Gründe der Wahl.

Diese Trennung ändert den Platz der Dokumentation.

Ich bewahre, was erklärt, warum das Produkt eine Richtung eingeschlagen hat: die Gespräche, die Zwänge, die Annahmen und die Abwägungen.
Ich baue aus dem Produkt wieder auf, was sein gegenwärtiges Verhalten beschreibt: 
- eine Antwort an den Support, 
- eine fachliche Dokumentation,
- ein Änderungsprotokoll,
- ...

Ich pflege nicht mehr von Hand zwei Fassungen desselben Verhaltens, die eine im Code und die andere in einem Dokument, das ab seiner Veröffentlichung zu altern beginnt (und sogar weit davor).

Trotzdem kommt nicht alles aus dem Code.
- Eine Nutzerstudie findet sich dort nicht.
- Eine regulatorische Pflicht behält ihre eigene Quelle.
- Eine Entscheidung geht nicht in dem Verhalten auf, das aus ihr folgt.

**Der Code dokumentiert, was umgesetzt wurde.**
**Der `Kontext` bewahrt das Warum und erlaubt, es zu besprechen, wenn sich die Lage ändert.**

##### Sechs Monate später zurückkehren

Die dem Support gegebene Antwort bleibt an die heute untersuchte Fassung des Produkts gebunden.
Sie beschreibt die folgenden Fassungen nicht von selbst.
- Sechs Monate später kann sich der Einladungsweg geändert haben.
- Ein Feature-Flag kann eine andere Variante aktivieren, oder eine neue Art der Anmeldung kann aufgetaucht sein.

Der `Kontext` bewahrt die Frage, die fachliche Antwort, das Datum der Prüfung, die untersuchte Fassung, die zitierten Belege und die festgehaltene Einschränkung.
So finde ich wieder, was wir wussten, als wir überlegt haben.

Um das gegenwärtige Verhalten zu kennen, bitte ich den Skill einfach, die Prüfung noch einmal auszuführen.
- Er geht vom tatsächlichen Produkt aus, statt die alte Antwort abzuschreiben.

Ich kann dann zwei Fragen unterscheiden, die oft verwechselt werden:
- warum haben wir diese Entscheidung damals getroffen?
- was tut das Produkt heute?

Der `Kontext` beantwortet die erste, indem er den Gedankengang bewahrt.
Der Skill beantwortet die zweite, indem er zur Quelle der Wahrheit zurückkehrt.

Das Produkt ersetzt also nicht den `Kontext`, und der `Kontext` beansprucht nicht, das Produkt zu enthalten.
- Das eine liefert eine überprüfbare Realität;
- das andere bewahrt das Wissen, das nötig ist, um ihr Sinn zu geben und sie weiterzuentwickeln.

Dieser Kreislauf hört nicht bei den äußeren Werkzeugen auf.
Wenn mehrere `Kontexte` an verschiedenen Seiten desselben Produkts arbeiten, muss auch ihr Wissen zirkulieren können, ohne in einem einzigen Ordner zu verschmelzen.

> [!note] Zum Merken — der code-zentrische Ansatz
> Keine Spezifikation wird als dauerhafte Beschreibung des Produkts gepflegt: was sein Verhalten beschreibt, wird aus dem Code wieder aufgebaut.
> Eine Antwort taugt nur so viel wie die Belege, die sie begleiten, und die Grenzen, die sie meldet.
> Der Code dokumentiert, was umgesetzt wurde; der `Kontext` bewahrt das Warum und erlaubt, es neu zu besprechen.

#### 6.3 — Der Tag, an dem ich drei `Kontexte` hatte

Ein Techniker erzählt mir, dass er einen Kunden zurückrufen musste, weil eine Angabe im Einsatzbericht fehlte.

Ich notiere den Satz.
Dann halte ich inne, weil ich nicht weiß, wohin damit.
- Ich habe einen `Kontext` zur Qualität der Einsatzberichte — den, der mich die ganze zweite Hälfte dieses Buches über beschäftigt hat.
- Ich habe einen zweiten zum Einsatz selbst: was er enthält, welche Regeln für ihn gelten, was darüber schon entschieden ist.
- Und ich habe einen dritten, weiteren, ein paar Wochen zuvor eröffnet: wie die Bediener dazu zu bringen sind, grundlegende Arbeiten an den Anlagen zu übernehmen.

Der Satz des Technikers betrifft alle drei:
- er belegt einen mangelhaften Einsatzbericht, 
- er sagt etwas über den Einsatz, 
- er erhellt die Frage der Bediener.

In diesem Moment nimmt das Problem eine neue Form an.
- Solange ich einen einzigen `Kontext` hatte, lautete die Frage: kommt das hinein, oder gehört es nicht zum Thema?
- Mit dreien lautet sie: in welchen?

##### Die beiden Arten, sich zu irren

Die erste Versuchung ist, alles zusammenzulegen.
- Ein einziger großer Raum, das ganze Wissen am selben Ort, keine Frage des Ablegens mehr.

Genau davor bin ich geflohen.
Ein einziger Raum, der alles enthält, schafft das Problem klassischer Dokumentenmanagementsysteme neu: einen Ort, an dem
- die Information vorhanden ist und das Sortieren bei jedem Nachsehen von vorn beginnt,
- die Ziele sich vermischen, 
- die Quellen sich anhäufen,
- und keine Notiz mehr einen klaren Eigentümer hat.

Ich habe diese Sackgasse am Anfang des Buches erzählt; sie mit frischem Wortschatz neu zu erschaffen machte sie nicht besser.

Die zweite Versuchung ist die umgekehrte: jeder `Kontext` bleibt bei sich.
Jeder ist sauber, umgrenzt, stimmig — und blind.

Das Ergebnis zeigt sich schnell.
Mein `Kontext` zu den Einsatzberichten hat drei Sitzungen damit verbracht, eine Regel zu konsolidieren, die der zum Einsatz schon enthielt.
Es war keine sichtbare Dopplung: es war doppelt getane Arbeit, ohne dass es jemand hätte bemerken können.

Es braucht also einen dritten Weg, und er beginnt damit, zu wissen, was jeder `Kontext` trägt.

##### Eine Zahl vor dem Namen

Meine `Kontexte` heißen `01-saisie-compte-rendu`, `02-intervention`, `03-autonomie-operateurs`, `04-exploitation-catch-all`.

Die Zahl ist kein Rang, sie ist eine Namenskonvention.
Sie sagt, was der `Kontext` trägt, noch bevor ich ihn öffne.

- **`02-` eine Einheit des Produkts.** Ein Teil der Software, der in Produktion läuft und eigene Regeln hat: `02-facturation` in einem ERP, `02-intervention` in meinem. Was darin steht, ist gesichert. Dieser `Kontext` bleibt aktiv.
- **`01-` eine Annahme über eine Einheit.** `01-saisie-compte-rendu`: ich glaube, das Ausfüllen sollte sich ändern, ich weiß noch nicht wie. Nichts von dem, was er enthält, ist gesichert; ich lege also einen `01-`-`Kontext` an, um das Stabile (in Produktion) klar von einer Annahme zu trennen.
- **`03-` ein Problem.** `03-autonomie-operateurs`: die Bediener dazu bringen, grundlegende Arbeiten an den Anlagen zu übernehmen. Das ist keine Funktion, es geht quer durch mehrere Einheiten und bringt `01-` hervor.
- **`04-` die Sammelablage.** Ein gehörter Satz, ein PDF, eine Ahnung: Material, dessen Thema noch keinen `Kontext` hat. Ohne sie müsste ich für jeden Ideenfetzen einen anlegen — so habe ich angefangen und stand nach wenigen Wochen mit über fünfzig substanzlosen `Kontexten` da.

##### Ein `01-` verlässt am Ende immer die aktive Arbeit

Am Tag der Inbetriebnahme hört das neue Ausfüllen auf, eine Annahme zu sein: es wird Teil des Einsatzes.

Was das Produkt nunmehr beschreibt, wird `02-intervention` vorgeschlagen.
Der Rest bleibt im erkundenden `Kontext`, der danach archiviert wird.
Es gibt nicht mehr zwei aktive Orte, an denen nachzusehen wäre, wie ein Einsatzbericht funktioniert.

Eine Annahme, die zu nichts führt, wird mitsamt dem archiviert, was sie gestoppt hat.
Das ist kein zu tilgender Fehlschlag: es ist das, was in zwei Jahren denselben Weg erspart.

Der `04-` dagegen leert sich in die andere Richtung.
An dem Tag, an dem ein Problem auftaucht, lege ich den zugehörigen `Kontext` an und sehe dann nach, was die Sammelablage dazu gespeichert hat.
Was zu nichts nützt, wird gelöscht.

All das regelt eine einzige Frage — wohin damit — indem es trennt, was ich untersuche, von dem, was gesichert ist.
- Ohne diese Trennung hinterlässt jede aufgegebene Annahme ihre Spuren in der Beschreibung des Produkts.
- Und man wagt nichts mehr zu vermuten an einem Ort, an dem alles wahr sein soll.

##### Der Fehler, für den ich Monate gebraucht habe

Ich habe damit angefangen, `03-tarification` zu eröffnen.
Das schien mir selbstverständlich: ein großes Thema, es betrifft mehrere Einheiten, es dauert an.

Sechs Monate später enthielt er: 
- die Preisliste,
- zwei Wettbewerbsvergleiche, 
- eine Diskussion über Rabatte, 
- ein Supportticket zu einer falschen Rechnung, 
- eine Notiz zur belgischen Mehrwertsteuer,
- drei Bildschirmfotos eines Wettbewerbers,
- ...
Nichts davon lag außerhalb des Themas: alles handelte tatsächlich von der Preisgestaltung.

Genau das ist das Problem.
Um Material abzulehnen, muss man sagen können: „das hilft mir nicht".
Nun suchte dieser `Kontext` aber nichts — **er hatte keine Frage**, nur ein Etikett.

`03-autonomie-operateurs` hat eine: wie die Bediener dazu zu bringen sind, grundlegende Arbeiten an den Anlagen zu übernehmen.

Ein `03-` ist also kein großes Thema. Es ist eine Frage.
Die Preisgestaltung ist deshalb nicht verschwunden: sie geht quer durch meine `Kontexte` — `02-facturation` trägt ihre Regeln, ein `01-` kann von ihr abhängen — ohne einen von ihnen zu beherrschen.

Meine Konvention hat also kein Fach für Domänen und für vieles andere auch nicht.
Sie dient dazu, abzulegen, was einen offensichtlichen Platz hat, und nicht mehr.
Der Rest wartet in der Sammelablage, und ich finde ihn wieder, indem ich beschreibe, was ich suche, statt mich daran zu erinnern, wo ich ihn abgelegt hatte.

Inzwischen habe ich zwei davon — eine Lösung, die ich durch Versuch und Irrtum gefunden habe.
Eine einzige Sammelablage vermischte Inhalte aus meiner Produktarbeit mit Inhalten aus der Domäne des industriellen Betriebs — zwei Wortschätze, zwei Zielgruppen, zwei Arten, dieselben Dinge zu benennen.
Er wurde schneller unlesbar, als er sich leerte.
- `04-exploitation-catch-all` nimmt Inhalte aus der fachlichen Domäne meiner Kunden auf: den Betrieb;
- `04-productops-catch-all` nimmt auf, was meine eigene Arbeit und ihre Organisation betrifft: Product Ops.

Jeder bleibt lesbar, also leert sich jeder.

Der Satz des Technikers brauchte die Sammelablage gar nicht.
Er ging in `02-intervention`, weil dort lebt, was unabhängig von der Frage, die ich mir gerade stelle, über das Produkt wahr ist.

Bleibt zu klären, wie meine drei `Kontexte` davon erfahren.

> [!note] Zum Merken — vier Präfixe, eine einzige Frage
> Die Zahl vor dem Namen sagt, was der `Kontext` trägt: `02-` eine Einheit, die läuft, `01-` eine Annahme über diese Einheit, `03-` ein Problem, das quer durch mehrere geht, `04-` die Zwischenablage für alles, was sich noch nicht einordnen lässt.
> Ein `01-` existiert, um seinem `02-` vorzuschlagen, was das Produkt nunmehr beschreibt, und danach archiviert zu werden. Führt er zu nichts, wird er mitsamt dem archiviert, was ihn gestoppt hat.
> Eine Domäne ist kein `Kontext`: sie geht quer durch mehrere, ohne einen zu beherrschen.
> Ein `Kontext` ohne Frage wird nie wissen, was nicht zum Thema gehört.

#### 6.4 — Beim Nachbarn lesen, ohne zu ihm zu ziehen

Ich nehme `01-saisie-compte-rendu` wieder auf, den `Kontext` zur Qualität der Einsatzberichte.
Um voranzukommen, muss ich die Regeln des Einsatzes selbst kennen: was ein Techniker eintragen darf, was verpflichtend ist und was schon entschieden wurde.

Diese Regeln leben nicht in meinem `Kontext`.
Sie sind in `02-intervention` festgeschrieben, dem benachbarten `Kontext`, der beschreibt, was im Produkt wirklich existiert.

Ich könnte sie abschreiben, um sie zur Hand zu haben.
Sechs Monate später hätte ich wahrscheinlich zwei Fassungen derselben Regel und keine einfache Möglichkeit zu wissen, welche gilt.

Ich beginne also mit einer leichteren Beziehung: Mein `Kontext` erklärt, dass er `02-intervention` konsultiert.

##### Lesen lässt das Wissen bei seinem Eigentümer

Diese Beziehung steht im stabilen Rahmen meines `Kontexts`, neben seiner Mission und seinen Direktiven.
Sie eröffnet ein genaues Recht: einzusehen, was `02-intervention` schon weiß.

Das Material bleibt bei seinem Eigentümer.
Es entwickelt sich dort weiter, und meine Erkundung stützt sich darauf, ohne es besitzen zu wollen.

So kann ich die geltende Regel zu den Pflichtfeldern prüfen, ohne sie in jeder Untersuchung zu verdoppeln, die einen Einsatzbericht betrifft.
Ich kann auch zu ihren Quellen und zu den Entscheidungen zurückgehen, die sie geprägt haben.

Lesen berechtigt nicht zum Ändern.
Kommt mir eine Notiz unvollständig oder falsch vor, kann mein `Kontext` einen Vorschlag machen, aber er bearbeitet seinen Nachbarn nie unmittelbar.

Diese erste Beziehung erfüllt einen häufigen Bedarf: Wissen von außen zu nutzen und es zugleich am zuständigen Ort weiterleben zu lassen.

Sie deckt nicht alle Fälle ab.

##### Aufnehmen macht das Wissen selbstständig

Manchmal genügt ein bloßes Nachsehen nicht.

Ich muss vielleicht die genaue Regel festhalten, auf der eine Entscheidung beruht.
Ich will sie vielleicht für den besonderen Zuschnitt meiner Erkundung umformulieren.
Ich brauche dieses Wissen vielleicht auch weiterhin, falls der `Kontext`, aus dem es stammt, archiviert, verschoben oder umgebaut wird.

In diesem Fall entscheide ich mich, es aufzunehmen.

Aufnehmen bringt ein Wissen in meinen eigenen `Kontext`.
Ich kann eine Notiz unverändert übernehmen oder sie in meinem Wortschatz umformulieren.
Je nach Bedarf kopiere ich auch die Quellen, mit denen sie sich prüfen lässt, oder ich behalte Verweise darauf.

Die Kopie wird deshalb keine Idee ohne Vergangenheit.
Sie bewahrt den `Kontext`, aus dem sie kommt, das Datum der Aufnahme und das, was umformuliert wurde.

Der Unterschied liegt also weniger im technischen Handgriff als in der Verantwortung, die daraus folgt:

- wenn ich lese, gehört das Wissen weiterhin dem Nachbarn;
- wenn ich aufnehme, gelangt eine selbstständige Fassung in meinen eigenen `Kontext`, und ich werde für ihren Gebrauch zuständig.

**Lesen schafft eine Abhängigkeit.**
**Aufnehmen schafft eine neue Verantwortung.**

##### Die Bewegung kann in die andere Richtung gehen

Meine Erkundung verbraucht nicht nur, was `02-intervention` schon weiß.
Sie bringt ihrerseits Beobachtungen, Annahmen und manchmal dauerhaftes Wissen hervor.

Beim Studium der Qualität der Einsatzberichte kann ich entdecken, dass eine Regel zum Ausfüllen in Wirklichkeit zum Einsatz selbst gehört.
Dieses Wissen sollte nicht in einem erkundenden `Kontext` eingeschlossen bleiben, der vielleicht am Ende archiviert wird.

Ich schreibe es nicht unmittelbar in `02-intervention`.
Ich schlage es ihm vor.

Die Richtung des Austauschs hat sich gerade geändert:

```text
01-saisie-compte-rendu ── liest ──▶ 02-intervention

01-saisie-compte-rendu ── schlägt vor ──▶ 02-intervention
                                      │
                                      └── entscheidet über die Aufnahme
```

Wer ein Wissen hervorbringt, entscheidet nicht über seinen endgültigen Platz.
Der `Kontext`, der es empfängt, beurteilt es nach seiner eigenen Mission.

Er kann:
- die Notiz unverändert übernehmen;
- sie in seinem Wortschatz umformulieren;
- eine Abweichung bewahren, wenn beide Lesarten gültig bleiben;
- die Aufnahme ablehnen, wenn das, was der Erkundung nützt, den Einsatz selbst nicht beschreibt.

Die Ablehnung ist kein Scheitern des Austauschs.
Sie verhindert, dass ein lokales Ergebnis stillschweigend zur allgemeinen Wahrheit wird.

##### Wenn die Erkundung zur Produktwirklichkeit wird

Ein paar Wochen später geht das neue Ausfüllen der Einsatzberichte in Produktion.
`01-saisie-compte-rendu` hat seine Rolle erfüllt: was nur eine Annahme war, ist eine Wirklichkeit des Produkts geworden.

Ich verschiebe deshalb nicht seinen ganzen Inhalt nach `02-intervention`.
Ich gehe durch, was die Erkundung hervorgebracht hat, und trenne zwei Gruppen.

Die erste enthält, was das Produkt nunmehr beschreibt oder erklärt:

- die Notizen, die die neuen Regeln des Ausfüllens festlegen;
- den vereinheitlichten Wortschatz, um sie zu benennen;
- die prägenden Entscheidungen und die Gründe dieser Wahl;
- die Widersprüche, die nach der Inbetriebnahme offen bleiben;
- die Quellen oder Verweise, die nötig sind, um dieses Wissen zu prüfen.

Diese Elemente werden `02-intervention` vorgeschlagen.
Der stabile `Kontext` häuft sie nicht blind an: er reichert seine vorhandenen Notizen an, formuliert um, was umzuformulieren ist, und legt nur dann eine neue Notiz an, wenn eine Idee wirklich neu ist.

In unserem Beispiel geht die Regel, die den Abschluss auf vier Angaben begrenzt, mitsamt der Entscheidung, die sie erklärt, zu `02-intervention`.
Sie beschreibt jetzt eine Wirklichkeit des Produkts.

Die zweite Gruppe erzählt die Geschichte der Arbeit, ohne das gegenwärtige Produkt zu beschreiben:
- die aufgegebenen Annahmen;
- die Entwürfe und die verworfenen Wege;
- die Zwischenfassungen;
- die Aufgaben, die nur zur Erkundung gehören;
- die Gespräche, die verstehen lassen, welcher Weg zurückgelegt wurde.

Diese Elemente bleiben in `01-saisie-compte-rendu`.
Sie sind nicht unnütz geworden: Sie erklären, was versucht wurde, warum bestimmte Wege verworfen wurden und was ohne neuen Grund nicht noch einmal begonnen werden sollte.

Ist diese Auswahl beendet, wird der erkundende `Kontext` als Ganzes archiviert.
Er bleibt lesbar und kann später wieder aufgenommen werden, beansprucht aber nicht mehr, die laufende Arbeit zu beschreiben.

Wäre die Erkundung zu nichts gekommen, wäre sie ebenfalls archiviert worden, mitsamt den Gründen ihres Abbruchs, ohne `02-intervention` etwas aufzudrängen.

Die Inbetriebnahme verschmilzt also nicht zwei `Kontexte`.
Sie löst eine Prüfung aus: Was nunmehr das Produkt beschreibt, geht zum stabilen `Kontext`; was die Erkundung erzählt, bleibt im archivierten `Kontext`.

Diese Auswahl schützt beide Seiten:
- die Erkundung bleibt frei, sich zu irren;
- der stabile `Kontext` bekommt nur, was er als das Seine anzuerkennen wählt.

##### Die Beziehungen gehören zum Rahmen

Lesen, Aufnehmen und Vorschlagen dürfen keine stillschweigenden Handgriffe bleiben.

Der stabile Rahmen des `Kontexts` nennt:
- welche anderen `Kontexte` er einsehen darf;
- was dieses Einsehen erlaubt;
- nach welchen Regeln ein Wissen aufgenommen werden darf;
- wie seine Herkunft und etwaige Umformulierungen bewahrt werden.

Diese Regelung verlangt keine aufwendige Infrastruktur.
Sie macht die Beziehungen schlicht explizit, damit Herkunft, Zuständigkeiten und Grenzen sichtbar bleiben.

Das Netz entsteht also nicht, indem alles mit allem verbunden wird.
Es entsteht Beziehung für Beziehung, jedes Mal, wenn eine Arbeit wirklich einen Nachbarn braucht.

- Beim Nachbarn zu lesen verhindert, dass sein Wissen dupliziert wird.
- Aufnehmen macht selbstständig, was bei mir leben soll.
- Vorschlagen lässt schließlich den Nachbarn entscheiden, ob er übernehmen will, was meine Erkundung hervorgebracht hat.

Dieser Austausch wirkt auf dem Papier schlüssig.
Er hat trotzdem einen Preis: ein Verweis kann unbemerkt altern, eine Kopie kann ihre Herkunft verlieren, und zwei `Kontexte` können unterschiedliche Lesarten bewahren.

Das wird das nächste Kapitel untersuchen.

> [!note] Zum Merken — drei Handlungen, drei Verantwortungen
> Lesen sieht ein Wissen ein, das bei seinem Eigentümer bleibt; Aufnehmen schafft davon eine selbstständige, belegte Fassung in dem `Kontext`, der sie empfängt.
> Eine Erkundung schlägt vor, was sie gelernt hat, aber der Eigentümer des Ziel-`Kontexts` entscheidet, was bei ihm eintritt.
> Die Inbetriebnahme verschmilzt die Ordner nicht: der stabile `Kontext` nimmt auf, was nunmehr das Produkt beschreibt, während die Erkundung den Rest bewahrt, bevor sie archiviert wird.

#### 6.5 — Was der Austausch kostet

Sechs Wochen sind vergangen.

Meine Arbeit an den Einsatzberichten ist bereit für die Durchsicht, und jemand bemerkt eine Abweichung.
Die Regel, auf die ich mich stütze — die sagt, welche Felder beim Abschluss verpflichtend sind — ist nicht mehr die des Produkts.

Sie hat sich geändert.
Während ich arbeitete, ist eine andere Erkundung zu einem Ergebnis gekommen, und der `Kontext` des Einsatzes hat es aufgenommen.

Niemand hat es mir gesagt.
Ich habe ihn nicht noch einmal gelesen, weil ich ihn sechs Wochen zuvor gelesen hatte und nichts anzeigte, dass ich dorthin zurückmusste.

Das vorige Kapitel stellt eine Regel auf, die schlüssig wirkt: Man verweist in der Richtung des Lesens und kopiert in der Richtung der Aufnahme.
Ich hielt sie für eine abschließende Lösung.

Sie beseitigt das Risiko nicht.
Sie verschiebt es, und es ist besser zu wissen, wo das Risiko am Ende liegt.

##### Eine Abhängigkeit, die man nicht sieht

Was gerade geschehen ist, hat einen Namen: eine blinde Abhängigkeit.

Die Verbindung ist lebendig, also kann sich das, was ich lese, ohne mich ändern.
Das ist nicht das Problem — es ist oft genau das, was ich will. Eine Regel, die sich bei ihrem Eigentümer ändert, ist das System, das funktioniert.

Das Problem ist, nicht zu wissen, dass sie sich geändert hat.

Was fehlt, ist leicht zu sagen: nichts überwacht das, was ich lese.
Mein `Kontext` weiß, von wem er abhängt; er weiß nicht, wann sich das, wovon er abhängt, geändert hat.
Das ist die Hälfte des Mechanismus, und es ist die kostspielige Hälfte.

Eine Kopie hätte mich davor geschützt.
Der `Kontext`, der empfängt, wird selbstständig: er hängt weder vom Bestehen noch von der Entwicklung seiner Quelle ab.

Aber dafür verliert er etwas anderes.
Ist nirgends vermerkt, woher die Kopie kommt, verschwindet die Herkunft — und ein Jahr später habe ich eine richtige Notiz, von der ich nicht mehr weiß, worauf sie beruht.
Genau diese Situation soll die in diesem Buch beschriebene Nachvollziehbarkeit verhindern.

Der Schluss ist also nicht, eine Seite zu wählen.
Er besteht darin, festzuhalten, was jeder Vorgang dokumentieren muss:
- ein **Verweis** verlangt zu wissen, wann sich seine Quelle ändert;
- eine **Kopie** verlangt zu sagen, woher sie kommt — welcher `Kontext`, zu welchem Datum, und was dabei umformuliert wurde.

> [!NOTE] Mögliche Entwicklung
> Eine weitere, noch ausstehende Antwort wird technischer Art sein: `Kontexte` könnten ihre Beobachter benachrichtigen, wenn sich ihr Zustand ändert — insbesondere dann, wenn die Änderung den von einem anderen `Kontext` überwachten Bereich betrifft.
> Der `Kontext` ist ein lebendiges Thema, bei dem noch viele Möglichkeiten zu erkunden sind.

##### Die Rechte, die das Lesen nicht gibt

Wenn ich einen `Kontext` häufig lese, fühlt er sich irgendwann ein wenig wie mein eigener an.
Ich hatte mehrmals Lust, eine Notiz beim Nachbarn unmittelbar zu verbessern — sie war unvollständig, ich wusste, was hineingehört, und es hätte mich dreißig Sekunden gekostet.

Die Regel bleibt deshalb unverändert: Was ich ihm zu sagen habe, ist ein Vorschlag, und die Entscheidung gehört dem Empfänger.

##### Löschen, ohne die Nachvollziehbarkeit zu zerstören

Das Löschen verlangt eine eigene Regel, und ich habe sie beim Leeren einer Zwischenablage gelernt.

Wenn eine Notiz den `Kontext` wechselt, bleiben die Quellen, die sie hervorgebracht haben, zurück.
Sie können allein dastehen, ohne dass noch eine Notiz mit ihnen verknüpft ist.

Der Reflex ist aufzuräumen.
Das ist nur teilweise richtig.

Eine schon gelesene und in Notizen verwandelte Quelle darf gelöscht werden: Was sie enthielt, lebt anderswo.
Eine Quelle, die noch niemand gelesen hat, darf nicht gelöscht werden.
- Sie trägt Material, das niemand herausgezogen hat, und sie wegzuwerfen heißt zu verlieren, was man nicht einmal geöffnet hat.

Das Kriterium ist also weder das Alter der Datei noch der Platz, den sie belegt.
- Entscheidend ist, ob die Quelle bereits gelesen wurde und was sie noch zitiert.

Eine Bedingung gehört dazu, und sie ist nicht verhandelbar.
Vor dem Löschen prüfen, dass keine Notiz, kein Glossareintrag, kein Entwurf und keine Zeile des Journals diese Quelle noch zitiert.
Ohne diese Prüfung zerstört die Regel die Nachvollziehbarkeit, die sie eigentlich schützen soll.

##### Eine Abweichung ist kein Fehler

Bleibt der Fall, dass zwei `Kontexte` über dasselbe Thema nicht dasselbe sagen.

Der Reflex ist, darin eine Unstimmigkeit zu sehen und also schnell zu entscheiden, um die Ordnung wiederherzustellen.
Das ist oft falsch.

Eine Abweichung kann auf einem unterschiedlichen Geltungsbereich beruhen: Jeder kann innerhalb seiner eigenen Grenzen recht haben.
Sie kann eine noch offene Annahme sein, die der eine untersucht und von der der andere nichts weiß.
Sie kann aus zwei Lesarten bestehen, die beide gelten, weil sie das Thema von zwei Orten aus betrachten.

Dann verdient sie, als solche bewahrt zu werden, und darüber entscheidet die betreffende Person.
Was das System sichern muss, ist, dass man von ihrem Bestehen weiß.

Eine vergessene Abweichung meldet sich am Ende immer im schlechtesten Moment: wenn sich jemand auf eine der beiden Fassungen stützt, ohne zu wissen, dass die andere besteht.
Genau das ist mir bei der Abschlussregel geschehen, nur dass es nicht zwei Lesarten waren, sondern eine einzige, die gealtert war.

Ein verlässliches Netz hat also seinen Preis, und ich benenne ihn lieber, als ihn in der Durchsicht zu entdecken.
Zwei `Kontexte` zu verbinden beseitigt die notwendige Wachsamkeit nicht: Es macht sie möglich und überträgt die Verantwortung dafür auf den Menschen.

Das ist im Grunde das, was dieses Buch von Anfang an erzählt.

> [!note] Zum Merken — der Preis des Netzes
> Ein Verweis kann unbemerkt altern, eine Kopie kann ihre Herkunft verlieren: Jeder Vorgang bringt eine Verpflichtung mit sich, und sie muss dokumentiert werden.
> Lesen berechtigt nicht zum Schreiben; was man dem Nachbarn zu sagen hat, ist ein Vorschlag, nie eine Verbesserung.
> Eine schon in Notizen verwandelte Quelle darf verschwinden; eine nie gelesene Quelle nicht — und nichts wird gelöscht, ohne zu prüfen, wer sie noch zitiert.
> Zwei `Kontexte`, die einander widersprechen, haben nicht zwangsläufig unrecht: schlimm ist, es zu übersehen.

## Abschluss

Das Buch hört hier auf, das Thema hört nicht mit ihm auf.

Der Epilog sagt, wo diese Arbeit steht, was sie nur gestreift hat und wo ihre Fortsetzung erscheinen wird.
Die Verwandtschaften ordnen den `Kontext` unter die Ansätze ein, die ihm vorausgingen oder ihn umgeben, damit du weißt, was er übernimmt und was er nicht übernimmt.
