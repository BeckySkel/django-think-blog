To downgrade to Heroku 20:

Login to Heroku with this command:

Heroku login -i

Then:

heroku stack:set heroku-20 -a <app name>

Replace <app name> with your app name for Heroku.

Then create that runtime.txt file in the root of your project containing:

python-3.8.14