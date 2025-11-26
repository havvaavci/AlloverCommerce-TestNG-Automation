# AlloverCommerce Test Automation (Selenium + TestNG)

This project is a UI test automation framework developed for the **AlloverCommerce** e-commerce application.  
It is built with **Selenium WebDriver**, **TestNG**, **Page Object Model (POM)**, and **ExtentReports** using TestNG listeners.

---

## 🧰 Tech Stack

- **Language:** Java  
- **Test Framework:** TestNG  
- **Automation Tool:** Selenium WebDriver  
- **Build Tool:** Maven  
- **Design Pattern:** Page Object Model (POM)  
- **Reporting:** ExtentReports (via TestNG Listener)  
- **Utilities:** Reusable methods (waits, JS actions, browser actions, Excel, config reader, etc.)

---

## 📁 Project Structure

```text
src
└── test
    └── java
        ├── Pages/           # Page Object classes for AlloverCommerce pages
        ├── Tests/           # TestNG test classes (US_XX, TC_XX, smoke, regression, etc.)
        └── utilities/       # Driver, BrowserUtils, WaitUtils, ConfigReader, ExcelUtils, JSUtils...

target
└── extentReport/            # Generated HTML reports

testng XML files (in project root)
├── smoketest.xml
├── registertest.xml
├── US_11TestRunner.xml
├── US_16Runner.xml
├── US_18_TC_01Runner.xml
├── US_18_TC_03Runner.xml
└── US_20Runner.xml
---

## 🚀 How to Run Tests

1️⃣ Clone or fork this repository  
2️⃣ Open the project in IntelliJ IDEA  
3️⃣ Update `configuration.properties`  
4️⃣ Run tests using one of the following options:

### ▶ From TestNG XML

Right-click any XML file (e.g., `smoketest.xml`) → **Run 'smoketest.xml'**

### ▶ From Maven (optional)

```bash
mvn clean test -DsuiteXmlFile=smoketest.xml

```markdown
## 🧪 Test Coverage

| Test Area                 | Status       |
|---------------------------|--------------|
| Login / Authentication    | ✔️ Completed |
| Registration              | ✔️ Completed |
| Vendor / Customer Flows   | ✔️ Completed |
| Smoke Suite               | ✔️ Completed |
| Regression Scenarios      | ⏳ Planned   |
| Additional Negative Cases | ⏳ Planned   |

## 👩‍💻 Author

**Havva Avcı**  
🔗 LinkedIn: https://www.linkedin.com/in/havva-avci/  
🔗 GitHub: https://github.com/havvaavci
