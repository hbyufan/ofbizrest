Implementation of this tutorial https://cwiki.apache.org/confluence/display/OFBIZ/Export+service+using+REST

Welcome to Apache OFBiz!

All you need to run OFBiz is a 1.7 (version 7) JDK
(not just the JRE, the full JDK).
http://java.sun.com/javase/downloads/index.jsp

You can load the demo data (strongly advised if you are new to
OFBiz) with the following command on the command line
from the OFBiz home folder (in Unix-like operating systems
type "./ant" rather than "ant" to use the embed ant version
 if you haven't installed it on your system) :

ant load-demo

Then start OFBiz:

ant start

(or "java -Xms128M -Xmx512M -XX:MaxPermSize=128m -jar ofbiz.jar")
(you can also run directly "ant load-demo start")

Once OFBiz starts, you can look at the demo storefront at:
http://localhost:8080/ecommerce

the back office at:
https://localhost:8443/ordermgr

and the administration interface at:
https://localhost:8443/webtools

You can log in with the user "admin" and password "ofbiz".

To stop OFBiz:

ant stop

To get the list of available commands:

ant -p

You will also find several platform dependent scripts in the
"tools" folder (for example for Windows and Unix-like operating
systems, the startup scripts are startofbiz.bat and startofbiz.sh).

Note that the default configuration uses an embedded Java database
(Apache Derby) and embedded application server components such as
Tomcat, Geronimo (transaction manager), etc.

For more details about OFBiz please visit the OFBiz Documentation page:

http://ofbiz.apache.org/documentation.html

In this page you will find links to useful guides such as:
* "Demo and Test Setup Guide"
* "Basic Production Setup Guide"
* "A Beginners Development Guide"

If you would like to get in touch with the OFBiz community of users and
developers, the following page will help to get started:

http://ofbiz.apache.org/community.html

Enjoy!