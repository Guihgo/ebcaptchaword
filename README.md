ebcaptchaword
=============

jQuery Captcha Plugin

A simple, lightweight jQuery plugin for creating and implementing captcha in jQuery.



Installation
============

Include script after the jQuery library.
<script type="text/javascript" src="jquery.ebcaptchaword.js"></script>


Usage
=====
Call the plugin:

$('the_value').edoncaptchaword();

"the_value" can be class or ID of the form. You are required to call a property of the form (class or ID).

When the plugin is called it will generate automatically a label and a text input at the bottom of the form before the submit input. 
The submit input automatically will disabled at the start. Also if you click on Enter it will do nothing.
The script will generate a random word and it will add to label. User just need to write the same word into input to
activate submit input of the form.

