### Where in the World...

This project was the implementation of the server that was used for assignment #2 (and partially what was necessary for lab #6). There were four routes to consider and create:

1. A `/sendLocation` API that users can `POST` to. This API takes a `POST` request from the user (either by using `curl` or by use of another XMLHttpRequest like A2) and, if the input is correct, returns the last 100 entries to the Mongo DB. This works as it should.
2. A `/locations.json` API that users can `GET`. When the user makes a `GET` request and includes a specific login, this API will return (in JSON) all the data entries for that specific login. If no login is provided, a blank array is returned. This works as it should
3. A `/redline.json` API that users can `GET`. When the users makes a `GET` request, this API will return (in JSON) the redline train information that is provided by the MBTA from http://developer.mbta.com/lib/rthr/red.json. This works as it should.
4. A `/` root. When the user comes to the root page (http://nameless-garden-8127.herokuapp.com/), all of the data entires that have been submitted are listed (descending from most recent). This works as it should.

See the assignment root [here](http://nameless-garden-8127.herokuapp.com/).

As of writting this, all of the assigned aspects of this assignment were implemented correctly.

All of the code was written/edited by Ben Tanen. However, some code was provided with some help. 

1. The function to sort an array of objects by a single key can be found [here](http://stackoverflow.com/questions/8837454/sort-array-of-objects-by-single-key-with-date-value) (used to sort arrays/objects by 'created_at')
2. The use of bodyParser and how to work with express: [here](https://stackoverflow.com/questions/5710358/how-to-get-post-query-in-express-node-js) and [here](https://stackoverflow.com/questions/25471856/express-throws-error-as-body-parser-deprecated-undefined-extended)
3. Misc. server port connection help: [here](http://stackoverflow.com/questions/15693192/heroku-node-js-error-web-process-failed-to-bind-to-port-within-60-seconds-of)

The assignment took approximately 3-5hours, written over the course of a few days.
