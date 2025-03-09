# **React Quiz App**

## **Description**

The **React Quiz App** is an interactive web application that helps users test and enhance their React knowledge through a structured quiz system. The app dynamically loads questions from a fake API, manages user answers, tracks progress, and includes a countdown timer. State management is handled using the **useReducer** hook, making it an excellent project for learning how to manage complex state logic in React.

This project walks through essential **React concepts** such as handling state with `useReducer`, fetching and managing asynchronous data, implementing UI interactions, and structuring a real-world React application.

---

## **Features**

✔ **useReducer for State Management** – Learn how to manage complex state logic using the `useReducer` hook.

✔ **Dynamic Question Loading** – Fetch quiz questions from a mock API and display them dynamically.

✔ **Loading & Error Handling** – Implement different states such as loading, error, and ready.

✔ **User Interaction & Navigation** – Move between questions, submit answers, and track progress.

✔ **Quiz Timer** – Set up a countdown timer using `useEffect`.

✔ **Restart & Completion Handling** – Allow users to restart the quiz and display final results.

---

## **Installation**

### **1. Clone the Repository**

```bash
git clone https://github.com/khanhpiu28/react-quiz-app.git
cd react-quiz-app
```

### **2. Install Dependencies**

```bash
npm install
```

### **3. Start the Application**

```bash
npm start
```

### **4. Open in Browser**

```
http://localhost:3000
```

---

## **Usage**

### **1. Understanding the Core Structure**

- The app initializes state using `useReducer`.
- Questions are fetched from a **fake API** before being displayed.
- The UI updates dynamically based on the quiz progress.

### **2. Navigating the Quiz**

- **Start a new quiz** – The app loads questions and initializes the quiz.
- **Answer questions** – The user selects an answer, and the app tracks the response.
- **Move to the next question** – The app updates the progress state and navigates forward.
- **Track progress** – A progress bar shows quiz completion.
- **Handle quiz completion** – Once all questions are answered, the final score is displayed.
- **Restart the quiz** – Users can reset and take the quiz again.

---
