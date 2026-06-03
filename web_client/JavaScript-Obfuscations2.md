# JavaScript-Obfuscation 2 
Statement :<br>
**Going Down 3 floors...**

## Solusion
So here is the second Obfusction challange, we got a clue from the "going down 3 floors " statment<br>
obfusction is a way to make the password difficult to read in javascript,<br>
So "going down 3 floors" could be means that the password processed 3 times using obfuscation <br>

## As always just go to the source of the web
<img width="1002" height="426" alt="Obs1" src="https://github.com/user-attachments/assets/b7d0ae2c-e8e2-471f-855a-5554e325ad22" /><br>
that the password !!!

# Using the same technique as before, using online Urldecoder
```bash
https://www.urldecoder.org/
```
use the inner "()" to decode <br>
<img width="1002" height="710" alt="Obs2" src="https://github.com/user-attachments/assets/6316b70c-e4d5-435e-977a-7bbbe7fb4a87" /><br>
Then we got the second obfuscation, just do it reapetly until you got 
``` bash
String.fromCharCode(104,68,117,102,106,100,107,105,49,53,54)
```
This is an javascript charcode, you can use the console from the web inspect, write it down and run 
## Thats it you got the Flag!!!

