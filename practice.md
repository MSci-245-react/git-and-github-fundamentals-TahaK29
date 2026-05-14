# What I learned 

I learned that in a single-page app, the browser first requests a URL and the server sends a small HTML shell. That HTML then loads bundle.js, which contains the packaged app. Once the JavaScript runs, it builds the page and takes over routing. When a user clicks a link to another “page,” JavaScript redraws the view instead of making a new server request.
