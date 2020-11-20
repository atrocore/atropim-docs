# Wie kann man eine effektive Teamarbeit organisieren?

In unserer PIM-Software gibt es gute Möglichkeiten für eine effiziente Zusammenarbeit von Mitarbeitern, sowohl intern als auch mit externen Agenturen oder Freelancern. So kann das Unternehmen eigene Produktmanager haben, die technische Produktbeschreibungen vorbereiten. Für die Erstellung guter Marketing- oder SEO-Texte und professioneller Produktbilder können aber auch Fachleute von außen eingesetzt werden.

Aus diesem Grund ist die effektive Gestaltung der Teamarbeit in einem PIM-System sowohl für die Qualität der Arbeitsergebnisse als auch für die Geschwindigkeit ihrer Erreichung von großer Bedeutung.

Der Zugang zum System kann sowohl direkt als auch über die Portal-Funktionalität gewährt werden, die für einen bestimmten Zweck konfiguriert und genutzt werden können. Beispiele der Nutzung von Portalen sind Lieferantenportal und Händlerportal.

Eine wichtige Besonderheit von AtroPIM ist die Möglichkeit, den Zugang bei Bedarf nicht nur zu einzelnen Entitäten, deren Einträgen, sondern auch auf der Feldebene zu verwalten.

## ACL Strict Mode

Standardmäßig ist für jede Entität die Option `not-set` für Zugangsberechtigungen angegeben, was bedeutet, dass der Zugang zu dieser Entität noch nicht konfiguriert wurde. Wenn `ACL Strict Mode` (in `Administration` → `Settings`) aktiviert ist, hat der Nutzer standardmäßig keine Zugangsberechtigungen, falls der Zugang nicht konfiguriert ist. Wenn `ACL Strict Mode` nicht aktiviert ist, hat der Nutzer den Zugang zu allen Entitäten, für welche seine Berechtigungen nicht konfiguriert sind. Wir würden empfehlen, `ACL Strict Mode` sofort nach der Systeminstallation zu aktivieren.

## Rollen, Benutzer und Teams im Überblick

AtroPIM hat ein sehr flexibles Zugangskontrollsystem, das auf Rollen, Teams und Nutzern basiert. Die Berechtigungen werden für jede Rolle einzeln konfiguriert. Man kann die Berechtigungen sowohl für Standard- als auch für benutzerdefinierte Entitäten einzeln einstellen.

Ein PIM-Nutzer ist ein Konto für den Systemzugang für eine bestimmte Person. Dem Nutzer werden eine oder mehrere Rollen zugewiesen, welche seine Berechtigungen im System bestimmen. Eine Rolle kann einem oder mehreren Nutzern zugewiesen werden.

Jeder Nutzer kann zu einem oder mehreren Teams gehören. Jedes Team kann mehrere Nutzer beinhalten.

## Verwendung von Teams

Teams werden erstellt, um die Mitarbeiter zu verbinden, die gleiche Pflichten haben, an demselben Projekt arbeiten oder für eine bestimmte Region verantwortlich sind. Jeder Nutzer kann gleichzeitig zu mehreren Teams gehören.

Um ein Team zu erstellen, muss der Administrator auf `Administration` → `Teams` →  `Create Team` gehen.

![](../../_assets/_assets/how-tos/wie-kann-man-eine-effektive-teamarbeit-organisieren/image8.png)

Die Erstellung von qualitativen Produktbeschreibungen erfordert die Zusammenarbeit zwischen verschiedenen Teams.

Damit der Nutzer, der zu einem bestimmten Team gehört, den Zugang zu einem bestimmten Eintrag hat, muss er den Zugang zu dieser Entität auf der Teamebene haben. Dabei muss dieses Team diesem Eintrag zugeordnet werden. Wenn z.B. die Mitglieder von zwei Teams den Zugang zu einem bestimmten Eintrag benötigen, muss man den Zugang für die beiden Teams freigeben. Damit Teams den Einträgen nach bestimmten Merkmalen automatisch zugeordnet werden, ist eine zusätzliche Programmierung erforderlich.

Durch eine korrekte Einstellung erhalten Ihre Mitarbeiter und Teams die Zugänge nur zu den Entitäten und Feldern, die sie für Erfüllung ihrer Aufgaben benötigen. Das ermöglicht, die Arbeit Ihrer Mitarbeiter optimal zu organisieren und deren Effizienz zu erhöhen.

## Verwendung von Nutzern

Um Zugang zum System zu haben, braucht der Nutzer ein eigenes Konto. Dem Nutzer kann die Rolle `Administrator` zugewiesen werden. In diesem Fall erhält er die höchste Zugangsebene mit maximalen Berechtigungen.

Jedem Nutzer können bestimmte Rollen zugewiesen werden und der Nutzer selbst kann bestimmten Teams zugeordnet werden. Um maximal flexibel zu sein, kann der Nutzer gleichzeitig mehrere Rollen haben und zu mehreren Teams gehören.

