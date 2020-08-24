# ISAQB-Seminar @zoom at Software Quality Labs

- Stephan Christman is lecturer
- no presence training - just via Zoom

## 20200824 - day 1

- erstmal Grundbegriffe und Defintionen, was ist Architektur?
- Kommunikation, Dokumentation - Sprache zu Anderen
- wie bewertet man architekturen?
- wie merkt man, dass architektur aus dem ruder läuft? maßnahmen?
- bei SoftwareQualityLabs scheinen alle zu bestehen; auch bei denen, die am Donnerstag gleich die Prüfung machen; gut machbar

- Herr N. arbeitet curtis instruments in biberis schweiz; medizinbereich, handcontrols für elektrische rollstühle; mölchte lernen bei einer legacy software die architektur gerade zu rücken; .NET und Xamarin
- Herr Lindecke-Klein; Uxmar in Kiel; dienstleister im bereich usability; maschinenbau; 25 jahre erfahrung; mappen von kundenanforderungen auf ISO läuft, aber wie kann man das auf eine architektur herunterbrechen; großer Freud von Ralph Westphal mit seinem "Flowdesign"; arc42 Vorlage in einem Projekt
- Herr H.; DAimler; Automotive-Bereich; autonomes Fahren; Bosch oder auch nvidia; backend; auch product owner; Überzeugung und Kommunikation; C4-Model (?); Kontext und Diagramme vereinheitlichen; Wissen bestätigen; neue Aspekte kennenlernen
- Herr Christmann als Tutor: TU Berlin Informatik; Künstliche Intelligenz; wissensbasierte Systeme; Embedded Bereich; Projektleiter; Teamleiter; "Qualität" am Ende; so spannend; dann zu Software Quality Lab; dort zufrieden; "wie kann man Qualität sicherstellen"?
-- Bereiche: Beratung; A-Spice-zertifizierung; Prozesses, klassisches Academy-Geschäft (UML, Scrum, Requirements; Testing; ..); operatives Geshäcft (Testmanager) - "Vorarlberg ist klein"; Frameworks entwickeln; kodieren; Werkzeuge (nicht nur nebenher anschaffen ..),
- Was kann man tun, damit man nachher nicht versucht zwanghaft Qualität hineinzutesten. Sondern, dass Qualität von Anfang an entsteht?
- Presencetrainings auch wieder machbar, da Masken doch recht gut schützen.

- Lernen mit "DEM Buch"; unklar welches Buch; ein Teilnehmer hat ein orangenes; meines ist grün
- Trainer sagt, dass das Buch - Nachfragen wegen Buch bei Organisatorin/nen

- aushandeln, wann man beginnen möchte
- drei Pausen: nach 1,5 h pause, 12 uhr mittagspause; dann 14 uhr eine weitere (kleine = 15 min Pausen)

------------------------
### Grundbegriffe

- keine einheitliche defintion von Architektur: auf eine Def. geeinigt
- Welche Rolle nimmt der Architekt ein? Skills? Was ist wichtig? Welche Kommunikation? Reicht es ein brillianter Techniker zu sein?
- SW-intensive Systeme
- Architektur stellt immer einen Kompromiss dar: stark und minder ausgeprägte Kategorien
- metapher der gebäudearchitektur: wird oft synonym verwendet; in bestimmten aspekten ähnliche betrachtungsweise; Strukturen um ein komplexes Problem verständlich machen durch Abstraktion;
- umldiagramme: sequenz-d., ..
besteht aus verschiedenen Sichten
- Informationen rausnehmen, die für diesen Fokus nicht relevant sind; andere informationen hervorgehoben: siehe 3d-ansicht; grundriss oder elektroplan
- Entwurfsentscheidungen sschaffen Raum für Flexibilität: nachträgliche Änderung möglioch, aber vielleicht nicht ökonomisch machbar
- im Rahmen ist das System gut anpassbar; außerhalb nicht
- Cloud, Microservices, ... frühere Zeiten andere Ansätze (keine Redundanz; Hardware teuer; ja nichts vielfach haben)
- falls sich die Kontextbedingungen ändern, muss das System anpgeasst werden. Vorschau i die Zukufnt nur begrenzt möglich
- wie sieht der Problembereich aus? Sichten und Abstraktionen helfen -> Qualität schaffen

