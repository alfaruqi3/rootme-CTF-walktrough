# Javascript-Authentication
## what is javascript-auth
JavaScript Authentication is a login system where the username and password are checked by JavaScript code running in your browser instead of being verified by a server.
- You enter a username and password.
- JavaScript compares them with values stored in the webpage's code.
- If they match, you are logged in.
- If they don't, access is denied.
## Why is it insecure?
Because the JavaScript code is sent to your browser,<br>
anyone can inspect it (F12 → Sources/View Source) and potentially find the correct credentials or the validation logic.<br>
Example:<br>
<br>
```JavaScript
if(username == "admin" && password == "secret123"){
    alert("Access granted");
}
```
<br>

A user can inspect the page and see that the password is **secret123**.

## Challange Web 
<img width="999" height="358" alt="1" src="https://github.com/user-attachments/assets/a62cb02f-839f-4c0c-a0e3-15f5928820a2" /><br>

## So as usually just straight go into the inspect page then search the ".js" file for the credential informations 
<img width="1007" height="377" alt="2" src="https://github.com/user-attachments/assets/dd6658fb-4770-4a6a-b66e-26f36771cbce" /><br>

here we got the "**login.js**" file that is exist in the web,<br>
so we search them in browser just add "**/login.js**" at the end of the url :<br>
<img width="1005" height="360" alt="3" src="https://github.com/user-attachments/assets/32d4d65f-9129-488e-ba7c-b5c104cc1eee" /><br>

## We redirect to this page 
<img width="1002" height="343" alt="4" src="https://github.com/user-attachments/assets/436a4320-243e-49f0-8567-0de7836e09f3" /><br>
## Now you can see the username and the password, use it and u got the flag 

