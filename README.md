The application is a starship sales site. We are wealthy spacefarers shopping
for a new ship. We want to search for starships, sort them by cost, and filter
them by cost (if we have a starship budget we don't want to look at ships above
it.)

If there are pilots associated with the starship, we want to get more
information about them as well, because we are concerned about previous owners.

INSTALLATION:
=============

Tested with

	Python 2.7.10 on Linux

Make sure that "swapi" (https://swapi-python.readthedocs.org/en/latest/readme.html#installation) is installed

	$ pip install swapi

Install Flask, A lightweight Python web framework (http://flask.pocoo.org/)

	$ pip install Flask

To run it, just type:

	$ ./starshipsales

and you can access it at port 5000

P.S: When you start the webapp, it might take some time to load the data, (to make the app work faster), so when you see the message "All data loaded... You can start using the webapp", then you can head to port 5000 to start using the application.
