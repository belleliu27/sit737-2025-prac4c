# SIT323/SIT737 - Cloud Native Application Development
## 4.2C: Enhanced Functionality for the Calculator Microservice

### Overview
The objective of this task is to expand upon the capabilities of the calculator microservice introduced in task 4.1P. By integrating supplementary features and refining its error handling mechanism, you will enhance your proficiency in microservice development while fortifying your ability to craft resilient and intuitive applications.

The required tools for doing this task are as follows:
- **Git**: [https://github.com](https://github.com)
- **Visual Studio Code**: [https://code.visualstudio.com/](https://code.visualstudio.com/)
- **Node.js**: [https://nodejs.org/en/download/](https://nodejs.org/en/download/)

## Part I: Additional Arithmetic Operations
Expand the capabilities of the calculator microservice by introducing support for advanced arithmetic operations such as exponentiation, square root, and modulo operations. You need to implement corresponding API endpoints to handle these operations, thereby enriching the functionality of the microservice and providing users with more comprehensive calculation capabilities.

### Features
The enhanced calculator now supports the following operations:
- **Addition**
- **Subtraction**
- **Multiplication**
- **Division**
- **Exponentiation**
- **Square Root**
- **Modulo**

These operations can be accessed via the following API endpoints:

### API Endpoints

#### 1. Addition
- **Endpoint**: `GET /add`
- **Query Parameters**: `num1`, `num2`
- **Example**: `GET /add?num1=5&num2=10`
- **Response**:
  ```json
  {
    "operation": "add",
    "num1": 5,
    "num2": 10,
    "result": 15
  }
#### 2. Subtraction

- **Endpoint**: `GET /subtract`
- **Query Parameters**: `num1`, `num2`
- **Example**: `GET /subtract?num1=10&num2=5`
- **Response**:
  - **operation**: subtract
  - **num1**: 10
  - **num2**: 5
  - **result**: 5

#### 3. Multiplication

- **Endpoint**: `GET /multiply`
- **Query Parameters**: `num1`, `num2`
- **Example**: `GET /multiply?num1=4&num2=5`
- **Response**:
  - **operation**: multiply
  - **num1**: 4
  - **num2**: 5
  - **result**: 20

#### 4. Division

- **Endpoint**: `GET /divide`
- **Query Parameters**: `num1`, `num2`
- **Example**: `GET /divide?num1=10&num2=2`
- **Response**:
  - **operation**: divide
  - **num1**: 10
  - **num2**: 2
  - **result**: 5

##### 5. Exponentiation

- **Endpoint**: `GET /exponent`
- **Query Parameters**: `num1`, `num2`
- **Example**: `GET /exponent?num1=2&num2=3`
- **Response**:
  - **operation**: exponent
  - **num1**: 2
  - **num2**: 3
  - **result**: 8

#### 6. Square Root

- **Endpoint**: `GET /sqrt`
- **Query Parameters**: `num1`
- **Example**: `GET /sqrt?num1=9`
- **Response**:
  - **operation**: sqrt
  - **num1**: 9
  - **result**: 3

#### 7. Modulo

- **Endpoint**: `GET /mod`
- **Query Parameters**: `num1`, `num2`
- **Example**: `GET /mod?num1=10&num2=3`
- **Response**:
  - **operation**: mod
  - **num1**: 10
  - **num2**: 3
  - **result**: 1
