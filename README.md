# Java-GradleDemo
A simple java project using gradle tool

Commands:

C:\Users\ankita.agarwal>cd javaDemo

C:\Users\ankita.agarwal\javaDemo>gradle init

> Task :init
Maven to Gradle conversion is an incubating feature.

BUILD SUCCESSFUL in 2s
2 actionable tasks: 2 executed
C:\Users\ankita.agarwal\javaDemo>gradle build

> Task :compileJava
warning: [options] bootstrap class path not set in conjunction with -source 1.5
warning: [options] source value 1.5 is obsolete and will be removed in a future release
warning: [options] target value 1.5 is obsolete and will be removed in a future release
warning: [options] To suppress warnings about obsolete options, use -Xlint:-options.
4 warnings

> Task :compileTestJava
warning: [options] bootstrap class path not set in conjunction with -source 1.5
warning: [options] source value 1.5 is obsolete and will be removed in a future release
warning: [options] target value 1.5 is obsolete and will be removed in a future release
warning: [options] To suppress warnings about obsolete options, use -Xlint:-options.
4 warnings

BUILD SUCCESSFUL in 7s
4 actionable tasks: 4 executed
C:\Users\ankita.agarwal\javaDemo>cd..

C:\Users\ankita.agarwal>cd trial

C:\Users\ankita.agarwal\trial>cd..

C:\Users\ankita.agarwal>mkdir javaGradle

C:\Users\ankita.agarwal>cd javaGradle

C:\Users\ankita.agarwal\javaGradle>gradle init --type java-application

BUILD SUCCESSFUL in 0s
2 actionable tasks: 2 executed
C:\Users\ankita.agarwal\javaGradle>gradle build
Download https://jcenter.bintray.com/com/google/guava/guava/23.0/guava-23.0.pom
Download https://jcenter.bintray.com/com/google/guava/guava-parent/23.0/guava-parent-23.0.pom
Download https://jcenter.bintray.com/org/sonatype/oss/oss-parent/7/oss-parent-7.pom
Download https://jcenter.bintray.com/com/google/j2objc/j2objc-annotations/1.1/j2objc-annotations-1.1.pom
Download https://jcenter.bintray.com/org/codehaus/mojo/animal-sniffer-annotations/1.14/animal-sniffer-annotations-1.14.pom
Download https://jcenter.bintray.com/com/google/errorprone/error_prone_annotations/2.0.18/error_prone_annotations-2.0.18.pom
Download https://jcenter.bintray.com/com/google/code/findbugs/jsr305/1.3.9/jsr305-1.3.9.pom
Download https://jcenter.bintray.com/org/codehaus/mojo/animal-sniffer-parent/1.14/animal-sniffer-parent-1.14.pom
Download https://jcenter.bintray.com/com/google/errorprone/error_prone_parent/2.0.18/error_prone_parent-2.0.18.pom
Download https://jcenter.bintray.com/org/codehaus/mojo/mojo-parent/34/mojo-parent-34.pom
Download https://jcenter.bintray.com/org/codehaus/codehaus-parent/4/codehaus-parent-4.pom
Download https://jcenter.bintray.com/com/google/j2objc/j2objc-annotations/1.1/j2objc-annotations-1.1.jar
Download https://jcenter.bintray.com/com/google/code/findbugs/jsr305/1.3.9/jsr305-1.3.9.jar
Download https://jcenter.bintray.com/org/codehaus/mojo/animal-sniffer-annotations/1.14/animal-sniffer-annotations-1.14.jar
Download https://jcenter.bintray.com/com/google/errorprone/error_prone_annotations/2.0.18/error_prone_annotations-2.0.18.jar
Download https://jcenter.bintray.com/com/google/guava/guava/23.0/guava-23.0.jar

BUILD SUCCESSFUL in 20s
7 actionable tasks: 7 executed
C:\Users\ankita.agarwal\javaGradle>gradle tasks

> Task :tasks

------------------------------------------------------------
All tasks runnable from root project
------------------------------------------------------------

Application tasks
-----------------
run - Runs this project as a JVM application

Build tasks
-----------
assemble - Assembles the outputs of this project.
build - Assembles and tests this project.
buildDependents - Assembles and tests this project and all projects that depend on it.
buildNeeded - Assembles and tests this project and all projects it depends on.
classes - Assembles main classes.
clean - Deletes the build directory.
jar - Assembles a jar archive containing the main classes.
testClasses - Assembles test classes.

Build Setup tasks
-----------------
init - Initializes a new Gradle build.
wrapper - Generates Gradle wrapper files.

