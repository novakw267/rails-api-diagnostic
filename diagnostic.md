# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The purpose of a backend, is to structure and hold data that is sent out to the client
and is the part that communicates directly with the source of the data.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
The model is the part to send and retrieve data. It gets a command from the controler
and respondes appropriately
```

Which layer in the MVC pattern communicates with the model?

```md
The controller is what tells the model what to do and what data to use.
```

Why don't we use views in our interpretation of the MVC pattern?

```md
If we used the view to interperate the data, we would have to use multiple views to
accomplish the same actions.
```

What does C.R.U.D stand for?

```md
create, read, update, delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
The controller would be my best guess, because that is what actually gives the command
to the model for what to do with the data it is retriving.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
create, get, patch, put, post(?), delete
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
The router inperates the request, then it is sent to the controller to tell the model what to do with what data, it retrives the data, sends it back to the controller in the way it was requested, and the controller sends it back to the client.
```

What is the command to generate a new rails-api app?

```bash
rails new commandapps
```

What is the command to start an instance of a rails server?

```bash
// your response here
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
db:drop,
db:create,
db:migrate,
db:seed,
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
```
