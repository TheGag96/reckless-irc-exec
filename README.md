# Reckless IRC Exec

## Intro

This guy is meant to let you run short snippets of code (ruby and javascript
best supported) in irc chat.

## Running

Copy config.example.js to config.js, create a branch in which you add that file
to your git, push that sucker to heroku.
e.g., after setting up the heroku remote in this repo, you could do the following:
```
git checkout -b exec
cp config.example.js config.js; vim config.js
git push heroku exec:master
```
