# Alexa-using-Python
Alexa has only 2 tasks to perform:

1. Listen

Alexa will pay attention to your order, as: “Hello Alexa, play music,” “Hello Alexa, what’s the time?”

Alexa will pay attention to your order, get it, and afterward do some activity as indicated by your order.

2. Speaking

At the point when Alexa will comprehend your order after paying attention to it, it will play out some activity on it.

Now let’s Implement Those Two Features:

To implement these two features, we will require two Python modules:

1. SpeechRecognition

2. Python Text-To-Speech (pyttsx3)

1. SpeechRecognition

This Python module performs speech recognition. It helps Alexa to listen what we are saying, catch that, and act accordingly.

Use the command below to install SpeechRecognition module, from your terminal:
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*4wp17O36fTlphSWLIVPPpA.png"/></p>

Once installed and imported, we can use it in our task.

2. Python Text-To-Speech (pyttsx3)

Text-to-Speech (TTS) module for Python works without internet or any delay.

First you’ll have to install it:
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*X03ut_qK6Gkyy9DMzwOPhw.png"/></p>

Our Alexa can finally speak with the help of this module.

Starting the Fun Part

We’ll create three different functions and each will be responsible for a single task.

Step #1. Importing modules

Let’s first import the modules:
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*fY_pkGhPlxOYr7RDG7gomA.png"/></p>

Step #2. Initializing of modules

To use them lets initialize them and make their objects:
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*vKEnGf7_GMbUaph-oQAcTQ.png"/></p>

Step #3. Create a method to convert text to speech — talk() method.
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*Hq8Eyk6f-9jevevY0tHiKw.png"/></p>

Step #4. Create a method for Speech Recognition
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:1100/format:webp/1*NCRmZMrnPZYxbeu4vvrn9w.png"/></p>

Step #5. Creating a method for response
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:786/format:webp/1*3SV6hAblRaqsRGsjCu58OA.png"/></p>

Here, we need to understand a few things:

i. Fetching required part: Suppose you want to hear a specific song or music. You’ll speak to Alexa this way: Play music_name. Using this command, we will just remove the word ‘play’ and get only the ‘music_name’ part:
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:592/format:webp/1*JxO2XGNst3EpP5tu6jer-w.png"/></p>

And, then we will store that music name (without ‘Play’) in variable song.

ii) pywhatkit.playonyt(): To use this module we have to install this module first and then import it. PyWhatKit has features to help us in automation. This module has a playonyt() method which we will use to play the required songs directly on YouTube.

First we’ll have to install it:
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*1dJpMxJyAmJhFh5Ht-GTKQ.png"/></p>

And then import it.

iii. datetime.datetime.now(): To use datetime Module first we have to install it and then import it. This module helps us to manipulate dates and times. The method now() returns the current time, datetime module is built-in Python module.

Import it this way:
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:272/format:webp/1*bhoGW-Rf23petW7Vi6u3Gg.pngg"/></p>

iv. wikipedia.summary(): First we will need to install and import the Wikipedia module. This Python library makes it easy to access data from Wikipedia. The summary() method gets the data from the summary section of the Wikipedia.

As we know it’s a third party module, then, we’ll have to install it first:
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*NM6-aY_dcYdQ4hN117NgbQ.png"/></p>

And then import it in our code.

v. pyjokes.get_joke(): First of all we have to install and import pyjokes module in order to use it in our program. This module will generate some funny jokes randomly which our Alexa will crack.

This is also a third-party module so first, we will have to install pyjokes.
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:786/format:webp/1*L5pYFtoLVIYTHkEZUa62yQ.png"/></p>

And then import it and use it.
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:828/format:webp/1*uIhq2jMRxwRzSwdwXQ3C7g.png"/></p>

Step #6. Let’s run our Alexa
<p align="center"><img src="https://miro.medium.com/v2/resize:fit:614/format:webp/1*98BehAB5YXuCT8aWAvsszA.png"/></p>

Finally, we make the call to the run_alexa() method.

Yayyyyyy! we have created our own Alexa.

Using some Python skills and with the help of some other modules you can add more features to Alexa.

Enjoy your Alexa :)
