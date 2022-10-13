# ClassicMotors
ClassicMotors is a website to find your dream car as per your convenience at own pace from the comfort of your home. This website contains following modules:-
1) Home
2) Login / Register
3) Popular Car
4) Services
5) Contact


Frontend Technologies- HTML, CSS, Javascript, Bootstrap.
Backend Technology- PHP
Database- Xampp(MySQL, Apache).
IDE- Visual Studio Code

For ClassicMotors, I also create a Database(classicmotors). In DB, I have created a two tables:- 
1) Users
2) contactus

CREATE TABLE users ( id INT NOT NULL AUTO_INCREMENT, email VARCHAR(100) NOT NULL, password VARCHAR(100) NOT NULL, full_name VARCHAR(100) NOT NULL, phone VARCHAR(20) NOT NULL, gender ENUM('male', 'female') NOT NULL,  PRIMARY KEY(id) );

CREATE TABLE contactus ( id INT NOT NULL AUTO_INCREMENT, email VARCHAR(100) NOT NULL,  full_name VARCHAR(100) NOT NULL, subject VARCHAR(200) NOT NULL, msg VARCHAR(500), PRIMARY KEY(id) );
 
Note- You must have to be open Xampp Control Panel and Start Apache & MySQL , Before running this website.
