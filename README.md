# Pong-SFML
A Pong game written in C++ using the SFML library. 

# Screenshots

![Screenshot](Screenshots/Screenshot%201.png?raw=true)
![Screenshot](Screenshots/Screenshot%202.png?raw=true)
![Screenshot](Screenshots/Screenshot%203.png?raw=true)

# Instructions

1. Clone the repository
2. Open a terminal in the sfml-pong folder (`cd sfml-pong`)
3. Run the following commands in the terminal to create and run an executable game file

`g++ Pong.cp -o pong -I include -L lib -l sfml-system -l sfml-window -l sfml-graphics -l sfml-audio -l sfml-network -Wl,-rpath ./lib`

`./pong`