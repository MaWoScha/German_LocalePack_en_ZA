# Englisches Sprachpaket für Magento (CE)
(Magento Community Modules - English (South Africa) Language Pack)<br />
(Módulos de Magento Community - Paquete de idioma inglés)

This language package is managed by MaWoScha.<br />
Dieses Sprachpaket wird von MaWoScha verwaltet.<br />
Este paquete de idioma está gestionado por MaWoScha.

* Siehe auch: [Internationalisierung – Magento in mehreren Sprachen](http://blog.siempro.co/?p=105&lang=de)
* See also: [Internationalization – Magento in several languages](http://blog.siempro.co/?p=105&lang=en)
* Véase también: [Internacionalización – Magento en varios idiomas](http://blog.siempro.co/?p=105&lang=es)

# Installation instructions / Installationshinweise / Instrucciones de instalación

You should install the following / Sie sollten Folgendes installieren / Usted debe instalar el siguiente:

*  [German LocaleFallback](https://github.com/MaWoScha/German_LocaleFallback)
*  [German LocalePack en_ZA](https://github.com/MaWoScha/German_LocalePack_en_ZA)
*  [German LocalePack en_US](https://github.com/MaWoScha/German_LocalePack_en_US) (Contains ONLY e-mail templates, NO csv files are included)

Logout from the backend once, if not already done. Then in the configuration under "Locale Options" set the "locale" as "en_ZA". The extension [German LocaleFallback](https://github.com/MaWoScha/German_LocaleFallback) now allows you, in addition set "Fallback language" as "en_US". Next, enable the static blocks "eMail Template Say Hello de", "eMail Template Contact de" and "eMail Template Say Bye de" in the CMS-Manager and set them up according to your needs. The extension [German LocalePack en_US](https://github.com/MaWoScha/German_LocalePack_en_US) provides you with this enhanced ability to configure the e-mail templates for the English language. If you are using the English language, you also enable the static blocks "eMail Template Say Hello en", "eMail Template Contact en" and "eMail Template Say Bye en".

Melden Sie sich zunächst einmal aus dem Backend ab, falls nicht schon geschehen. Danach stellen Sie in der Konfiguration unter "Optionen für Lokalisierungen" für die "Sprachumgebung" "en_ZA" ein. Die Erweiterung [German LocaleFallback](https://github.com/MaWoScha/German_LocaleFallback) erlaubt Ihnen nun, zusätzlich als "Ausweichsprache" "en_US" festzulegen. Aktivieren Sie als nächstes in der CMS-Verwaltung die statischen Blöcke "eMail Template Say Hello de", "eMail Template Contact de" und "eMail Template Say Bye de" und richten diese nach Ihren Bedürfnissen ein. Die Erweiterung [German LocalePack en_US](https://github.com/MaWoScha/German_LocalePack_en_US) stellt Ihnen diese verbesserte Konfiguriermöglichkeit auch für die englische Sprache bereit. Wenn Sie auch die englische Sprache verwenden, aktivieren Sie ebenfalls die statischen Blöcke "eMail Template Say Hello en", "eMail Template Contact en" und "eMail Template Say Bye en".

Salir del backend una vez, si no lo ha hecho. A continuación, establezca en la configuración en "Opciones de configuración regional" para la "Configuración regional" "en_ZA". La extensión [German LocaleFallback](https://github.com/MaWoScha/German_LocaleFallback) ahora le permite, configurar además una "Idioma segunda opción" "en_US". A continuación, active los bloques estáticos "eMail Template Say Hello de", "eMail Template Contact de" y "eMail Template Say Bye de" en el gestor de CMS y ajustarlos de acuerdo a sus necesidades. La extensión [German LocalePack en_US](https://github.com/MaWoScha/German_LocalePack_en_US) le proporciona esta capacidad mejorada para configurar las plantillas de correo electrónico para el idioma Inglés. Si está utilizando el idioma Inglés, también activa los bloques estáticos "eMail Template Say Hello en", "eMail Template Contact en" y "eMail Template Say Bye en".


# Git-Repository / Git-Verwaltung

Dieses Git-Repository kann genutzt werden für:

* Reine Informationszwecke
* Entwicklung aktueller Versionen
* Behebung von Fehlern in bereits veröffentlichten Versionen
* Alternative Downloads (unabhängig von den offiziellen Quellen)
* Eigene Sprachversion basierend auf en_US
* Melden von Fehlern und PullRequests
* Aktives Mitwirken am Sprachpaket

## Reporting bugs / Melden von Fehlern / Cómo informar de problemas

Errors may be reported on GitHub / Fehler können auf GitHub gemeldet werden / Los errores pueden ser reportados en GitHub
<a href="https://github.com/MaWoScha/German_LocalePack_en_ZA/issues">https://github.com/MaWoScha/German_LocalePack_en_ZA/issues</a>

Wir freuen uns, wenn dieses Repository aktiv dazu genutzt, wird Fehler zu melden (Issue) und zu beheben (PullRequest im _preview_-Branch).

Oben dann einfach auf "Issues" klicken -> "New Issue", um ein Anliegen zu übermitteln. Bestehende Anliegen hingegen können auch ohne GitHub-Account eingesehen werden, inklusive deren Bearbeitungsstand.

_Beachten Sie dazu bitte:_ Wenn hier in den Versionen Veränderungen eingepflegt werden, dann entsprechen diese nicht mehr dem Stand des Sprachpakets, welches Sie über Magento Connect installieren können. Es ist leider nicht möglich dort veröffentlichte Releases nachträglich zu bearbeiten. :-)

_Hinweis:_ PullRequests sind bitte immer im Preview-Branch zu senden.

## Aktives Mitwirken am Sprachpaket

Lust am Sprachpaket mitzuwirken und einen (zumindest kostenlosen) Github- und/oder Crowdin.net-Account? Dann einfach MaWoScha kontaktieren und wir stimmen eine eventuelle Zusammenarbeit ab.

Viel Spaß mit dem englischen Magento Sprachpaket!

MaWoScha


# Hints / Hinweise / Avisos

This is a derived work of [German LocalePack de_CH](https://github.com/MaWoScha/German_LocalePack_de_CH),<br />
refactured and internationalized from MaWoScha.

This extension is tested with Magento 1.6.2, 1.7.0, 1.8.1, 1.9.0 and 1.9.1. <br />
The language pack is suitable for Magento 1.6.x until 1.9.x, but the language files are complete as of version 1.7.0 and up 1.9.4.x.

As long as the language files of this extension are empty, this language pack does nothing (yet).
But as soon as you enter some specific, in South Africa common words and phrases, you will benefit from the functionality of "Fallback language".


Dies ist eine abgeleitete Arbeit von [German LocalePack de_CH](https://github.com/MaWoScha/German_LocalePack_de_CH),<br />
überarbeitet und internationalisiert von MaWoScha.

Diese Erweiterung ist mit Magento 1.6.2, 1.7.0, 1.8.1, 1.9.0 und 1.9.1 getestet. <br />
Das Sprachpaket ist für Magento 1.6.x bis 1.9.x nutzbar, indes die Sprachdateien sind vollständig ab Version 1.7.0 und bis 1.9.4.x.

Solange die Sprachdateien dieser Erweiterung leer sind, tut dieses Sprachpaket (noch) nichts.
Sobald Sie aber einige spezielle, in Südafrika gebräuchliche Wörter und Phrasen eintragen, profitieren Sie von der Funktionalität der "Ausweichsprache".


Se trata de una obra derivada de [German LocalePack de_CH](https://github.com/MaWoScha/German_LocalePack_de_CH),<br />
revisado e internacionalizado de MaWoScha.

Esta extensión se prueba con Magento 1.6.2, 1.7.0, 1.8.1, 1.9.0 y 1.9.1. <br />
El paquete de idioma es adecuado para Magento 1.6.x hasta 1.9.x, pero los archivos de idioma están completos a partir de la versión 1.7.0 y hasta 1.9.4.x.

Mientras los archivos de idioma de esta extensión están vacías, este paquete de idioma (todavía) no hace nada.
Pero tan pronto como entras en alguna específica, común en las palabras y frases de Sudáfrica, que se beneficiarán de la funcionalidad de "Idioma segunda opción".

MaWoScha