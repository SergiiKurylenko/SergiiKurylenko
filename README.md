# QA Automation Project

## 📌 About the Project
This repository contains automation test scripts for **web and mobile applications** using **Java, Selenium, Selenide, Appium, and RestAssured**. The goal is to ensure software quality by implementing automated test frameworks and integrating them into **CI/CD pipelines**.

## 🛠️ Technologies & Tools
- **Java** (Maven, JUnit)
- **Selenium & Selenide** (Web UI Testing)
- **Appium** (Mobile Testing for iOS/Android)
- **RestAssured** (API Testing)
- **JMeter** (Performance Testing)
- **Git & Docker** (Version Control & Containerization)
- **CI/CD Pipelines** (Jenkins/GitHub Actions)

## 🚀 Getting Started
### Prerequisites
- Install **Java JDK 11+**
- Install **Maven**
- Install **Appium Server** for mobile testing
- Install **Docker** (optional for containerized tests)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```
2. Install dependencies:
   ```sh
   mvn clean install
   ```

## 🔥 Running Tests
### Web Automation Tests
```sh
mvn test -Dtest=WebTestSuite
```

### Mobile Automation Tests
```sh
mvn test -Dtest=MobileTestSuite
```

### API Tests
```sh
mvn test -Dtest=ApiTestSuite
```

## 📂 Project Structure
```
📦 your-repository
 ┣ 📂 src/test/java
 ┃ ┣ 📂 webTests
 ┃ ┣ 📂 mobileTests
 ┃ ┣ 📂 apiTests
 ┃ ┗ 📂 utils
 ┣ 📜 pom.xml
 ┣ 📜 README.md
 ┗ 📜 .gitignore
```

## 📢 Contact
**Sergii Kurylenko**  
📧 Email: sergiykurylenko@gmail.com  
🔗 LinkedIn: [linkedin.com/in/sergii-kurylenko](https://www.linkedin.com/in/sergii-kurylenko)
