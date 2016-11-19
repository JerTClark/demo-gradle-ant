:buildSrc:compileJava UP-TO-DATE
:buildSrc:compileGroovy UP-TO-DATE
:buildSrc:processResources UP-TO-DATE
:buildSrc:classes UP-TO-DATE
:buildSrc:jar UP-TO-DATE
:buildSrc:assemble UP-TO-DATE
:buildSrc:compileTestJava UP-TO-DATE
:buildSrc:compileTestGroovy UP-TO-DATE
:buildSrc:processTestResources UP-TO-DATE
:buildSrc:testClasses UP-TO-DATE
:buildSrc:testNG UP-TO-DATE
:buildSrc:test UP-TO-DATE
:buildSrc:aggregateTestReports UP-TO-DATE
:buildSrc:check UP-TO-DATE
:buildSrc:build
Defining custom 'build' task when using the standard Gradle lifecycle plugins has been deprecated and is scheduled to be removed in Gradle 3.0
:jerant:tasks

------------------------------------------------------------
All tasks runnable from project :jerant
------------------------------------------------------------

Build tasks
-----------
assemble - Assembles the outputs of this project.
buildDependents - Assembles and tests this project and all projects that depend on it.
buildNeeded - Assembles and tests this project and all projects it depends on.
classes - Assembles main classes.
clean - Deletes the build directory.
jar - Assembles a jar archive containing the main classes.
testClasses - Assembles test classes.

Documentation tasks
-------------------
groovydoc - Generates Groovydoc API documentation for the main source code.
javadoc - Generates Javadoc API documentation for the main source code.

Help tasks
----------
components - Displays the components produced by project ':jerant'. [incubating]
dependencies - Displays all dependencies declared in project ':jerant'.
dependencyInsight - Displays the insight into a specific dependency in project ':jerant'.
help - Displays a help message.
model - Displays the configuration model of project ':jerant'. [incubating]
projects - Displays the sub-projects of project ':jerant'.
properties - Displays the properties of project ':jerant'.
tasks - Displays the tasks runnable from project ':jerant'.

Verification tasks
------------------
check - Runs all checks.
test - Runs the unit tests.

Other tasks
-----------
about.html - Demonstrates generation of a file using tokens
all - Removes the temporary junk
build.no.docs - Creates directories, compile source, runs tests, and create jar
chained - Copies .java source as both .java and .txt to ${dist.folder}
composite - Copies .java source as both .java and .java.txt to ${dist.folder}
dist - Cleans up the dist folder
docs - Cleans JavaDocs
execute - Runs the program
generate - Generates all documentation
hello
jer.clean.build - Removes the temporary junk
jer.clean.compile - Cleans compiled classes
jer.clean.dist - Cleans up the dist folder
jer.clean.docs - Cleans JavaDocs
jer.examples.about.html - Demonstrates generation of a file using tokens
jer.examples.chained - Copies .java source as both .java and .txt to ${dist.folder}
jer.examples.composite - Copies .java source as both .java and .java.txt to ${dist.folder}
jer.examples.readme.docs - Demonstrates creating platform-compatible README file
jer.examples.scripts - Demonstrates copying platform-specific scripts distributable to their respective OSes
jer.examples.unjarchive - Demonstrates un-jarring JAR file
jer.testing.test.compile - Compiles the test source
jer.testing.test.init - Create tests structure
mockTask
readme.docs - Demonstrates creating platform-compatible README file
scripts - Demonstrates copying platform-specific scripts distributable to their respective OSes
test.run - Runs JUnit tests
unjarchive - Demonstrates un-jarring JAR file
update

Rules
-----
Pattern: clean<TaskName>: Cleans the output files of a task.
Pattern: build<ConfigurationName>: Assembles the artifacts of a configuration.
Pattern: upload<ConfigurationName>: Assembles and uploads the artifacts belonging to a configuration.

To see all tasks and more detail, run gradle tasks --all

To see more detail about a task, run gradle help --task <task>

BUILD SUCCESSFUL

Total time: 3.809 secs
