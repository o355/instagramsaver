# Instagram Saver
An upcoming project that will easily save all your Instagram posts. (coming late 2017, probably)

# Hopes for the project
I'm presently working on PyWeather, so I don't really have time to work at all on Instagram Saver. However, I do expect the program to work like such:

A user will enter their username (the account will have to be public, for now) into an .exe.

The program will begin to fetch user media from Instagram's API, and put all files into a /tmp folder.

Once all the images got fetched, using some zipping library or program (7-zip?), things will get zipped, and the file moved out of the /tmp directory. 

And that'll be it.

A command line option will be available for users to define a custom API key. Maybe, just MAYBE a GUI will get included.

# "ETA"?
Early 2018. It really depends on how hard Instagram's API is. Actually coding in support for saving photos, fetching the API is stuff I know thanks to PyWeather. I'm good with the GUI (it'd be appJar, please sue me), and coding in a simple GUI is uh, simple. Otherwise, I don't know Instagram's API, zipping files (using 7-zip), copying files, and deleting them at the end (add the filenames to an array?).

# The backstory
I actually wanted to make sure I could save my Instagram posts for no good reason. Being that the only non-shady service didn't work, I thought: "Hold up, I know something about APIs and Python. I'll make one on my own!".

And this project that won't become 100% active until late 2017 was born!
