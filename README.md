# Hubot

This is a version of GitHub's Campfire bot, hubot. He's pretty cool.

You'll probably never have to hack on this repo directly.  Instead this
repo provides a library that's distributed by npm that you simply
require in your project.

## Getting Your Own

Make sure you have [node.js](http://nodejs.org/) and [npm](http://npmjs.org/) installed.

Download the [latest version of hubot](https://github.com/github/hubot/downloads).

Then follow the instructions in the README in the `hubot` directory.

## Scripts

Hubot ships with a couple of default scripts, but there's a growing
number of extras in the [hubot-scripts](https://github.com/github/hubot-scripts)
repository. `hubot-scripts` is a way to share scripts with the entire
community.  Check out the [README](https://github.com/github/hubot-scripts#readme)
for more help on installing individual scripts.

## Local Testing

Install all of the required dependencies by running `npm install`.

It's easy to test scripts locally with an interactive shell:

    % bin/hubot

...and to run tests:

    % make test

## Twitter

Just set the following environment variable to make your twitter bot

process.env.HUBOT_TWITTER_KEY
process.env.HUBOT_TWITTER_SECRET
process.env.HUBOT_TWITTER_TOKEN
process.env.HUBOT_TWITTER_TOKEN_SECRET

If your bot is called hubotine , someone who tweets 'hubotine ping' or '@hubotine ping' with its @user account will received from your bot twitter account '@user PONG'
