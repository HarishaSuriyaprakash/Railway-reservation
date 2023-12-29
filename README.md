Setup

Create a user called 'root' and set the password to '1234'.
Create a new database called 'railway'.
Create 3 tabels called 'user','train' and 'chart'.
The fields of 'user' table will be uname(string),pass(string),age(int),g(string),timestamp(timestamp),sno(int which should be auto incremented).
The fields of 'train' table will be tnum(int), tname(string), seats(int), bp(string), dp(string), fAC(int), sAC(int), tAC(int), sc(int), doj(date), dtime(string), atime(string), sno(int which should be auto incremented).
The fields of 'chart' table will be pnr(int), name(string), age(int), gender(string), seatno(int), coach(string), status(string), timestamp(timestamp), dot(date), sno(int which should be auto incremented), tnum(int).

To run the file

javac railway.java
java railway.