Um einen neuen Nutzer zu erstellen, muss der Administrator auf `Administration` → `Users` gehen und auf den Button `Create User` klicken. 

![](../../_assets/_assets/how-tos/wie-kann-man-eine-effektive-teamarbeit-organisieren/image54.png)

Die Nutzer sollen im System den Zugang zu genau den Daten und Funktionen haben, die sie für die Erfüllung ihrer Dienstpflichten benötigen, nicht mehr.

Jeder PIM-Nutzer kann die Daten des eigenen Kontos ansehen und bearbeiten (falls für die Rolle solche Berechtigungen eingestellt sind) und das Passwort ändern. Man kann auch ansehen, welche Berechtigungen der Nutzer hat, abhängig davon, welche Rollen ihm zugewiesen sind. Dafür muss man auf `Access` in den Einstellungen des persönlichen Kontos klicken. Es ist zu erwähnen, dass der Nutzer die Summe aller Berechtigungen seiner Rollen erhält.

![](../../_assets/_assets/how-tos/wie-kann-man-eine-effektive-teamarbeit-organisieren/image17.png)

Beispiel:

Dem Nutzer sind die Rollen 1 und 2 zugewiesen.

Mit der Rolle 1 hat er Zugang und Berechtigungen zu den Entitäten A und B. Mit die Rolle 2 hat er Zugang und Berechtigungen zu den Entitäten B und C. Da dem Nutzer beide Rollen zugewiesen sind, erhält er Zugang und Berechtigungen zu den Entitäten A, B und C.

## Verwendung von Rollen

Eine neue Rolle kann vom Administrator erstellt werden:

`Administration` → `Roles` → `Create Role`

![](../../_assets/_assets/how-tos/wie-kann-man-eine-effektive-teamarbeit-organisieren/image26.png)

Bei der Erstellung einer Rolle müssen die Berechtigungen zu `Create`, `Read`, `Edit`, `Delete` und `Stream` für erforderliche Entitäten eingestellt werden.

### Berechtigungen und Zugangsebenen

Man kann die Berechtigungen für folgende Aktionen im System einrichten:

-   Сreate
-   Read
-   Edit
-   Delete
-   Stream

Für jede Berechtigung kann man die Zugangsebene einstellen. So kann es z.B. eingestellt werden, dass der Nutzer nur eigene Einträge, Einträge der eigenen Teams, zu denen er gehört, oder alle Einträge im System bearbeiten kann. Einstellbar sind folgende  Zugangsebenen:

-   `all` – der Nutzer hat den Zugang nicht nur zu eigenen Einträgen, sondern auch zu den Einträgen aller anderen Nutzer.
-   `team` – der Nutzer hat den Zugang zu den Einträgen, die von den Nutzern der Teams erstellt wurden, zu denen er gehört. 
-   `own` – der Nutzer hat den Zugang zu eigenen Einträgen.
-   `no` – der Nutzer hat keine Zugangsberechtigungen.

Die Berechtigungen eines Nutzers bezüglich der Einträge im System werden mithilfe deren Ownership Informationen festgehalten:

![](../../_assets/_assets/how-tos/wie-kann-man-eine-effektive-teamarbeit-organisieren/image57.png)

Wird der Benutzer zum Owner oder Assigned User eines Eintrags gesetzt, hat er den Zugang zu diesem Eintrag, falls seine Zugagsebene `own` oder höher für diese Entität (hier z.B. Produkte) ist.

Ein Eintrag kann direkt einem oder mehreren Teams zugeordnet werden, somit bekommen den Zugang zu diesem Eintrag alle Nutzer, die zu diesen Teams gehören, falls deren Zugangsebene `team` ist.

Für jede Entität im System kann man die Möglichkeit aktivieren oder deaktivieren, dieser Entität `Teams`, `Assigned User` und `Owner` zuzuordnen.

Dafür muss man auf `Administration` → `Еntity Manager` gehen, die nötige Entität öffnen und auf `Bearbeiten` klicken. Danach muss man das Häkchen bei der Checkbox `Team`, `Assigned User` oder `Owner` setzen und die Änderungen speichern.

 ![](../../_assets/_assets/how-tos/wie-kann-man-eine-effektive-teamarbeit-organisieren/image28.png)

Dies ist notwendig, um die Zugänge zu den Einträgen dieser Entitäten zu konfigurieren.

Um besser zu verstehen, auf welche Weise die Berechtigungen und Zugangsebenen bestimmt werden, schauen wir uns die folgenden Beispiele an.

#### Beispiel 1:

Wenn es nötig ist, dass der Übersetzer die entsprechenden Produktattribute übersetzen kann, sollte man

-   Die Rolle `Übersetzer` anlegen.
-   Den Nutzer für den Übersetzer im System anlegen und diesem Nutzer die Rolle `Übersetzer` zuordnen.
-   Dieser Rolle die Berechtigung `Edit` für die Entität Produktattribut setzen, indem man die Zugangsebene `own` auswählt.
-   Sicherstellen, dass für alle Attributeinträge für Übersetzungen der Übersetzer als Assigned User festgelegt ist.
-   Einrichten, dass der Übersetzer alle Produktattribute lesen kann, damit er die Werte sehen kann, die zu übersetzen sind.

