# Akpotu-Augustine-Ntishor-Day3
 Project: Build a simple contact form with various input types.


Form Elements:

1. <form>: The container element for your form.
2. <input>: Used for various input types (e.g., text, email, password, checkbox).
3. <textarea>: For multi-line text input.
4. <select>: For dropdown menus.
5. <button>: For submit or reset buttons.
6. <label>: For associating text with input elements.

Form Attributes:

1. action: Specifies the form submission URL.
2. method: Specifies the submission method (e.g., GET, POST).
3. name: Assigns a name to the form or input element.
4. type: Specifies the input type (e.g., text, email, password).
5. placeholder: Adds a hint or example text.
6. required: Makes the input field mandatory.
7. checked: Pre-selects a checkbox or radio button.

Input Types:

1. text: Single-line text input.
2. email: Email address input.
3. password: Password input.
4. checkbox: Checkbox input.
5. radio: Radio button input.
6. file: File upload input.

Now, let's build a simple contact form with various input types, Uncle N!

Project Code:

<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>
  
  <label for="message">Message:</label>
  <textarea id="message" name="message" required></textarea>
  
  <label for="subscribe">Subscribe:</label>
  <input type="checkbox" id="subscribe" name="subscribe">
  
  <button type="submit">Send</button>
</form>