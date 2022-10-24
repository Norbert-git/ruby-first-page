# README

Create first page with :

- rails generate controller home index
  - you can see the page Localhost:3000/home/index

Change the route from Localhost:3000/home/index to just Localhost:3000
Go to folder config and find file routes.rb
add to file: root 'home#index'

In terminal
rails routes will give all routes
