# Coding Challenge "Test Script for summer.sh "

Test scripts for summer.sh using MAVEN+TESTNG+JAVA

### Prerequisites
- Apache Maven 3.6.0 should be installed
- Java - 8 should be installed


### Installing

- Extarxct the summer.tar.gz file
- Enter the following maven command
    mvn clean

## Running the tests

- Enter the following maven code to run the test
    mvn test
    
- To add more inputs
    - Modify the @Dataprovider in both SummerFileTest.java and SummerTest.java file.
    - Execute mvn clean and mvn test commands

### Functionality of the tests

- Using TestNG @DataProvider, inputs are pushed to "summer.sh"
- Using TestNG Assert data has been validated with the expected
- Using Maven project is build and test are executed 

## Built With

* [TestNG](http://testng.org/doc/documentation-main.html) - Testing Framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [Java](https://docs.oracle.com/javase/8/docs/api/) - Used to write scripts


## Authors

* **Anusha Nadigepu** 

