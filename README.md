Reverse URL
===========

Bookmarklet to reverse an url in download sites.

You want download a music, film or another file and after click redirectioning to another page with a part of an current url is a real download url inverted to need registry something or inform the cell phone number.

To put this bookmarklet in your browser and resolve problems some above is simple.

Add a bookmark on your favorite browser with the code below:

    javascript:(function(){
       script=document.createElement('SCRIPT');
       script.type='text/javascript';
       script.src='https://raw.github.com/brunoarueira/reverse_url/master/reverse_url_bookmarklet.js';
       document.getElementsByTagName('head')[0].appendChild(script);
    })();

PS: This code you put at the same local of the url but without 'http://'

Thanks.
