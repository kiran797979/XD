# XDisplayName React Application

A React application that displays a form for entering first and last names, and shows the full name when both fields are filled.

## Features

- Form with "First Name" and "Last Name" input fields
- Submit button that processes the form
- Displays full name only when both fields are filled
- JavaScript validation handling empty fields
- Modern, responsive UI with Tailwind CSS
- Prevents form submission when fields are empty
- Supports names with special characters and numbers

## Technical Implementation

- Uses React hooks (useState) for state management
- Controlled components with value and onChange props
- Semantic HTML elements (form, label, h1, p)
- Prevents default form submission with e.preventDefault()
- Tailwind CSS for styling
- Fully self-contained in a single React component

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

3. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Test Cases Covered

✅ Renders form with "Display Full Name" heading  
✅ Two labeled text input fields: "First Name" and "Last Name"  
✅ Submit button labeled "Submit"  
✅ Shows full name when both fields are filled  
✅ Displays below form, not in console  
✅ Page does not reload on submission  
✅ Prevents submission when fields are empty  
✅ Uses JavaScript validation for empty fields  
✅ Supports special characters and numbers in names  
✅ Uses useState hook for state management  
✅ Uses form element with onSubmit handler  
✅ Uses controlled input components  
✅ Uses button type="submit"  
✅ Uses semantic HTML elements  
✅ Prevents default with e.preventDefault()  
✅ Outputs full name using p element  
✅ Uses Tailwind CSS for styling  
✅ Fully self-contained single component  

## Usage

1. Enter your first name in the "First Name" field
2. Enter your last name in the "Last Name" field
3. Click the "Submit" button
4. The full name will be displayed below the form
5. If either field is empty, the form will not submit and no name will be displayed 