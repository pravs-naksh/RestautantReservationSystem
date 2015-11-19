#Project : Restaurant Reservation System
    Egen Solutions Project
## Requirements:

Owner | View Reservation: <br/>
Owner can view list of reservations.
Click on each reservation item for more details.  <br/>
Owner | View Seating Area  <br/>
Owner can view seating area (tables) in a list form.
Each item can have ConfirmationCode, Size, Status, Since fields.
On clicking ConfirmationCode, open reservation detail screen.     <br/>
Owner | Create and Edit a Reservation:   <br/>
Same as Customer Create and Edit Reservation flows.


Owner | Profile & Settings:  <br/>
Owner can view/edit restaurant profile details like Name, Contact, Email, Address etc.
Owner can update settings like Auto Assign, Restaurant Open/Closing days and times etc.  <br/>
Owner | Assign Table:          <br/>
Open reservation detail screen from list of reservations.
On clicking Assign Table, open seating map and select table.  <br/>
Owner | Auto Assign Table:    <br/>
If Auto Assign is enabled, system should assign the table to a new reservation automatically.  <br/>
Owner | Change Table:           <br/>
Owner should be able to change the table for a reservation.       <br/>
Owner | View Contact List:    <br/>
Owner can view contact list of all the customers and their past reservations.    <br/>

## Development [3 Modules]:

User Interface Design [Due after HTML and CSS]:  <br/>
Responsive Design. Test on desktop and tablet. Mobile optional but recommended.
You can use a CSS framework like Bootstrap.
Use HTML5 and CSS3 features like new elements, fonts, transitions, transformations.   <br/>
RESTful API [Due after RESTful]:     <br/>
Data exchange format: JSON
Jersey + Jackson (preferred)
MySQL, Tomcat (or any other J2EE server/container)
JavaScript [Due after AngularJS]:    <br/>
Single Page Application using AngularJS
Multiple views, routing, follow a style-guide.
Build, Optimization, and Testing       <br/>
grunt
Karma/Jasmine for unit testing.