## Simple Redis Server in Golang

Redis is a popular in-memory data store known for its speed and flexibility. This repository implements a basic Redis server written in Golang for educational purposes. It provides a starting point to understand the core functionalities of a Redis server and how Golang can be used to build such a system. 

**Getting Started**

This is a basic implementation to help you understand the concepts behind building a Redis server in Golang. It currently has bugs and might not be suitable for production use. 

**Features:**

* Implements a simple server structure using Golang.
* Listens for connections from clients.
* Includes a function to handle client connections (currently has bugs).

**Prerequisites:**

* Golang installed on your system

**Building the server:**

The project uses a Makefile to manage building and running the server. 

1. Clone the repository:

```
git clone https://github.com/<your_username>/simple-redis-server
```

2. Navigate to the project directory:

```
cd simple-redis-server
```

3. Run the following command to build the server:

```
make build
```

This will create a binary named `redis-server` in the current directory.

**Running the server:**

1. Run the following command to start the server:

```
./redis-server
```

**Testing the server:**

There is a basic client test included in the code. However, it is recommended to use the official Golang Redis client library for more robust testing.

**Note:**

The client code currently has bugs and needs to be fixed. 

**Further Improvements:**

* Fix the bugs in the client code.
* Implement additional functionalities of a Redis server.
* Enhance error handling and logging.
* Write unit tests for the server code.
