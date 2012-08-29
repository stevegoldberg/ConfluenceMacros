The Last Login Group macro produces a table of all users within a specified group with the following columns:
 - Full name;
 - Email address;
 - Date and time of their last successful login.

This is useful if you want to check on whether a particular group are making use of their logins (for example, prospective clients). 

SECURITY WARNING:
As this could potentially reveal sensitive information, implementation should be carefully thought out beforehand. There is a 'show-if' conditional included which will only show the output to a specified group (this can be modified to a 'hide-if' if required). You will need to ensure that you have the 'show-if' macro available on your Confluence instance. You should also change the specified group 'venda' to the user group on your own instance that you want to display the information to.

If you do not want to reveal the email address (or any other column) to the user, you can delete or comment out the relevant column without incident. It may also be possible to add conditionals around these columns as well.