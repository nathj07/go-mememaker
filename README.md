# go-mememaker

The purpose of this repo is as a tutorial. Using the api.imgflip.com service we will build a simple API client.

## In place

Already in place for you are:
1. flags, the basic flags are defined and validate
2. data structures, structs with tags for the response from the api
3. a simple GET request

## TODO
The next tasks are:
1. Define the POST request, this uses URL values
2. Add to the flags, to accept more information from the user

## Bonus Tasks
Once those basics are done you can move on to:
1. Downloading and/or Displaying the resultant meme image from within this app
2. Use a custom HTTP client - defining timeouts among other things

At this point you will have a complete app that will function pretty well for making memes as you want them.
the next step here would be to write unit tests for this code. That will likely involve
some level of refactoring and will introduce the Go testing packages.