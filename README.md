# Microservices Project 🚀

This repository contains 3 microservices built using **Java Spring Boot** for managing **Cards**, **Loans**, and **Accounts**. These services provide basic functionalities such as creating cards, managing loans, and handling accounts data. It also includes a Postman JSON collection to test the services.

## Microservices Overview 🛠️

- **Cards Service** 💳: Manages card-related operations such as card creation and retrieval.
- **Loans Service** 🏦: Handles loan applications and management.
- **Accounts Service** 💼: Manages user account information and balances.

### Technologies Used 💻

- **Java 17+**
- **Spring Boot 2.x**
- **Spring Web** (REST API)
- **Spring Data JPA** (Database interactions)
- **H2 Database** (In-memory database for demo)
- **Postman** (for API testing)
- **Maven** (Build tool)

### Postman Collection 📑

The repository includes a **Postman JSON collection** to test and interact with the microservices. Import the collection in Postman to get started quickly.

### Running the Microservices ⚙️

1. **Clone this repository**:
    ```bash
    git clone https://github.com/yourusername/microservices.git
    ```

2. **Navigate to each service directory** and run:
    ```bash
    mvn spring-boot:run
    ```
3. **Test the services** using the Postman collection included in the `postman` folder.

### Features 🎯

- **Cards Service**: Create, view, and manage cards.
- **Loans Service**: Apply for loans and check loan statuses.
- **Accounts Service**: Create user accounts, view balances, and more.

### Postman Testing 🚀

The Postman collection contains the following endpoints:
- **Cards Service**:
  - `POST /cards` - Create a new card.
  - `GET /cards/{id}` - Get card details.
  
- **Loans Service**:
  - `POST /loans` - Apply for a loan.
  - `GET /loans/{id}` - Get loan details.
  
- **Accounts Service**:
  - `POST /accounts` - Create an account.
  - `GET /accounts/{id}` - View account details.

### Credits 🏅

This project is built following the **Microservices** course by **Madan Reddy** on Udemy. 🎓

> [Madan Reddy's Microservices Course on Udemy](https://www.udemy.com/course/microservices-with-spring-boot/)

### License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to contribute to the project! 😊
