.. include:: ../../../Includes.txt

f:form.textarea
===============

This ViewHelper allows you to add a TEXTAREA (text input field) to an HTML form, which allows a website visitor to enter
text on multiple lines. For example, this type of field is usually seen in a contact form, where the website visitor
can enter the text of his or her message.

Properties
----------

All the :ref:`universal tag attributes <UniversalTagAttributes>`

All the :ref:`universal form field attributes <UniversalFormFieldAttributes>`

Examples
--------

::

 <f:form.textarea name="myExtName[message]" />


or

::

 <f:form.textarea property="message" />
