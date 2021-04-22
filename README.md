# CalendarApp

- Add Try catch for invite function (Not Priority)
- Get flask-mail working (loop through invite list and send mails) (Done)
- Add start date and end date (end date must be greater than start date)(Done)
- Connect database to online version 
- Multiple event names being generated (need to check) (Not Priority)


## Principles
GRASP
    Creator  
        Event_utils: because the Event Utils class has all the creator access to events and mail 
    Information Experts  
        Class User and Event  
            because they hold all info regarding the same  
    Low Coupling  
        Class user and event are low coupled   
    Controller  
        Form classes recieve reqs. from UI forms and contains methods  
  
SOLID 
    Liskov Substitution  
        For view we can substitute the different views (by design)  

OO
    Encapsulation       
        We have classes encapsulating the different functionalities, like event, user_methods etc.  
    Inheritence  
        FlaskForm is inherited by EventForm, UserForm etc.
    

    


