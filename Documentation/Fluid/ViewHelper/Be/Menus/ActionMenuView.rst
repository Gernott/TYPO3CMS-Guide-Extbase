.. include:: ../../../../Includes.txt

f:be.menus.actionMenuView
=========================

This ViewHelper creates a select box. With the addition of the `f:be.menus.actionMenuItem` ViewHelper, you can fill this 
select box with options, which will lead to an appropriate view when they are selected.

Properties
----------

defaultController
~~~~~~~~~~~~~~~~~
:aspect:`Variable type`
    String

:aspect:`Description`
    Provide the name of the Controller to be used in the event that the Controller name isn't provided in the 
    individual ActionMenuItem ViewHelper. As the Controller parameter is required for the ActionMenuItem ViewHelper 
    anyway, you're better off not setting this property in this ViewHelper.

:aspect:`Default value`
    NULL

:aspect:`Required`
    Yes

Example
-------

The following menu contains a Select element with two menu entries. Further details of the ActionMenuItem ViewHelper 
are in its own documentation.

::

 <f:be.menus.actionMenu>
   <f:be.menus.actionMenuItem label="New" controller="Fluid" action="new" />
   <f:be.menus.actionMenuItem label="{f:translate(key='List')}" controller="Fluid" action="list" />
 </f:be.menus.actionMenu>