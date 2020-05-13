# Form-Validation
Form validation must be kept to validate the entry of the user.

Form validation occurs after the client had entered all the necessary data and then pressed the Submit button. If the Data entered by the client is missing or incorrect then this script should request the client to resubmit the form with correct information. Entire process happens at the client side only before sending to the the sever end.


In the script given, we are calling regvalidateform() to validate the data when onsubmit event is occuring.

/^[A-Za-z_0-9]{3,}@[A-Za-z]{3,}[.]{1}[A-Za-z]{2,6}$/

This can be explained as email should contain character  A-Z/a-z or numeric 0-9.
Must contain '@' and a '.'






