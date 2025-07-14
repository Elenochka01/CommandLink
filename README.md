# 🧪 CommandLink Automated Test Suite

[![Java](https://img.shields.io/badge/Java-17-blue.svg)](https://www.oracle.com/java/)
[![Selenium](https://img.shields.io/badge/Selenium-Automation-brightgreen)](https://www.selenium.dev/)
[![JUnit](https://img.shields.io/badge/JUnit-Test_Framework-red.svg)](https://junit.org/)
[![Build Passing](https://img.shields.io/badge/build-passing-brightgreen)]()

## 📌 Project Description

**CommandLink Automated Test Suite** is a Java-based UI test automation framework developed to verify the core navigation and redirection features of the [CommandLink](https://www.commandlink.com) website.  

This project focuses on validating that key sections of the website — such as **"Solution"** and **"Company"** — function as expected, including accurate redirection to the **Careers** page.  

The framework uses:
- **Selenium WebDriver** for browser automation  
- **JUnit** for test management  
- **Page Object Model (POM)** for maintainable code structure  
- Manual waits (`Thread.sleep`) for visual demo purposes (e.g., recorded walkthroughs)

It is designed for fast feedback during UI testing and provides the foundation for future scalability, such as full regression coverage, integration with CI/CD pipelines, and advanced wait strategies.

---

## ⚙️ Technologies & Tools

- Java 17
- Selenium WebDriver
- JUnit 5
- Maven
- ChromeDriver
- IntelliJ IDEA
- Git & GitHub
- Thread.sleep (for demo video purposes)
- Assertions for URL and element validation

---

## 📁 Project Structure

```
CommandLink/
│
├── src/test/java/
│   ├── tests/               # Test classes (e.g., SolutionTest, CompanyTest)
│   ├── pages/               # Page Object classes
│   └── utils/               # Utilities (optional)
│
├── pom.xml                  # Maven project file with dependencies
└── README.md                # Project overview and instructions
```

---

## 🔍 Features Covered

- Navigation to “Solution” and “Company” sections
- Redirection validation (e.g., to "Careers" page)
- Assertions on expected URLs
- Use of `Thread.sleep()` for visual validation during demo recording
- Page Object Model implementation

---

## 👩‍💻 Author

**Elena Odnodvortseva**  
QA Automation Engineer | [GitHub](https://github.com/Elenochka01)
