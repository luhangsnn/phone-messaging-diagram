## Use Case Scenarios

### Accessing an account
1. The user enters the extension 
      * a. If the extension is not 8888, and it is an existing extension, the phone asks the user to leave a message by pressing 1 or # to access the account.
      * b. If this is not a valid extension, ask the user to enter the extension again 
      * c. The user selects the option “access an account” by pressing  #
      * d. The user is asked for a password 
2. If the extension is 8888, the user is prompted to enter the password
3. The user enters the password
4. The security system checks if the extension and the password is a correct combination
5. If the combination is not correct, return a message “The password/the ext is not correct”  and ask the user to reenter 
6. Otherwise, prompt the user to select from 3 options:
      - Press 1 to retrieve messages, press 2 to change greeting, and 3 change your password

### Retrieving a message
1. After accessing the user’s account (A), press 1 to retrieve the messages
2. The first message is displayed on the phone 
3. The user has to select from 3 options:
      * a.Press 1 to play the current message
      * b. Press 2 to delete the current message
      * c. Press 3 to skip the current message
4. After the selection, an acknowledgement of the action is given. 
5. The next message is played and the user is given the option again and repeat 2) until all the new messages are played. 
6. After all new messages are played, the saved messages will be played per user’s selection repeated from 2)

### Deleting a message
1. After entering the correct password (A), the user is prompted with an options menu.
2. The user presses 1 to retrieve messages.
3. The user presses 1 to play the current message.
4. The system processes the selection and the next message is played.
      * a. If the user  presses 2 to delete the current message, an acknowledgement is given and the next message is played. 
      * b. If there are no messages left, the user options menu is restated.

### Leaving a message
1. The user enters an extension 
2. If the extension is the phone’s extension, return a message “You can’t leave a message to yourself”.
3. If not, checks if the extension is valid/activie. 
4. the phone asks the user to leave a message by talking. 
5. The user either hangs the phone, or a timeout in number of second.
