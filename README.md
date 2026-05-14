# Selenium Java Automation Portfolio
### QA Automation Framework | Shilpa Soni | CTFL Certified

---

## 🧪 About This Project
End-to-end test automation framework for [SauceDemo](https://www.saucedemo.com) 
e-commerce application, built using Selenium WebDriver with Java.
Demonstrates real-world QA automation skills including Page Object Model, 
TestNG, Maven, and HTML reporting.

---

## 🛠️ Tech Stack
| Tool | Purpose |
|---|---|
| Java | Programming language |
| Selenium WebDriver 4.18 | Browser automation |
| TestNG | Test framework |
| Maven | Build and dependency management |
| WebDriverManager | Automatic driver management |
| Extent Reports | HTML test reporting |
| Page Object Model | Design pattern |
| Git & GitHub | Version control |

---

## 📁 Project Structure
selenium-java-portfolio/
├── src/
│   ├── main/java/
│   │   └── pages/
│   │       ├── LoginPage.java
│   │       ├── InventoryPage.java
│   │       ├── CartPage.java
│   │       └── CheckoutPage.java
│   └── test/java/
│       ├── tests/
│       │   ├── LoginTest.java
│       │   ├── CartTest.java
│       │   ├── CheckoutTest.java
│       │   └── E2ETest.java
│       └── utils/
│           ├── BaseTest.java
│           └── ExtentReportManager.java
├── reports/
│   └── TestReport.html
├── testng.xml
└── pom.xml

---

## ✅ Test Cases Covered
| Test | Description | Status |
|---|---|---|
| Successful Login | Verify valid user can login | ✅ Pass |
| Add Item To Cart | Verify item added to cart correctly | ✅ Pass |
| Remove Item From Cart | Verify item removed from cart | ✅ Pass |
| Successful Checkout | Verify complete checkout flow | ✅ Pass |
| Complete E2E Journey | Login → Cart → Checkout → Order confirmation | ✅ Pass |

---

## 🚀 How To Run

**Prerequisites:**
- Java JDK 19+
- Maven
- Chrome Browser

**Run all tests:**
```bash
mvn clean test
```

**Run via TestNG suite:**
Right click `testng.xml` → Run

---

## 📊 Test Report
After running tests, HTML report is generated at:
reports/TestReport.html

---

## 👩‍💻 Author
**Shilpa Soni** — QA Engineer | CTFL Certified  
📧 shilpasoni4991@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/shilpasoni94)
