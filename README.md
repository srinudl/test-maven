mvn validate: This step validates if the project structure is correct. For example – It checks if all the dependencies have been downloaded and are available in the local repository.

mvn compile: It compiles the source code, converts the .java files to .class and stores the classes in target/classes folder.

mvn test: It runs unit tests for the project.

mvn package: This step packages the compiled code in distributable format like JAR or WAR.

Integration test: It runs the integration tests for the project.

Verify: This step runs checks to verify that the project is valid and meets the quality standards.

mvn install: This step installs the packaged code to the local Maven repository.

mvn deploy: It copies the packaged code to the remote repository for sharing it with other developers.


#######################

Javac Error: javac : command not found

If you had an older javac installed, you may need to sudo alternatives --config javac to make javac point to the newly installed version.


sudo alternatives --config javac
