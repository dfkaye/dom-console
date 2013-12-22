dom-console
===========

Intercepts console method calls and writes to a dom list.

intent
------

For dev-time use, so you don't need to press F12 + reload a page, or for legacy browsers 
that don't support the console object, or the required addon is not installed (it happens).

example
-------

You can visit the browserified version of tape tests in my [simplegraph]
(https://rawgithub.com/dfkaye/simplegraph/master/browser-test/suite.html) repo to see what it looks like.

On that page you can open the browser console - the dom will still be updated.  Try a few of the built-in methods 
such as console.info('test') to see the dom update with the new message.  You can clear the console as well,
by running console.clear() (not just "clear()" as that isn't supported - this *is* a dev-time shim, after all :).

use
---

Include the script tag before other scripts that may write to the console. No other change needed 
on your part.

    <script src='[path-or-url-to]/dom-console.js></script>
    
    <!-- your stuff -->
    <script src='mystuff.js'></script>
    