- welche menge an defintionen gibt es?
- EX! übung: welche begrifflichkeiten kommen in nallen sechs defintionen vor?
-- components; relationship between components; environment; innensicht/außensicht; constraints, fundamental; system; Orgranisation
-- Result:
--- Komponenten/Bausteine mit Schnittstellen und Beziehungen (Komponenten ist Baustein, aber nicht jeder Baustein muss eine Komponente sein; Ausprägung)
--- Bausteine als  allgemeiner Begriff, Komponenten als spezielle Ausprägung davon (Stereotyp Component?)
--- (cost cuttin concerns (?)) - nicht alles kann beliebig aufgeteilt werden
--- übergreifende entwurfsentscheidungen mit systemweiten oder den gesamten lebenszyklus betreffenden Konsequenzen (Architekt sollte sich mit Desing auskennen; gensauo wie umgekehrt)
--- (Desing als Verfeinerung der Architektur)

was muss ein Architekt können?
- reicht es aus sich mit der Technik auszukennen?
- Architektur immer als Kompromiss; eierlegende Wollmilchsau nicht möglich; bedingt durch die Einflußfaktoren (die zum Teil in Widerspruch stehen)
- Anforderungsanalyse: dort sollte der A. mitarbeiten: Anforderungsmanagement; so ist es möglich fürhzeitig ein Feedback zu geben; mit Produktmanagement und PO; auch Prüfung der Machbarkeit; Kosten; Reliablity; Portability; .. haben hohen Einfluss auf die Archtitektur, aber oft nicht explizit genannt
- mitmachen beim RE! (nicht nur, aber involviert sein)
- Prototypen anfragen
- Anforderungen; Priorisierung; Releases- & Iterationsplan
- Hardwareentwicklung: Abgrenzung HW und SW; 
- Qualitätssicherung: Risikenm, Zeitplan, Testkonzept, Testbarkeit, Testautomatisierung vorbereiten
- IT-Betrieb:
- Projektleitung: projektplan; Entscheidung über Umfang, Konste, Zeitplan
- es reicht nicht nur technisch brilliant uafgestellt zu sein; sondern man muss kommunikativ gut aufgestellt sein; kompromisses schließen, leute abholen, win-wion-situationen schaffen, .. nicht nur in hinsicht auf die reine funktionalität
- verständnis über das System herstellen; dependency injection, observer pattern, states, .. so erklären, das leute auch außerhalb mitreden können
- raum schaffen leuten zuzuhören, die tenisch versiert, aber introvertiert sind
- sechs stakeholder teilweise auch im konflikt
- PO wird an features bemessen; dev technisch anspruchsvolle lösung; PM cost-cutting ..
typen der sw-intensiven systeme: informationsS, embedded S, mobile SW
- Informationssystem:
-- darstellung und strukturierung der information sehr wichtig für die akzeptanz des systems; entscheidungs- und unterstützungssystem
- Entscheidungsunterstützungssysteme; Expertensysteme; Suchmaschine; Büroautomatisierung
- architektur im wasserfallmodell: rückschritte/rückmeldungen möglich; aber nur zum nächstvorderen schritt; führt zu problemen, der kunde wird seine lösungswünsche anpassen, also das ziel bewegt sich
- V-modell als verfeinerung: aber trotzdem noch ein phasenmodell
- man(n) hat haufig mit unvollständiger information zu tun; iterative architektur-entwicklung dann als natürliche folge; inkremementelle entwicklung
- Scrum in Grundzügen: Selbstheilung durch iterative abwicklung; transparent umsetzung der "dinge"; klare Aufteilungen; falls man etwas direkt nach Sprint ändern will - weiß der PO eigentlich was er (oder die stakeholder) wollen?; oder falls team nicht performt, sollte man nachbessern; zielen bei moving target einfacher; product backlog, sprint backlog
- welche folgen für die architektur (scrum): innerhalb des teams mit PO und Team zusammenarbeiten; was, wenn man aber einen zentralisitischen ansatz für die frameworks hat? in drei wochen kann man die nicht so viel umsetzen, viel, viel initialisierungsaufwand; aber wir sind nicht allein mit diesem problem, Krücke (Hilfe) der Nullsprints: 2-3 sprints mit durchstich technisch die basis legen (tooling und mit sonstigen dingen, die man benötigt; mit timeboxed events); oder am anfang iust das potential shipable product "so dünn"; vielleicht am anfang nur ein "login screen"; und nebenbei die architektur entwicklen; oder eben iterativ-inkrementell
- [Pause bis 10:55 Uhr]

