# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The back-end is where things happens behind the scenes ... it is were the processing occurs ..
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
the controller is the "C" in the model
```

Which layer in the MVC pattern communicates with the model?

```md
The Controller communicates with the model
```

Why don't we use views in our interpretation of the MVC pattern?

```md
The client uses the View
```

What does C.R.U.D stand for?

```md
Create, Read, Update, Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
the CRUD occurs at the data level - our Model
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
Index
Show
Create
Update
Destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
GET access the API,
Routes to certain action
Action defines what needs to be done
View returns the ooutput
```

What is the command to generate a new rails-api app?

```bash
bundle install in the rails api repo ;-)
it works ... I didn\'t ask why ...
```

What is the command to start an instance of a rails server?

```bash
rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
bin/rake db:drop
bin/rake db:create
bin/rake db:migrate
bin/rake db:seed
bin/rake db:examples
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
 def set_name(name, age)
   @name = name
   @age = age
 end
```
