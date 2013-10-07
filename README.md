dom-console
===========

Intercepts console method calls and writes to a dom list.

intent
------

For dev-time use, so you don't need to press F12 + reload a page, or for legacy browsers 
that don't support the console object, or the required addon is not installed (it happens).

Include the script tag before other scripts that may write to the console. No other change needed 
on your part.

example
-------

You can visit the browserified version of tape tests in my [nested-graph]
(https://rawgithub.com/dfkaye/nested-graph/master/browser/test-bundle.html) repo to see if it's 
right for you.
