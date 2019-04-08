# SoftwareEngineeringProject
The Project for CT216


## How to use the app
  Register an account and you will be redirected to a page with the following options available:  
      - Video chat  
      - Text chat  
      - File Transfer  
      - Join room  
      
File transfer and Join room are incomplete functionalities. After selecting either video or text chat
a unique room will be created for you to which you will be redirected. You can copy-paste the link in a new tab or another client
in order to test it out. 

Preferably use google chrome as it is the browser that this app was intensively tested with (note: works on android phones)

### Registration
Tests are carried out in order to check if user inputs meet validation requirements however the responses with flash messages
are not implemented and so invalid input will still create an account. In the code, all the tests are displayed and were planned
to be used with .hbs and flash-messages

### Signing Out
Once you log in, your session will be saved such that you do not need to login again. In the case where you need to logout, in the
rooms page ('/users') you will find a settings icon to the top right, once cicked a menu will appear with the first three options
being unstable but at the end there is the Sign out button that you can click to sign out. 
