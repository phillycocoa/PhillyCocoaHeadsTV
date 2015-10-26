# PhillyCocoaHeadsTV
An AppleTV app that lets you watch Philly CocoaHead presentations.

# Running the server-content locally

Since this is a TVML-style app it expect to get content from a web server. During development you'll want to run a simple web server locally and for that we recommend node. 

Once you have node and npm install (we recommend using homebrew for that), install the web server with:

`npm install http-server -g`

Then within the `server-content` directory run the server on port 9001

`http-server -p 9001`

If you don't want to install node you can use OS X's default python to run a web server (but in my experience it can be a little buggy).

`python -m SimpleHTTPServer 9001` 