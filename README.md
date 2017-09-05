# sonarqube-quality-gate
A shell script that checks the status of a SonarQube quality gate via REST API. Can be used to break a CI build.

Developed because the Jenkins Quality Gate checker plugin doesn't authenticate with later versions of SonarQube, and can only be executed a post-build step.
