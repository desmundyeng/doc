# Authentication

Authentication ensures that only authorized users can access the system. It plays a critical role in securing sensitive
data and features.

## Login Options

The system supports 2 login options: using <b>Password</b> and <b>OTP</b>

<note>
<b>Login with Password</b> is selected by default
</note>

<tabs>
<tab title="Login with Password" id="tab-password-login-id">
<procedure title="Login with Password" id="password-login-id">
   <p>
Users can log in using their registered email along with a secure password. When a <a href="User-Management.md">user
is created</a>, the user will receive an e-mail with a random secure password and link to the portal.</p>
   <step>Select <b>Login with Password</b></step>
   <img src="password-based-login.png" alt="Alt text" width="300" thumbnail="true"/>
</procedure>
</tab>


<tab title="Login with OTP" id="tab-otp-login-id">
<procedure title="Login with OTP" id="otp-login-id">
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
</tab>
</tabs>

## Change password
<note>
<p>Change Password is only available after logging in.</p>
</note>
<procedure title="" id="change-password-id">
   <step>Tap on <b>Profile icon</b></step> 
   <img src="auth_change_password.png" alt="Alt text" thumbnail="true"/>
    <step>Key-in current and new password. Then, select <b>Update Password</b></step>
   <img src="auth_change_password_details.png" alt="Alt text" width="300" thumbnail="true"/>
</procedure>

## Forgot password

<procedure title="" id="forgot-password-id">
   <step>On login page, select <b>Forgot Password</b></step> 
   <img src="auth_forgot_password.png" alt="Alt text" width="300" thumbnail="true"/>
   <step>Key-in email and select <b>Reset Password</b></step> 
   <img src="auth_forgot_password_.png" alt="Alt text" width="300" thumbnail="true"/>
   <step>Check email and use the new temporary password to login</step> 
   <img src="auth_forgot_password_2.png" alt="Alt text" width="300" thumbnail="true"/>
</procedure>

## Password Rules

To ensure account security, passwords must adhere to the following rules:

- Must be at least 8 characters long.
- Should include at least one uppercase letter (A–Z).
- Should include at least one lowercase letter (a–z).
- Should include at least one numeric digit (0–9).
- Should include at least one special character (e.g., `@`, `#`, `$`, `%`).