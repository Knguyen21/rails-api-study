# Rails as an API Study

Use your favorite search engine and the provided readings to research and answer
the following questions (no prior knowledge is expected).

In your answers, be sure to cite any relevant sources you consulted in your
search. We ask you to write answers in your own words in order to see how you
process what you've read. Please do not answer with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

Please note:

-   Many of the readings will mention the "view" layer. We won't be covering the
    view layer in this program.
-   For now, we'll use the `rails-api` gem to create rails applications.
    `rails-api` is set to become part of Rails 5. We will never type `rails
    new`, instead preferring `rails-api new`.

## Required Readings

-   [Starting Ruby on Rails: What I Wish I Knew | BetterExplained](http://betterexplained.com/articles/starting-ruby-on-rails-what-i-wish-i-knew/)
-   [Intermediate Rails: Understanding Models, Views and Controllers | BetterExplained](http://betterexplained.com/articles/intermediate-rails-understanding-models-views-and-controllers/)
-   [Getting Started with Rails — Ruby on Rails Guides](http://guides.rubyonrails.org/getting_started.html)
-   [The Rails Command Line — Ruby on Rails Guides](http://guides.rubyonrails.org/command_line.html)
-   [Rails Routing from the Outside In — Ruby on Rails Guides](http://guides.rubyonrails.org/routing.html)
-   [Action Controller Overview — Ruby on Rails Guides](http://guides.rubyonrails.org/action_controller_overview.html)

## Define Model Responsiblities

In your own words, define what the responsibilities of the model layer are in
Rails.

```md
the model layer in Rails is a Ruby class that talk to the database. In addition it stores and validates data.
http://betterexplained.com/articles/intermediate-rails-understanding-models-views-and-controllers/
```

## Define Controller Responsiblities

In your own words, define what the responsibilities of the controller layer are
in Rails.

```md
The controller layer takes input the user gives, e.g. a URL, and send outputs to the view.
http://betterexplained.com/articles/intermediate-rails-understanding-models-views-and-controllers/

```

## Define Router Responsiblities

In your own words, define what the router does in Rails.

```md
The router in Rails figues out which controller to use
```

## The Request-Response Cycle in Rails

Starting with a client making a GET request to a particular URL, describe how
the parts of Rails interact to produce and send a response.

```md
First the web browser receives the request. Aftwerard it creates a new controller. The controllers parse the request and then talks to model, which goes to the the database and returns the result to the controller. Next the controller sends the results to the view, which will decide what will get displayed to the browser.

https://www.youtube.com/watch?v=3mQjtk2YDkM
```
