# Authentication

Authentication ensures that only authorized users can access the system. It plays a critical role in securing sensitive
data and features.

## Login Options

The system supports the following login options:

1. **Password-Based Login**
2. **OTP-Based Login**

<procedure title="Password-Based Login" id="password-login-id">
   <p>
Users can log in using their registered email along with a secure password. When a <a href="User-Management.md">user
is created</a>, the user will receive an e-mail with a random secure password and link to the portal.</p>
   <step>Select <b>Login with OTP</b></step>
   <img src="password-based-login.png" alt="Alt text" width="300" thumbnail="true"/>
</procedure>


<procedure title="OTP-Based Login" id="otp-login-id">
   <p>
   An alternative to password-based login, this option uses a One-Time Password (OTP). The OTP is sent to the user's
   email and must be entered to authenticate successfully. To use OTP-Based Login, </p>
   <step>Select <b>Login with OTP</b></step>
   <img src="otp-based-login.png" alt="Alt text" width="300" thumbnail="true"/>
   <step>Click <b>Request OTP</b></step>
   <img src="otp-based-login-request-otp.png" alt="Alt text" width="300" thumbnail="true"/>
   <step>Check e-mail for OTP</step>
   <img src="otp-based-login-email.png" alt="Alt text" width="300" thumbnail="true"/>
   <step>Copy and paste the 4 digit <b>One-Time Password</b> to OTP field and click <b>Sign In</b></step>
   <img src="otp-based-login-otp.png" alt="Alt text" width="300" thumbnail="true"/>
</procedure>

## Password Rules

To ensure account security, passwords must adhere to the following rules:

- Must be at least 8 characters long.
- Should include at least one uppercase letter (A–Z).
- Should include at least one lowercase letter (a–z).
- Should include at least one numeric digit (0–9).
- Should include at least one special character (e.g., `@`, `#`, `$`, `%`).