# DE-Mon - Ekos Monitoring Tool for Astrophotography
DE-Mon is a simple service that can run on any Linux system using the astrophotography imaging suite Ekos, including [Astroberry](https://www.astroberry.io/) and StellarMate, enabling the user to remotely monitor via browser the session progress during the night.

You need to have a secure token that can be requested contacting me at [this email address](mailto:astropills.it@gmail.com).

I will create a new token for you that will allow you to have access to a simple dashboard hosted on my server, as soon as I have a better implementation of the server side it will be added to this repository so you can host it yourself elsewhere. :)

DE-Mon has also a very primitive web server that listens on your local address using the port 5000, however it's more for debugging and future development that for real monitoring from the browser.

If you just want an executable to run on your Linux distribution get the compiled package from [here](https://github.com/aktasway-it/de-mon/releases).

If you instead want to run it as a Python application on your Raspberry, just clone the repository wherever you like and run the script. You'll be notified if some dependencies are not met, but it should be enough to run the following commands:

`sudo apt update && sudo apt install python3-pyqt5`

`python3 -m pip install --upgrade pip`

`python3 -m pip install flask requests`

Once installed the dependencies you don't need to run this command ever again, obviously. :)

To launch the application either double click **demon** or from the terminal run:

`./demon`

It's still a very early version, so bugs might be behind the corner, be aware!

Clear skies!