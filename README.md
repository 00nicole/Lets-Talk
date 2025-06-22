# Lets-Talk
Let's Talk is a peer-to-peer communication application, that allows users to message eachother through different terminals.

⚡️ How to run:
```
make                     # Compile the program
./s-talk [My Port] [Target Machine] [Target Port]   # Run the program
make clean               # Clean up compiled files
```

Example: 
```
./s-talk 5000 localhost 6000
```
To terminate the connection, input "!" into the terminal.

Developed using UDP sockets and POSIX threads for multithreading. Backed with my own statically Linked-List implementation!

Created October 2023 🌟
