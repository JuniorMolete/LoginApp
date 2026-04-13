1. The program starts execution in the main method inside the Main class. This is the entry point of the Java application.
2. A Scanner object is created to allow the program to read input from the user via the keyboard (System.in).
3. An object of the Login class is declared and then initialized. This object will be used to access methods that handle login or registration logic.
4. The program displays a heading: "User Registration" to inform the user of the current process.
5. The user is prompted to enter their first name. The Scanner reads the input using nextLine() and stores it in a variable.
6. The same process is repeated for:
   * Last name
   * Username
   * Password
   * Phone number
7. Each input is stored in its own variable so it can be used later (for validation or display).
8. After collecting all inputs, the program can pass this data to methods in the Login class (e.g., to validate username format, check password strength, or verify phone number format).
9. The Login class processes the data and may return results such as:
   * Whether the username is valid
   * Whether the password meets requirements
   * Whether the phone number format is correct
10. Based on the results, the program can display appropriate messages to the user (e.g., success or error messages).
11. The program ends after displaying the final output.
