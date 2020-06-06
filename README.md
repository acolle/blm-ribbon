# blm-ribbon
A ribbon to add on your website to support the Black Lives Matter (BLM) movement and protests.

### Code Snippet
On your HTML page, simply add the code below. If you use external CSS files, just add the code inside ```<style></style>``` in your CSS file.

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    
    <!-- All your metadata -->
    
    <style>
      #ribbon a {
         -webkit-transition: all 0.15s ease-out;
         transition: all 0.15s ease-out;
         cursor: pointer;
         -webkit-text-decoration: none;
         text-decoration: none;
         outline: none;
         position: fixed;
         padding-top: 0.5rem;
         padding-bottom: 0.5rem;
         padding-left: 80px;
         padding-right: 80px;
         top: 50px;
         font-size: 16px;
         background-color: #000;
         color: #fff;
         z-index: 100;

         // Top Right Ribbon - Comment the next 4 lines if you want the ribbon at the top left corner of your page
         right: -80px;
         -webkit-transform: rotate(45deg);
         -ms-transform: rotate(45deg);
         transform: rotate(45deg);

         // Top Left Ribbon - Uncomment the next 4 lines if you want the ribbon at the top left corner of your page
         // left: -80px;
         // -webkit-transform: rotate(-45deg);
         // -ms-transform: rotate(-45deg);
         // transform: rotate(-45deg);
      }

       #ribbon a:hover {
         text-decoration: underline;
       }
    </style>
  </head>
  <body>
    
    <span id="ribbon">
      <a href="https://twitter.com/search?q=%23BlackLivesMatter" target="_blank" rel="noopener noreferrer">Black Lives Matter</a>  
    </span>
    
     <!-- The rest of your HTML page -->
    
  </body>
</html>
```

By default, the ribbon is at the top right corner of the page. If you want the ribbon at the top left corner of the page, simply comment out the lines 28 to 31 in the code above, and uncomment the lines 34 to 37.

By default, the ribbon redirects to Twitter's feed for #BlackLivesMatter but you can change it by updating the value of the `href` attribute in the code above with the URL of your choice.

Some organisations working to empower Black communities include:

* [Black Alliance For Just Immigration](https://baji.org/)
* [Black Lives Matter](http://blacklivesmatter.com/)
* [Blackout For Human Rights](http://www.blackoutforhumanrights.com/)
* [Black Women’s Blueprint](https://blackwomensblueprint.ourpowerbase.net)
* [Common Ground Foundation](https://commongroundfoundation.org/)
* [The Sadie Collective](https://www.sadiecollective.org/)
* [The Trayvon Martin Foundation](http://trayvonmartinfoundation.org/)
* [NAACP](https://naacp.org/)
* [Showing Up For Racial Justice](https://www.showingupforracialjustice.org/)
