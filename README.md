# CS360
A repository of work for my CS360 SNHU course

* Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

  This app was designed to help track inventory, specifically for smaller businesses who need help tracking inventory among multiple people but that cannot afford to purchase a full inventory tracking system. 
* What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

  The screens necessary for the user needs were a login screen with the capability to allow users to log in and also to register as a new user if they have not done so already. There needed to be a settings screen to allow the app to send SMS messages for lock stock alerts. Then a main page with the inventory list which showed all items in inventory, the amount on hand, and the ability to delete or add items to the database. There also needed to be a screen to edit existing items in the database to be able to track how many of a thing were in stock.
* How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

  I, unfortunately, put the functionality of the code behind the visuals, which ended up causing nothing but headaches. I spent so long focusing on what I wanted it to look like, that the functionality couldn't keep up with what I needed it to be able to do. In the future, I will absolutely focus first on the functionality, putting the visuals on the back burner. Keeping with object oriented programming is absolutely the way to go, however.
* How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

  As I added each new screen in the app, I would run it on an emulated device and manually test each function to ensure it worked. I also made use of the Android studio's built in Log Cat function to make sure it would work as well.
* Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

  One place I really needed some innovation with was the xml design with constraint layout. I would create a TextView, set the width to Wrap_content, and set the layout constraints to start at the start of parent and end at the end of parent, then get annoyed that the TextView actually butted up against the edges of the screen. So I would put in a line to add horizontal margins to the layout, but the margins wouldn't actually appear on the screen, so the textview stayed up against the edges. So I had to change the width from wrap content to a hard coded width size, which worked for the project, but would obviously create issues in actual deployment as it would not work as intended on different sized phones.
* In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

  One part of the app I feel I was particularly sucessful with was setting up the login. It linked to a login database with a table for usernames and associated passwords. I made it so the buttons to login or add user couldn't be used until a password was entered, the username and password couldn't be null, and had toast pop-ups informing the user if a user with that username couldn't be found, if the password didn't match, if the username DID already exist when trying to add a new user, and if the login was successful. I feel pretty proud of that part.
