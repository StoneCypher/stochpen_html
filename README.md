stochpen_html
=============

stochpen_html is an Erlang stochastic test library that generates penetration strings for html (generates attempts to hax0r your sox0rs; little bobby tables and etc.)

This allows a developer to make trivial use of resources like 

 * the [OWASP Fuzzing DB](https://www.owasp.org/index.php/Category:OWASP_Fuzzing_Code_Database), 
 * the [OWASP Filter Evasion Cheat Sheet](https://www.owasp.org/index.php/XSS_Filter_Evasion_Cheat_Sheet), 
 * the [HTML Purifier Smoke Test](http://htmlpurifier.org/live/smoketests/xssAttacks.php), 
 * the [RSnake List](http://code.google.com/p/fuzzdb/source/browse/trunk/attack-payloads/xss/xss-rsnake.txt), 

 and so forth.  More suggestions for targets would be appreciated.  Those lists are related and share significant overlap.

 The driving observation here is that a single case of each of those attacks is not enough.  What is needed is a tool which can produce variations on those attacks, including combinations, wrappings, substitutions, and other not-actually-innocuous variants.  This tool is an attempt at a step in that direction: a way to generate large volumes of attack string on demand.

 Examples
 --------

 (todo)