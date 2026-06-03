# JavaScript-Obfuscation
## What is Obfuscation
JavaScript obfuscation is the process of making JavaScript code difficult for humans to read and understand while keeping it working normally.<br>
Example:<br>

Normal code:
```JavaScript
alert("Hello");
```
Obfuscated code:<br>
```JavaScript
eval(String.fromCharCode(97,108,101,114,116,40,34,72,101,108,108,111,34,41));
```
## Why it is used:
- Protect code from being easily copied
- Hide how the code works
- Make reverse engineering harder

## So here we go
We got alert pop-up who ask the password, just use "Curl" command to get the source page of the web and search for the password <br>
```bash
Curl -i <url>
```
## The result 
<img width="997" height="526" alt="1" src="https://github.com/user-attachments/assets/287e2784-00ce-4516-bd24-65925924bf21" /><br>
The password here is an URL encode, we can't use it yet<br>
so decode it using an UrlDecoder : <br>
```bash
https://www.urldecoder.org/
```
## The result 
<img width="999" height="685" alt="2" src="https://github.com/user-attachments/assets/1786a7e7-b0a5-44b1-a687-322660092670" />
<br>
## See you got the password, use it and you will get the Flag!!!
