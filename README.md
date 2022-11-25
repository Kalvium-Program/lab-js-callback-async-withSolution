![Logo-nav](https://s3.ap-south-1.amazonaws.com/kalvi-education.github.io/front-end-web-development/Kalvium-Logo.png)

## How to approach this lab:

This lab targets the idea of callback functions. This lab should be completed step by step - following all the instruction given below.
You need to solve this lab in the order given below:

1. withoutCallback.js
2. callback.js

**NOTE:** There is only one **_html_** file, in this lab. So, you need to change the **_index.html_**, in **_index.html_** file, in order to run a particular js file.
For eg:
If I want to run callback.js file, then change the **_src="withoutCallback.js"_** to **_src="callback.js"_** .

If you are stuck, go to **_help.md_** file and seek out the hints given.

## Starter Code:

Each javascript file, consists of two variables:

1. cookies - it is a list of objects, consisting of name of couple of cookies.
2. newCookie - it stores the name of a new cookie.

## Instruction to withoutCallback.js :

### Progression 1:

create a function to get all the cookies from **cookies** list.
**Note:** Make sure your naming pattern is describing what you are doing from the above function.

### Progression 2:

inside the above function - use in built js function **_setTimeout()_** function, and inside this function -> print all the cookies on your browser. --> keep the time to be = 1000.

### Progression 3:

create another function to create a cookie. In this function too -> use **_setTimeout()_** function and inside this function -> push **newcookie**, to your **cookies** list. keeping the time to be 2000.

### Progression 4:

call both functions.
check whether the third cookie, you added is being printed or not.

## Instruction to callback.js :

### Progression 5:

copy the entire code from **withoutCallback.js**, and add a callback function as an argument to your create cookie function and call the callback function just after you push the new cookie to your cookies list.
just call the function which creates the cookie for you and pass the function. which gets all the cookies.
check whether - now the third cookie is being printed on your browser or not.

Happy Coding Kalvium❤️
