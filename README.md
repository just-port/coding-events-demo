# coding-events-demo

  This is an events tracker for meetups, conferences, etc. It's 
written in Java with Gradle, Spring Boot, and Thymeleaf. It is 
definitely not a Meetup clone... 

  Currently it has the functionality to display and create new 
events and tags for those events. Persistence is a recent addition
and validation is still a work in progress, but has been 
implemented in most of the app. 

  Coming soon is the ability to make user accounts and track
events the user is interested in or has created. Authentication 
is also in the works. My ideas for the person class are:

public class Person
ID(unique generated int)
first name(String)
last name(String)
password(String)
email(String)
(language(String), birthday(Date), gender(enum??),
bio(Optional String))
interests - probably List<Tags>
events they might be interested in or are attending List<Event>
events that they've created List<Event>
