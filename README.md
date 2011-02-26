Playbook Firebug
================

This is really just dirt simple way to add debugging to your Blackberry WebWorks apps. 

Installation
------------

Just add the hosted firebug-lite code to your head::

    <script type="text/javascript" src="https://getfirebug.com/firebug-lite.js"></script>

For some reason, you don't even need to do anything in to allow this in your config, but just to be safe you may want to add

      <access uri="http://getfirebug.com/" subdomains="true" />
