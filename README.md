## Projects

In this particular course we designed projects from a security point of view. The programming language used was primarily C++, although we sometimes made use of C as well. We would exchange our projects with an opposition team and would try to find weaknesses and esploits in each others projects. Following are the differe projects we designed in this course.

### Command-Line Minesweeper

This project involved building a clone of the classic Minesweeper game which comes with any Windows PC. One can play the game from the command line and we included different levels for the player to choose from. We had to build this game keeping in mind the SEI CERT C Coding Standards, to make sure we are following all the secure coding standards. Here's the [link](https://github.com/akshay9594/Minesweeper) to the source code of the project.

### Gee-Mail

In this project we built an asynchronus(same machine) messaging platform. The interface resembled that of an Emailing service like Gmail. We incorporated User registration, login and authentication functionalities along with an inbox and an outbox to check for new messages. We also had Encryption and Decryption functionalities w.r.t the messages. As soon as a User registers with his credentials, the Username and password are stored in a SQL database. We used SHA256 to hash the password and Salsa20 for Encryption of the messages. You can find the source code [here](https://github.com/akshay9594/Gee-mail).

### Markovian Tweets

The idea here is to display random tweets on the command line by way of prediction. The words are fetched from files and every word after the first word is picked up based on the amount of times it appears after the first word in the file. Subsequent words are thus fetched and displayed as an entire tweet of 280 characters. Find the source code [here](https://github.com/akshay9594/Markovian-tweets).

