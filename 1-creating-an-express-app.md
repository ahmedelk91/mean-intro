# npm init && npm install --save express

- What is NPM?
- What does `package.json` do?
- What does `--save` do?

# Added index.js

- What does `require` do?
- What's the difference between `require("hello")`, `require("./hello")`, and `require("./hello.js")`?
- Note the `()` at the end of `express()`. This means `require("express")` must be returning what kind of object?
- What does the `.get` in `app.get` indicate?
- What do `req` and `res` stand for?
- What happens if you don't include `res.send`?
- What is `3001`, and how does it affect what you do in your browser?

![#](images/initial-server.png)

# npm install --save express-handlebars

- Whenever you `npm install --save` something, you'll also probably need to do what?
- Before you can `require` something, you'll probably need to do what?

![#](images/express-hbs.png)

# Added views

- `<%= yield %>` in Rails is like what in Handlebars?

![#](images/layout-main.png)

![#](images/app-welcome.png)

# Configured Handlebars

- What's the difference between `res.send` and `res.render`?

![#](images/configured-hbs.png)

# Added express.static and CSS

- What do the two arguments in `app.use` in this snippet do?
- If I write `app.use("/wombat", express.static("chicken"))`...
  - In which folder should I put all my CSS files?
  - When I `<link>` to my CSS, with what will the `href` path begin?

![#](images/add-static.png)

![#](images/add-css.png)

![#](images/linked-css.png)

# Added font-end Javascript

- What's the difference between front-end Javascript and back-end Javascript?

![#](images/add-js.png)

![#](images/linked-js.png)

# Added candidates#index route

- What does the second argument in `res.render` do? What kind of data type should it be?

![#](images/add-index.png)

![#](images/index-view.png)

# Added fake data

- What is `module.exports` and how is it related to `require`?

![#](images/add-seeds.png)

![#](images/add-connection.png)

![#](images/require-connection.png)

![#](images/pass-data-to-index.png)

# Added #each in index

- What's the difference between how you begin an end an `each` loop in Handlebars?
- How is Handlebars' `#each` similar to Ruby's `.each`?

![#](images/each-in-index.png)

# Added candidates#show route

![#](images/added-show.png)

![#](images/show-route.png)

# Included data in candidates#show

![#](images/data-in-show.png)

# Added #unless in candidates#show

- What is the "opposite" of `#unless`?

![#](images/added-unless.png)

# Deploying to Heroku

- What does a Procfile do?
- What's the point of environment variables?
- How do you access environment variables?

![#](images/procfile.png)

![#](images/env-port.png)