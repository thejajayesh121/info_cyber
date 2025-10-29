# Fundamental of computer security
## Identification,Authentication, and Authorization
|Concept       |Description          |Example                       |
|--------------|---------------------|------------------------------|
|**Identication**|Claiming an identity|Typing username              |
|**Authentication**|Proving identity|Entering password/fingerprint  |
|**Authorization**|Granting access  |Accessing certain files after login|
## key principle:
"Authentication verifies who you are. Authorization decides whta you can do."

# Authentication Methods
- Knowledge-based: Passwords,PINs
- Posssession-based: Smart cards,OTP tokens
- inherence-based:Biometrics (fingerprint,faceID)
- Multifactor Authentication (MFA): Combination of 2 or more above
- single sign-on (SSO): one-time login across multiple systems (e.g., Google or Microsoft SSO)
#Authorization Models
-DAC (Discreationary access control): Owner decides who can access(window permissions)>
-MAC(Mandatory access control):Access based on classification levels(Military systems).
-RBAC(Role-based access control):permission asigned to roles (Admin,manager,user).
-ABAC(Attribute-Based Access control):Access based on conditions(time,location,user type).
## Example:
An "HR Manager" role can veiw employee data,while "Employee" role can only veiw theirown profile.
# Best practices
- Use strong, Unique  passwords
- Apply MFA whenever possible.
- Review role-based permissions regularly.
- Log all Authentication and access event


![download](https://github.com/user-attachments/assets/6f584139-2989-4695-bbde-63a5cd2f4ac2)
