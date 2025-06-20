---

# ✅ To-Do List Application Deployment

A simple yet effective **To-Do List** web app built using **HTML**, **CSS**, and **JavaScript**, deployed on **AWS S3** for global availability and scalability.

---

## 📌 Step 1: Project Overview

* **🎯 Objective**: Create an interactive To-Do List with core task management functionality, hosted on AWS.
* **🛠️ Tech Stack**:

  * **Frontend**: HTML5, CSS3, JavaScript (vanilla)
  * **Hosting**: AWS S3 (Static Website Hosting)
* **✨ Key Features**:

  * Add, edit, delete tasks
  * Mark tasks as complete
  * Responsive layout with gradient styling

---

## 🧱 Step 2: HTML Structure

* **Basic Setup**:

  * `<!DOCTYPE html>` for HTML5 compliance
  * Meta tag: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
  * Title: `"To-Do List"`

* **Core Elements**:

  * **Container**: `.todo-container` to wrap all content
  * **Input Section**: Text input (`taskInput`) + “Add Task” button
  * **Task List**: `<ul>` dynamically populated with `<li>` tasks

---

## 🎨 Step 3: CSS Styling

* **Global Styles**:

  * Gradient background (purple → blue)
  * Font: Arial; text: white

* **Todo Container**:

  * White card-like box with rounded corners and shadow
  * Width: `350px`, centered using margin auto

* **Task Items**:

  * Flex layout for task text + buttons
  * Button colors: Edit (orange), Delete (red), Add (purple)
  * Hover background: `#ececec`

* **Completed Tasks**:

  * Toggle `complete` class for task strikethrough

---

## ⚙️ Step 4: JavaScript Functionality

* **`addTask()`**:

  * Validates input
  * Creates a `<li>` with task text and action buttons
  * Appends task to the list

* **Edit Function**:

  * Switches between "Edit" and "Save"
  * Replaces text span with editable input

* **Delete Function**:

  * Removes task from the DOM when "Done" is clicked

* **Mark Complete**:

  * Click task text → toggles `complete` class 

---

## ☁️ Step 5: AWS Deployment

* **Steps**:

  * Upload HTML, CSS, JS files to an **S3 bucket**
  * Enable **Static Website Hosting**
  * Make files publicly accessible

* **Benefits**:

  * 🌍 Global reach
  * ⚡ Fast static content delivery
  * 💰 Cost-effective and scalable

---

## ✨ Step 6: Key Features & Interactions

| Feature         | Description                          |
| --------------- | ------------------------------------ |
| **Add Task**    | Input text + “Add Task” button       |
| **Edit Task**   | Click “Edit” → edit → “Save”         |
| **Delete Task** | Click “Done” button to remove task   |
| **Mark Done**   | Click task text to toggle completion |

---

## 🚀 Step 7: Potential Improvements

* **Bug Fix**:

  * Add `text-decoration: line-through` to `.complete` class

* **Enhancements**:

  * 💾 Local Storage for persistent task data
  * 🔁 Drag-and-drop to reorder tasks
  * 🔖 Add categories or priority labels

* **Backend Integration**:

  * Use AWS Lambda + DynamoDB to store tasks in the cloud

---

## 🏁 Step 8: Conclusion

* Fully client-side app with essential CRUD operations
* Built with clean, responsive design
* Deployed on AWS for global reach and scalability

---

## ▶️ Demo Instructions

1. **🔬 Local Testing**:
   Open `index.html` in your web browser.

2. **🌐 AWS Hosting**:
   Access via:
   `http://your-bucket.s3-website-region.amazonaws.com`

---
