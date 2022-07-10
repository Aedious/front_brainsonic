This project is not yet finished
i've done this project in native js / nodejs with express
Modifications i would have done :
    - handles operations with double signs ex (15 +- 12)
    - link the backend with the frontend (cors error with localhost)
    - check is the last resut contains an cell with a '-' sign and concat this to make a negative number
    - handle possible overflow and float numbers
    - handle if we have multiples operations who are handle in the same function (12 * 15 * 16 * 48) it may cause issues due to the slice function in the for loop 
    - i woul've like to make a recursive function for the factorial in the backend section