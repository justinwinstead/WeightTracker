# WeightTracker

•	Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The WeightTracker application was designed to allow users to store their daily weight measurements and track their progress towards their fitness goals. I utilized three SQLite tables to store the weights, goals, and user accounts for my users. 

•	What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

I used three screens to meet my user’s needs. The first, the login screen, allows the user to enter their username and password to login to their user account. In addition, they can use the create account button to create an account if they need to. The next screen, the main screen, shows the user’s weight inputs in reverse chronological order. Alongside this, it shows the user’s goal weight and provides buttons to create, edit, and delete weight inputs and goals. The last screen, the input screen, allows the user to create and edit weights and goals. Some of the design aspects that I included to create a more user-friendly design were the floating action button to add weights and the calendar dialog for users to select a date for their weight input.

•	How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

I approached the process of coding my app by first structuring my files with classes and method stubs. Then, I start coding each method and utilize testing strategies to ensure that each method works as intended. After all the methods are coded, I test each method again to make sure that any future code did not create any bugs in previous code. I can use this with white-box and black-box testing techniques in future projects to prevent bugs and mitigate user risk.

•	How did you test to ensure your code was functional? Why is this process important and what did it reveal?

I stress tested my system with a range of different inputs to ensure that my app was not prone to crashing when faced with malformed inputs. This process is vital as a lack of testing can lead to app crashes and possible user data breaches. I found quite a few bugs that needed to be addressed with this approach.

•	Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

I had to innovate in my input activity to ensure that each way a user could interact with their data was implemented properly. I used a switch case statement alongside an intent extra to implement different functionality depending on the way that the user accessed the activity. This allowed me to use one activity to serve a variety of user needs.

•	In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I felt that my login activity demonstrated my understanding of the requirements and knowledge of more advanced Android coding concepts. I utilized robust input verification to ensure that users were creating unique accounts that were not easily abused. 
