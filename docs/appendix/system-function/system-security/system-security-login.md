
# System.Security.login


## Description
Use this function to log in directly, avoiding the system's built-in login page.

## Grammar
System.Security.login(username: string, password: string): Promise<boolean>

Parameter

username

password

Return

Whether login succeeded.

## Code Example                                                                                                                                                                                                                                                                                                          
At the top of the page, there is a 'Switch User' button. Clicking the button opens the 'LoginPopup' popup. After the user enters their username and password and successfully login, the system automatically redirects to the project homepage.

Switch User Button Script

<img width="220" height="113" alt="image" src="https://github.com/user-attachments/assets/fd327a32-8ced-4020-b306-aa291112feca" />

```typescript 
const result = await System.UI.openPopup('LoginPopup');
if (result === 'GoHomePage') {
    System.UI.goHome();
}


```   
Login Button Script for the LoginPopup page

<img width="397" height="412" alt="image" src="https://github.com/user-attachments/assets/a982f9ac-1a41-4ed5-b74f-3a31690966b7" />

```typescript 
const usernameInput = await System.UI.findControl('UsernameInput');
const passwordInput = await System.UI.findControl('PasswordInput');
const succeeded = await System.Security.login(usernameInput.text, passwordInput.text);
if (succeeded) {
    System.UI.close('GoHomePage');
}


```   


