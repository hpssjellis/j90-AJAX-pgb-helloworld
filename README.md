j-AJAX-pgb-helloworld
=====================

This App shows one way to get AJAX working on Phonegap Build



updated Jan 28, 2014



Like always I really do not know what I am doing, I just keep trying things until they work. 


PROBLEM 1: You must have a php enabled website for AJAX to work. The ajax.php file must be on a website in a location such as http://www.yourURL.com/yourFolder/ajax.php   You can't even test this code on your own computer. You can test these files by putting all three on your website and seeing what they do. If they work on the website, they will probably Work using phonegap build.


PROBLEM 2: Apple does not like AJAX, since it is not fully contained. Not sure if they are allowing more AJAX now or just allowing certain developers to use AJAX


PROBLEM 3: Almost zero php security in these examples. This is just to get AJAX working, you really need to look into php security before using this code in a production App.


Normally I would define the access allowed in a config.xml file, but things seem to work fine using Phonegap Build so I didn't here.    <access origin="http://www.yourURL.com"  subdomains="true" /> 

In the code I have used a keyup event but any event could be used to fire the AJAX command.

The code worked using Phonegap Build Ver 2.9 so I saw no reason to test it with version 3.1




************************************************************************************************************

###Disclaimer: I spend my time getting complex things working in simple ways. I have no idea if I am doing anything correctly so please beware if you use my work. If you like this App and can hum, play or sing please help the musically illiterate, use a flash capable computer to add your favorite song at http://www.rocksetta.com 

