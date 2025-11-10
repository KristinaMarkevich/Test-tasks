<a href="https://docs.google.com/spreadsheets/d/1cnhNEgGn-4fhCDv6k20MxPACdwyw-9uYmTjycEXIFlY/edit?usp=sharing">Link</a> to google sheet 


| Info| | 
|-----------|-------|
| Product      | https://context.reverso.net  | 
| Data      | 03/10/2025  | 
| Build      | 1.0   |
| Tester    | Markevich Kristina   | 
| Environment	    | Windows 11 Pro, Google Chrome Ver: 140.0.7339.208   | 

**CHECK LIST FOR REGISTRATION PAGE**

**Submodule - Registration via email**

1. Email
```
valid email 

only letters > error message

email without @ > error message

only numbers > error message

only .com > error message

email without .com > error message

not latin letters > error message

empty value > error message

input only special characters > error message

email already exists > error message
```

2.Password 

(8-100 symbols,
Passwords must have at least one lowercase letter ('a'-'z').

Passwords must have at least one uppercase letter ('A'-'Z')

Passwords must have at least one digit ('0'-'9').
```
enter valid password (8-100 symbols with lowercase and uppercase letters and min 1 digit)

enter valid password 7 symbols > error message

enter valid password 9 symbols

enter valid password 99 symbols

enter valid password 100 symbols

enter valid password 101 symbols > error message

enter password 8-100 symbols only with lowercase letters > error message

enter password 8-100 symbols with lowercase letter and 1 digit > error message

enter password 8-100 symbols only with uppercase letters > error message

enter password 8-100 symbols with uppercase letter and 1 digit > error message

enter password 8-100 symbols with lowercase and uppercase  letter > error message

enter password 8-100 symbols using only digits > error message

only uppercase letters > error message

only lowercase letters > error message

only digits > error message

only special characters > error message

empty value > error message

enter not latin letters using lower and uppercase letters and min 1 digit > error message
```

3. Confirm password
```
enter the same password like in "password" field 

enter different password then in "password" field > error message
```

**Submodule - Registration via social media**

1. Registration via Google account
```
with valid number 

with valid email

with non-existing number > error message

with non-existing email > error message
```
2. Registration via Facebook account
```
with valid number 

with valid email

with non-existing number

with non-existing email > error message
```
3. Registration via Apple account
```
with valid number 

with valid email

with non-existing number > error message

with non-existing email > error message
```
**Submodule - Policy**

1. Terms of use
```
the hyperlink is clickable 

the hyperlink leads to the page "Terms, Collaborative Dictionary"
```
**Submodule - Additional**

1. Notifications consent
```
the checkbox is clickable
```
2. Hyperlink "Login here"
```
hyperlink "Login here" leads to "Log In" page
```



**TEST CASE EXAMPLE FOR REGISTRATION PAGE**

**ID** - 1

**Summary**  

                 Registration via email by non-existing user 

**Pre-conditions**

                 1. The email is created

                 2. The user is not registered

**Test data**   

                email: ff@bk.com

                password: Register12
  `<p align="center"><strong>Steps to reproduce and   Expected results</strong></p>

      1. Open the site https://context.reverso.net/                                The site is opened

      2. Click the button "Log in"                                                 "Log in" menu is displayed
                     
      3. Choose the option "Register"                                              Registration page is opened
                     
      4. Enter email from test data in the "Email" field                           Email is displayed in the "Email" field
                     
      5. Enter valid password from test data in the "Password" field               Password is displayed in the "Password " field
                      
      6. Enter same password in the "Confirm Password" field                       Password is displayed in the "Confirm Password" field
                     
      7. Click "Sign Un" button                                                    Verification page is displayed
                     
      8. Check the inbox                                                           Verification letter is received 
                      
      9. Open verification letter > Click the verification button                  Verification button is active 
                                                                                   > User account is opened in the other tab
                     



