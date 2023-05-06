# gradle-testng-jenkins

This code covers how can we run TestNG Tests using gradle test scope without creating a testng.xml Suite file. 

1. Command to run specific test - 

```
./gradlew clean test -DtestsToRun=uiTests.SampleTest_FF.*
```


2. Command to run multiple tests from different packages -
```
./gradlew clean test -DtestsToRun=uiTests.*,chromeTests.*
```

3. Command to run tests matching groups - 
```
./gradlew clean test -Dgroups=chrome
```

For a detailed explanation, please watch my YouTube video -  https://youtu.be/-cOCK123D6E
