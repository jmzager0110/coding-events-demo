# coding-events-demo
New Class for coding-events, "Person"
Purpose:
Creating this class would make it possible for one to create an account in coding-events so that they can follow events they'd be interested in & track their caledar of events.

Current state of Person in coding-events
This currently does not exist, rather is in the desgin stage.

Future Implementation & Improvements
The Person class would hold the follow:
  Fields
  id - an int type that would automatically generate an id for each user
  firstName & lastName - string types that would hold these values for the user
  email - a string type to hold their email address, which would act as their username, w/ validation
  password - a string type to hold their password, w/ validation to be specified later
  
  Methods
  All fields with the exception of id would have getters & setters (id will not need a setter)
  Equals & hashcode, toString, and validation to be determined at a later time
  
  References
  Profile - a class to gather all the user's data
  eventsAttending & eventsOwned, where the former stores the events user is interested in attending, the latter events the user has created & shared
  This class would have a many-to-many relationship with Event (via eventsAttending), and a one-to-many relationship with Events (via eventsOwned)
  
