## Instagram Challenge

I'm going to make a clone of instagram, let's see how it goes. 

### Stack

 - Ruby on Rails web App
 - Active Record ORM
 - AWS Bucket to hold pictures
 - SQLite database
 - RSpec and Capybara for testing because that's what Rails likes.

Considering using Rails as the API and creating a seperate FrontEnd but I've already got an API/FrontEnd mashup project running so lets keep this one simple.

### User Stories

```
As an amateur photographer
So that I can share my photos
I can post my pictures to a website
```

```
As an amateur photographer
So that I know my photos are good
Users can like my photos
```

```
As a site user
So that my photos are mine
I can create an account to post from
```

```
As an amateur photographer
So that I can improve my skills
Users can comment on my photos
```

```
As a content producer
So my photos can be organised
I can apply tags to each photo
```

```
As a site user
So that I can quickly find content
I can search photos by tags
```

### Site Mockups && User Flow

![Domain Model](docs/Instagram_Model.png)

### Starting Off

To begin this project I am going to creat a page where anyone can post a picture, pictures posted will be displayed on the main page and there will be no user registration.