# Form-Validation-in-HTML-CSS-and-JavaScript

This form validation system includes:

1. **Robust Validation Features**:
   - Real-time validation as users type
   - Specific error messages for each field
   - Visual cues (red/green borders and icons)
   - Submit button that enables only when all fields are valid

2. **Field Validations**:
   - Name: Requires at least 2 characters
   - Email: Validates format using regex
   - Phone: Ensures 10 digits (automatically removes non-digits)
   - Password: Checks for minimum length (8 chars), numbers, and special characters
   - Confirm Password: Verifies it matches the password field

3. **Enhanced User Experience**:
   - Password strength indicator with three levels
   - Password visibility toggle
   - Helper text for fields that need formatting guidance
   - Success message after form submission
   - Form reset after successful submission

4. **Responsive Design**:
   - Works on all screen sizes
   - Clean, modern styling with subtle animations
   - Accessible focus states for keyboard navigation

The form performs all validation on the client side using JavaScript, making it fast and responsive without requiring server interactions for initial validation.
