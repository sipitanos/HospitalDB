# HospitalDB
This is a sample of A Hospital's Full Stack Infrastructure, populated with some examples to be able to function

The project was created with Eclipse IDE and with TomCat server. To import it just import it as a war project and it works out of the box.

Inser this to the bottom of the Tomcat's xml file:

\<listener\>
   \<listener-class\>
      listeners.StartupListener 
   \</listener-class\>
\</listener\>
