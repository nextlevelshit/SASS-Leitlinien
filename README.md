# SCSS-Leitlinien

Warum immer so viel Gelaber, wenn es auch einfach geht. Hier bekommt ihr eine ordentliche Vorlage für eure SCSS-Dateien. Solltest du dich mit den verschiedenen CSS-Spezifitäten nicht so gut auskennen, kannst du es gerne hier nachlesen:



* [CSS Guide Lines by Harry Roberts](http://cssguidelin.es/)
* [CSS Specifity by Smashing Magazine](http://www.smashingmagazine.com/2007/07/27/css-specificity-things-you-should-know/)


## main.scss

```css
/*----------------------------------------------------------------
* Settings
*----------------------------------------------------------------
*
* Global variables, site-wide settings, config switches, etc.
*/

//$font-size: 12px;
//$color-default: #a0a0a0;


/*----------------------------------------------------------------
* Generic
*----------------------------------------------------------------
*
* Low-specificity, far-reaching rulesets (e.g. resets).
*/

//@import "../bower_components/normalize-scss/_normalize.scss";


/*----------------------------------------------------------------
* Base
*----------------------------------------------------------------
*
* Unclassed HTML elements (e.g. a {}, blockquote {}, address {}).
*/

html {
//...
}

body {
//...
}


/*----------------------------------------------------------------
* Helper classes
*----------------------------------------------------------------
*
* Simple classes helpers (e.g. .fullheight {}).
*/

//@import "helpers.floating";


/*----------------------------------------------------------------
* Objects
*----------------------------------------------------------------
*
* Objects, abstractions, and design patterns (e.g. .media {}).
*/

//@import "objects.navigation";


/*----------------------------------------------------------------
* Components / UI
*----------------------------------------------------------------
*
* Discrete, complete chunks of UI (e.g. .carousel {}).
*/

//@import "ui.layout"; // Overall layout


/*----------------------------------------------------------------
* Trumps / Overrides
*----------------------------------------------------------------
*
* Discrete, complete chunks of UI (e.g. .carousel {}).
*/

//@import "trumps.footer";

```

## SCSS Compiler

