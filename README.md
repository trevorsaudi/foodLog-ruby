# FOODLOG RUBY
- A ruby on rails application that keeps track of food

# Running the project
- cd into the project folder foodlog
```
rails s 
```

# Generating a model
- generate a model that represent a table in the database, and the columns which are the fields in the database
- rails uses a domain specific language that directly interacts with the database

```
rails g scaffold Entry meal_type:string calories:integer proteins:integer carbohydrates:integer fats:integer
rails db:migrate
```
