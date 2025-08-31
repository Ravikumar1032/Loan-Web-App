# Loan Application Web App

## Screenshots of the Web App

Below are screenshots showcasing the functionality and design of the application:

![Screenshot 10](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(10).png)
![Screenshot 11](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(11).png)
![Screenshot 12](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(12).png)
![Screenshot 13](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(13).png)
![Screenshot 14](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(14).png)
![Screenshot 15](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(15).png)
![Screenshot 16](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(16).png)
![Screenshot 17](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(17).png)
![Screenshot 18](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(18).png)
![Screenshot 19](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(19).png)
![Screenshot 20](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(20).png)
![Screenshot 21](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(21).png)
![Screenshot 22](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(22).png)
![Screenshot 23](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(23).png)
![Screenshot 24](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(24).png)
![Screenshot 25](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(25).png)
![Screenshot 26](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(26).png)
![Screenshot 27](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(27).png)
![Screenshot 28](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(28).png)
![Screenshot 29](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(29).png)
![Screenshot 30](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(30).png)
![Screenshot 31](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(31).png)
![Screenshot 32](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(32).png)
![Screenshot 33](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(33).png)
![Screenshot 34](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(34).png)
![Screenshot 35](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(35).png)
![Screenshot 36](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(36).png)
![Screenshot 37](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(37).png)
![Screenshot 38](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(38).png)
![Screenshot 39](https://github.com/Ravikumar1032/Loan-App/blob/main/Screenshots/Screenshot%20(39).png)

---

## Overview
The Loan Application Web App is a comprehensive solution for loan management. It provides workflows for both users and administrators, featuring functionalities such as loan application submission, credit assessment, eligibility determination, and loan report generation. The application is responsive and built with modern web technologies.

---

## Features
### User Workflow
- **Sign-Up/Login**: Secure authentication system for users.
- **Loan Application Form**: Multi-step form for personal, financial, and CIBIL/bank details.
- **Acknowledgment Page**: Displays confirmation upon loan application submission.

### Admin Workflow
- **Admin Dashboard**: Overview of loan applications and statuses.
- **Application Review**: Detailed credit assessment and decision-making.
- **Loan Report Card**: Generation of detailed loan summaries.

### Additional Features
- **Credit Assessment Logic**: Automated calculations for eligibility.
- **Responsive Design**: Works across all devices.

---

## Tech Stack
### Frontend
- React.js
- CSS (custom styling)

### Backend
- Node.js (Express.js)
- MongoDB (Database)

---

## Directory Structure
```
src/
├── components/
│   ├── AdminDashboard/
│   │   ├── AdminDashboard.css
│   │   ├── AdminDashboard.js
│   │   ├── ApplicationReview.css
│   │   ├── ApplicationReview.js
│   │   ├── CreditAssessment.js
│   │   ├── LoanApplications.css
│   │   ├── LoanApplications.js
│   │   ├── ReportsAnalytics.css
│   │   ├── ReportsAnalytics.js
│   ├── Auth/
│   │   ├── Auth.css
│   │   ├── AuthContainer.js
│   │   ├── Login.js
│   │   ├── PrivateRoute.js
│   │   ├── SignUp.js
│   ├── Images/
│   │   ├── bg1.jpg
│   │   ├── bg2.jpg
│   │   ├── bg3.jpg
│   │   ├── bgVideo.mp4
│   │   ├── bgvideo2.mp4
│   │   ├── bgvideo3.mp4
│   │   ├── feature1.jpg
│   │   ├── feature2.jpg
│   │   ├── feature3.jpg
│   ├── Pages/
│   │   ├── ErrorPage.js
│   │   ├── Home.css
│   │   ├── Home.js
│   │   ├── UserHome.js
│   ├── services/
│   │   ├── api.js
│   ├── Shared/
│   │   ├── Button.js
│   │   ├── Footer.css
│   │   ├── Footer.js
│   │   ├── Header.css
│   │   ├── Header.jsx
│   │   ├── InputField.js
│   │   ├── Modal.js
│   ├── UserDashboard/
│       ├── Acknowledgment.js
│       ├── LoanStatus.css
│       ├── LoanStatus.js
│       ├── UserDashboard.css
│       ├── UserDashboard.js
│       ├── UserDashboard1.js
│       ├── UserHome.css
│       ├── UserHome.js
│       ├── LoanForms/
│           ├── FinancialDetailsForm.js
│           ├── LoanApplication.css
│           ├── LoanApplicationForm.js
│           ├── PersonalDetailsForm.js
├── context/
│   ├── AuthContext.js
├── styles/
├── App.css
├── App.js
├── App.test.js
├── index.css
├── index.js
├── reportWebVitals.js
├── setupTests.js
```

---

## Setup Instructions

### Prerequisites
- Node.js
- MongoDB

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Ravikumar1032/loan-app.git
   cd loan-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure the database:
   - Set up the MongoDB database.
   - Update the `.env` file with your MongoDB connection string and other environment variables.

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000`.

---


## Color Theme
| Element             | Color       |
|---------------------|-------------|
| Primary Color       | #4CAF50     |
| Secondary Color     | #FF9800     |
| Accent Color        | #1976D2     |
| Background          | #F5F5F5     |
| Error Color         | #F44336     |

---

## Contribution
Feel free to contribute to this project by creating issues or submitting pull requests. Ensure that your code adheres to the coding standards and is well-documented.

---

## Contact
For any inquiries, reach out to **M. Ravikumar Naik** at [ravikumarnaik1015@gmail.com](mailto:ravikumarnaik1015@gmail.com).
