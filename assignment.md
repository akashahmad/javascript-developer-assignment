# JavaScript developer assignment

For this assignment you'll create an app for listing events. You'll load the events from a Redis stream.


## Description

<img src="https://user-images.githubusercontent.com/709159/99451145-0d146780-2922-11eb-97cb-7e7ec85b0ba7.png">

We’d like you to build an implementation of this using a modern web framework on the client. You should use whatever you’re most comfortable with for this, but we recommend using React. On the server we’d like to see something that can load events from a Redis event stream, send them to the client, and build a UI for displaying those events that includes a button for pausing/resuming the events, and a search box for filtering the events.

Here’s what we care about:

* It works
* Write this like you would write production code at your company. i.e.
	* Proper error handling and logging
	* Resilient code that can recover from crashes/failures
* The code is high-quality and tested

Feel free to use the `docker-compose.yml` file I attached if you decide to use Docker for this challenge. The stream image will simulate a stream of events.