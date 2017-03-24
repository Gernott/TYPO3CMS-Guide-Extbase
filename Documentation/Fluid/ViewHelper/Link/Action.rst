.. include:: ../../../Includes.txt

f:link.action
=============

Dieser ViewHelper erstellt einen Link zu einer anderen aufzurufenden Action

Properties
----------

All the :ref:`universal tag attributes <UniversalTagAttributes>`

Exclusive properties for the HTML-Element
#########################################

name
~~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Der name des Links

:aspect:`Default value`
    NULL

:aspect:`Mandatory`
    No

rel
~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Gibt die Beziehung zwischen dem aktuellen Dokument und dem verknüpften Dokument an

:aspect:`Default value`
    NULL

:aspect:`Mandatory`
    No

rev
~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Gibt die Beziehung zwischen dem verknüpften Dokument und dem aktuellen Dokument an

:aspect:`Default value`
    NULL

:aspect:`Mandatory`
    No

target
~~~~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    In welchem Fenster soll der Link geöffnet werden?

:aspect:`Default value`
    NULL

:aspect:`Mandatory`
    No

Exclusive properties of this ViewHelper
#######################################

action
~~~~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Auf welche Actionmethode soll der Link zeigen

:aspect:`Default value`
    NULL

:aspect:`Mandatory`
    No

arguments
~~~~~~~~~
:aspect:`Variable type`
    Array

:aspect:`Description`
    Welche Argumente/Parameter sollen dem Link angehängt werden

:aspect:`Default value`
    Leeres Array

:aspect:`Mandatory`
    No

controller
~~~~~~~~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Auf welchen Controller soll der Link zeigen

:aspect:`Default value`
    NULL

:aspect:`Mandatory`
    No

extensionName
~~~~~~~~~~~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Auf welchen Controller und/oder Action welcher Extension soll der Link zeigen

:aspect:`Default value`
    NULL

:aspect:`Mandatory`
    No

pluginName
~~~~~~~~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Auf welchen Controller und/oder Action welchen Plugins soll der Link zeigen

:aspect:`Default value`
    NULL

:aspect:`Mandatory`
    No

pageUid
~~~~~~~
:aspect:`Variable type`
    Integer

:aspect:`Description`
    Auf welche Seiten-UID soll verlinkt werden

:aspect:`Default value`
    NULL

:aspect:`Mandatory`
    No

pageType
~~~~~~~~
:aspect:`Variable type`
    Integer

:aspect:`Description`
    Auf welche Seitentyp ID soll verlinkt werden.

:aspect:`Default value`
    0

:aspect:`Mandatory`
    No

noCache
~~~~~~~
:aspect:`Variable type`
    Boolean

:aspect:`Description`
    Verhindert das Caching der aufzurufenden Seite

:aspect:`Default value`
    FALSE

:aspect:`Mandatory`
    No

noCacheHash
~~~~~~~~~~~
:aspect:`Variable type`
    Boolean

:aspect:`Description`
    Verhindert, dass der cHash-Parameter nicht mit an die URL angehangen wird.

:aspect:`Default value`
    FALSE

:aspect:`Mandatory`
    No

section
~~~~~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Auf welchen Anker soll die Zielseite springen (#anker)

:aspect:`Default value`
    Leerer String

:aspect:`Mandatory`
    No

format
~~~~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Gibt an um welches Format es sich bei der Zielseite handelt. Alternativ gibt es noch "xml"

:aspect:`Default value`
    Leerer String

:aspect:`Mandatory`
    No

linkAccessRestrictedPages
~~~~~~~~~~~~~~~~~~~~~~~~~
:aspect:`Variable type`
    Boolean

:aspect:`Description`
    Normalerweise werden Links auf geschützte Seiten nicht erzeugt. Hier mit kann man die Linkgeneration erzwingen.

:aspect:`Default value`
    FALSE

:aspect:`Mandatory`
    No

additionalParams
~~~~~~~~~~~~~~~~
:aspect:`Variable type`
    Array

:aspect:`Description`
    Fügt weitere Parameter der Zielseite an. Im Gegensatz zu arguments, können hiermit Variablen hinzugefügt werden die nicht mit dem Extensionnamen geprefixed werden.

:aspect:`Default value`
    Leeres Array

:aspect:`Mandatory`
    No

absolute
~~~~~~~~
:aspect:`Variable type`
    Boolean

:aspect:`Description`
    Nach Aktivierung wird der Zeilseite noch der Domainname und Pfad vorangestellt.

:aspect:`Default value`
    FALSE

:aspect:`Mandatory`
    No

addQueryString
~~~~~~~~~~~~~~
:aspect:`Variable type`
    Boolean

:aspect:`Description`
    Falls der aktuellen Seite bereits Parameter über die URL mitgegeben wurden, könnt Ihr hier nun entscheiden, ob diese Parameter auch mit auf die Zielseite übergeben werden.

:aspect:`Default value`
    FALSE

:aspect:`Mandatory`
    No

argumentsToBeExcludedFromQueryString
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
:aspect:`Variable type`
    Array

:aspect:`Description`
    Falls Ihr addQueryString aktiviert habt, aber einen oder zwei bestimmte Parameter wieder entfernen wollt, dann tragt Ihr hier diese Parameter ein.

:aspect:`Default value`
    Leeres Array

:aspect:`Mandatory`
    No

Beispiel
--------

::

 <f:link.action action="show">Zeige Details</f:link.action>
