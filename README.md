# Form Validation Project

This project contains a simple HTML form with client-side validation using JavaScript. It includes both sign-in and sign-up forms, with comprehensive input validation for various fields.

## Features

* **Sign-in and Sign-up Forms:** Provides two separate forms for user authentication.
* **Client-Side Validation:** Uses JavaScript to validate form inputs before submission.
* **Input Validation:**
    * Username: Required, minimum 4 characters, alphanumeric and underscore only.
    * Password: Required, minimum 6 characters for sign-in, 8 characters for sign-up, with at least one uppercase letter, one lowercase letter, one number, and one special character.
    * Full Name: Required, minimum 3 characters.
    * Email: Required, valid email format.
    * Age: Required, numeric, above 18 and below 120.
    * Phone Number: Required, 10 digits.
    * Website: Optional, valid URL format.
    * Confirm Password: Must match new password entry.
* **Error Messages:** Displays clear error messages for invalid inputs.
* **Success Messages:** Shows success messages upon successful form submission.
* **Form Toggling:** Allows users to switch between sign-in and sign-up forms.
* **Responsive Design:** Utilizes CSS for a clean and responsive layout.

## Technologies Used

* **HTML:** Structure of the web page.
* **CSS:** Styling of the web page.
* **JavaScript:** Client-side form validation and interactivity.

## How to Use

1.  **Clone the Repository:**
    ```bash
    git clone <repository-url>
    ```
2.  **Open `index.html`:** Open the `index.html` file in your web browser.
3.  **Interact with the Forms:** Fill out the forms and observe the validation messages.
4.  **Toggle Forms:** Use the "Sign Up" and "Sign In" links to switch between forms.

## JavaScript Validation Details

The JavaScript code includes the following validation functions:

* `showError(input, errorId, message)`: Displays error messages.
* `isValidEmail(email)`: Validates email format using regex.
* `isValidPassword(password)`: Validates password strength using regex.
* `isValidPhone(phone)`: Validates phone number format using regex.
* `isValidURL(url)`: Validates URL format using regex.

## Customization

* **Styling:** Modify the CSS in the `<style>` tags to customize the appearance of the forms.
* **Validation Rules:** Adjust the validation rules in the JavaScript code to meet your specific requirements.
* **Additional Fields:** Add more input fields to the forms and implement corresponding validation logic.

## Notes

* This project focuses on client-side validation. Server-side validation is recommended for production environments.
* The password validation requires a strong password. You can adjust the regex to change password requirements.
* The phone number validation requires a 10 digit number.
