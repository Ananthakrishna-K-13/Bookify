# Online Library Management System

- Developed as part of the course Operating Systems Lab (EG301P) at IIIT-Bangalore.
- Socket-based client-server application for online library management.
- Features include user authentication, book and member management (add, delete, modify, search).
- Server-side handles client requests; client-side provides interface for users.
- Utilizes OS concepts: socket programming for communication, multi-threading for multiple client handling, file handling for data storage, semaphores and file-locking for concurrency control.

## Run Locally

- Install make if you do not have make installed.
```bash
sudo apt install make
```
- Create necessary datafiles and compile the src files.
```bash
cd osminiproject
make all
```
- Change directory to /bin.
```bash
cd bin
```
- Execute the `./create_admin` in the bin directory and enter the admin username and admin password.
```bash
./create_admin
```
- To run the server-side program, run the following:
```bash
./server
```
- To run the client-side program, run the following:
```bash
./client
```
## Features
- This application can have multiple admin and multiple users.
- Admins are created manually using the `./create_admin` in `/bin` directory.
- Users can be created only by Admins.

### Admin
- Add a new Book to the library.
- Delete a Book from the library.
- Update the number of copies available for a particular Book.
- Add a new User.
- List all Books.
- List all Users

### Client
- List all Books.
- Issue a Book.
- Return a Book.
- List all Books issued by that particular user.

## Authors
- [@Ananthakrishna-K-13](https://github.com/Ananthakrishna-K-13)