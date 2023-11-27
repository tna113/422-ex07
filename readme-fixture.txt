to run CheckingAccountTestFixture
- open a shell terminal window
- type ./gradlew runCheckingFixture

to run CheckingAccountTestFixture with file path argument
- open a shell terminal window
- type ./gradlew runCheckingFixture --args="CheckingAccountTest"

to run SavingsAccountTestFixture
- open a shell terminal window
- type ./gradlew runSavingsFixture --args="SavingsAccountTest"

test command language
- groovy language similar to java
- found inside build.gradle
- tasks are units of work that are run on an application's build
- runCheckingFixture or runSavingsFixture is the name of the task, it can be referenced on the command line if you want to run that task via: ./gradlew taskName

modified/added files
- CheckingAccountTestFixture
- SavingsAccountTestFixture
- CheckingAccountTest.csv
- SavingsAccountTest.csv
- build.gradle
- readme-fixture.txt