Define CRUD.
 - Create, Read, Update, Destroy (every database has these steps)

Why do we use set method_override: true?
  - it helps you be able to read or call functions that may not have been able to be read otherwise.

Explain the difference between value and name in this line: <input type='text' name='task[title]' value="<%= @task.title %>"/>.
- the name = 'task[title]' is specifically calling a title from a hash, whereas the @task.title is calling the actual ruby object that @task is associated with.

What are params? Where do they come from?
- params are in place of variables, or they are values that you can access within HTML


Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?
