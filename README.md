# Task Manager Project - Rig Freyr

# Checks for Understanding

1. Define CRUD.

- CRUD stands for Create, Read, Update, and Delete; the four basic database manipulation tasks most commonly required by APIs.

2. Define MVC.

- MVC stands for Model, View, Controller; it references a simple but effective design pattern commonly used by APIs for managing database requests. The Controller recieves user requests through appropriate routing, then passes them to a Model that retrieves and/or alters the requested data in the actual database. The Model then passes this data through the Controller to a View that renders the result of the user's request in a visible form.

3. What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.

- routes.rb (to define the endpoint for the GET request) and task_controller.rb (to define the functionality performed once that endpoint is reached)

4. What are params? Where do they come from?

- params are the actual pieces of information included in HTTP database manipulation requests. They usually come from the request body.

5. What is the purpose of a serializer?

- A serializer serves to add additional functionality or processing to the data passed to a controller by a model before it is rendered as a view. This commonly takes the form of formatting JSON reqponses to appear cleaner or more readable.

