.. include:: ../../../Includes.txt

f:form.hidden
=============

This ViewHelper allows you to create a hidden field in an HTML form. Such a field can be useful to provide record UIDs
in the form, which the website visitor can't see but which are essential when transmitting the form data to the web
server.

Properties
----------

All the :ref:`universal tag attributes <UniversalTagAttributes>`

All the :ref:`universal form field attributes <UniversalFormFieldAttributes>`

Examples
--------

::

 <f:form.hidden name="myExtName[ttAddressUid]" value="15" />


or

::

 <f:form.hidden property="ttAddressUid" value="15" />