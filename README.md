mailer-plugin
=============

Breakout of the default Mailer from the Jenkins core.

Contributing
------------

### Run / Debug cycle:

Execute `mvn hpi:run`. This will compile the plugin and launch a Jenkins instance on http://localhost:8080

### Create Package (.hpi):

Execute `mvn hpi:hpi`. This will create `throttle-concurrent.hpi` in the `target/` directory

For other mvn targets, see: https://jenkins-ci.org/maven-hpi-plugin/
