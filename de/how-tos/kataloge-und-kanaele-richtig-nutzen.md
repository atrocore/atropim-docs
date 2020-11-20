# Wie kann man die Kataloge und Kanäle richtig nutzen?

Kataloge und Kanäle bilden die Grundlage für eine Multichannel-Veröffentlichung Ihrer Produktinformationen. Sie ermöglichen, das Produktsortiment zu verwalten und eigene Multichannel-Strategie möglichst flexibel umzusetzen.

Ein Katalog ist das Sortiment der Produkte, die nach einem bestimmten Merkmal gruppiert sind, wenn Sie z.B. eine neue Kleiderkollektion haben. Produkte werden den Katalogen direkt zugeordnet.

![](../../_assets/kataloge-und-kanaele-richtig-nutzen/image29.png) 

Kanäle sind Enddestinationen für Ihre Produktinformationen. Produkte können den Kanälen direkt oder indirekt über die Produktkategorien zugeordnet werden. Die indirekte Zuordnung erfolgt über die Zuordnung des Kategoriebaums, zu dem die Kategorie gehört, zu einem Kanal. Ein Kategoriebaum kann zu mehreren Kanälen zugleich zugeordnet sein. In diesem Fall wird das Produkt allen diesen Kanälen entsprechend zugeordnet.

Als Kanäle können Onlineshops, Marketplaces, Apps, Druckkataloge und andere Anwendungen gelten. An einen bestimmten Kanal werden alle kanalspezifischen Produktinformationen übergeben, die für diesen Kanal extra angegeben sind, und auch allgemeine Produktinformationen, die für alle Kanäle gemeinsam sind.

Somit bestimmen die Kataloge die Produkte, die exportiert werden sollen, und Kanäle – die genauen Informationen, die für diese Produkte zu übertragen sind.

## Erstellung von Katalogen

Um einen neuen Katalog zu erstellen, muss man auf die Entitätsseite der Kataloge wechseln und auf den Button `Erstellen` klicken.

![](../../_assets/kataloge-und-kanaele-richtig-nutzen/image11.png)

Jeder Nutzer kann die Struktur von Katalogen entsprechend seinen Anforderungen einstellen. So können Kataloge für die Segmentierung des Produktsortiments verwendet werden, um die Produktinformationen für entsprechende Kanäle weiter zu exportieren und um historische Produktinformationen zu speichern, z.B. für die Erstellung der Kataloge von Kleidung- und Schuhkollektionen von den Lieferanten: “Jacken Herbst-Winter 2017”, “Jacken Herbst-Winter 2018”. Den Namen des Katalogs sind so anzugeben, dass es sofort klar ist, welche Produkte darin enthalten sind, oder man kann den Namen des Kanals angeben – somit ist es klar, wofür dieser Katalog gedacht ist.

## Erstellung von Kanälen

Um einen neuen Kanal zu erstellen, klickt man auf der Seite der Kanäle auf den Button `Erstellen`.

![](../../_assets/kataloge-und-kanaele-richtig-nutzen/image37.png)

Um die Menge an Produktinformationen einzuschränken, die durch einen Kanal übergeben werden, kann man bei der Einrichtung des Kanals zusätzlich angeben:

-   Lokales – damit die Beschreibungen in bestimmten Sprachen übergeben werden.
-   Währungen – damit nur die Preise in bestimmten Währungen übergeben werden.

![](images/image51.png)

### Speichern von mehrsprachigen(multilokalen) Produktinformationen

Kanäle können regionale Anbindung haben, da für unterschiedliche Länder die Produktinformationen in verschiedenen Sprachen verwendet werden können. Dafür gibt es im AtroPIM mehrsprachige Felder und Produktattribute. Die Produktinformationen in verschiedenen Sprachen kann man im System unabhängig davon angeben, welchen Kanälen dieses Produkt zugeordnet ist.

### Wofür werden kanalspezifische Attribute genutzt?

In einigen Fällen müssen Kanäle regionale Besonderheiten oder gesetzliche Anforderungen bezüglich der Beschreibungen bestimmter Produkte berücksichtigen. Zudem kann es in einigen Fällen nötig sein, unterschiedliche Werte bei Produktattributen anzugeben, z.B. unterschiedliche Produktnamen, weil bestimmte Plattformen Einschränkungen bezüglich der Namenslänge haben können, oder Beschreibungen diverser Länge, oder gar unterschiedliche Beschreibungen. Außerdem können in unterschiedlichen Ländern unterschiedliche Maßeinheiten verwendet werden, so muss man Attributwerte in entsprechenden Maßeinheiten angeben.

Im AtroPIM ist dies möglich dank der Nutzung von kanalspezifischen Attributen. Um sie zu nutzen, muss man bei der Konfiguration der Produktfamilien angeben, welches Attribut kanalspezifisch sein muss.

## Nutzung von Kanälen für Übergabe der Produktinformationen

Im AtroPIM können die Informationen für verschiedene Kanäle auf folgende Weisen übergeben werden:

-   Via AtroPIM REST API
-   Via API eines anderen Systems, wenn man einen entsprechenden Connector seitens AtroPIM entwickelt
-   Via Export Feeds

Wenn ein Kanal für die Datenübergabe via API eingestellt wird, kann man diesen Kanal auch für den Datenexport via Export Feeds nutzen.
