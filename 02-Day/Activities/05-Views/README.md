### Stub Views & URL Mappings  (20 Minutes)

  * **Instructions** | Setting up views and mapping them to routes in Django can seem labor-intensive at first, but you'll find that they become quite mechanical with practice. For this activity, you'll ned to do two things: Write three views, and map them to routes.

  * First, create three views: `index`, `detail`, and `add`.

  * In your `index` view, return an HTML string containing a header and a `<ul>` with two or three list items. They can say anything at all.

  * In your `detail` and `add` views, just return an HTML string containing headers. Something like "This is the detail/add view!" is fine.

  * Next, map these views to urls in `users/urls.py`. The routes should correspond to your method names.

  * Finally, make sure the Django project as a whole knows about the urls for your `users` app.

  * Kick up a development server and make sure everything's working properly in the browser.

  * _HINTS_ | Keep in mind that we're not returning pure strings — you need to import a function to turn them into proper Http responses. Also, don't forget that you can use """triple quotes to write multi-line strings in Python.""" This should make it easier to write your `index` view's HTML response.

  * Take a moment to think about your solution when you finish. Can you think of a way to make it more robust or elegant?
