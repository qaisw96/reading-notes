# Heroku 

## Prepare the app
To clone a local version of the sample application that you can then deploy to Heroku, execute the following commands in your local command shell or terminal:

```
git clone https://github.com/heroku/node-js-getting-started.git
cd node-js-getting-started
```

## Create an app on Heroku, which prepares Heroku to receive your source code.

```
heroku create
Creating sharp-rain-871... done, stack is heroku-18
http://sharp-rain-871.herokuapp.com/ | https://git.heroku.com/sharp-rain-871.git
Git remote heroku added
When you create an app, a git remote (called heroku) is also created and associated with your local git repository.

Heroku generates a random name (in this case sharp-rain-871) for your app, or you can pass a parameter to specify your own app name.

```

## View logs
Heroku treats logs as streams of time-ordered events aggregated from the output streams of all your app and Heroku components, providing a single channel for all of the events.

View information about your running app using one of the logging commands, heroku logs --tail:
```
heroku logs --tail
2011-03-10T10:22:30-08:00 heroku[web.1]: State changed from created to starting
2011-03-10T10:22:32-08:00 heroku[web.1]: Running process with command: `npm start`
2011-03-10T10:22:33-08:00 heroku[web.1]: Listening on 18320
2011-03-10T10:22:34-08:00 heroku[web.1]: State changed from starting to up

```
