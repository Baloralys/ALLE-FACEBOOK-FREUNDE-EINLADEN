# ALLE-FACEBOOK-FREUNDE-EINLADEN
Hier wird genau beschrieben, wie du alle eigenen Freunde auf Facebook zu einer Veranstaltung oder Facebook-Seite einladen kannst.

1. Klicke bei Veranstaltungen auf EINLADEN > FREUNDE AUSWÄHLEN ODER bei Facebook-Seiten auf Alle anzeigen Freunde zur Facebook-Seite einladen

2. Scrolle bis ganz nach unten, damit deine Freundesliste vollständig geladen wird, da sonst nicht alle Freunde eingeladen werden

3. Drücke jetzt (gleichzeitig)

Tastenkombination  | Browser
------------- | -------------
**STRG + SHIFT + J**  | Google Chrome
**STRG + SHIFT + K**  | Mozilla FireFox
**F12**  | Internet Explorer

Es wird sich ein Fenster mit einem Eingabebereich öffnen. 
Bei Google Chrome Browser und Internet Explorer muss man zusätzlich zuerst auf CONSOLE klicken.

###### Für Veranstaltungen folgenden Code kopieren und einfügen. Danach auf Enter drücken:
```javascript
javascript:elms=document.getElementsByName("checkableitems[]");for (i=0;i<elms.length;i++){if (elms[i].type="checkbox" )elms[i].click()}; alert('Fertig, all deine Freunde wurden selektiert!');
```

###### Für Facebook-Seiten folgenden Code kopieren und einfügen. Danach auf Enter drücken:
```javascript
javascript:var inputs = document.getElementsByClassName('_1pt_ _1pu0'); for(var i=0; i<inputs.length;i++) { inputs[i].click() }; alert('Fertig, all deine Freunde wurden selektiert!');
```

***

**Hinweis: Achte auch nach dem kopieren und einfügen bitte darauf, dass "javascript" ebenfalls eingefügt wurde. Beim Internet Explorer Logo Internet Explorer wird der Code (bei älteren Versionen) außerdem erst mit einem Klick auf den kleinen grünen Pfeil rechts ausgeführt.**


> Bitte beachten: Je nach Anzahl der Freunde und Geschwindigkeit des Rechners kann das eine ganze Weile dauern. Man muss nur etwas Geduld haben.
