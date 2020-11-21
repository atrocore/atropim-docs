# Erste Schritte – wie kann man das System richtig konfigurieren?

Damit die Produktdaten qualitativ sind, müssen die Hauptentitäten, die im System verwendet werden, vor dem Beginn der Systemnutzung richtig konfiguriert werden. Die Bezeichnung “Entität” wird für Module oder Tabellen mit strukturierten Daten verwendet, die im System mit einem bestimmten Zweck gespeichert sind. Also, als Entitäten gelten die Kategorien, Kanäle, Assoziationen, Kataloge usw. Die Entitäten können miteinander verknüpft werden, so z.B. kann ein Produkt gleichzeitig zu mehreren Kategorien gehören. 

Der Anwender muss nicht unbedingt alle verfügbaren Entitäten verwenden. Braucht er irgendwelche Entitäten nicht, können diese einfach deaktiviert werden, und umgekehrt, falls man noch weitere Entitäten benötigt, können diese zusätzlich erstellt und mit bestehenden Entitäten verknüpft werden.

In diesem Artikel gehen wir von den Anforderungen eines durchschnittlichen Anwenders aus, der alle Entitäten braucht. Im Nachgang werden wir erläutern, welche Entitäten für die vollwertige und effektive Arbeit des Systems konfiguriert werden sollten. 

## Attribute konfigurieren

Das Produktattribut bestimmt eine gewisse Eigenschaft eines Produktes. Dank der Typisierung der Attribute sind ihre Werte auch typisiert. So werden die Produktattribute nicht nur verwendet, um das Produkt allseitig und vollwertig zu beschreiben, sondern auch bei den Filtern, um dem Endkunden dabei zu helfen, das nötige Produkt schneller zu finden. Gerade deshalb ist die Produktbeschreibung mit den Attributen sehr wichtig. Typische Attribute für Kleidung sind z.B. Größe und Farbe. 

Bei AtroPIM gibt es 14 Attributtypen. Die Nutzung von Attributtypen ist für eine bessere Typisierung und entsprechende Validierung der Daten im System nötig. Für nähere Informationen zu Attributen und ihren Typen lesen Sie bitte die [Dokumentation](https://github.com/atrocore/atropim-docs/blob/master/en/user-guide/attributes.md). 

Für nähere Informationen zur Konfiguration der Produktattribute lesen Sie den Artikel: [“Wie kann man die Produktattribute erstellen?”](./wie-kann-man-die-produktattribute-erstellen.md).

## Assoziationen konfigurieren

Assoziationen werden für die Speicherung diverser Beziehungen zwischen den Produkten genutzt. Solche Beziehungen mögen den potentiellen Kunden aus verschiedenen Gründen interessant erscheinen – der Eine möchte Ersatz für ein vorhandenes Produkt kaufen, ein Anderer kann Interesse an bestimmten zugehörigen Produkten haben usw. Assoziationen können sowohl einseitig (Produkt A ist mit dem Produkt B assoziiert, aber nicht umgekehrt) als auch zweiseitig (ist Produkt A mit dem Produkt B assoziiert, dann ist auch Produkt B mit dem Produkt A assoziiert) sein. 

Bei AtroPIM kann jeder User selbst die Beziehungstypen konfigurieren, die er zu benutzen beabsichtigt. Typisch sind folgende Beziehungsarten: 

-   Replaces
-   Is replacement of
-   Cross-Selling
-   Up-Selling
-   Consist of
-   Is Part of
-   usw.

Für nähere Informationen zur Erstellung der Produktassoziationen lesen Sie den Artikel [“Wie kann man eine vollwertige und qualitative Produktbeschreibung in 6 Schritte erstellen. Schritt 5.”](./produktbeschreibung-in-6-schritten.md#schritt-5-geben-sie-assoziierte-produkte-an).

## Produktfamilien konfigurieren

Die Definition einer Produktfamilie ist der erste Schritt für eine Segmentierung des Produktsortiments des Anwenders. Man braucht Produktfamilien, um die Beschreibungen der Produkte einer Art zu vereinheitlichen. Produktfamilien bestimmen, welche Attribute ein Produkt von dieser Produktfamilie haben soll. 

Für nähere Informationen zur Konfiguration der Produktfamilien lesen Sie den Artikel: [“Wie kann man die Produktfamilien erstellen?”](./wie-kann-man-die-produktfamilien-erstellen.md).

## Kategorien konfigurieren

Man verwendet Kategorien zur Gruppierung der Produkte zu Vermarktungszwecken. Die Kategorien helfen Endkunden, das gewünschte Produkt schneller zu finden. So werden die Kategorien fast in jedem Onlineshop und bei jeder Handelsplattform genutzt. Mittels der Zuordnung einer Kategorie zu einer Parent-Kategorie können die Kategorien Kategoriebäume bilden. So kann man in AtroPIM mehr als einen Kategoriebaum erstellen. Jedes Produkt kann einer und mehr Kategorien zugeordnet sein. 

Der größte Unterschied zwischen Kategorien und Produktfamilien liegt darin, dass ein Produkt mehrere Kategorien, aber nur eine Produktfamilie haben kann. Die Produktfamilie bestimmt, welche Produktattribute bei einem Produkt auszufüllen sind, damit die Produktbeschreibung als qualitativ gilt. Eine Kategorie dagegen dient ausschließlich Marketingzwecken – das Produkt soll von einem Kunden schneller und einfacher gefunden werden.

Durch die Zuordnung eines Produktes zu einer bestimmten Kategorie kann der Kanal mitbestimmt werden, welchem die Produktdaten zu übergeben sind.

Für nähere Informationen zur  Produktkategorisierung lesen Sie den Artikel: [“Wie kann man die Kategorien konfigurieren?”](./wie-kann-man-die-kategorien-konfigurieren.md). 

## Kataloge und Kanäle konfigurieren

Kataloge können im System dafür verwendet werden, unterschiedliche Produktsortimente, Kataloge von verschiedenen Lieferanten oder unterschiedliche Versionen von eigenen Katalogen zu verwalten. Es kann ein Masterkatalog erstellt werden, dem die Daten von anderen Katalogen zufließen.

Kanäle sind die Destinationen für die Produktinformationen; diese können z.B. sein: Erstellung eines Druckkatalogs, Onlineshops, Marktplätze etc. Die Nutzung der Kanäle ermöglicht eine effektive Realisierung Ihrer Multichannel- oder Omnichannel-Strategie.

Für nähere Informationen zur Konfiguration der Produktfamilien lesen Sie den Artikel: [“Wie kann man die Kataloge und Kanäle richtig nutzen?”](./kataloge-und-kanaele-richtig-nutzen.md). 
