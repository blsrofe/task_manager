1. Define CRUD.

Create, Read, Update, Delete

2. Why do we use set method_override: true?

HTML form submission does not allow you to make POST requests but when you use this setting it allows you to override this restriction by using \_method in the form.

3. Explain the difference between value and name in this line: `<input type='text' name='task[title]' value="<%= @task.title %>"/>.`

Value is what is actually typed into the input field by the user. Name is what is needed so that the value field will be sent somewhere.

4. What are params? Where do they come from?

Params are input entered by the user. They come from when the user inputs information into a form.

5. Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task?

One of the routes for each just simply shows you what is there. The second route is needed to actually do some action; in this case create a task or edit a task.
