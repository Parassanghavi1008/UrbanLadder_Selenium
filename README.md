# UrbanLadder(Cucumber Selenium Automation Testing)

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/5b/Urban_Ladder_Logo.png" alt="Urban Ladder" width="300">
</p>

##  Introduction

This project automates the testing of the **Urban Ladder** website using **Java**, **Selenium WebDriver**, **Cucumber**, and **TestNG**. It follows a Behavior Driven Development (BDD) approach using Gherkin syntax and validates major e-commerce features such as searching, filtering, adding to cart, and checkout processes.

---

##  Objective

To create a robust, maintainable, and scalable test automation framework that ensures:

- Functionality of key user flows on the Urban Ladder website
- Seamless execution using BDD (Cucumber)
- Clear and visual reporting of test results

---

##  Automated Scenarios

1. **Home Page Verification**  
   - Load the Urban Ladder home page  
   - Assert that the page loads successfully

2. **Search Functionality**  
   - Enter `"Sofa"` in the search bar  
   - Verify that product listings appear

3. **Filter Application**  
   - Apply Price filter  
   - Validate filtered results

4. **Add to Cart**  
   - Click a product  
   - Switch to a new tab  
   - Add the product to cart  
   - Confirm it's added

5. **Checkout Process**  
   - Navigate to the cart  
   - Simulate checkout  
   - Enter dummy shipping details  
   - Reach the payment page (simulation)

---
```
UrbanLadder_Selenium/
├── .idea/                         
├── src/
│   └── test/
│       ├── java/
│       │   ├── pageObject/        
│       │   ├── stepdefinitions/   
│       │   │   ├── AddToCartPageSteps.java
│       │   │   ├── HomePageSteps.java
│       │   │   └── SearchPageSteps.java
│       │   └── testrunner/
│       │       └── CucumberTest.java  # Test Runner file
│       └── resources/
│           └── features/          
│               ├── AddtoCart.feature
│               ├── HomePage.feature
│               └── SearchPage.feature
├── target/                        
├── .gitignore                     
├── pom.xml                        
└── testng.xml                     
```
---
##  Tech Stack

| Technology      | Description                            |
|----------------|----------------------------------------|
| Java           | Core programming language              |
| Selenium WebDriver | Browser automation                 |
| Cucumber       | BDD Framework using Gherkin syntax     |
| TestNG         | Test orchestration                     |
| Maven          | Project build tool                     |

---

## 📁 Project Structure

---

## 🧪 Tools & Frameworks

![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white)
![Cucumber](https://img.shields.io/badge/Cucumber-23D96C?style=flat&logo=cucumber&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apache-maven&logoColor=white)
![TestNG](https://img.shields.io/badge/TestNG-FF6C37?style=flat&logo=testng&logoColor=white)
![VS Code](https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

---

## 📄 Reports

Cucumber HTML reports are generated after each test run under the `/target/cucumber-reports/` directory.

---

## 💡 How to Run

1. Clone the repository
2. Open in VS Code or IntelliJ
3. Run `mvn clean install`
4. Execute tests via `testng.xml` or `Runner.java`
5. View report in `/target/cucumber-reports/`

---

## 🌐 Application Under Test

🔗 [Urban Ladder](https://www.urbanladder.com/)

---

## 📹 Demo Video

📺 [Watch Test Execution Demo](https://youtu.be/YOUR_DEMO_VIDEO_LINK)

---
