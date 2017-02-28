[![Build Status](https://travis-ci.org/CS-Worcester-CS-348-SP-2017/CIExample.svg?branch=master)](https://travis-ci.org/CS-Worcester-CS-348-SP-2017/CIExample)

# Continuous Integration Example

## CS-348 Spring 2017

Now with TravisCI Integration! 

# Continuous Integration Exercise

##Fork the Repository
[https://github.com/CS-Worcester-CS-348-SP-2017/CIExample]()

## Clone the Repository

## Add the original repository as an upstream remote

##  Create a `add-name` branch, and switch to that branch

##Build with Maven
In Git Bash or Mac Terminal:

```
cd CIExample
mvn clean compile
```

##Run JUnit Tests with Maven
```
mvn test
```

##Build JAR File with Maven and Run
```
mvn clean package
java -jar target/CIExample-0.0.1-SNAPSHOT.jar
```

##View Travis CI Builds
[https://travis-ci.org/CS-Worcester-CS-348-SP-2017/CIExample]()

##Look at Maven Configuration
Look at the `pom.xml` file in the CIExample

##Look at the Travis Configuration
Look at the `.travis.yml` file in the CIExample

##Look at the Git Configuration
Look at the `.gitignore` file in the CIExample

##Modify the CIExample to Include your Name

###Git Workflow

	3. Add the change
	4. Pull any changes that have ocurred since their last pull, and correct merge conflicts
	4. Commit the change, with a message describing the change (include line number and correction, e.g. `Correct misspelling, line 1: UGN -> GNU` )
	5. Push the change
	6. Make a pull request to have their change merged into the original repository, including in the pull request text a notation that it closes the assigned issue (e.g. `Closes #42`)

####Edit the code
Based on the last digit of your WSU Student ID, edit the appropriate `EndsWith` class. For example, my ID ends with `2`, so I edited the `EndsWith2.java` file. Look at `EndsWith2.java` as an example for what to do.

####Build the code with Maven
```
mvn clean compile
```

####Test the code with Maven
```
mvn test
```

Go update the test for the code you just wrote and test again.

####Build JAR File with Maven and Run
```
mvn clean package
java -jar target/CIExample-0.0.1-SNAPSHOT.jar
```

####Before committing your changes, make sure your repository is up-to-date with upstream
```
git pull upstream master
```

Resolve any conflicts

####Add your code and commit your changes

####Push changes

####Make a pull request to have your change merged into the original repository

####Go to the original repository and approve the pull request

####Check Travis

##Copyright and License
####&copy; 2017 Karl R. Wurst, Worcester State University

<img src="http://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-sa.png" width=100px/>This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit <a href="http://creativecommons.org/licenses/by-sa/4.0/" target="_blank">http://creativecommons.org/licenses/by-sa/4.0/</a> or send a letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View, California, 94041, USA.

