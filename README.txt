BS3-JQ2-YAMM

-- About -- Lightbox and Bootstrap Mega-Menu for Bootstrap 3.3.1 & Jquery 2.1.1

Utilizes Bootstraps modal plugin to implement a lightbox gallery and Custom CSS to Display the Mega-Menu Dropsdowns - Lightbox forked from AshleyDW and Dropdown Mega-Menu forked from YAMM (Yet Another Mega Menu) Geedmo's - YAMM3

-- simple Install -- Unzip package in htdocs server folder(XAMPP)

or

create a simple HTTP-Server by running from the command line:

http-server: a command-line http server

http-server is a simple, zero-configuration command-line http server. It is powerful enough for production usage, but it's simple and hackable enough to be used for testing, local development, and learning.

Installing globally:

Installation via npm. If you don't have npm yet:

$ curl https://npmjs.org/install.sh | sh

Once you have npm:

$ npm install http-server -g

This will install http-server globally so that it may be run from the command line. Usage:

$ http-server [path] [options]

[path] defaults to ./public if the folder exists, and ./ otherwise. Installing as a node app

$ mkdir myapp $ cd myapp/ $ jitsu install http-server

If you do not have jitsu installed you can install it via npm install jitsu -g Usage Starting http-server locally

$ node bin/http-server

Now you can visit http://localhost:8080 to view your server Deploy http-server to nodejitsu

$ jitsu deploy

You will now be prompted for a subdomain to deploy your application on Available Options:

-p Port to use (defaults to 8080)

-a Address to use (defaults to 0.0.0.0)

-d Show directory listings (defaults to 'True')

-i Display autoIndex (defaults to 'True')

-e or --ext Default file extension if none supplied (defaults to 'html')

-s or --silent Suppress log messages from output

--cors Enable CORS via the Access-Control-Allow-Origin header

-o Open browser window after staring the server

-h or --help Print this list and exit.

-c Set cache time (in seconds) for cache-control max-age header, e.g. -c10 for 10 seconds (defaults to '3600'). To disable caching, use -c-1.