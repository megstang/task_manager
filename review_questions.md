Define CRUD.
 - Create, Read, Update, Destroy (every database has these steps)

Why do we use set method_override: true?
  - it helps you be able to read or call functions that may not have been able to be read otherwise.

Explain the difference between value and name in this line: <input type='text' name='task[title]' value="<%= @task.title %>"/>.
- the name = 'task[title]' is specifically calling a title from a hash, whereas the @task.title is calling the actual ruby object that @task is associated with.

What are params? Where do they come from?
- My understanding is that params are included within the browser of the user. They are generated when the user goes to a page and when you use a Get request. I believe they are usually in hashes, and they hold some sort of key value pair. 


Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?
- I think that these routes are similar to methods. We can't both display and edit something at the same time, so we need to create two routes for it. 
