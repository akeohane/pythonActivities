### Display Models in Index & Detail Views (35 Minutes)

  * **Instructions** | Your task for this activity is to flesh out your `index` and `detail` using models.

  * To start, open up the Django shell using `manage.py`. Import your `User` class, and create/save a few users. Before moving on, retrieve all of them. Ensure you see what you expect to see.

  * Before moving on, try to retrieve a single user with the method: `User.objects.get`. We could retrieve the `jane` object we created before with `User.objects.get(first_name='Jane')`, or `User.objects.get(last_name='Doe')`. Do you see a pattern? How else could we retrieve the `jane` object? Test your hypothesis with the models you created.

  * Next, open up your views file. Update your `index` route to retrieve all of the Users you've saved, and send them out to the template for rendering. Don't forget to make the corresponding change in the template itself.

  * Start up a development server and hit your `index` route. Make sure you see what you expect.

  * Open up your views file again. and take a look at your `detail` view. Retrieve one of your users using `User.objects.get`, and pass this user to the template.

  * Update your template to display the user object you passed. Don't worry about displaying its specific properties yet—just make sure you're definitely passing the user you expect. _HINT_: This is a great place to use an `if` tag for debugging purposes!

  * Once you've verified that you're sending the user properly, update your template to display the user's properties. You don't have to build out a pretty UI for this, but you're free to have some fun with it if you'd like.

  * When you finish with that—you're done! Take a moment to review your solution. Is there anything you can fix or improve? In your detail view, can you think of a way to search for a particular user dynamically based on the request parameters?

  * Ask everyone around you if they're doing alright with the exercise. If you find someone who's having trouble, help them. Remember, this is your development team—if you finish early, their success becomes your responsibility.
