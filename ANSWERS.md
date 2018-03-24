# Q0: Why is this error being thrown?

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
The random Pokemon is appearing in the reverse order of the list in the seeds.rb. The common factor is that they are all listed in seeds.rb.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

When the button is clicked, it invokes the capture method in Pokemon controller. After it is captured, it's reroutes to the homepage.

# Question 3: What would you name your own Pokemon?

It's original name.

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

I passed the trainer's page into the redirect_to. 

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

When a user enters the name of the pokemon that already exists, the error message will be displayed.

# Give us feedback on the project and decal below!

Hard. But interesting.

# Extra credit: Link your Heroku deployed app
