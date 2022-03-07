mailer-plugin
=============

[![Deprecated](https://img.shields.io/badge/Pantheon-Deprecated-yellow?logo=pantheon&color=FFDC28)](https://pantheon.io/docs/oss-support-levels#deprecated)

Breakout of the default Mailer from the Jenkins core.

Contributing
------------

### Run / Debug cycle:

Execute `mvn hpi:run`. This will compile the plugin and launch a Jenkins instance on http://localhost:8080

### Create Package (.hpi):

Execute `mvn hpi:hpi`. This will create `mailer.hpi` in the `target/` directory. Rename to `mailer.jpi`

For other mvn targets, see: https://jenkins-ci.org/maven-hpi-plugin/
