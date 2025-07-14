💻 Technologies Used
HTML5: Structures the content and defines the layout of the web pages (Registration, Login, Dashboard).

CSS3: Styles the application, providing a modern and responsive user interface with animations and a clean design.

JavaScript : Handles all the dynamic functionalities, including:

Form validation for all input fields.

Password visibility toggle.

Image preview for profile pictures.

Page navigation (switching between Register, Login, and Dashboard views).

User data storage and retrieval using localStorage.

User registration and login logic.

Displaying user-specific information on the dashboard.

✅ Validations Added
The registration form includes comprehensive client-side validations to ensure data integrity and a smooth user experience. Error messages are displayed in real-time as the user types.

Full Name:

Required.

Minimum 3 characters.

Cannot contain digits.

Cannot have the same character repeated three or more times consecutively (e.g., "aaa").

Email:

Required.

Must be a valid email format (e.g., user@example.com).

Checks for uniqueness (email must not already exist in the stored users).

Password:

Required.

Minimum 8 characters.

Must contain at least one uppercase letter.

Must contain at least one lowercase letter.

Must contain at least one number.

Must contain at least one special character (!@#$%^&*).

Confirm Password:

Required.

Must match the Password field.

Phone Number:

Required.

Must be exactly 10 digits.

Gender:

Required (at least one option must be selected).

Date of Birth:

Required.

User must be at least 18 years old.

Address:

Required.

Minimum 10 characters.

City:

Required (a city must be selected from the dropdown).

Skills Known:

Required (at least one skill must be selected).

Terms and Conditions:

Required (checkbox must be checked).

🚀 Steps to Run the Project
This project is a single HTML file and does not require any special setup or server to run.

Save the file: Copy the entire HTML code provided and save it as an .html file (e.g., index.html) on your computer.

Open in Browser: Locate the saved index.html file and open it with any modern web browser (e.g., Chrome, Firefox, Edge, Safari).

That's it! The application will load in your browser, and you can start interacting with the registration, login, and dashboard features. All user data will be stored locally in your browser's localStorage.