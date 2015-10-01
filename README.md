# Introduction to RESTful APIs
In this exercise we looked at the building of a simple RESTful API.

## Exercises
1. Updated npm using the commands 'npm cache clear' and 'npm install -g npm'.

1. Downloaded the files in this repository, extracted them, and opened a command prompt in the directory.

1. Installed express in the current directory using the command 'npm install express'.

1. Downloaded curl.exe from [here](http://www.paehl.com/open_source/?CURL_7.44.0).

1. Run rest.js using node.

1. Connected to http://127.0.0.1/todo using the command 'curl -v http://127.0.0.1:8000'. Examined the request and response.

1. Added a new route in rest.js with the format '/todo/\<num\>', where \<num\> is an integer. The route responded, in JSON, with the task at index \<num\>.

## Advanced exercises
1. Created a new route to delete an element of the todos, by index.

1. Created a new route to add todos, using the HTTP POST method. Curl allowed me to send POST requests from the command line.

$ curl --data "addition=theoneandonly" http://127.0.0.1:8000/todo/add/

## Note
Had to add body-parser as another npm module to do the POST parameter parsing.

- See [this](http://stackoverflow.com/questions/8506658/node-js-express-routing-with-get-params) Stack Overflow post for the syntax for using parameters in routes.

- To understand where express is installed, it is recommended you read [this](https://docs.npmjs.com/files/folders).

- Have a look at [HTTP Made Really Easy](https://www.jmarshall.com/easy/http/) for a great tutorial on HTTP.
