# Maven-project-with-tests
 
Maven JaCoCO is a free Java code coverage tool.

JaCoCo plugin is added in build->plugins tag.

<groupId>org.jacoco</groupId>
<artifactId>jacoco-maven-plugin</artifactId>
<version>0.7.2.201409121644</version>

run the following command from the command prompt or IntelliJ IDEA terminal:
mvn package     
(or mvn clean package is you want to recreate the target folder)

Open index.html file generated in the target/site/jacoco folder.
The report gives information about the test coverage.
12 of 19 instructions are not covered by tests.(Green indicates lines that are covered by tests, red indicates lines that are not covered by tests).

prepare-agent goal runs and prepares the agent that does the analysis.
report goal: This agent gathers test coverage information when the tests are run and creates the report as part of the prepare-package phase.
