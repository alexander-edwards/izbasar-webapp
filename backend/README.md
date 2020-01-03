# Description of Back-End Architecture

Main Technologies for Back-End are: Spring Boot and Database(???)

## API

This is only rough example of possible APIs

1. User:

   - Mentor:
     a) High School, City, Country, Graduation Year
     b) University, City, Country, Graduation Year
     c) Bio
   - Mentee:
     a) Bio

2. Blogs (Can Possible get ready templates):

   - Author = Either Mentor or Mentee
   - Headings
   - Sub-headings
   - Content
   - Media

## Technologies

## Springboot

- Spring boot vx.x.0
- Java - OpenJDK11

## Database

We should decide on which DB to use. Potentials:

1. PostgreSQL - I have used it with Django. Works pretty well
2. MongoDB
3. MySQL


## 03/01/2020: Alex ##

Updates: 
A basic webapp has been set up using spring boot. Currently able to create new webpages and the like with simple @RestController. 
Docker looks good and will be necessary. We should look at that immediately upon initiating the project (when we are all together) so we can containerise early (will be easier than migrating later I think, though there are most likely easy migrating tools.) Kubenetes looks cool but I think we would only need that waaay down the line so now we should not focus on that I think. 
I'm not uploading all the files onto here because they are a real mess and won't even work unless you have gone through the lengthy process of setting up spring on your machine. Once I have more of a working project I'll upload.

Next steps: 
Start implementing a basic form. Build a class for users, hook up an SQL server, and handle the get/post requests to create a demo sign in page. For now do everything via localhost so it's easy to transfer over later. 

