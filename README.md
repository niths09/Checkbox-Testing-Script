# Check Box Selenium Automation Project

This project automates the process of interacting with checkboxes on a practice webpage. The automation script checks and unchecks three car brand checkboxes (BMW, Benz and Honda) using Selenium WebDriver, with delays to allow the user to observe the actions clearly. 

## Features
- Automates the selection (checking) and deselection (unchecking) of three checkboxes: BMW, Benz and Honda.
- **WebDriverWait** is used for explicit waiting to ensure elements are clickable before interacting.
- A small delay is added between each check and uncheck action to make the user observe the change in checkbox state.
- The script uses **ChromeDriver** to perform browser automation.
- After each interaction with the checkbox, the script introduces a wait to simulate a realistic interaction speed.
  
## Prerequisites
Before running the project, ensure that you have the following installed:

1. **Java**: Install Java Development Kit (JDK) on your machine (check by running `java -version` in your terminal).
2. **Selenium WebDriver**: Selenium version 4.25.0 is required for automation. You can add Selenium dependencies in your project through Maven or Gradle.
3. **ChromeDriver**: Download the correct version of **ChromeDriver** that matches your Chrome browser version from [here](https://sites.google.com/a/chromium.org/chromedriver/downloads). Ensure it’s set in your system’s PATH or you specify its location in the code.
4. **IDE**: Use an IDE like IntelliJ IDEA, Eclipse, or any Java-supported IDE to run the code.

## Technologies Used
- **Java**: Programming language used for writing the automation scripts.
- **Selenium 4.25.0**: WebDriver version used for automating browser actions.
- **ChromeDriver**: The WebDriver for automating Google Chrome browser.
- **WebDriverWait**: To manage waiting and synchronization in automation scripts.