#### Beispiel 2:

Man hat folgende Teams:

-   General Product Team – dazu gehören Marc, Andrea, John.
-   New Catalog Team – dazu gehören Marc, Andrew, Bill.

Man hat Rollen mit folgenden Zugängen zum Bearbeiten:

-   Сopywriter – оwn
-   Product Manager – team
-   Photographer – own
-   Marketing Manager – own

Den Nutzern sind folgende Rollen zugewiesen:

-   Marc – Product Manager
-   Andrea – Copywriter
-   John – Product Manager
-   Andrew – Photographer
-   Bill – Marketing Manager

Es gibt im System folgende Produkte:

-   Electric engine b124e

-   das angegebene Team New Catalog Team
-   Assigned User: Andrea
-   Owner: -

-   Electric engine c212f

-   das angegebene Team New Catalog Team
-   das angegebene Team General Product Team
-   Assigned User: Andrew
-   Owner: -

Die Berechtigungen zum Bearbeiten des Produktes “Electric engine b124e” erhalten dementsprechend: 

-   Marc – weil er zum Team gehört, das für dieses Produkt angegeben ist und die ihm zugewiesene Rolle den Zugang zum Bearbeiten auf der Ebene `team` hat. 
-   Andrea – weil sie Assigned User für dieses Produkt ist und die ihr zugewiesene Rolle den Zugang zum Bearbeiten auf der Ebene `own` hat. 

Die Berechtigungen zum Bearbeiten des Produktes “Electric engine c212f” erhalten dementsprechend:

-   Marc – weil er zum Team gehört, das für dieses Produkt angegeben ist und die ihm zugewiesene Rolle den Zugang zum Bearbeiten auf der Ebene `team` hat.
-   Andrew – weil er Assigned User für dieses Produkt ist und die ihm zugewiesene Rolle den Zugang zum Bearbeiten auf der Ebene `own` hat.
-   John – weil er zum Team gehört, das für dieses Produkt angegeben ist und die ihm zugewiesene Rolle den Zugang zum Bearbeiten auf der Ebene `team` hat.

Obwohl der Nutzer Bill zum Team gehört, das für beide Produkte angegeben ist, werden ihm diese Produkte nicht angezeigt, weil die ihm zugewiesene Rolle den Zugang zum Bearbeiten nur auf der Ebene `own` hat.

### Berechtigungen auf Feldebene

AtroPIM bietet unter anderem die Möglichkeit an, die Zugangsrechte auf der Feldebene einer bestimmten Entität zu konfigurieren. Dazu muss man bei der Bearbeitung der Rolle auf dem Panel `Field Level` auf das Icon `✚` nach der entsprechenden Entität klicken. Es wird ein Popup mit den zu dieser Entität gehörenden Feldern geöffnet. Nachdem man das Feld ausgewählt hat, kann man den Zugang zum Lesen oder Bearbeiten dieses Feldes einstellen, indem man `yes` oder `no` für die erforderliche Aktion angibt. 

![](../../_assets/_assets/how-tos/wie-kann-man-eine-effektive-teamarbeit-organisieren/image35.png) 

Diese Funktion ist notwendig, wenn der Nutzer den Zugang zu bestimmten Einträgen benötigt, dabei aber die Werte in anderen Feldern nicht ändern (z. B. um versehentliche Änderungen zu vermeiden) oder sehen darf. Diese Funktion ist besonders nützlich, wenn verschiedene Personen für die Ausfüllung diverser Felder zuständig sind. Wenn Sie beispielsweise einen Mitarbeiter haben, der auf der Produktseite nur technische Details eintragen muss, ist es empfehlenswert, für ihn die Berechtigungen zum Bearbeiten der Felder `SKU` oder `Product Status` einzuschränken.

Bevor Sie die Rolle einstellen, müssen Sie sorgfältig und gründlich analysieren, welche Aufgaben ein bestimmter Nutzer erfüllen muss und welche Zugangsrechte er erhalten soll.

Für die Berechtigung `Delete` ist es empfehlenswert, die Zugangsebene nicht höher als `own` zu setzen – um zu vermeiden, dass der Nutzer die Einträge löscht, die nicht von ihm hinzugefügt wurden.

Korrekte Rolleneinstellungen ermöglichen, die Anzahl der Fehler im System zu reduzieren, die Datensicherheit zu gewährleisten und versehentliche Änderungen durch Nutzer zu vermeiden, die keine Berechtigungen dazu haben sollen. Die allgemeine Regel, an die man bei der Rollenkonfiguration halten sollte, lautet wie folgt: Man muss für den Nutzer die Berechtigungen und den Zugang nur zu den Entitäten und deren Felder einstellen, zu denen er den Zugang für die Erfüllung seiner Dienstpflichten benötigt.
