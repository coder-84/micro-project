Title: Micro Project Work.
**Overview**
The Student Enrollment Form micro project is designed to create a web-based form for managing student data, specifically storing and updating information in the STUDENT-TABLE relation of the SCHOOL-DB database. The form includes essential input fields such as Roll No, Full Name, Class, Birth Date, Address, and Enrollment Date.

Benefits of using JsonPowerDB
1. Minimum Development Cost.
2. Minimum Time to Market
3. Minimize the complexity of interoperability of different applications
4. Maximum data processing performance
5.Technology Futuristic
     ○ Fills gap from database to big-data
     ○ Pluggable with new algorithms and pluggable and user defined API
6. Minimize Total Cost of Ownership

**Dependencies**
1. Bootstrap 3.4.1: CSS and JS framework for styling and responsiveness.
2. jQuery 3.5.1: JavaScript library for simplified DOM manipulation.
 
**How to Run**
1. Open the index.html file in a web browser.

2. The form will be displayed with input fields for Roll No, Full Name, Class, Birth Date, Address, and Enrollment Date. On page load or any control button click, an empty form will be displayed.

3. The cursor will remain at the first input field (Roll No), and all other fields and buttons will be disabled initially.

4. Enter data in the Roll No field. If the Roll No does not exist in the database, the [Save] and [Reset] buttons will be enabled. Move the cursor to the next field and enter data in the form.

5. Check that all data fields are valid (non-empty).

6. Click the [Save] button to store the data in the database. The form will be reset to step 2.

7. If the Roll No already exists in the database, the form will display the existing data. The [Update] and [Reset] buttons will be enabled, allowing you to modify other fields.

8. Check that all data fields are valid (non-empty).

9. Click the [Reset] button at any time to reset the form to step 2.
. **output**
 ![image](https://github.com/coder-84/micro-project/assets/90142563/b15ace34-5822-42c0-8d17-2385f5c9d7ae)
![image](https://github.com/coder-84/micro-project/assets/90142563/91d5568e-c2bb-4b7f-915f-559c0ccdf99f)



**Database Connection**
The form uses the "http://api.login2explore.com:5577/api/iml" API for database interaction. The connection token, database name ("SCHOOL-DB"), and relation name ("STUDENT-TABLE") are specified in the JavaScript code.

Important Note
This project is a simple illustration and uses a placeholder API. In a real-world scenario, you would need a secure backend server and database with proper authentication and authorization mechanisms.
