Created this project using the following terminal command:

mvn archetype:generate -B -DarchetypeGroupId=org.appfuse.archetypes -DarchetypeArtifactId=appfuse-basic-struts-archetype -DarchetypeVersion=2.1.0 -DgroupId=com.cht -DartifactId=accountant -DarchetypeRepository=http://oss.sonatype.org/content/repositories/appfuse

AppFuse Basic Struts Archetype
--------------------------------------------------------------------------------
If you're reading this then you've created your new project using Maven and
accountant.  You have only created the shell of an AppFuse Java EE
application.  The project object model (pom) is defined in the file pom.xml.
The application is ready to run as a web application. The pom.xml file is
pre-defined with Hibernate as a persistence model and Struts 2 as the web
framework.

To get started, please complete the following steps:

1. Download and install a MySQL 5.x database from 
   http://dev.mysql.com/downloads/mysql/5.0.html#downloads.

2. Run "mvn jetty:run" and view the application at http://localhost:8080.

3. More information can be found at:

   http://appfuse.org/display/APF/AppFuse+QuickStart

