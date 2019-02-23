# BoilerPlate
 
  * ## Boilerplate src folder ##
    * **doc** - contains documentations
    * **img** - contains gitignore
    * **js** - contains javaScript files
    * **.editorconfig** - to define and maintain consistent coding styles
    * **.gitattributes** - gives attributes to pathnames
    * **.gitignore** - files or folders listed in this file will not be tracked by git
    * **404 html** - error html page when a page is not found
    * **browserconfig.xml** - used to define things like tile backgrounds, badge updates, and tile notifications. lets you set these images using external XML files rather than metadata within the HTML markup of the page.
    * **favicon.ico** - file containing one or more small icons, associated with a particular website or webpage such as the bookmark icon
    * **humans.txt** - a tribute to the people that contributed to the building of a website
    * **icon.png** - picture of the icon
    * **index.html** - the main webpage of a website that holds the html code of the page
    * **robots.txt** - used to instruct search engine robots to crawl & index pages on the website
    * **site.webmanifest** - provides information about your application in JSON format and about how it should behave.
    * **tile-wide.png** - can be used for the wide tile (558x270px)
    * **tile.png** - can be used for the small, medium, and large tiles being automatically resized if necessary(558x558px).
    
    
    
    
    
  * ## Boilerplate index.html ##
    * **<!doctype html>** - HTML5 doctype declaration 
    * **html class="no-js" lang=""** - html is the beginning of the html document, class is a created attribute to group items by class name. The "no-js" class can be used to specify custom styles when javascript is disabled. lang is the language that you're writing the code in.
    * **head** - head element is a container for metadata. All information about the webpage.
    * **meta charset="utf-8"** - utf-8 is one of the encoding methods created to be able to display and work with characters/words from other languages such as Mandarin, Arabic.
    * **meta http-equiv="x-ua-compatible" content="ie=edge"** - allows web authors to choose what version of Internet Explorer the page should be rendered as.
    * **title** - The title of your webpage that goes onto the tab open on your page.
    * **meta name="description" content=""** - gives a description of your webpage when it is used on search-engines.
    * **meta name="viewport" content="width-device-width, initial-scale=1"** -  A messaage to the mobile browser saying it's designed for mobile screens too. For a responsive web page
    * **link rel="manifest" href="site.webmanifest"** - deployment of the web app manifest
    * **link rel="apple-touch-icon" href="icon.png"** - defines an image to be used on Apple devices that represents that page or site.
    * **link rel="stylesheet" href="css/normalize.css"** - link to the normalize.css that provides better cross-browser consistency in the default styling of HTML elements.
    * **link rel="stylesheet" href="css/main.css"** - link to where you would put your main css file.
    * **body** - the body tag defines the document's body and contains all the actual contents of the document.
    * **if lte IE 9...upgrade your browser** - informing your site visitor that their choice of browser is outdated.
    * **the p tag** - signifies a paragraph.
    * **script src="js/vendor/modernizr-{{MODERNIZR_VERSION}}.min.js"** - the script tag is the beginning of the javascript code, and the src is the file where the javascript is located. Modernizr is a JS library that detects which HTML5 and CSS3 features your visitor's browser supports.
    * **all the jquery lines** - the version of jquery, and loading jquery from a CDN. The second script tag will check if window.jQuery is defined which means the script was successfully loaded from the CDN.
    * **script src="js/plugins.js"** - javascript plugins
    * **script src="js/main.js"** - location of your main javascript file
    * **window.ga** - adds analytics.js to your site. Activates google analytics tracking by inserting ga.js into the page.
    

