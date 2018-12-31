### Base & View Templates  (20 Minutes)

  * **Instructions** | The activity you wrote last time returned raw HTML strings to be rendered in the browser. Your task for this activity is to convert them to templates.

  * Start by creating the correct folder structure in your `users` directory.

  * Next, create a base template with the basic HTML structure. Pull in the Bootstrap CSS from MaxCDN, and put it in the document head: <https://www.bootstrapcdn.com/> 

  * Create three templates, one for each of your views, that extend this template.

  * Two of your views simply returned headers. Pass the string to the template as a variable named `header`, and render it in the appropriate tags.

  * In the template that includes a `ul`, send both the header string and an array of items to the template. Refer to the example template your instructor slacked out to you for the control structure syntax.

  * Once your list renders properly, see if you can add an `if` check to display a special message when the collection is empty.

  * If you get stuck, don't hesitate to reach out to a TA!