Distribution tasks
------------------
assembleDist - Assembles the main distributions
distTar - Bundles the project as a distribution.
distZip - Bundles the project as a distribution.
installDist - Installs the project as a distribution as-is.

Documentation tasks
-------------------
javadoc - Generates Javadoc API documentation for the main source code.

Help tasks
----------
buildEnvironment - Displays all buildscript dependencies declared in root project 'javaGradle'.
components - Displays the components produced by root project 'javaGradle'. [incubating]
dependencies - Displays all dependencies declared in root project 'javaGradle'.
dependencyInsight - Displays the insight into a specific dependency in root project 'javaGradle'.
dependentComponents - Displays the dependent components of components in root project 'javaGradle'. [incubating]
help - Displays a help message.
model - Displays the configuration model of root project 'javaGradle'. [incubating]
projects - Displays the sub-projects of root project 'javaGradle'.
properties - Displays the properties of root project 'javaGradle'.
tasks - Displays the tasks runnable from root project 'javaGradle'.

Verification tasks
------------------
check - Runs all checks.
test - Runs the unit tests.

Rules
-----
Pattern: clean<TaskName>: Cleans the output files of a task.
Pattern: build<ConfigurationName>: Assembles the artifacts of a configuration.
Pattern: upload<ConfigurationName>: Assembles and uploads the artifacts belonging to a configuration.

To see all tasks and more detail, run gradle tasks --all

To see more detail about a task, run gradle help --task <task>

BUILD SUCCESSFUL in 1s
1 actionable task: 1 executed
C:\Users\ankita.agarwal\javaGradle>gradle tasks --all

> Task :tasks

------------------------------------------------------------
All tasks runnable from root project
------------------------------------------------------------

Application tasks
-----------------
run - Runs this project as a JVM application

Build tasks
-----------
assemble - Assembles the outputs of this project.
build - Assembles and tests this project.
buildDependents - Assembles and tests this project and all projects that depend on it.
buildNeeded - Assembles and tests this project and all projects it depends on.
classes - Assembles main classes.
clean - Deletes the build directory.
jar - Assembles a jar archive containing the main classes.
testClasses - Assembles test classes.

Build Setup tasks
-----------------
init - Initializes a new Gradle build.
wrapper - Generates Gradle wrapper files.

Distribution tasks
------------------
assembleDist - Assembles the main distributions
distTar - Bundles the project as a distribution.
distZip - Bundles the project as a distribution.
installDist - Installs the project as a distribution as-is.

Documentation tasks
-------------------
javadoc - Generates Javadoc API documentation for the main source code.

Help tasks
----------
buildEnvironment - Displays all buildscript dependencies declared in root project 'javaGradle'.
components - Displays the components produced by root project 'javaGradle'. [incubating]
dependencies - Displays all dependencies declared in root project 'javaGradle'.
dependencyInsight - Displays the insight into a specific dependency in root project 'javaGradle'.
dependentComponents - Displays the dependent components of components in root project 'javaGradle'. [incubating]
help - Displays a help message.
model - Displays the configuration model of root project 'javaGradle'. [incubating]
projects - Displays the sub-projects of root project 'javaGradle'.
properties - Displays the properties of root project 'javaGradle'.
tasks - Displays the tasks runnable from root project 'javaGradle'.

Verification tasks
------------------
check - Runs all checks.
test - Runs the unit tests.

Other tasks
-----------
compileJava - Compiles main Java source.
compileTestJava - Compiles test Java source.
processResources - Processes main resources.
processTestResources - Processes test resources.
startScripts - Creates OS specific scripts to run the project as a JVM application.

Rules
-----
Pattern: clean<TaskName>: Cleans the output files of a task.
Pattern: build<ConfigurationName>: Assembles the artifacts of a configuration.
Pattern: upload<ConfigurationName>: Assembles and uploads the artifacts belonging to a configuration.

BUILD SUCCESSFUL in 0s
1 actionable task: 1 executed
C:\Users\ankita.agarwal\javaGradle>gradle -q complieJava

FAILURE: Build failed with an exception.

* What went wrong:
Task 'complieJava' not found in root project 'javaGradle'. Some candidates are: 'compileJava'.

* Try:
Run gradle tasks to get a list of available tasks. Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 0s

C:\Users\ankita.agarwal\javaGradle>gradle -q compileJava
C:\Users\ankita.agarwal\javaGradle>gradle run

> Task :run
Hello world.

BUILD SUCCESSFUL in 1s
2 actionable tasks: 1 executed, 1 up-to-date
C:\Users\ankita.agarwal\javaGradle>gradle -q jar
C:\Users\ankita.agarwal\javaGradle>
