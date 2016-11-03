# Q0: Why is this error being thrown?
Because the Pokemon model wasn't generated yet.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
They are selected randomly using the .sample method (called in home) from the database.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
It creates a button that will call the method at the given route and passing in the pokemon.

# Question 3: What would you name your own Pokemon?
Pokadam

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

I gave it a path for the trainer.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
Flash[:error] takes the given input and creates an error message

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
