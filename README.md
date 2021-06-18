# Celebrity-Match-Discord-Bot

The Celebrity Matcher Discord Bot is a bot that when called will take the users profile picture and return the top 5 closest matches to celebrities.

To activate the bot, the user types "$match" in the text channel.

Example shown here:

![Screenshot of the bot in action, my profile picture is Drake and the bot returns Drake as a match.](DrakeExample.jpg)


## Dependencies

The Bot is currently configured to run on a heroku instance using their free python dynamo with the following dependencies:

- discord
- mtcnn
- keras_applications
- keras_vggface
- tensorflow-cpu
- pillow
- opencv-python-headless