## Ebenen der Architektur:
- Themen bisher: Bausteine, Schnittestellen, Definition der Begrifflichkeiten, 
- [check this] conways law: organisiation und teamstruktur stehen in wechselwirkung zueinander; kommunikatinsstruktur ist eine kopie der systemstruktur; melvon conway 1968
- kann man teams aufteilen, wenn man bausteine nicht entkoppelt? nur mit hohem orga-aufwand
- technische lösung sollte zur orga-struktur passen; also die technische lösung; das kann zu viel negativem feedback führen
- 4 teams working on a compiler -> four pass compiler
- falls man eine schichten architektur: gui, logick datenbank hat -> dann drei teams
- architekten in jedem team: abstimmung der architekten (zentral); aber sehr hoher overhead für die abstimmung; quelle von missverständnisse?
- vor- und nachteile zentraler und dezentraler architektur?
- Ex! Übung 1.1.1. Zentrale versus dezentrale Architektur

Zentrale Architektur:
+ verbindlich für alle Teams; gut für die Durchschnittsthemen; Vermeidung von Doppelaufwänden; homogene Lösung
- nicht flexibel; langsamer aufgrund von Anpassungen (initial); Abstimmung der Vorgabe mit vielen Teams, Konfliktpotential; Hammer/Schraube-Problem; Auseinanderdriften von legacy Ansätzen

Dezentrale Architektur:
+ Hammer/Nagel; Fokussierte Lösung problembezogen; Schnittstellen fokussiert; initial schneller, Knowhow kann steigen (technscihe Vielfalt zum Lernen)
- Gefahr technischer Schulden; Abstimmungsbedarf ist größer; Redundanz; Latenzen; System ist mehr als die Summer aller Teile; Lokale Optimierungen; Einflüße schwer zu behrrschen -> sehr präzise Schnittstellenbeschreibungen notwendig; Integration ggfs. schwierig

--> Architektur nich tim Elfenbeinturm entwickeln

## Einflußfaktoren
- randbedingungen schreiben lösunsräum vor
- WAS: funktionale anforderungen beschreiben, was gemacht werden soll; Funktio, Verhalten, Strukturen
- nichtfuntkionale A., Qualitätsanforderung: natürlichsprachig dokumentiert (daher meist ncith qualifizierbar); daher messbar machen was nicht messbar ist; "ein schönes userinterface", "ein schnelles system"; quantifizierbar machen; Zeiten, Usability (entsprechend einigen Regeln);

ISO 25010: listet Qualitätsmerkmale; diese sichten
- Basis um mit der Fachlichkeit die Diskussion zu starten .. [TODO anschauen; definitiv]
-- Funktionale Eignung, Zuverlässigkeit, Benutzbarkeit, Performance, Sicherheit, Kompatibilitöt, Wartbarkeit, Portierbarkeit
-- Beispiel: "schnell" je nach Sichtweise subjektiv: 10s kann für ein Dokument-Öffnen für den Dienstleister ok sein, aber nicht für Anwender (-> Zeitverlust akkumuliert sich schnell übers Jahr, daher auch Geldverlust)
- Begriff der Testbarkeit

- Architekturziele sind Qualitätsmkermale
- Projektziele versus Architekturziele: Porjektleiter bleibt "Chef", SA weist auf die Risiken und Alternativen hin

- Einflußfaktoren stehen in Wechselwirkung; und stehen zum Teil im Gegensatz "Security versus Benutzbarkeit"
- je nachdem wo man die Lösung platziert, sind manche Einflußfaktoren sehr gespannt
- deshalb ist Kommunizieren und proaktives Abholen der Beteiligten notwendig

- [check this!] Kano-Modell:
-- müssen alle Anforderungen umgesetzt werden um den Kunden zufriedenstelen?
-- Basisfaktoren: definitiv; Kunde wird diese nicht nachfragen; Kunde wird diese nicht nachfragen im Erfolgsfall; maximal Nulllinie
-- Leistungsfaktoren: mehr machen als die Konkurrenz -> auslieferbar
-- Begeisterungsfaktoren: dazugepackt; Kunde weiß eigentlich gar nicht, dass das geht; ist begeistert
-- damit sehr bewusst umgehen und einen schönen Mix anbieten -> gutes Produktmanagement
- Menschen sind aber sehr schnell verwöhnt

- explizites versus implizites Wissen:
- Zusammenhang mit Basisfaktoren: eis über wasseroberfläche: sachen, die explizit kommuniziert werden
- unter Wasseroberfläche: 2/3 des eisberges sind unsichtbar; nicht kommunizert, Annahme, dass andere es gleich interpretieren
[Pause bis 12:50]

