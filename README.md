# README

## Intro
This is the repository of the group "**Bug-Fixer**" for the FS24 Programmierproject.
The game we will develope is called "**Hol's der Compiler**". It's a Card game and may be best described as a very simple version of Poker. Each player has a set of cards from 1 to 12, which he/she can use to bit on a tablecard. However he/she can use each card only once! The tablecards have either positive or negarive values and the winners (or looser) of the round will earn this card. The player who has the most points in the end, wins the game.


## How does it work
The game will run on the Java programming language and we use Java version 17.0.10+11 (Use your Terminal with java --version). For this the IntelliJ IDEA will be used with the Google Java Style Format. One needs to make sure that he has the most recent version of JavaFX!

After downloading the jar file holsDerCompiler.jar and opening his terminal one can:
- Start a server: `java -jar holsDerCompiler.jar server <Port Number>`
- Start a client: `java -jar holsDerCompiler.jar client <Server's IP-Adress>:<Port Number>`


<details><summary>Current Development Status</summary>


(07.04.24 12:00)
- Game winners are now storred in a csv file with the propperties: Name, highScore, Number of Wins
- The GUI is running and all features and applications are working (high score, player list, lobby list, joing & creating lobbies, ...)
- Log4J and JUnit are implement. However not all test are "on green". This needs to be fixed.
- Game logic still needs to be debugged.
- Sound and 3D animations are working (sometimes).
- Propper manual is written (/Milestons/Milestone5/Manual_V1)





(23.04.24 21:00)
- Game logic is debugged
- Game winners are now added to external file
- Said file can be printed using /highScore in the chat
- Built Jar must be implemented
- Log4J and JUnit must be implemented
- GUI must be finished

(19.04.24 10:00)
- Whole code of server, client and game logic is newly written
- Game is now working
- PingPong is working
- All old functions/features are working
- The project is on timeline again
- Basic GUI is working

(10.04.24 17:00)
- Game is not workig propperly
- Due to that, GUI is not working
- We tried to fix the game and distroyed a lot of the code.

(08.04.24 22:06)
- Jar Built must be crated
- Gamelogic must be implemented properly
- PingPong must be implemented
- Whisperchat must be implemented
- GUI for Chat is working
- Gamelogic is written
- PingPong is written
- New Network Protocol is implemented
- Players can change Nicknames via GUI
- Whisperchat is written
- Players can create and switch Lobbies
- Chat in each Lobby is working

(24.03.24 16:40)
- Server is running
- Arbitrarily many clients can connect to Server
- Nickname is suggested
- Groupchat is working but not with Network Protocol
- Network Protocol is being updated
- PingPong is being implemented in new Network Protocol

</details>


## Participants
These are the participants in this group and their corresponding roles and mail adresses:
| Participants        | Role           | eMail  |
| ------------- |:-------------:| -----:|
| Domonkosh      | Responsible for Server & Client | [domonkos.szer@stud.unibas.ch](mailto:domonkos.szer@stud.unibas.ch) |
| Dominik      | Responsible for GUI       |   [dominik.kipfer@stud.unibas.ch](mailto:dominik.kipfer@stud.unibas.ch) |
| Mael | Responsible for GUI      |    [mael.pittet@stud.unibas.ch](mailto:mael.pittet@stud.unibas.ch) |
| Leon | Projectmanager, Responsible for QA | [leon.behrens@stud.unibas.ch](mailto:leon.behrens@stud.unibas.ch) |


## Goal of the Project
The main goal of this "Programmierproject" is firstly to develope a Computer game based on a Clien-Server archidecture. 
While doing so projectmanagement and working in a group of software developers will be tought as well.

<details><summary>Informations to update this page</summary>


For more information about readmes, you can either [read a guide](https://github.com/18F/open-source-guide/blob/18f-pages/pages/making-readmes-readable.md) or have a look at the readmes of popular open-source projects such as [Swift by Apple](https://github.com/apple/swift) or [Tensorflow](https://github.com/tensorflow/tensorflow)

 [Gitlab markdown syntax](https://docs.gitlab.com/ee/user/markdown.html), for example when talking about a :bug: (bug) or if your code is slow like a :snail:.
You can also tag people using @username and reference issues using '#1', where 1 is the issue number. For more features, consult the linked Gitlab syntax guide. 

If you don't like reading documentation, [here's a cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).
</details>
