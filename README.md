
README.md: This file, providing instructions and information about the project.
Dependencies
Bootstrap 3.4.1: CSS and JS framework for styling and responsiveness.
jQuery 3.5.1: JavaScript library for simplified DOM manipulation.
 
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

**Database Connection**
The form uses the "http://api.login2explore.com:5577/api/iml" API for database interaction. The connection token, database name ("SCHOOL-DB"), and relation name ("STUDENT-TABLE") are specified in the JavaScript code.

Important Note
This project is a simple illustration and uses a placeholder API. In a real-world scenario, you would need a secure backend server and database with proper authentication and authorization mechanisms.