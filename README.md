# Cyber-Security
Codepath cyber security course

# Walkthrough
The first exploit I found was with XSS in creating posts. You simply create a new post and write javascript in the text field.
![](https://raw.githubusercontent.com/Holocraft/Cyber-Security/master/XSS.gif)

The next exploit was with XSS via DOM manipulation via the twenty fifteen theme. There is a vulnerability with the genericons which was using outdated jQuery code so you just have to use that to put a code snippet into the URL.
![](https://raw.githubusercontent.com/Holocraft/Cyber-Security/master/XSS2.gif)

The final exploit is simple user enumeration. You can guess usernames while trying to log in and the error messages will supply information on whether the user exists or not. You can then move on to guessing the password once you've found a valid user.
![](https://raw.githubusercontent.com/Holocraft/Cyber-Security/master/Enumeration.gif)
