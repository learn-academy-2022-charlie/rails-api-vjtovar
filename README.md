# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

[x] Story: As a developer I can create an animal model in the database. An animal has the following information: common name, latin name, kingdom (mammal, insect, etc.).
[x] Story: As the consumer of the API I can see all the animals in the database.
Hint: Make a few animals using Rails Console
[x] Story: As the consumer of the API I can update an animal in the database.
[x] Story: As the consumer of the API I can destroy an animal in the database.
[x] Story: As the consumer of the API I can create a new animal in the database.
[x] As the consumer of the API I can create a sighting of an animal with date (use the datetime datatype), a latitude, and a longitude.
Hint: An animal has_many sightings. (rails g resource Sighting animal_id:integer ...)
Hint: Datetime is written in Rails as “year-month-day hr:min:sec" (“2022-01-28 05:40:30")
[x] As the consumer of the API I can update an animal sighting in the database.
[x] As the consumer of the API I can destroy an animal sighting in the database.
Story: As the consumer of the API, when I view a specific animal, I can also see a list sightings of that animal.
Hint: Checkout the Ruby on Rails API docs on how to include associations.
Story: As the consumer of the API, I can run a report to list all sightings during a given time period.
Hint: Your controller can look like this:
