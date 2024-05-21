# PASSWORD
The main issue while using the Oracle XE DATABASE 11.2 faced by me was to create a new user for login and also to reset your password.

# Create a NEW USER LOGIN (Using CMD)
To create a new user (login) and set a password in Oracle Database XE 11.2 using the command line, follow the steps:

1. **Open Command Prompt(cmd)**
   - Press '**Windows**+**R**',type '**cmd**',press '**Enter**'.
     
2. **Set the ORACLE_SID environment variable**:
   - Ensure that the ORACLE_SID is set to your database's SID. For Oracle XE, it's usually '**XE**'.
      - set ORACLE_SID=XE

3. **Log in to SQL*Plus as a privileged user (e.g., SYSDBA):**
   - Start SQL*Plus and connect as SYSDBA.
      - sqlplus / as sysdba

4. **Create a new user and assign a password:**
   - Once logged in, create the new user and set the password.
     - CREATE USER new_user IDENTIFIED BY new_password;
     - Type your new username and password that you want to create and use for login oracle
 
