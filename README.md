uncensor_deviantart
===================

Javascript bookmarks to uncensor deviantart.com  
  
To use it, in firefox, create a new bookmarks.  
In url field, put the content of uncensor_deviantart.js.  
In name field, put what you want.  
Save it.  
  
Go on a deviantart.com censor page like http://smirtouille.deviantart.com/art/Battle-Angel-Alita-186864592  
Click on your new bookmarks and normaly, the censored image will be show.  
  
If you got a problem send me a mail at oros [at] ecirtam.net (in french or english)
  
  
Update 2015/07/31
-----------------
  
Now deviantart.com use the cookie "agegate_state" with the value "1".  
So this code works :  
```
javascript:(function(){document.cookie="agegate_state=1";window.location.reload();})();
```
But if you have disabled cookie, uncensor_deviantart.js can works with old pictures (post before 2015/??/??)  .
