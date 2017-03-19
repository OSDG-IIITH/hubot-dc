# Hubot DC Adapter (Not Really)

## Description

This is a DC "Adapter". While in reality, it implements most of the client protocols to make things work. It is called "Adapter" because hubot calls it that.

## Configuring the Adapter

The IRC adapter requires only the following environment variables.

* `HUBOT_DC_SERVER`
* `HUBOT_DC_NICK`

And the following are optional.

* ``

### DC Server

This is the full hostname or IP address of the DC server you want your hubot to connect to. Make a note of it.

### IRC Nick

This is the optional nick you want your hubot to join with. If omitted it will
default to the name of your hubot.

## Contribute

Here's the most direct way to get your work merged into the project.

1. Fork the project
2. Clone down your fork
3. Create a feature branch
4. Hack away and add tests, not necessarily in that order
5. Make sure everything still passes by running tests
6. If necessary, rebase your commits into logical chunks without errors
7. Push the branch up to your fork
8. Send a pull request for your branch

## Credits

Shamelessly copied from [hubot-irc](https://github.com/nandub/hubot-irc)