- [Ex!] Übung 1.1.2
-- "willleihen": Idee für webapp zum nachbarschaftlichen Ausleihen von Werkzeugen (am Wochenende)
-- Seite 19ff in dem ÜbungsPDF sind die Anfangsdaten für die "App"
-- Fokus auf die nichtf. Anforderungen und Qualitätscharakteristiken nach ISO 25010 (Checkliste) --> see: ISO25010.png
-- Fragen zur Spezifikation an Trainer stellen; er ist der Auftraggeber
My notes:
-- Nichtfunktionale Anforderungen:
--- Ressourcenverbrauch
--- Performance (1000 Anfragen /Minute; 3 Sekunden Antwortzeit) -> was ist eine Anfrage? Wie sieht das im API aus?
--- Datenschutz (Vertraulichkeit)
--- Benutzbarkeit für Oma
--- portierbarkeit (für mobile Systeme)
--- Datensicherheit
--- Zuverlässigkeit (Zurückgeben muss technisch gewährleistet sein)

-- Randbedingungen
--- Geschäftsmodell
--- Provision
--- Landkarte darstellen (woher?)
--- Teamgröße (wieviele Leute eigentlich zur Verfügung?) 4 Entwickler, 1 Tester, 1 Scrum-Master, 1 PO (CEO)
--- Rechtliche Aspekte: DSVGO
--- Zeit und Budget?
--- Partnerschaft mit Social Networks zum Authentifizieren

-- Wechselwirkungen
--- 2/4/i (see the use cases ..)
--- 3/b/a
--- 9/4/e
--- 7/e

# Systemabgrenzung
- Systemkontext: Diskussion sehr gut mit Fachbereichen machbar
- guter Projektleiter wird aber das gleiche machen: erstmal checken, was ist innerhalb und was ist außerhalb der Systemgrenzen; wen zum Meeting einladen, wen nicht?
- anfangs die Systemgrenzen unscharf
- Datellungsformen: Use-Case-Diagramm (Stärke und das Ziel; auf innere Darstellung kann verzichtet werden; Abhängigkeitsbeziehung; Pfeil immer in Richtung der Abhängigkeit; von Akteur zu 'use'; Person oder anderes Steereotyp, Aussagegehalt recht groß); Komponentendiagramm
- [Ex!] Willleihen als Use-Case-Diagramm: see WillLeihenUseCase.png
-- DomainDrivenDesign: Unter welcher Fragestellung wird das UseCasediagramm gerade modelliert?
--- Google: BusinessBenefits/BusinessCases? wer ist von wem abhängig?
--- WL (WillLeihen): -> aus dem Diagramm entstehen recht viele MakeOrBuy-entscheidungen; da Top-down, kann man dasmit vielen diskutieren, sehr schnittstellenbasierte Sicht
--- da wo immer die Spoitze in dem Diagramm ist, muss eine Schnittstelle angeboten werden
--- Zeitaufwand für Code-Änderungen: Einlesen 70%; Programmieren 10%, Problem Lösen 20%
--- Übergang von Black- zu Whiteboxing: weiterhin sehr schnittstellenorientierte Sicht
--- Arten von Bausteinen von feingranular to grobgranular: fließend
--- auf hohe Kohäsion achten, fördert meist auch geringe Kopplung
--- Sachen eher lose koppeln, weil besser testbar
--- Beispeil mit niedriger Kohäsion; zwei Komponenten greifen gegenseitig aufeinander zu (S1 und S2 auf ABCD..); schlecht testbar
--- divide et imperae, zwischen fachlicher und technischer Art zu unterscheiden, dinge einfach wie möglich zu machen, separation of concerns, single responsibility principle
--- ein baustein macht genau eine sache; leichter wartbar (und testbar)
--- resue and release equivalence principle
--- wenn man dinge nur teilweise für die wiederverwendung vorsieht, sollte man sie trennen. ganz oder gar nicht.
--- common-closure-principle: externe lib ändert sich schnell, adapter dazwischenpacken um sich zu entkoppeln
--- common-reuse-principle: nicht anderen meine abhängigkeit aufdrücken; eventuell komponentenfuntkionalität splitten und dann getrennt releasen

- klare Trennung zwischen fachlicher und technischer Architektur:
-- techn. Architektur: nichtf. Anforderungen, Querschnittskonzepte, hjarware, Gateway für Security, Proxy für Cachcing, 2. Server für Ausfallsicherheit; eher horizontal geschnitten
-- fachliche A.: (siehe Übungszettel); eher vertikal geschnitten

