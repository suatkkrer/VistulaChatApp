# VistulaChatApp
# ABSTRACT
The main objective of this thesis is to provide the description of an author's mobile application software together with necessary information about the technologies pertaining to it. The name of the application is "VISTULA CHAT APP." Its purpose is to help its users to communicate with the School students easily. In particular, the students can easily make new friends thanks to this application because everyone can reach each other without difficulty, and there is no need even to go personally to the School to make new friends. The application will show its users all the other users. After selecting any of our students who use the Vistula Chat app, one can send them a message request, and after they accept, one can start talking to each other instantly. After the chat screen appears, texts can easily be exchanged regardless of whether the user is online or not; the fact that the other user is offline does not change anything, the message is delivered automatically when the user is online. The technologies used are Java, Firebase (Database system), and Android Studio. The latter has been used because of the need to generate a working application that every student can download on their phones, and they can use the application quite easily.
# Application
# User Login Page

![1](https://user-images.githubusercontent.com/60031387/83143726-ac367000-a0f2-11ea-96ab-f4ff4b7696fb.png)

When the application is open, the user can see the login screen first. If the user already has an account, login is possible. In the opposite case, the user can click the "Create New Account” button, being redirected to “create a new account” page. If a valid e-mail address or password is not introduced, the user is warned by the system with a message like “Email cannot be empty" or "Password cannot be empty." Similar warnings will also be produced if the information entered does not match the database; namely, the user will receive a warning from the database server, and will not be able to log in. Additionally, if the user wants to log in with a phone, it is sufficient just to click the “Sign in with Phone” button.

# Sign Up Page

![2](https://user-images.githubusercontent.com/60031387/83143815-cf611f80-a0f2-11ea-82c2-f2ff2331ca44.png)

On this page, the user can register after entering email and password. The password must not be less than six digits. After clicking the "Sign up" button, the user will log in directly to his or her account. There is no need to re-enter email and password. If the account exists, one can click the "I have already account" TextView control and go to the login screen.

# Sign in with Phone Page

![3](https://user-images.githubusercontent.com/60031387/83143912-f28bcf00-a0f2-11ea-8ba9-4e3e2237fec3.png) ![4](https://user-images.githubusercontent.com/60031387/83143919-f586bf80-a0f2-11ea-82e7-d78167cf34f9.png)

On this page, one has to enter one’s phone number with the country code. If the database cannot find the number, it will give an “Invalid Phone Number. Please Enter Your Country Code” warning. If the phone number is correct, the user will see the text “Message is Sent," and an SMS will be sent. After clicking the “Send Verification Code” button, the field where the code is entered the code and a button to be pressed for confirmation, confirm is displayed. If the entered code is correct, the user is directed to the user settings page. However, the page described above cannot be obtained from the emulator. One has to have a phone with the Android operating system to use this page.

# User Settings Page

![5](https://user-images.githubusercontent.com/60031387/83144111-3979c480-a0f3-11ea-9d96-90034bb75b5a.png)

When the user enters his\her account for the first time with email registration or phone registration, the above screen will be displayed. The user can create a username and status on this screen. When the user clicks on the default profile picture, the app will allow to choose an image from the phone. If the user does not select the profile picture, the default profile photo will remain. After logging into an account, the user can add or change it in the settings section. The users will also be able to login to the main page after clicking the “Update” button.

# User Settings Page 2

![6](https://user-images.githubusercontent.com/60031387/83144259-6cbc5380-a0f3-11ea-8ed3-c9da1bc6298a.png)

After logging to the main page, the settings can be found on the top right. With this option, the user can find new friends, create a new group, go to the options section to update the profile, or log out of the account.

# Find Friends and Send Request Page

![7](https://user-images.githubusercontent.com/60031387/83144265-6ded8080-a0f3-11ea-8c0c-1fef879bbf4a.png) ![8](https://user-images.githubusercontent.com/60031387/83144266-6e861700-a0f3-11ea-9325-494272577677.png)

On this page, the username, status, and profile pictures of existing users are displayed. When the user's profile is clicked on the user profile, the user will go to a page where he\she can send a message request to the user. Also, a message request can be canceled before the user to whom sent that message request has been sent, can see it.

# Friends and Requests Page

![9](https://user-images.githubusercontent.com/60031387/83144267-6e861700-a0f3-11ea-8e00-94e7f72e6fc5.png) ![10](https://user-images.githubusercontent.com/60031387/83144268-6f1ead80-a0f3-11ea-8127-be92ccf1499a.png)

When a user sends a message request to us, or when we send a message request to another user, this request appears in the section of requests. If we want to send a message to that user, we can accept this request, or we can reject the user’s request. If we agree, we can see the user on the Friends tab.

# Group Page

![11](https://user-images.githubusercontent.com/60031387/83144272-6f1ead80-a0f3-11ea-9623-fae48a12f381.png) ![12](https://user-images.githubusercontent.com/60031387/83144273-6fb74400-a0f3-11ea-8fb5-4fbe948458cf.png)

We can create a group by clicking on the options at the top right; the group we created will appear in this tab. After entering the group, we have created, we can write a message here, and other users can see it. But the author couldn't complete creating a group part; when the group is created, all users in the database are included in this group.

# Chat Page

![13](https://user-images.githubusercontent.com/60031387/83144275-6fb74400-a0f3-11ea-8a9b-5112eeb7cc01.png) ![14](https://user-images.githubusercontent.com/60031387/83144277-704fda80-a0f3-11ea-8c6c-de9e8849dc09.png)

Finally, the users who accept the message requests can start chatting to each other. In addition, the user who sends the message is in green and on the right, and the message sent by the other user is in white and on the left.
