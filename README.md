#Project : Restaurant Reservation System
    Egen Solutions Project
## Requirements:

Owner | View Reservation: <br/>
Owner can view list of reservations.
Click on each reservation item for more details.
Owner | View Seating Area
Owner can view seating area (tables) in a list form.
Each item can have ConfirmationCode, Size, Status, Since fields.
On clicking ConfirmationCode, open reservation detail screen.
Owner | Create and Edit a Reservation:
Same as Customer Create and Edit Reservation flows.


Owner | Profile & Settings:
Owner can view/edit restaurant profile details like Name, Contact, Email, Address etc.
Owner can update settings like Auto Assign, Restaurant Open/Closing days and times etc.
Owner | Assign Table:
Open reservation detail screen from list of reservations.
On clicking Assign Table, open seating map and select table.
Owner | Auto Assign Table:
If Auto Assign is enabled, system should assign the table to a new reservation automatically.
Owner | Change Table:
Owner should be able to change the table for a reservation.
Owner | View Contact List:
Owner can view contact list of all the customers and their past reservations.

## Development [3 Modules]:

User Interface Design [Due after HTML and CSS]:
Responsive Design. Test on desktop and tablet. Mobile optional but recommended.
You can use a CSS framework like Bootstrap.
Use HTML5 and CSS3 features like new elements, fonts, transitions, transformations.
RESTful API [Due after RESTful]:
Data exchange format: JSON
Jersey + Jackson (preferred)
MySQL, Tomcat (or any other J2EE server/container)
JavaScript [Due after AngularJS]:
Single Page Application using AngularJS
Multiple views, routing, follow a style-guide.
Build, Optimization, and Testing
grunt
Karma/Jasmine for unit testing.