[check!] i18n ? was ist das? "The terms are frequently abbreviated to the numeronyms i18n (where 18 stands for the number of letters between the first i and the last n in the word internationalization, a usage coined at Digital Equipment Corporation in the 1970s or 1980s)[3][4] and L10n for localization, due to the length of the words.[5][6] Some writers have the latter acronym capitalized to help distinguish the two.[7]" en.wikipedia.orga-aufwand

- Dinge so einfach wie möglich machen; viel Text zu schreiben ist immer einfach, aber geht es nicht auch einfacher?
- eine Hierarchie verstehet jeder einfacher als wenn jeder von jedem abhängig ist

-- Entwurf Top-down (schnelles reingleiten, nicht allzu verkopft; aber Integration wird etwas vor sich hergeschoben; Reibungsverluste bei fianler Integration trten spät auf) und Bottom-up (Verfeiner die BlackBox indem du Inhalt als WhiteBox zeigst; Inhalte sind weitere BlackBoxes, verfeiner auch sie)
-- kein shipable work-increment possible (Top Down)
-- 7+/-2 ist gute Faustregel für (Millersche Zahl) Zerlegung und Visualisierung

-- Fachliche Bausteine aus Fachobjekten herleiten
-- wording: am besten in Muttersprache; am besten wegen dem größeren Wortschatz und Feinheiten
[Pause bis 14:55]

[Ex!] Aufteilung der Ports (nach außen) - fachlicher Art: see Day1_Schnittstellen.png
- [check this] IAM: Identity-and-Access-Management (Registrierung; Authentifizierung; Authorisierung - all in one); see https://en.wikipedia.org/wiki/Identity_management
- nur Nutzung beschreiben, aber keine Datenflüße abbilden! siehe: werbenetzwerk und Werbung und SAE-Logik
- Dinge, die zusammengehören, auch zusammen gruppiert. Use-Case-Prinzip mit Akteur als Generalisierung und Spezialisierung auch machbar
- welche Komponenten essential wichtig? die mit den meisten Kanten
- welche Komponenten priznipiell instabil: emhr ausgehen Kanten als eingehende; siehe SAE-Logik (wird kritische Komponente werden)
- in der Diskussion ist das Problem einen Schritt klarer geworden :)

## Zusammenfassung Tag 1:
- siehe: (als Bild)  Day1_Zusammenfassung.png
- Architektur ist die Verortung von Funktionalität; damit nichtfunktionale Anforderungen erfüllt werden
- Projektziele vs. Architekturziele (Architekturziele eher längerfristiger Natur; Projektziele sind kurzfristig)
- BausteineKomponenten
- Sichten: jeweiligen Stakeholdern eine Lösung erklären, darlegen (aspektorientiert)
- Unterschiedliche Ziele der Stakeholder
-- sechs Stakeholder: Projektleiter, Testmanager, RE-Ingenieur, Entwicklungsteam, Hardware (!), IT (alles zum Laufzeitverhalten)
- Kommuniktionsfähigkeit des Architekten: Konfliktfähigkeit, Zuhören, proaktives Handeln (nicht Warten bis das Problem übermächtig wird; sich Arbeit machen)
- Softskills
- ISO 25010: mindestens drei davon benennen können
- Wechselwirkungen
- Conway's Law: Organisation wirkt auf die Lösung; Lösung wirkt auf die Organisation
- Organisatorische Randbedingungen
- Einflußfaktoren
- Systemkontext: Rollen; externe Ressourcen/systeme, die einwirken
- Separation of concerns: (nicht verwechseln mit Single-Responsibility): Aspekt nicht selber aufteilen [check this]
- Top-Down vs. Bottom-up: was ist besser? beides. TD + schnittstellenfokusiert; BU: sehr konrekt; verheddern in Details
- Teile-Hersche: Vorteil: Komplexitätsreduktion
- Resue-release-Äquivalenz-Principle: externe Ressourcen komplett nutzen oder eventuell Refactorisieren
- Common closure-principle: 
- Kohäsion
- Kopplung: lose gekoppelt, hohe Kohäsion
- KISS: Verständnis fördern

Hausarbeit für Morgen:
- zu allem, was man heute gehört hat, sich eine MultipleChoice oder "Ja/Nein"-Frage überlegen (siehe zu der Übersicht Zusammenfassung)
