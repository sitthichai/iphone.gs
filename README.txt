320/480 Grid System for iPhone
Version 1.0
2009-4-16

Created by Ching-Lan 'digdog' Huang. Baased on Nathan Smith's 960 Grid System (http://960.gs). 
Check official website for more detail: http://homepage.mac.com/digdog/iphone.gs/

==============================================================================================

Thanks for downloading "320/480 Grid System for iPhone." I created this for my own iPhone-only
web pages, and hope it helps to streamline your web development workflow on iPhoneOS platform.

Unlike the 960 Grid System, "320/480 Grid System for iPhone" seperated css into two parts, one
is for iPhone portrait mode(320.css for 320 pixels width), and the other is for landscape mode 
(480.css for 480 pixels width). You may simply include them both in the <head> tag, or use one
of them that meets your needs. Optionally, you may also include rest.css and text.css to reset 
browser stylesheet at the beginning. Here is an example of XHTML snippets for using CSS files:

<head>
<link rel="stylesheet" type="text/css" media="all" href="css/reset.css" />
<link rel="stylesheet" type="text/css" media="all" href="css/text.css" />
<link rel="stylesheet" type="text/css" media="all" href="css/320.css" />
<link rel="stylesheet" type="text/css" media="all" href="css/480.css" />
</head>

The files in the "320/480 Grid System for iPhone" are free of charge, licensed under GPL/MIT.

==============================================================================================

References:

960 Grid System
http://960.gs

Eric Meyer's browser reset stylesheet
http://meyerweb.com/eric/tools/css/reset/