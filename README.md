# slack-faker

Use this app to create fake Slack conversations for screenshot and pranking purposes. I TAKE NO RESPONSIBILITY FOR YOUR ACTIONS OR THEIR RESULTS - that's on you, bucko.

## Setup

To add a user, take a screenshot of their Slack profile picture, and put that file in `profile_pics/theirname.png` (we'll say the file is called `theirname.png`).

Open `config/users.json` and add a user to the "users" array, specifying their display name in `name` and the name of the profile picture you just added to `profile_picture` (e.g. `theirname.png`).

## Usage

Open `index.html` in a web browser, choose your `users.json` file in the file selector, and click "Load". The names and profile pictures of the users should appear.

To send a message, click the desired user, enter the message in the "Message" textbox, and enter the time in the "Time" textbox - to copy Slack's format, format time like this: `4:54 PM`. Click submit.

Continue sending messages between your users until you are satisfied.

Take a screenshot of the fake chat and send it to your friend.

Please don't get yourself fired. I am not responsible for the way you use this application nor the results of your use.

Have fun :)
