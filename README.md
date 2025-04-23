# Twitter Login Automation

This project is a simple Java-based Selenium automation test for logging into Twitter. It uses **Maven** for dependency management and **TestNG** as the testing framework. The project is structured to demonstrate browser-based testing using ChromeDriver and the Maven Wrapper.

## Features

- Automated browser testing with **Selenium WebDriver**
- Test structure and lifecycle managed using **TestNG**
- **Maven Wrapper** included to ensure consistent Maven usage across environments
- WebDriver binaries automatically managed via **WebDriverManager**

##  Project Structure
```

- JDK 8 or above
- Git
- Chrome browser installed
```

### Clone the Repository

```
git clone https://github.com/<your-username>/twitter_app.git
cd twitter_app
```

## Run with Maven Wrapper
### Use the Maven Wrapper to install dependencies and run the tests:

```
./mvnw clean test
```

## Login Credentials
⚠️ Important: For security reasons, do not hardcode credentials in the source code.

Use environment variables or external configuration files to manage login information securely.

## Test Files
LoginTest.java: Opens Twitter’s login page and performs a basic login interaction.

TwitterAppApplicationTests.java: Placeholder test to ensure the context loads properly (useful if integrated into a Spring Boot project).

## Dependencies
Selenium WebDriver

## TestNG

WebDriverManager (by Bonigarcia)

All dependencies are declared in the pom.xml file
