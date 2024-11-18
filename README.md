### **Objective:**

In this exercise, you’ll integrate a public API to create a table displaying user data, with pagination and filteres, and modal popup.

### **Exercise Overview:**

1. **Public API Integration:**
You’ll use the Random User API to fetch a list of users.
    - **API Example**: `https://randomuser.me/api/?page=1`
    - documentation: https://randomuser.me/documentation#format
    
    You will implement a table with the following features:
    
    - **Pagination**: Users should be able to browse through multiple pages of user data.
    - **Filters**: Include filters for the following columns:
        - **Gender** (`male`, `female`)
        - **Nationality** (e.g., `US`, `GB`, `FR`)
        - **Age Range** (e.g., `18-30`, `30-50`, `50+`)

2. **Table Structure:**
The table should present **basic information** about the users, including the following 5-6 columns:
    - **Name** (first and last name)
    - **Email**
    - **Gender**
    - **Age**
    - **Nationality**

3. **Modal:**
Clicking the name of the user will open a modal and display their profile picture (from the API).

4. **Setup and Tools:**
You’ll start with an empty React project, and you’re free to install any libraries or tools that will help you complete the task efficiently. Feel free to use any UI component library (e.g., Material UI, Mantine) or API libraries (e.g., axios, fetch).

### **Submission Guidelines:**

- This exercise has a time frame of 1 hour. 
- The scope is bigger than the time frame, plan and prioritize your steps.
- Once completed, please submit a zip file of your project.

### **Evaluation Criteria:**

- Functionality before visuals
  - Proper API integration with working filters and pagination.
  - Implementation of the modal functionality to show user images.
- Consistency in file structure, naming conventions
- Separation into components where it makes sense
- Clear and communicative component/variable/function names

### **Bonus Points**:

- Implement sorting functionality (e.g., by age or name).
