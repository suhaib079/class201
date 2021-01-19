
# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

ersistent local storage is one of the areas where **native client applications** have held an advantage over web applications.
### cookies dowanside 
1. included with every HTTP request, thereby slowing down your web application
2.   thereby sending data unencrypted over the internet
3. limited to about 4 KB of data

# A BRIEF HISTORY OF LOCAL STORAGE HACKS BEFORE HTML5

Microsoft invented a great many things and included them in their  browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML **Behaviors**, and one of these behaviors was called **userData**its allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.
Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” Within the Flash environment, the feature is properly known as Local Shared Objects. Briefly, it allows Flash objects to store up to 100 KB of data per domain but 
Flash gives each domain 100 KB of storage “for free.” Beyond that, it prompts the user for each order of magnitude increase in data storage
> Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers.
 survey these solutions, a pattern emerges: all of them are either specific to a single browser, or reliant on a third-party plugin. Despite heroic efforts to paper over the differences (in dojox.storage), they all expose radically different interfaces
 # INTRODUCING HTML5 STORAGE
 it’s a way for web pages to store named key/value pairs locally, within the client web browser.
 Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specificationWeb Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification.
  
 > HTML5 STORAGE SUPPORT
>IE	FIREFOX	SAFARI	CHROME	OPERA	IPHONE	ANDROID
>8.0+	3.5+	4.0+	4.0+	10.5+	2.0+	2.0+

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key.
 
 # TRACKING CHANGES TO THE HTML5 STORAGE AREA
 The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.
 The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener to hook the storage event, you’ll need to check which event mechanism the browser supports.

 #  to hook the storage event, you’ll need to check which event mechanism the browser supports.

 5 megabytes” is how much storage space each origin gets by default. This is surprisingly consistent across browsers, although it is phrased as no more than a suggestion in the HTML5 Storage specification Each digit in that float is being stored as a character, not in the usual representation of a floating point number

 # HTML5 STORAGE IN ACTION
 HTML5 Storage, we can save the progress locally, within the browser itself. Here is a live demonstration. Make a few moves, then close the browser tab, then re-open it. If your browser supports HTML5 Storage
 localStorage object to save whether there is a game in progress

 # KEY-VALUE PAIRS: COMPETING VISIONS
 new API has been standardized and implemented across all major browsers, platforms, and devices. As a web developer
 >all interested implementors have used the same SQL backend (Sqlite), but we need multiple independent implementations to proceed along a standardisation path. Until another implementor is interested in implementing this spec, the description of the SQL dialect has been left as simply a reference to Sqlite
 


