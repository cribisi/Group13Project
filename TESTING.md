Who: Lucas Sward, Xi Gao, Chad Ribisi, Fernando Mercado, Mahalia Evans
Title: Hound Dogs
Vision: Facilitate a friendly environment for people to find a furry friend. 

User Acceptance Test Plans

Feature 1: Login
	The user will login using their username and password, the test will pass if the program returns true for a valid username and password string.The program should return false if invalid username or password strings are used. Also, if the username and password fields are left blank the program should return false.

Feature 2: Sign-up 
The user will sign up using a username and password, then the program should take the username and password and check if the username and password are a valid string ie. not code, and the php file should also check to see if the username is already taken. If an invalid string is entered and the php file doesn't catch it and returns true, then it fails, but if the php file catches the error and returns false then it passes. If a valid username and password are entered and the php file uses them and returns true, then it passes. Also, the program should put out an error if the passwords entered don’t match and return false, or if either of the fields are left blank.

Feature 3: Map Location
	The user will enter a location where they have a dog. The program should throw an error message and return false if an invalid location was entered, an invalid location being a location not in Boulder. The test should also return true if a correct location is entered by the user and output a message that a valid location was entered.

Automated Tests:
Unit test automated testing tool
https://phpunit.de/
Instructions for running:
1. clone the github
2. open terminal in the directory that the github files are in
3. make sure you have phpunit installed by following the instructions on the website 
4. run command: phpunit DogMapTest.php, for the DogMap.php unit test
5. the output should be two "." and also some messages saying that there are undefined indexes Latitude and Longitude, but those are just for getting the Longitude and Latitude from an html form.
https://docs.google.com/a/colorado.edu/document/d/1u9YI02F_qOGA4KoTkCapM9oz4z80oQaty4TSO-tyIfk/edit?usp=sharing
