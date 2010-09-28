/*!
 * jQuery password123: iPhone Style Passwords Plugin - v1.2 - 9/28/2010<br/>
 * http://timmywillison.com/samples/password123/<br/>
 * 
 * Copyright (c) 2010 timmy willison<br/>
 * Dual licensed under the MIT and GPL licences.<br/>
 * http://timmywillison.com/licence/<br/>
 */

*Version: 1.2, Last updated: 9/28/2010*
 
Demo         - <a href="http://timmywillison.com/samples/password123/">http://timmywillison.com/samples/password123/</a>
GitHub       - <a href="http://github.com/timmywil/password123">http://github.com/timmywil/password123</a>
Source       - <a href="http://github.com/timmywil/password123/raw/master/jquery.password123.js">http://github.com/timmywil/password123/raw/master/jquery.password123.js (11.6kb)</a>
(Minified)   - <a href="http://github.com/timmywil/password123/raw/master/jquery.password123.min.js">http://github.com/timmywil/password123/raw/master/jquery.password123.min.js (3.4kb)</a>

License

Copyright (c) 2010 timmy willison,<br/>
Dual licensed under the MIT and GPL licenses.<br/>
http://timmywillison.com/license/<br/>

Support and Testing

Versions of jQuery and browsers this was tested on.

jQuery Versions - 1.3.0-1.4.2<br/>
Browsers Tested - Internet Explorer 6-8, Firefox 2-3.7, Safari 3-5,<br/>
Chrome 4-5, Opera 9.6-10.5.

Release History

1.2   - (9/28/2010) Placeholders changed to only work with HTML5 placeholder attribute,<br/>
          'value' attribute now reserved for actual values<br/>
1.1   - (7/5/2010) Add Placeholder functionality<br/>
1.0   - (7/4/2010) Initial release

<h1>Usage</h1>

<pre>
$('input:password').password123();
<pre>

<h3>Placeholders</h3>
For placeholders, just use the HTML5 placeholder attribute:

<pre>
<input type="password" placeholder="password">
</pre>

This will work in all browsers and you can keep placeholders specific to certain elements.

<br/>
<h3>Options</h3>

<pre>
$('input:password').password123({
                
    // You can use any html character code or
    // plain text character
    character: "&#8226;",
    
    // This is the delay for when the last
    // character will change
    delay: 2000,
    
    // Use any prefix you like for the new
    // field ids, but they will always be zero-indexed
    prefix: "iField",
    
    // Enable the override of the placeholder attribute
    placeholder: true,
    
    // With this classname, you can set placeholder
    // specific styles in your own css
    placeholderClass: 'place',
    
    // You can mask the placeholder
    maskPlaceholder: false
    
});
</pre>