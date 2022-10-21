# artist-page

### Description

This application is a template for an artists business website. This could be subject to modification but the general purpose would be for an artist to manage their personal business.

## Requirements

- Ruby 2.7.4
- NodeJS (v16), and npm
- Heroku CLI
- Postgresql

See Environment Setup below for instructions on installing these tools if you
don't already have them.

## Getting Started

After cloning, **cd** into the project folder. 

There is some code in **db/seed.rb** file to start. Run the migrations and seed files to set up database:

```bash
rails db:migrate db:seed
```

Install ruby and javascript dependencies

```bash
bundle install
npm install --prefix client
```
Then, to setup the rails server run:

```bash
rails s
```
and to setup the react server run:

```bash
npm start --prefix client
```

## Features:

### Users

Most likely this would not need users, but a Users will be created for the purpose of sending messages and making comments.


### Home Page

This page will have an about me of the artist and some photos. 

### View Portfolio

This page will neatly display images of the "art". This could also have a comments section.

### Submit Form

Depending on the type of artist they may have different needs. Some artists may need this section to make appointments, some may need this for receiving any kind of messages. 

