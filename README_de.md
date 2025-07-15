# Prinzipien der Barrierearmut

_Ein Satz an übergeordneten Leitprinzipien für den Umgang mit Barrierefreiheit im Web._

-   [Perfektion ist der Feind](#perfektion-ist-der-feind)
-   [Standardmäßig oder Tod](#standardmäßig-oder-tod)
-   [Gleichwertigkeit ist oberstes Gebot](#gleichwertigkeit-ist-oberstes-gebot)
-   [Design für die Umsetzung](#design-für-die-umsetzung)
-   [Struktur zuerst](#struktur-zuerst)
-   [Nutze deine Worte](#nutze-deine-worte)
-   [Tools sind keine Identitäten](#tools-sind-keine-identitäten)
-   [Weniger ist weniger](#weniger-ist-weniger)
-   [Werde bezahlt](#werde-bezahlt)
-   [Angeln, nicht Fische geben](#angeln-nicht-fische-geben)
-   [Keine Punkte für Show](#keine-punkte-für-show)
-   [Lass das Böse verrotten](#lass-das-böse-verrotten)

## Perfektion ist der Feind

Nichts ist – und kann – zu 100 % barrierefrei sein. Wer das behauptet, lügt oder versteht Barrierefreiheit nicht – meist beides. Es ist in Ordnung, nicht vollständig barrierefreie Arbeit abzuliefern, solange sie _barrierefreier_ ist. Tu, was im Rahmen der Gegebenheiten möglich ist. Wenn die Rahmenbedingungen unzumutbar sind, stell diese zuerst infrage. Du denkst vielleicht, du bist nicht die perfekte Person für Barrierefreiheit – aber _du bist da_. Verlass dich nicht auf abwesende (oder nicht existierende) Barrierefreiheits-Superheld\*innen.

## Standardmäßig oder Tod

Barrierefreiheit funktioniert nicht als Plugin, Add-on oder Opt-in. Wenn eine Oberfläche anbietet, Barrierefreiheit zu _aktivieren_, ist sie nicht barrierefrei. Ein Schalter mit zu wenig Kontrast, der hohen Kontrast „einschaltet“? Game over. Barrierefreiheit im Nachhinein drüberzustülpen funktioniert grundsätzlich nicht. Die konkreten Features solcher Third-Party-Overlays sind irrelevant. Wehre dich konsequent gegen diese _nachträgliche_ Denkweise. Ein MVP ohne Barrierefreiheit ist nicht – auch nicht minimal – „viabel“.

## Gleichwertigkeit ist oberstes Gebot

Es geht nicht darum, eine bessere oder gute Erfahrung zu schaffen – sondern eine _vergleichbare_. Interfaces dürfen nicht für einige schwer und für andere leicht sein. Manche Interfaces sind nun mal komplex und manche Inhalte schwer verständlich – du kannst nicht entscheiden, wer sich dafür interessiert oder damit umgehen kann. Wenn ein Bild einen Witz darstellt, sollte der Alternativtext _denselben Witz_ auf andere Weise erzählen, nicht den Witz erklären. Ob der Witz beleidigend ist oder nicht verstanden wird, betrifft _Inklusion_, nicht Barrierefreiheit.

## Design für die Umsetzung

„Form folgt Funktion“ – aber viele Organisationen designen zuerst und entwickeln danach. Visuelle Entwürfe lassen zu viele Umsetzungsfragen offen, und Entwickler\*innen werden animiert, die Optik über die Usability zu stellen. Drag-and-Drop braucht Buttons für die Tastatur – und die müssen im „Design“ erscheinen. Als Accessibility-Pro solltest du früh mitreden, konzeptionell. Denn Funktion kommt vor Form. Und Funktion muss barrierefrei sein.

## Struktur zuerst

Eine schlecht strukturierte Oberfläche kann technisch WCAG-konform sein. Eine gut strukturierte, intuitive Oberfläche kann mehrere WCAG-Fehler enthalten – und trotzdem barriereärmer sein. Automatisierte Tools finden nur Einzelfehler. Du musst das große Ganze im Blick haben: Was verwirrt oder überfordert Nutzer\*innen? Wo entstehen Stolpersteine? Verschwende keine Zeit mit dem Abhaken einzelner Kriterien, wenn die Gesamtstruktur Schrott ist.

## Nutze deine Worte

Ein großer Teil von Barrierefreiheit bedeutet: Texte bereitstellen. Buttons, Links und Inputs brauchen Labels. Titel und Überschriften sind auch Labels. Statusmeldungen beschreiben Zustände. Labels zu vergeben reicht aber nicht – der _Text_ ist entscheidend. Gute Texte kann man nicht automatisieren. KI kennt deinen Kontext nicht. Lerne schreiben und redigieren – oder hol dir Leute dazu, die das können.

## Tools sind keine Identitäten

Eingeschränkt sein ist genauso wenig wie nicht eingeschränkt sein. Screenreader-Nutzer*innen nutzen verschiedene Tools, auf verschiedene Arten, für verschiedene Zwecke. Es gibt *nicht* den typischen Screenreader-User. Also: Designe nicht *für* Screenreader-Nutzer*innen – designe _für die Fähigkeiten_ von Screenreadern. Menschen kann man nicht quantifizieren – Inputs und Outputs schon.

## Weniger ist weniger

„Weniger ist mehr“? Falsch. Weniger ist einfach weniger – und das ist gut. Viel zu oft wird etwas gebaut, nur weil man es kann oder weil andere es gemacht haben. Hör auf damit. Je mehr wir bauen, desto komplexer wird alles – und desto eher geht’s schief. Nicht nur technisch, sondern vor allem beim Verstehen. Meistens sollten Komponenten einfach nur _Inhalt_ sein. Versteck Inhalt nicht hinter Buttons. Eine Liste in ein Tab-Interface zu verwandeln ist keine Verbesserung – sondern Angeberei mit Nachteilen.

## Werde bezahlt

Lass deine Leidenschaft für Barrierefreiheit nicht ausnutzen. Wie jede Arbeit verliert auch Accessibility-Arbeit an Wert, wenn sie gratis gemacht wird. Es ist kein Bonus, kein Hobby, keine Wohltat. Es ist _essentieller_ Teil von UI-Design. Wenn du dafür bezahlt wirst, musst du dafür auch offiziell zuständig sein. Accessibility gehört in die Rollenbeschreibung. Wenn „alle zuständig“ sind, ist oft niemand zuständig. Hüte dich vor dieser Rhetorik.

## Angeln, nicht Fische geben

Barrierefreie Produkte brauchen barrierefreie Prozesse und Organisationen. Heute kannst du gute Arbeit abliefern – aber wer macht’s morgen? Oder macht’s morgen kaputt? Accessibility heißt vielleicht: ein Frontend-Team mit Accessibility-Skills. Oder ein CMS zu ersetzen, das keine barrierefreien Outputs liefert. Oder Redakteur\*innen zu schulen. Wenn du alles allein fixst – bleibt es nicht lange gefixt.

## Keine Punkte für Show

Firmen wollen _so tun_, als ob sie Barrierefreiheit ernst nehmen – statt es wirklich zu tun. Sie stellen Profis ein, geben aber keine Ressourcen. Sie machen Tests mit Betroffenen, ignorieren aber die Ergebnisse. Sie bezahlen für Audits, setzen aber keine Empfehlung um. Sie bestehen auf Kontrastprüfung – aber nicht, wenn's ihre CI betrifft. Willst du wirklich was bewirken? Besteh auf _Praxis statt PR_.

## Lass das Böse verrotten

Manche Produkte sind von Natur aus toxisch: süchtig machend, hasserfüllt, desinformierend. Solche Systeme (und die Firmen dahinter) lassen sich nicht reformieren – egal, was sie dir erzählen. Opfere dich nicht auf, um das Unrettbare zu retten. Ihr Scheitern ist _nicht_ dein Scheitern. Schütze deinen Ruf und deine mentale Gesundheit. Es gibt genug Inaccessibility – such dir lieber Projekte, die es wert sind.
