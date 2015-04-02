# ALLE-FACEBOOK-FREUNDE-EINLADEN
Hier wird genau beschrieben, wie du alle eigenen Freunde auf Facebook zu einer Veranstaltung oder Facebook-Seite einladen kannst.

1. Klicke bei Veranstaltungen auf EINLADEN > FREUNDE AUSWÄHLEN ODER bei Facebook-Seiten auf Alle anzeigen Freunde zur Facebook-Seite einladen

2. Scrolle bis ganz nach unten, damit deine Freundesliste vollständig geladen wird, da sonst nicht alle Freunde eingeladen werden

3. Drücke jetzt (gleichzeitig)
**STRG + SHIFT + J** bei Chrome Browser Logo Google Chrome
**STRG + SHIFT + K** bei FireFox Browser Logo Mozilla FireFox
**F12** bei Internet Explorer Logo Internet Explorer
Es wird sich ein Fenster mit einem Eingabebereich öffnen. Bei Chrome Browser Logo Google Chrome und Internet Explorer Logo Internet Explorer muss man zusätzlich zuerst auf CONSOLE klicken.

4. Für Veranstaltungen folgenden Code kopieren und einfügen. Danach auf Enter drücken:
`javascript:elms=document.getElementsByName("checkableitems[]");for (i=0;i<elms.length;i++){if (elms[i].type="checkbox" )elms[i].click()}`

5. Für Facebook-Seiten folgenden Code kopieren und einfügen. Danach auf Enter drücken:
`javascript:var inputs = document.getElementsByClassName('_3hqu'); for(var i=0; i<inputs.length;i++) { inputs[i].click() };`

***

**Hinweis: Achte auch nach dem kopieren und einfügen bitte darauf, dass "javascript" ebenfalls eingefügt wurde. Beim Internet Explorer Logo Internet Explorer wird der Code (bei älteren Versionen) außerdem erst mit einem Klick auf den kleinen grünen Pfeil rechts ausgeführt.**


> Bitte beachten: Je nach Anzahl der Freunde und Geschwindigkeit des Rechners kann das eine ganze Weile dauern. Man muss nur etwas Geduld haben.
