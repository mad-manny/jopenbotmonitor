# JOpenBotMonitor

JOpenBotMonitor is a Jave EE web application built to run on Java application servers like [Apache Tomcat](https://tomcat.apache.org/).
It is designed to log malicious web bot activities and make them visible for the interested public.

## DOWNLOAD

Current Version: [1.170703](https://github.com/mad-manny/jopenbotmonitor/blob/master/JOpenBotMonitor.1.170703.war)

## LICENSE
CC-BY-ND

This work is licensed under a [Creative Commons Attribution-NoDerivatives 4.0 International License](http://creativecommons.org/licenses/by-nd/4.0/).

## INSTALLATION INSTRUCTIONS
The installation instructions are depending on the type and configuration of your Java application server.
The application comes as Java EE .war archive.

Important: The application must be installed at the **ROOT context** of your application server!
* Correct: `http://your.domain.com/`
* Wrong: `http://your.domain.com/JOpenBotMonitor/`

If you want to use JOpenBotMonitor on a server, that is already hosting a site, you can achieve that by the following options:
1. Using a new subdomain.
2. Configuring virtual hosts, where requests using host **your.domain.com** get routed to our site and requests using the IP address get routed to the JOpenBotMonitor application.
