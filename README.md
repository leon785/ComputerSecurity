# ComputerSecurity

· Developed a web forum for antique sales using PHP that stores data in a web database. Allows users to register and login, post pictures and text, allows the administrators to post and view all users’ sent posts.

· Implemented protection against SQL injection, Dictionary attack, CSRF and XSS by check-methods, import frequently-used-text library and magic quotes. Further improved the security by QR code two-step verification, Google reCAPTCHA.

These above are reflected in the:

1. Have the policy to check the password entropy, when sensitive encypted when storing to the database, allow users to recover the password by answer the security questions they filled in when register.
2. Implemented the counter-measures for SQL injection, XSS, CSRF, suspicious file upload, dictionary attack.
3. Make sure the user identity is genuine by using QR code two-step verification, email verification, registration and login.
4. Avoid robotic brute force attack by using Google reCAPTCHA.
5. Preventing serious consequences by banning the IP address when reaching the maximum number of incorrect passwords, alerting user's registered email when the account was logged in at a different IP address.
   
