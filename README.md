# ChatBoxPopup
This project - On a Home page " Send message  chat " pops up with a form to fill with phone number, name , email and a  short description of text message to be submitted. 
Also captured the success message that return after the form filled. Additionally back arrow button (<) and minimize(x) were also automated .
Process- when a object is not captured, look for the iframe object and also use "driver.switchTo().defaultContent();" for iframe handling and switchTo the driver to another frame.
After the driver is moved into new frame if the object is not found then the elements are in parent frame.

