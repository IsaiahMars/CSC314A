Software Requirements:
    Python - https://www.python.org/downloads/

Module Requirements:
In Visual Studio Code, open a terminal with ctrl + `, and type "pip install MODULE_NAME_HERE" to install the following:
    flask
    flask-login
    flask-sqlalchemy
    sqlalchemy-utils
    sqlalchemy
    cryptography
    requests

You can run the website by running the 'main.py' file.

I'm not quite finished with the project so I didn't bother commenting on all of my JavaScript files, but here's a brief explanation of how the game works.

This game uses JavaScript, JQuery, SocketIO, Flask-SocketIO and an HTML canvas element. The canvas element can be used in an infinitely recursive loop to clear, draw, and update images on screen for every iteration of the loop. On-screen buttons and tracked client-side inputs are used to 'manipulate' a player's state throughout the game, as well as the player's environment. JQuery, SocketIO and Flask-SocketIO are used to send JSON objects containing player data to and from the client so that each user can have a somewhat unique experience within the game. This game is a scrupulous mix of object-oriented and procedural programming, and is comprised of over 1,800 lines of code. The concept of making games with HTML canvas elements is not my own, and a lot of the work I did for this project would not have been possible if not for a YouTube channel of the name 'Franks laboratory', whose tutorials I've been watching since the beginning of this year. A link to the game tutorial I watched before starting this project is provided below, as there are many noticeable similarities within integral parts our code.

'JavaScript 2D Game Tutorial', Franks laboratory:
https://youtu.be/eYTnoJluds0

All resources and images used in the website were paid for by me, or sourced from sites that make their artwork accessible to the public domain.


Resubmission Changes: 
-Added the instructions page.
-Modified crop grow time values.

When we switch our projects to use a PostgreSQL database, the game should be finished. I wasn't able to continue my work remotely over the break, but I'm pretty pleased with where I'm currently at in the development stage.