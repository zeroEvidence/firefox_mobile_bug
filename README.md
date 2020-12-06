# Get started
## Using your own web server:
put the public directory on a local web server and follow the instructions bellow.

## Using the supplied web server:
Assuming you have node.js and npm installed, run the following commands inside this directory:
```bash
$ npm i
$ npm run start
```

## To view the bugs:
Go to the index.html page using Firefox on an Android mobile.
The two input fields represent a credit-card form, the top being cc-number and bottom being cc-expiry.
Type a 16 digit number, it will auto focus the cc-expiry when you reach 16 digits, (it's important to let the code auto-focus onto expiry for you).
Go back to the cc-number and delete it using the delete button from the end to the start.
Type in another 16 digit number slowly using a diferent number each time so you can see where the digit is being placed.
Note when you get to "4012 3" the next digit will be placed at the second-last place. e.g. "4012 43" not "4012 34"
