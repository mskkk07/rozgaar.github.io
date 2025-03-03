# Form Validation Project

This project contains a simple HTML form with client-side validation using JavaScript. It includes both sign-in and sign-up forms, with comprehensive input validation for various fields.

## Features

* **Sign-in and Sign-up Forms:** Provides two separate forms for user authentication.
* **Client-Side Validation:** Uses JavaScript to validate form inputs before submission.
* **Input Validation:**
    * Username: Required, minimum 4 characters, alphanumeric and underscore only.
    * ![image](https://github.com/user-attachments/assets/e4169d4f-0b09-48a8-8bcc-0db25cfe034e)

    * Password: Required, minimum 6 characters for sign-in, 8 characters for sign-up, with at least one uppercase letter, one lowercase letter, one number, and one special character.
    * ![image](https://github.com/user-attachments/assets/423fe668-f235-473a-a873-ba6fcd68ea1e)

    * Full Name: Required, minimum 3 characters.
    * ![image](https://github.com/user-attachments/assets/ccc14daa-505e-43e9-bd0d-783a751da020)

    * Email: Required, valid email format.
    * ![image](https://github.com/user-attachments/assets/cf9e7fe8-f133-4b17-a90b-c4eba33bbb31)

    * Age: Required, numeric, above 18 and below 120.
    * ![image](https://github.com/user-attachments/assets/7bb687f0-91a3-472c-b730-4b3717dcb284)

    * Phone Number: Required, 10 digits.
    * ![image](https://github.com/user-attachments/assets/4c610ea9-0ef4-43c4-95c3-c556a7dbbc79)

    * Website: Optional, valid URL format.
    * Confirm Password: Must match new password entry.
* **Error Messages:** Displays clear error messages for invalid inputs.
* ![image](https://github.com/user-attachments/assets/bb2ea433-d859-4a6d-80f6-a4a8836642c1)
* ![image](https://github.com/user-attachments/assets/a675f973-ee7a-4426-818b-2a869eb8d75a)


* **Success Messages:** Shows success messages upon successful form submission  and ressets the page.
* ![image](https://github.com/user-attachments/assets/833ae7bd-47b5-4e04-b74d-c8111f3f94f5)

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
2.  **Open `form.html`:** Open the `form.html` file in your web browser.
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
