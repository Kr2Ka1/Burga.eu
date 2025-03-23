## **Burga.eu testing with Cypress**

### **Project Description**  
This repository contains automated tests and configurations for the **Burga.eu** e-commerce website. The project ensures the website's functionality, performance, and UI consistency using automation tools.  

### **Technologies Used**  
- **Cypress** (for end-to-end testing)  
- **GitHub Actions** (for CI/CD integration)  

---

## **Getting Started**  

### Relevant information. Testing on the site is limited, so most of the tests were done using vpn and different IP addresses due to the security on the site. Therefore, not all tests may load.

### **1. Clone the Repository**  
```sh
git clone https://github.com/Kr2Ka1/Burga.eu.git
cd Burga.eu
```

### **2. Install Dependencies**  
Ensure you have **Node.js (22.x)** installed, then run:  
```sh
npm install
```

### **3. Run Cypress Tests**  
To open Cypress in interactive mode:  
```sh
npx cypress open
```

To run tests in headless mode:  
```sh
npx cypress run
```

Run a specific test:  
```sh
npx cypress run --spec cypress/integration/example.spec.js
```

### **4. View Test Reports**  
Cypress generates test results in the **reports/** directory. 

---

## **Continuous Integration (CI) with GitHub Actions**  
The repository includes a **GitHub Actions** workflow to automatically execute tests on push and pull requests.


