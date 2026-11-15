# MyAccountApp

Mobile Application Development - Practical 04: Data Transfer Between Screens and Form Handling.

In this lab we built a simple account registration app using Expo Router in VS Code. It has three screens:

- **Registration screen** (`app/index.js`) - the user enters username, email, phone number, password, confirm password and year of birth. The form checks that all fields are filled and the passwords match, then sends the data to the next screen with `router.push`.
- **Review screen** (`app/review.js`) - shows the details using `useLocalSearchParams`, including the calculated age. "Edit Info" goes back with `router.back()` and "Confirm & Submit" goes to the success screen. If the age is under 18, an alert says the user must be 18 to proceed.
- **Success screen** (`app/success.js`) - welcomes the user by name.

Output screenshots are in the `Output_Screens` folder.
