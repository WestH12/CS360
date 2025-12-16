# CS360

# Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The application was designed to meet the user's need to manage their inventory under a secure login process while dynamically altering the items.
Additionally, users can request to be notified by SMS when items drop to a low quantity. 

# What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
There are three screens required to support the full functionality of the application: login, inventory, and settings screens. 
For the login screen, the feature of verifying login credentials and allowing for the creation of new login credentials was implemented.
For the inventory screen, the features of adding, incrementing, decrementing, and removing items were implemented.
For the settings screen, the feature of toggling and asking permission to send SMS notifications was implemented. 
Overall, all screens followed a simple top-down approach as the processes and features the user would engage in would logically flow downward on the screen.

# How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
My approach to coding my application abided by the simple loop of: reading documentation/requirements, hands-on development and issue resolution, and then using outside resources like documentation for issue resolution.
This strategy could be applied to almost anything, including future development projects, as it emphasizes hands-on application, development, and problem-solving before reaching out to outside resources. 

# How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
The testing of my code was entirely through hands-on navigation and engagement with the features to ensure that the relevant processes and actions were occurring.
Additionally, the use of LogCat was immensely helpful as it allowed me to see the potential flaws within my logic and identify the exact problem occurring. 
For example, when testing the incrementation/decrementation of the items, I found that modifying the second item would apply those changes to the first item.
From here, I identified a discrepancy between the indices of the code and the databas,e allowing for a quick resolution. 
