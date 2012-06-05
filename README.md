# Balloons.IO

Balloons.IO is a web multi-room chat server and client ready to use.
It’s build with the help of node.JS, Express, Socket.IO and Redis. [Follow us on twitter][]

  [Follow us on twitter]: http://twitter.com/gravityonmars

![image][]

  [image]: http://gravityonmars.com/wp-content/themes/gom3/images/projects/balloons-io/app-1.png

## Installation

The installation of certain tools can be a bit annoying, but these then
become inseparable friends to all developer. We will not explain how
to install each and every one of these tools, especially because their
sites do much better than what we could do ourselves:

### Requirements

-   [node.JS]: http://nodejs.org
-		[Redis-server]: http://redis.io

If you have these 2 tools installed, go to terminal and type:

`npm install`

Balloons uses easy-OAuth for authentication with Twitter. You can easily
change this code to authenticate with Facebook.

To connect Balloons with Twitter follow these steps:

Log in with your account https://dev.twitter.com/. 
Create a new application (https://dev.twitter.com/apps/new) and then copy 
the keys that twitter gives you in the file config.sample.json
Rename config.sample.json to config.json

Run `node balloons`
Point your browser to `http://127.0.0.1:3000`

Enjoy!
