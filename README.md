# ChatBot-on-Whatsapp-using-Tasker
A chat bot to entertain your friends on WHATSAPP when you are offline....
Tools needed :
1. ROOTED ANDROID DEVICE !!
2. Tasker (android app)
3. WhatsTasker (A tasker plugin app) (this app is going to need the root access)
4. Account on Bot-Libre website.. (for application ID)

NOW !!

what you all need to do is...
1. Import the ChatBot.prf.xml file in Tasker by long pressing Profile tab in that Tasker app...
2. After importing this check whether the "OnWhatsApp" task is automatically created or not...
3. If not created import OnWhatsApp.tsk.xml, otherwise leave this file...
4. Now Import the most important file that is Chat_Bot.tsk.xml.

Now your chatbot is made but still not ready to chat with your friends...

So now go to VARS(variables) tab in the Tasker app, you will see four different variables with null value in them, they are,
1.%AppID
2.%Bot
3.%ConvID
4.%IDignore

So now what these variables are suppose to ??

1.%AppID - this variable is the application ID, for which you have made a Bot-Libre account, you will see this in the User-Details of            your Bot-Libre account. (this is your personal key dont share it with anyone)
  
2.%Bot- this variable is the bot with which you want to chat with, The Bot-Libre website provides the API for many bots they have, so         they have given each bot a different Bot ID. This you will find in the Respective Bot's description. If you didnt understood          anything about this %Bot then simply assign it the value "165" or "160" 165 corresponds to Einstein Bot and 165 correspond to         Brain Bot.
