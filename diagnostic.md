# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
TO COMMUNICATE WITH THE FRONT END!!! No yeah but it communicates withe the front end and takes requests and interprets them, makes changes, or updates, and returns a resonse back.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The controller sends a request to the model.
```

Which layer in the MVC pattern communicates with the model?

```bash
The controller communicates with the model.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
We dont use views in our interpretation of the MVC pattern because HTML, CSS, etc dont know whats happening in the back end. The solely read what the controller gives them.
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
The model
```
List at least 5 standard actions that C.R.U.D corresponds to?

```bash
index, create, show, update, destroy
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
• The browser makes a GET request and sends it to the server.
• The server uses routes to figure out which controller to use.
• The dispatcher passes the parameters to the controller.
• The controller gives orders to the model for people.
• The model finds 'person/1' and sends back the information to the controller.
• The controller sends the information back to the server.
• The server displays it on the browser.
```

What is the command to generate a new rails-api app?

```bash
$ rails new my_api --api
```

What is the command to start an instance of a rails server?

```bash
$ rails s
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
• db:drop
• db:create
• db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
bin/rails generate scaffold pet name:Larz age:1234567890
```

List two advantages of using serializers? (2 bullet points)

```bash
• Turns an object into human readable format
• Stores objects in a binary format
```
