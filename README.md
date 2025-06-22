# Lets-Talk
Let's Talk is a peer-to-peer communication application, that allows users to message eachother through different terminals.

# Prerequisites:
* Linux machine
* `gcc` and `pthreads` installed

# ⚡️ How to run:
```
make                     # Compile the program
./s-talk [My Port] [Target Machine] [Target Port]   # Run the program
make clean               # Clean up compiled files
```

# Example Usage: 
User 1: 
```
./s-talk 5000 pc-2 6000
```
User 2:
``` 
./s-talk 6000 pc-1 5000
```
To terminate the connection, either user can input `!` into the terminal and press enter.

Developed using UDP sockets and POSIX threads for multithreading. Backed with my own statically Linked-List implementation!

Created October 2023 🌟
