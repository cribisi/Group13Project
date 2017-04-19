Who: Lucas Sward, Xi Gao, Chad Ribisi, Fernando Mercado, Mahalia Evans
Title: Hound Dogs
Vision: Facilitate a friendly environment for people to find a furry friend. 

User Acceptance Test Plans

Feature 1: Login
	The user will login using their username and password, the test will pass if the program retrieves the correct username and password, so if one or the other (username or password) are not found in the database, then display the error message incorrect username or password. Also, if the username and password fields are left blank throw error message saying you must enter a username and password.

Feature 2: Sign-up 
The user will sign up using a username and password, then the program should take the username and password and correctly enter them into the database. If the incorrect values are added to the database, then it fails. If the correct username and password are entered into the database , then it passes. Also, the program should put out an error if the passwords entered don’t match, or if either of the fields are left blank.

Feature 3: Map Location
	The user will enter a location where they have a dog. The program should throw an error message if an invalid location was entered, an invalid location being a location not in Boulder.

Automated Tests:
Unit test automated testing tool
https://phpunit.de/
