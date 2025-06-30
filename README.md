# CS-360-Portfolio

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The app i developed wad a weight tracking app. The user can add a goal weight and log their current weights each day. When the daily logged weight reached the goal weight the app would notify the user through push and SMS notifications. 

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The first screen was a login/create account screen for secure and personalized weight tracking. The main activity displayed the current daily weight log and the goal weight. The add weight screen let users add new weight and featured an add and cancel button.
Set goal weight scrren was very similar to the add weight screen. Also this included SMS permission requests to send alerts when the goals were reached. I utilized a clear layout using linear layout and constraint layout. Big buttons were implemented for spacing and easy interaction. Text prompts were used to guide the user through hints or status updates. 

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
My coding approach used a modular structure, intent-based navigation, listeners and lambdas, as well as permission checks.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
Testing included manual testing through the android emulator. Logcat for debugging, trigger based tests such as goal weight testing checks, and UI testing to verify buttons and data flow. 

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
A key challenge was enabling goal weight tracking and triggering notifications. This required me to create and join multiple database tables. Handling Android 13+ permission flows for notifications. Testing SMS on emulators without real phone numbers. Innovative solutions included using notification channels, fake numbers, and intent-based UI refreshes to simulate realistic user behavior

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The most successful component was the goal weight tracking with notification and SMS integration. It demonstrated effective use of SQLite for user-specific data and Android’s notification APIs. Also, it showed permission request flows and real-world application of user feedback and progress alerts.
